<template>
  <div>
    <Profile />
    <Info />
  </div>
</template>

<script>
import Info from '~/components/Info.vue';
// import Profile from '~/components/Profile.vue';
export default {
    head() { },
    name: "IndexPage",
    components: { Info }
}
</script>
