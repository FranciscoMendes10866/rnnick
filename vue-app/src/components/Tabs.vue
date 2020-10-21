<template>
  <div>
    <div class="tabs is-boxed is-centered">
      <ul>
        <li class="is-active" data-target="product-details">
          <a>Product Details</a>
        </li>
        <li data-target="delivery-information">
          <a>Delivery Information</a>
        </li>
      </ul>
    </div>
    <div class="px-2" id="tab-content">
      <div id="product-details">
        <h3 class="is-size-5 title">Product Details</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga,
          reprehenderit voluptates! Quisquam dolores distinctio minima eligendi,
          sint enim quaerat. Totam eaque eligendi quis, itaque beatae id sit
          fuga voluptatibus a autem debitis sequi, officiis dolores corporis!
          Necessitatibus, libero voluptate? Fuga, natus iusto! Perspiciatis iure
          officiis rerum, illo temporibus iusto voluptatum.
        </p>
      </div>
      <div id="delivery-information" class="is-hidden">
        <h3 class="is-size-5 title">Delivery Information</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga,
          reprehenderit voluptates! Quisquam dolores distinctio minima eligendi,
          sint enim quaerat. Totam eaque eligendi quis, itaque beatae id sit
          fuga voluptatibus a autem debitis sequi, officiis dolores corporis!
          Necessitatibus, libero voluptate? Fuga, natus iusto! Perspiciatis iure
          officiis rerum, illo temporibus iusto voluptatum.
        </p>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({})
</script>