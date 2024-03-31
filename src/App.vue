<template>
  <div class="container mt-3">
    <div class="grid">
      <div class="row">
        <div class="col">
          <p class="h3 text-success fw-bold">App Component</p>
          <p class="fst-italic">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sapiente saepe doloremque quaerat neque doloribus. Eum debitis nesciunt accusamus obcaecati repudiandae.</p>
        </div>
      </div>
    </div>
   <Customer/>
  </div>
</template>

<script>
import Customer from "@/components/Customer.vue";
export default {
  components:Customer 
};
</script>


<style>
@import "./styles.css";
</style>
