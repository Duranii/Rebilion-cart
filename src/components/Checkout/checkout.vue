<template>
    <div class="main">
        <p class="check">Checkout</p>
        <div class="checkout">
            <p class="cart">Cart</p>
            <div class="arrow"><svg xmlns="http://www.w3.org/2000/svg" width="4" height="8" viewBox="0 0 4 8" fill="none">
                    <path d="M0.0263367 7.50002C0.0264534 7.36745 0.0792084 7.24036 0.173003 7.14668L2.73034 4.58935C2.80774 4.51196 2.86915 4.42009 2.91104 4.31897C2.95293 4.21785 2.97449 4.10947 2.97449 4.00002C2.97449 3.89056 2.95293 3.78218 2.91104 3.68106C2.86915 3.57994 2.80774 3.48807 2.73034 3.41068L0.176337 0.855016C0.0852576 0.760715 0.0348604 0.634414 0.0359996 0.503315C0.0371388 0.372217 0.0897234 0.246811 0.182427 0.154107C0.275131 0.0614025 0.400538 0.00881802 0.531636 0.00767881C0.662735 0.0065396 0.789036 0.0569368 0.883337 0.148016L3.43734 2.70168C3.78075 3.04577 3.97362 3.51205 3.97362 3.99818C3.97362 4.48432 3.78075 4.9506 3.43734 5.29468L0.880004 7.85202C0.810177 7.92189 0.721218 7.96951 0.624352 7.98888C0.527487 8.00824 0.427056 7.99848 0.335733 7.96082C0.24441 7.92317 0.166287 7.8593 0.111223 7.77729C0.0561586 7.69528 0.0266208 7.5988 0.0263367 7.50002Z" fill="#84849A"/>
                </svg>
            </div>
            <p class="shipping">Shipping & Billing</p>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'checkout',
    }
</script>

<style>
    .check{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 700;
        font-size: 36px;
        color: #000034;
        margin: 0;
        padding-bottom: 10px;
    }
    .checkout{
        display: flex;
        gap: 10px;
        padding-left: 4px;
    }
    .cart{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        color: #84849A;
        margin: 0;
    }
    .shipping{
        font-family: 'Poppins';
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        color: #000034;
        margin: 0;
        padding-bottom: 60px;
    }
</style>