<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Header from '../components/Checkout/header.vue'
import checkout from '../components/Checkout/checkout.vue'
import timer from '../components/Checkout/timer.vue'
import express from '../components/Checkout/express.vue'
import information from '../components/Checkout/information.vue'
import shipping from '../components/Checkout/shipping.vue'
import total from '../components/Total/total.vue'
import card from '../components/Total/card.vue'
import freeService from '../components/Total/freeService.vue'

</script>

<template>
  <main>
    <Header />
    <div style="max-width: 1350px; margin: auto;">
      <div style="display: flex;">
        <div style="width: 50%; padding-top: 60px; padding-left: 80px;">
          <checkout />
          <timer />
          <express />
          <information />
          <shipping />
        </div>
        <div style="background: #fafbfc; width: 100%; padding-top: 60px; padding-left: 60px; padding-right: 80px;">
          <total />
          <card />
          <freeService />
        </div>
      </div>
    </div>

  </main>
</template>
