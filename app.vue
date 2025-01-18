<template>
  <div>
    <NuxtPage />
  </div>
</template>

<style>
.font-playfair {
  font-family: 'Playfair', serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  font-variation-settings: 'wdth' 100;
}

* {
  font-family: 'Inter', serif;
}

.filter__checkbox-list::-webkit-scrollbar
{
    background-color: #2c2c31;
    border-radius: 8px;
    width: 7px;
    overflow: hidden;
}

.filter__checkbox-list::-webkit-scrollbar-thumb
{
    background-color: #43434a;
    border-radius: 8px;
}
</style>
