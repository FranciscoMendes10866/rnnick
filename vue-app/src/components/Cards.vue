<template>
  <div>
    <section class="section is-hidden-mobile">
      <div class="container">
        <h3 class="title has-text-centered is-size-4">Related Products</h3>
        <div class="mt-5 columns is-centered is-8 is-variable">
          <div class="column is-4-tablet is-3-desktop">
            <div class="card">
              <div class="card-image has-text-centered px-6">
                <img
                  :src="require('@/assets/p1.png')"
                  alt="Placeholder image"
                />
              </div>
              <div class="card-content">
                <p>£12.95</p>
                <p class="title is-size-5">Cortardo Cup</p>
              </div>
              <footer class="card-footer">
                <p class="card-footer-item">
                  <a href="" class="has-text-grey">View</a>
                </p>
              </footer>
            </div>
          </div>
          <div class="column is-4-tablet is-3-desktop">
            <div class="card">
              <div class="card-image has-text-centered px-6">
                <img
                  :src="require('@/assets/p2.png')"
                  alt="Placeholder image"
                />
              </div>
              <div class="card-content">
                <p>£12.95</p>
                <p class="title is-size-5">Cortardo Cup</p>
              </div>
              <footer class="card-footer">
                <p class="card-footer-item">
                  <a href="" class="has-text-grey">View</a>
                </p>
              </footer>
            </div>
          </div>
          <div class="column is-4-tablet is-3-desktop">
            <div class="card">
              <div class="card-image has-text-centered px-6">
                <img
                  :src="require('@/assets/p3.png')"
                  alt="Placeholder image"
                />
              </div>
              <div class="card-content">
                <p>£12.95</p>
                <p class="title is-size-5">Cortardo Cup</p>
              </div>
              <footer class="card-footer">
                <p class="card-footer-item">
                  <a href="" class="has-text-grey">View</a>
                </p>
              </footer>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>