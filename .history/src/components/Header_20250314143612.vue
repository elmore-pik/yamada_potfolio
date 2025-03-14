<script setup>
const intro = 'フロントエンドエンジニア見習いです';
</script>

<template>
  <header>
    <img src="/yamada.png" alt="太郎のアイコン" width="128" height="128">
    <h1>山田太郎</h1>
    <p>{{ intro }}</p>
  </header>
</template>

<style scoped>
/* headerのスタイル */

header {
  background: #eee;
  text-align: center;
  padding: 32px 0;
}

header img {
  border-radius: 50%;
}

h1 {
  margin: 16px 0 0;
  font-weight: normal;
  font-size: 24px;
}
</style>