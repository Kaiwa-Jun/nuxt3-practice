<template>
  <h1>TOP</h1>
  <nav id="breadcrumbs">
    <ul>
      <li>TOP</li>
    </ul>
  </nav>
  <section>
    <p>
      <!-- <NuxtLink to="/member/memberList"> -->
      <NuxtLink v-bind:to="{ name: 'member-memberList' }">
        会員管理はこちら
      </NuxtLink>
    </p>
  </section>
</template>

<script></script>
