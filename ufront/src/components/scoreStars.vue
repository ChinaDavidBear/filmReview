<template>
  <div>
    <font-awesome-icon
      v-if="Math.floor(score/2)>=1"
      class="text-warning"
      :icon="['fas','star']"
    />
    <font-awesome-icon
      v-if="Math.floor(score/2)>=2"
      class="text-warning"
      :icon="['fas','star']"
    />
    <font-awesome-icon
      v-if="Math.floor(score/2)>=3"
      class="text-warning"
      :icon="['fas','star']"
    />
    <font-awesome-icon
      v-if="Math.floor(score/2)>=4"
      class="text-warning"
      :icon="['fas','star']"
    />
    <font-awesome-icon
      v-if="Math.floor(score/2)>=5"
      class="text-warning"
      :icon="['fas','star']"
    />
    <font-awesome-icon
      v-if="Math.round(score/2)>Math.floor(score/2)"
      class="text-warning"
      :icon="['fas','star-half']"
    />
  </div>
</template>
<script>
export default {
    props:{
        score:Number
    }
}
</script>
<style>

</style>
