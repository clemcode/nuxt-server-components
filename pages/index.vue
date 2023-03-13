<template>
  <div>
    <NuxtLink to="/client" :prefetch="false">
      Regular component
    </NuxtLink>
    <p>
      <code>date-fns</code> ne sera pas inclus sur cette page.
    </p>
    <HeavyComponent />
  </div>
</template>
