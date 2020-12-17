<template>
  <div class="max-w-screen-xl mx-auto px-6 py-20">

    <div id="martyStanding" class="sm:grid sm:grid-cols-10 py-10">
      <div class="col-span-5 flex items-center justify-center">
        <h1 class="text-5xl font-black text-left w-full leading-tight">Hey Marty, what's going on?</h1>
      </div>
      <div class="col-span-5">
        <marty-standing />
      </div>
    </div>

    <div id="martyBalancing" class="sm:grid sm:grid-cols-10 py-10">
      <div class="col-span-5 flex items-center justify-center">
        <h1 class="text-5xl font-black text-left w-full leading-tight">Marty! Watch your balance!</h1>
      </div>
      <div class="col-span-5">
        <marty-balancing />
      </div>
    </div>

    <div id="martyBalancing" class="sm:grid sm:grid-cols-10 py-10">
      <div class="col-span-5 flex items-center justify-center">
        <h1 class="text-5xl font-black text-left w-full leading-tight">Alright Marty, see you later!</h1>
      </div>
      <div class="col-span-5">
        <marty-waving />
      </div>
    </div>

  </div>
</template>

<script>
import MartyStanding from './Martys/MartyStanding.vue'
import MartyBalancing from './Martys/MartyBalancing.vue'
import MartyWaving from './Martys/MartyWaving.vue'

export default {
  components: {
    MartyStanding,
    MartyBalancing,
    MartyWaving
  },
  data() {
    return {

    }
  }
}
</script>

<style scoped>

</style>
