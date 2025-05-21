<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
import { Link } from '@inertiajs/vue3';
import 'mdb-vue-ui-kit/css/mdb.min.css';

defineProps({
  laravelVersion: {
    type: String,
    required: true,
  },
  phpVersion: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <AppLayout title="Dashboard">
    <!-- Navigation Bar -->
        <nav class="bg-white shadow-sm">
        <div class="max-w-[1200px] mx-auto px-6">
            <div class="flex justify-end h-[70px] items-center">
            <div class="flex space-x-6 items-center text-sm font-medium">
                <Link href="/" class="text-gray-700 hover:text-green-600 no-underline">Home</Link>
                <Link href="/tentang-kami" class="text-gray-700 hover:text-green-600 no-underline">Tentang Kami</Link>
                <Link href="/solusi" class="text-gray-700 hover:text-green-600 no-underline">Solusi</Link>
                <Link href="/blog" class="text-gray-700 hover:text-green-600 no-underline">Blog</Link>
                <Link href="/kontak" class="text-gray-700 hover:text-green-600 no-underline">Contact</Link>
            </div>
            </div>
        </div>
        </nav>



    <!-- Page Content -->
    <section class="py-12 bg-gray-50 min-h-[calc(100vh-160px)]">
      <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
        <div class="bg-white shadow-md sm:rounded-lg p-6">
          <Welcome />
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-6 text-center text-sm text-gray-500">
      Laravel v{{ laravelVersion }} (PHP v{{ phpVersion }})
    </footer>
  </AppLayout>
</template>
