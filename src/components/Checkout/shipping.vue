<script setup>
import landingPage from '../Checkout/landingPage.vue'
</script>

<template>
    <div class="main">
        <p class="ship-text">Shipping method</p>

        <div class="shipping-flex">
            <div class="free-flex">
                <div><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="12" cy="12" r="11.5" stroke="#4B4E68"/>
                    <circle cx="12" cy="12" r="6" fill="#4B4E68"/>
                    </svg>
                </div>
                <p class="free-text">Free shipping</p>
            </div>  
            <p class="ten-dollars">$10</p> 
        </div>

        <div class="shipp-flex">
            <div class="free-flex">
                <div><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <circle cx="12" cy="12" r="11.5" stroke="#D5D0DF"/>
                    </svg>
                </div>
                <p class="free-text">DHL with price</p>
            </div>
            <p class="ten-dollars">$20</p>
        </div>

        <p class="payment">Payment Method</p>
        <p class="all">All transaction are secured and encryted</p>
        <div for="email">
            <div class="card">
                <div class="ok"><svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <g clip-path="url(#clip0_376_468)">
                    <path d="M4.58339 14.1667C5.27375 14.1667 5.83339 13.6071 5.83339 12.9167C5.83339 12.2264 5.27375 11.6667 4.58339 11.6667C3.89303 11.6667 3.33339 12.2264 3.33339 12.9167C3.33339 13.6071 3.89303 14.1667 4.58339 14.1667Z" fill="#84849A"/>
                    <path d="M15.8333 2.5H4.16667C3.062 2.50132 2.00296 2.94073 1.22185 3.72185C0.440735 4.50296 0.00132321 5.562 0 6.66667L0 13.3333C0.00132321 14.438 0.440735 15.497 1.22185 16.2782C2.00296 17.0593 3.062 17.4987 4.16667 17.5H15.8333C16.938 17.4987 17.997 17.0593 18.7782 16.2782C19.5593 15.497 19.9987 14.438 20 13.3333V6.66667C19.9987 5.562 19.5593 4.50296 18.7782 3.72185C17.997 2.94073 16.938 2.50132 15.8333 2.5ZM4.16667 4.16667H15.8333C16.4964 4.16667 17.1323 4.43006 17.6011 4.8989C18.0699 5.36774 18.3333 6.00363 18.3333 6.66667H1.66667C1.66667 6.00363 1.93006 5.36774 2.3989 4.8989C2.86774 4.43006 3.50363 4.16667 4.16667 4.16667ZM15.8333 15.8333H4.16667C3.50363 15.8333 2.86774 15.5699 2.3989 15.1011C1.93006 14.6323 1.66667 13.9964 1.66667 13.3333V8.33333H18.3333V13.3333C18.3333 13.9964 18.0699 14.6323 17.6011 15.1011C17.1323 15.5699 16.4964 15.8333 15.8333 15.8333Z" fill="#84849A"/>
                    </g>
                    <defs>
                    <clipPath id="clip0_376_468">
                    <rect width="20" height="20" fill="white"/>
                    </clipPath>
                    </defs>
                    </svg>
                </div>
                <input class="input-border" type="email" placeholder="2587 9860 2354">
            </div>
        </div>
        <div class="card-number">Card Number</div>

        <div for="email">
            <div class="card_name">
                <div><svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <g clip-path="url(#clip0_441_4752)">
                    <path d="M10 10C10.9889 10 11.9556 9.70676 12.7779 9.15735C13.6001 8.60794 14.241 7.82705 14.6194 6.91342C14.9978 5.99979 15.0969 4.99446 14.9039 4.02455C14.711 3.05465 14.2348 2.16373 13.5355 1.46447C12.8363 0.765206 11.9454 0.289002 10.9755 0.0960758C10.0055 -0.0968503 9.00021 0.00216643 8.08658 0.380605C7.17295 0.759043 6.39206 1.39991 5.84265 2.22215C5.29324 3.0444 5 4.0111 5 5C5.00132 6.32568 5.52853 7.59668 6.46593 8.53407C7.40332 9.47147 8.67432 9.99868 10 10ZM10 1.66667C10.6593 1.66667 11.3037 1.86217 11.8519 2.22844C12.4001 2.59471 12.8273 3.1153 13.0796 3.72439C13.3319 4.33348 13.3979 5.0037 13.2693 5.6503C13.1407 6.29691 12.8232 6.89085 12.357 7.35703C11.8908 7.8232 11.2969 8.14067 10.6503 8.26929C10.0037 8.3979 9.33348 8.33189 8.72439 8.0796C8.1153 7.82731 7.59471 7.40007 7.22844 6.8519C6.86216 6.30374 6.66667 5.65927 6.66667 5C6.66667 4.11595 7.01786 3.2681 7.64298 2.64298C8.2681 2.01786 9.11595 1.66667 10 1.66667Z" fill="#979AB8"/>
                    <path d="M10 11.6672C8.01155 11.6694 6.10518 12.4603 4.69914 13.8664C3.29309 15.2724 2.50221 17.1788 2.5 19.1672C2.5 19.3883 2.5878 19.6002 2.74408 19.7565C2.90036 19.9128 3.11232 20.0006 3.33333 20.0006C3.55435 20.0006 3.76631 19.9128 3.92259 19.7565C4.07887 19.6002 4.16667 19.3883 4.16667 19.1672C4.16667 17.6201 4.78125 16.1364 5.87521 15.0424C6.96917 13.9485 8.4529 13.3339 10 13.3339C11.5471 13.3339 13.0308 13.9485 14.1248 15.0424C15.2188 16.1364 15.8333 17.6201 15.8333 19.1672C15.8333 19.3883 15.9211 19.6002 16.0774 19.7565C16.2337 19.9128 16.4457 20.0006 16.6667 20.0006C16.8877 20.0006 17.0996 19.9128 17.2559 19.7565C17.4122 19.6002 17.5 19.3883 17.5 19.1672C17.4978 17.1788 16.7069 15.2724 15.3009 13.8664C13.8948 12.4603 11.9884 11.6694 10 11.6672Z" fill="#979AB8"/>
                    </g>
                    <defs>
                    <clipPath id="clip0_441_4752">
                    <rect width="20" height="20" fill="white"/>
                    </clipPath>
                    </defs>
                    </svg>
                </div>
                <input class="input-border" type="text" placeholder="Name on Card">
            </div>
        </div>

        <div class="name-flex">
            <div for="email">
                <div class="second">
                    <input class="input-border" type="text" placeholder="MM/YY">
                </div>
            <!-- <div class="first-name">First Name</div> -->
            </div>

            <div for="email">
                <div class="second">
                    <input class="input-border" type="text" placeholder="CVV">
                </div>
            <!-- <div class="last-name">last Name</div> -->
            </div>
        </div>

        <div class="tick">
            <div><svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                <g clip-path="url(#clip0_1_671)">
                <path d="M17.5 0H2.5C1.83696 0 1.20107 0.263392 0.732233 0.732233C0.263392 1.20107 0 1.83696 0 2.5L0 20H20V2.5C20 1.83696 19.7366 1.20107 19.2678 0.732233C18.7989 0.263392 18.163 0 17.5 0V0ZM8.95667 14.4442C8.80189 14.599 8.61813 14.7218 8.41588 14.8056C8.21362 14.8894 7.99684 14.9326 7.77792 14.9326C7.55899 14.9326 7.34221 14.8894 7.13996 14.8056C6.9377 14.7218 6.75394 14.599 6.59917 14.4442L2.74417 10.5892L3.9225 9.41083L7.7775 13.2658L16.0775 4.96667L17.2558 6.145L8.95667 14.4442Z" fill="#4B4E68"/>
                </g>
                <defs>
                <clipPath id="clip0_1_671">
                <rect width="20" height="20" rx="2" fill="white"/>
                </clipPath>
                </defs>
                </svg>
            </div> 
            <p>By checking this box, I acknowledge that I have read and agree to the <br><strong>Terms of Service</strong>, and <strong>Monthly Billing Terms</strong>  of this website and want to <br> opt-in for the monthly billed Dream Collection Club®</p>     
        </div>

        <div>
            <p class="billing">Billing Address</p>
            <p class="specify">Specify the address for your payment option</p>
            <landingPage/>
        </div>
    </div>    
</template>

<script>
    export default{
        name: 'shipping',
    }
</script>

<style>
    .ship-text{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 24px;
        color: #000034;
    }
    .shipping-flex{
        display: flex;
        align-items: center;
        gap: 345px;
    }
    .free-flex{
        display: flex;
        align-items: center;
        gap: 10px;
        padding-bottom: 20px;
    }
    .free-text{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 16px;
        color: #4B4E68;
        padding-bottom: 5px;
        margin: 0;
    }
    .ten-dollars{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
        color: #000034;
        padding-bottom: 17px;
        margin: 0;
    }
    .shipp-flex{
        display: flex;
        align-items: center;
        gap: 340px;
    }
    .payment{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        color: #000034;
        padding-top: 20px;
        padding-bottom: 8px;
        margin: 0;
    }
    .all{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 14px;
        color: #84849A;
        padding-bottom: 30px;
        margin: 0;
    }
    .card{
        display: flex;
        align-items: center;
        gap: 10px;
        width: 500px;
        height: 56px;
        border: 1px;
        border-radius: 100px;
        border: 1.5px solid #D6D8EE;
        padding-left: 40px;
    }
    .ok{
        padding-top: 3px;
    }
    .card-number{
        display: flex;
        justify-content: center;
        position: relative;
        bottom: 67px;
        left: 33px;
        width: 90px;
        height: 18px;
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 12px;
        color: #84849A;
        background: white;
    }
    .card_name{
        display: flex;
        align-items: center;
        gap: 10px;
        width: 500px;
        height: 56px;
        border: 1px;
        border-radius: 100px;
        border: 1.5px solid #D6D8EE;
        padding-left: 40px;
        margin-top: 20px;
    }
    .tick{
        display: flex;
        gap: 12px;
        margin-bottom: 50px;
    }
    .tick p{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 14px;
        color: #4B4E68;
        margin: 0;
    }
    .tick strong{
        color: #000034;
    }
    .billing{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 24px;
        padding-bottom: 8px;
        margin: 0;
        color: #000034;
    }
    .specify{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 400;
        font-size: 14px;
        padding-bottom: 20px;
        margin: 0;
        color: #84849A;
    }
    button{
        display: flex;
        gap: 6px;
        justify-content: center;
        align-items: center;
        width: 257px;
        height: 56px;
        background: #050824;
        border-radius: 100px;
        border: none;
        margin-top: 50px;
        margin-bottom: 50px;
    }
    button p{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 18px;
        color: #FFFFFF;
        cursor: pointer;
    }
</style>