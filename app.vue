<template>
  <Body
    class="antialiased duration-300 transition-colors text-gray-800 dark:text-gray-200 bg-white dark:bg-gray-950"
  >
    <NuxtLayout>
      <Header />
      <header>
        <ul>
          <li>
            <NuxtLink to="/">Home</NuxtLink> 
            <NuxtLink to="/events">Events</NuxtLink> 
          </li>
        </ul>
      </header>
      <NuxtPage />
    </NuxtLayout>
  </Body>
</template>