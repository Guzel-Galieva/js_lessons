<template
  ><div class="auth-layout">
    <h2 class="page-title">
        {{$route.meta.title}}
    </h2>
    <div class="page-container">
      <router-view />
    </div>
  </div>
</template>

<script>
export default {
  name: "AuthLayout",
  methods: {},
};
</script>

<style scoped>
.auth-layout{
    width: 100%;
    max-width: 500px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
}
</style>
