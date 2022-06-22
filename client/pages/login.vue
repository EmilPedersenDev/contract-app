<template>
  <div class="login">
    <div class="login__wrapper">
      <n-button secondary
        >Login with Google <i class="fa-brands fa-google"></i>
      </n-button>
    </div>
  </div>
</template>

<script setup>
import { NButton } from "naive-ui";
</script>

<style lang="scss" scoped>
.login {
  height: 100vh;
  position: relative;
  .login__wrapper {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    min-height: 300px;
    width: 100%;
    max-width: 500px;
    box-shadow: 0 0 10px 1px rgb(209, 209, 209);
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 5px;
    .n-button {
      .n-button__content {
        .fa-brands.fa-google {
          padding-left: 0.375rem;
        }
      }
    }
  }
}
</style>
