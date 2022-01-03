<template>
  <div class="content flex">
    <nav>
      <NuxtLink to="/" class="selected">Overview</NuxtLink><br>
      <NuxtLink to="/tracker" class="not-selected">Tracker</NuxtLink>
    </nav>
    <section class="text">
      Never gonna give you up
    </section>
  </div>
</template>

<style>

.content {
  margin-left: 76px;
  margin-right: 76px;
}

.content > nav {
  font-min-size: 19px;
}

.selected {
  font-weight: 700;
}

.not-selected {
  color: rgba(255, 255, 255, 0.7);
}

@media only screen and (min-width: 600px) {
  .content {
    display: grid;
    grid-template-columns: 9fr 1fr;
  }
  .content > section {
    grid-area: 1 / 1 / 1 / 1;
  }
}

.content > nav {
  text-align: right;
}

</style>