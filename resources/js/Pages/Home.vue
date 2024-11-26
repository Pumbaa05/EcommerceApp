<script setup>
import MainLayout from "@/Layouts/MainLayout.vue";
import { Head } from "@inertiajs/vue3";
</script>
<template>
    <Head title="Home" />

    <MainLayout>
        <div class="py-12">
            <div class="mx-auto max-w-7xl sm:px-6 lg:px-8">
                <div class="overflow-hidden bg-white shadow-sm sm:rounded-lg">
                    <div class="p-6 text-gray-900">
                        Welcome to your Inertia.js app!
                    </div>
                </div>
            </div>
        </div>
    </MainLayout>
</template>
