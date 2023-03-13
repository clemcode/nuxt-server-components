<template>
  <div>
    <NuxtLink to="/" :prefetch="false">
      Server component
    </NuxtLink>
    <p>
      <code>date-fns</code> sera inclus sur cette page.
    </p>
    <HeavyClientComponent />
  </div>
</template>
