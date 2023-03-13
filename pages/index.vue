<template>
  <div>
    <NuxtLink to="/client" :prefetch="false">
      Regular component
    </NuxtLink>
    <p>
      <code>date-fns</code> ne sera pas inclus sur cette page.
      <p>(Inspecter les sources > _nuxt > node_modules)</p>
    </p>
    <HeavyComponent />
  </div>
</template>
