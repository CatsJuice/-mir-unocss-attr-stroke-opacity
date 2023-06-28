<script setup lang="ts"></script>

<template>
  <div flex="~ nowrap gap-10" justify-center>
    <div>
      <code>stroke-opacity="0.5"</code>, <br>actual opacity is 0.005,
      <div>border is invisible</div>
      <svg width="200" height="200">
        <circle
          cx="100"
          cy="100"
          r="80"
          stroke="red"
          stroke-width="20"
          stroke-opacity="0.5"
          fill="#ff000030"
        />
      </svg>
    </div>

    <div>
      <code>stroke-opacity="50"</code>, <br>actual opacity is 0.5,
      <div>border is visible</div>
      <svg width="200" height="200">
        <circle
          cx="100"
          cy="100"
          r="80"
          stroke="red"
          stroke-width="20"
          stroke-opacity="50"
          fill="#ff000030"
        />
      </svg>
    </div>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
