<template>
  <div>
    <!-- Navbar -->
    <Navbar />

    <!-- Breadcrumbs -->
    <Breadcrumbs />

    <!-- product info -->
    <section class="section">
      <div class="container">
        <div class="columns is-vcentered is-multiline">
          <div class="column is-6-tablet is-3-desktop">
            <h1 class="is-size-3-mobile is-size-1-desktop title">Docker</h1>
            <h2 class="is-size-3-mobile is-size-2-desktop subtitle">
              Dark Roast
            </h2>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eos
              dolores nam accusamus nulla dignissimos veniam vitae sunt minus
              natus illum?
            </p>
          </div>
          <div class="column is-6-tablet is-5-desktop has-text-centered">
            <img
              :src="require('@/assets/product.png')"
              alt="docker coffee image"
              class="px-6"
            />
          </div>
          <div class="column is-12-tablet is-4-desktop">
            <div class="is-size-4 mb-4">£10.95</div>
            <p class="mb-4">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis
              perferendis ipsa totam.
            </p>
            <form>
              <div class="control mb-6">
                <div class="select is-dark">
                  <select>
                    <option>Small (250g)</option>
                    <option>Large (500g)</option>
                  </select>
                </div>
              </div>
              <button class="button is-primary">Add to Cart</button>
            </form>
          </div>
        </div>
      </div>
    </section>

    <section class="section">
      <div class="container">
        <div class="columns is-variable is-8">
          <div class="column is-7-tablet">
            <!-- Tabs -->
            <Tabs />
          </div>
          <div class="column is-5-tablet">
            <!-- Box -->
            <Box />
          </div>
        </div>
      </div>
    </section>

    <!-- Cards -->
    <Cards />

    <!-- modal -->
    <div class="modal">
      <div class="modal-background"></div>
      <div class="modal-content has-background-white py-5 px-5">
        <h3 class="title mb-6">Join the Club</h3>
        <form>
          <div class="field">
            <label class="label">Name</label>
            <div class="control">
              <input class="input" type="text" placeholder="Name" />
            </div>
          </div>
          <div class="field">
            <label class="label">Email</label>
            <div class="control">
              <input class="input" type="email" placeholder="Email" />
              <span class="icon is-small is-left">
                <i class="fas fa-envelope"></i>
              </span>
            </div>
          </div>
          <div class="field">
            <div class="control">
              <label class="checkbox">
                <input type="checkbox" />
                I agree to the <a href="#">terms and conditions</a>
              </label>
            </div>
          </div>
          <div class="mt-6 has-text-centered">
            <button class="button is-warning">Sign Up</button>
          </div>
        </form>
      </div>
    </div>

    <!-- Footer -->
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Navbar from '../components/Navbar.vue'
import Breadcrumbs from '../components/Breadcrumbs.vue'
import Footer from '../components/Footer.vue'
import Cards from '../components/Cards.vue'
import Tabs from '../components/Tabs.vue'
import Box from '../components/Box.vue'

export default defineComponent({
  name: "Home",
  components: {
    Navbar,
    Breadcrumbs,
    Footer,
    Cards,
    Tabs,
    Box,
  }
});
</script>
