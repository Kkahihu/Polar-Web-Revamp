<template>
  <header>
    <!-- Jumbotron -->
    <div class="container mx-auto px-6 flex relative py-16">
      <div class="sm:w-2/3 lg:w-2/5 flex flex-col relative z-20">
            <span class="w-20 h-2 bg-gray-800 dark:bg-white mb-12">
            </span>
        <h1 class="font-bebas-neue uppercase text-2xl sm:text-6xl font-black flex flex-col leading-none dark:text-white text-gray-800">
          UNLOCK THE POWER OF LOCATION
          <span class="text-xl sm:text-5xl text-orange-500">
            I N T E L I G E N C E
                </span>
        </h1>
        <p class="text-sm sm:text-base text-gray-700 dark:text-white">
          GEOSPATIAL DATA INSPIRED DECISION MAKING
        </p>
        <div class="flex mt-8">
          <a href="#" class="uppercase py-2 px-4 rounded-lg bg-orange-500 border-2 border-transparent text-white text-md mr-4 hover:bg-orange-400">
            Get started
          </a>
        </div>
      </div>
      <div class="hidden xl:block md:w-3/5 sm:w-1/3 lg:w-3/5 relative">
        <img src="../static/Around_the_world.gif" class="max-w-xl  md:max-w-xl m-auto" alt="Header_1"/>
      </div>
    </div>
    <!-- Jumbotron -->
  </header>

</template>

<script>
export default {
  name: "HeaderView"
}
</script>

<style scoped>

</style>
