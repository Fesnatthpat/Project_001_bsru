<script setup lang="ts">
import { useRoute } from 'vue-router';

const route = useRoute();
</script>

<template>
    <div
        class="bg-white px-5 py-2 rounded-2xl overflow-x-auto scrollbar-none w-full max-w-[95%] md:w-full lg:w-[990px]">
        <ul class="flex gap-5 text-black whitespace-nowrap">
            <NuxtLink to="/Page-Project" :class="{ 'bg-[#1c66d6] text-white': route.path === '/Page-Project' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                หน้าหลัก
            </NuxtLink>

            <NuxtLink to="/Page-Pj-1" :class="{ 'bg-[#1c66d6] text-white': route.path === '/Page-Pj-1' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                เสนอหัวข้อ
            </NuxtLink>

            <NuxtLink to="/Page-Pj-2" :class="{ 'bg-[#1c66d6] text-white': route.path === '/Page-Pj-2' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                ยื่นสอบหัวข้อ
            </NuxtLink>

            <NuxtLink to="/chapter-1" :class="{ 'bg-[#1c66d6] text-white': route.path === '/chapter-1' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                บทที่ 1
            </NuxtLink>

            <NuxtLink to="/chapter-2" :class="{ 'bg-[#1c66d6] text-white': route.path === '/chapter-2' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                บทที่ 2
            </NuxtLink>

            <NuxtLink to="/chapter-3" :class="{ 'bg-[#1c66d6] text-white': route.path === '/chapter-3' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                บทที่ 3
            </NuxtLink>

            <NuxtLink to="/chapter-4" :class="{ 'bg-[#1c66d6] text-white': route.path === '/chapter-4' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                บทที่ 4
            </NuxtLink>

            <NuxtLink to="/chapter-5" :class="{ 'bg-[#1c66d6] text-white': route.path === '/chapter-5' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                บทที่ 5
            </NuxtLink>

            <NuxtLink to="/final-exam" :class="{ 'bg-[#1c66d6] text-white': route.path === '/final-exam' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                ยื่นสอบจบ
            </NuxtLink>

            <NuxtLink to="/thesis-submission" :class="{ 'bg-[#1c66d6] text-white': route.path === '/thesis-submission' }"
                class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                ส่งเล่มบัณฑิตนิพนธ์
            </NuxtLink>
        </ul>
    </div>
</template>
