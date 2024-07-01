<script>
import GroupPic from "../../assets/Group 1000004336.png";
import GreenPic from "../../assets/green.png";
import PinkPic from "../../assets/pink.png";

export default {
        data: function () {
            return {
                GroupPic: GroupPic,
                GreenPic: GreenPic,
                PinkPic: PinkPic
            }
        }
    }
</script>

<template>
<div class="Main">    
    <div class="nike">
        <div class="snikker">
            <img src="GroupPic" />
            <p>Nike sneakers</p>
        </div>
        <p>$120.90</p>
    </div>

    <div class="nike">
        <div class="snikker">
            <img src="Green" />
            <p>Nike sneakers</p>
        </div>
        <p>$120.90</p>
    </div>

    <div class="nike">
        <div class="snikker">
            <img src="PinkPic" />
            <p>Nike sneakers</p>
        </div>
        <p>$120.90</p>
    </div>
</div>    

<div class="line">
    <div class="subtotal-flex">
        <p>Subtotal:</p>
        <p>$362.70</p>
    </div>
    <div class="free-flex">
        <p>Shipping:</p>
        <p>Free</p>
    </div>
</div>

<div class="total-flex">
        <p>Total</p>
        <p>$362.70</p>
    </div>
</template>

<script>
    export default{
        name: 'total',
    }
</script>

<style>
    .line{
        border-top: 1px solid #D6D8EE;
        border-bottom: 1px solid #D6D8EE;
        width: 515px;
    }
    .nike{
        display: flex;
        gap: 251px;
        align-items: center;
        padding-bottom: 19px;
    }
    .snikker{
        display: flex;
        gap: 20px;
        align-items: center;
    }
    .subtotal-flex{
        display: flex;
        gap: 380px;
    }
    .free-flex{
        display: flex;
        justify-content:space-between;
        padding-bottom: 0px;
    }
    .total-flex{
        display: flex;
        gap: 415px;
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 600;
        font-size: 16px;
    }
</style>