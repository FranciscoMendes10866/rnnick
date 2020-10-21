<template>
  <div>
    <nav class="navbar is-white has-shadow">
      <!-- logo / brand -->
      <div class="navbar-brand">
        <a class="navbar-item">
          <img
            :src="require('@/assets/logo.png')"
            style="max-height: 70px"
            class="py-2 px-2"
          />
        </a>
        <a class="navbar-burger" id="burger">
          <span></span>
          <span></span>
          <span></span>
        </a>
      </div>

      <div class="navbar-menu" id="nav-links">
        <!-- right links -->
        <div class="navbar-end">
          <a class="navbar-item">My Account</a>
          <a class="navbar-item">Shopping Cart (0)</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>