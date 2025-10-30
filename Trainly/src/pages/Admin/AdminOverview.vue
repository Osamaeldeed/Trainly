<template>
  <section>
    <div>
      <h2 class="text-[24px] font-medium text-gray-900">Dashboard Overview</h2>
      <p class="mt-2 text-[16px] text-gray-500">
        Welcome back, here's what's happening today
      </p>
    </div>

    <!-- Cards Section -->
    <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
      <!-- Card 1 -->
      <div class="bg-white rounded-2xl shadow p-4">
        <h3 class="text-gray-700 font-medium text-[16px]">Total Trainers</h3>
        <p class="text-3xl font-semibold text-gray-900 mt-2">248</p>
        <p class="text-green-600 text-sm mt-1">+12% from last month</p>
      </div>

      <!-- Card 2 -->
      <div class="bg-white rounded-2xl shadow p-4">
        <h3 class="text-gray-700 font-medium text-[16px]">Total Trainees</h3>
        <p class="text-3xl font-semibold text-gray-900 mt-2">1,842</p>
        <p class="text-green-600 text-sm mt-1">+18% from last month</p>
      </div>

      <!-- Card 3 -->
      <div class="bg-white rounded-2xl shadow p-4">
        <h3 class="text-gray-700 font-medium text-[16px]">Active Sessions Today</h3>
        <p class="text-3xl font-semibold text-gray-900 mt-2">32</p>
        <p class="text-yellow-500 text-sm mt-1">8 pending approval</p>
      </div>

      <!-- Card 4 -->
      <div class="bg-white rounded-2xl shadow p-4">
        <h3 class="text-gray-700 font-medium text-[16px]">Monthly Revenue</h3>
        <p class="text-3xl font-semibold text-gray-900 mt-2">$45,280</p>
        <p class="text-green-600 text-sm mt-1">+23% from last month</p>
      </div>
    </div>
  </section>
</template>


<script>
export default {
  name: "AdminOverview",
};
</script>