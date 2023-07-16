<template>
  <div>
    <ul>
      <li v-for="i in 10" :key="i">
        <NuxtLink :to="`/posts/${i}`">
          Post #{{ i }}
        </NuxtLink>
      </li>
    </ul>
  </div>
</template>
