<template>
    <div class="main">
        <div class="boxv">
            <div class="fire">
                <p class="ten">🔥 Your cart is reserved for 10:00 minutes</p>
                <div class="time">
                    <p class="box1">00</p>
                    <p class="colon">:</p>
                    <p class="box1">{{ formattedTime(minutes) }}</p>
                    <p class="colon">:</p>
                    <p class="box1">{{ formattedTime(seconds) }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'timer',
    data() {
        return {
            minutes: 10,
            seconds: 0,
        };
    },
    mounted() {
        this.startTimer();
    },
    methods: {
        startTimer() {
            const timerInterval = setInterval(() => {
                if (this.minutes === 0 && this.seconds === 0) {
                    clearInterval(timerInterval);
                    // Timer has reached 00:00, handle your logic here
                    return;
                }

                if (this.seconds === 0) {
                    this.minutes--;
                    this.seconds = 59;
                } else {
                    this.seconds--;
                }
            }, 1000);
        },
        formattedTime(value) {
            return value < 10 ? `0${value}` : value;
        },
    },
};
</script>


<style>
    .boxv{
        width: 540px;
        height: 139px;
        background: #f5f5f8;
        border-radius: 32px;
    }
    .fire{
        max-width: 480px;
        margin: auto;            
    }
    .ten{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        color: #000034;
        margin: 0;
        padding-top: 30px;
    }
    .time{
        display: flex;
        gap: 4px;
    }
    .box1{
        display: flex;
        justify-content: center;
        align-items: center;
        width: 46px;
        height: 37px;
        background: #FFFFFF;
        border-radius: 12px;
    }
    .colon{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        padding-top: 5px;
    }
</style>