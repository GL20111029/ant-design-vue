<docs>
---
order: 11
title:
  zh-CN: 密码框
  en-US: Password box
---

## zh-CN

密码框。

## en-US

Input type of password.

</docs>
<template>
  <a-input-password v-model:value="value" placeholder="input password" />
</template>
<script lang="ts" setup>
import { ref } from 'vue';
const value = ref<string>('');
</script>
