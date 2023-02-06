<template>
  <Foo :foo="Math.random()" client:load />
  <slot />
</template>
