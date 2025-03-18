<script setup lang="ts">
</script>

<template>
    <div class="min-h-screen w-full flex justify-center items-center">
        <!-- bg -->
        <div
            class="bg-gradient-to-t from-[#a9c9fb] to-[#1c66d6] rounded-2xl w-full p-5 lg:max-w-[1500px] h-auto lg:h-[800px] flex justify-center items-center">
            <!-- box-Project-container -->
            <div class="flex flex-col justify-center items-center w-full">
                <!-- Navbar -->
                <div
                    class="bg-white px-5 py-2 rounded-2xl overflow-x-auto scrollbar-none w-full max-w-[95%] md:w-full lg:w-[990px]">
                    <ul class="flex gap-5 text-black whitespace-nowrap">
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">หน้าหลัก
                        </NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                            เสอนหัวข้อ</NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                            ยื่นสอบหัวข้อ</NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">บทที่ 1
                        </NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">บทที่ 2
                        </NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">บทที่ 3
                        </NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">บทที่ 4
                        </NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">บทที่ 5
                        </NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                            ยื่นสอบจบ</NuxtLink>
                        <NuxtLink to="/" class="hover:bg-[#1c66d6] hover:text-white transition p-2 rounded-2xl">
                            ส่งเล่มบัณฑิตนิพนธ์</NuxtLink>
                    </ul>
                </div>

                <!-- box-item-PJ -->
                <div
                    class="bg-white relative flex flex-col items-center w-full max-w-[95%] sm:max-w-full md:w-[990px] lg:max-w-[990px] xl:max-w-[1200px] h-auto mt-5 rounded-2xl p-5">
                    <div class="text-[24px] sm:text-[30px] text-center mt-2">โครงงานของฉัน</div>
                    <div
                        class="bg-[#1c66d6] rounded-[5px] flex justify-center items-center text-white w-[60px] h-[30px] sm:w-[70px] sm:h-[40px] absolute right-5 top-5">
                        0%
                    </div>
                    <div class="mt-5 w-full">
                        <div class="border border-gray-400 w-full h-auto rounded-[5px] p-4 sm:p-5">
                            <h2 class="text-black text-lg sm:text-2xl">ชื่อโครงงาน:
                                ระบบบริหารจัดการโครงงานภาควิชาวิทยาการคอมพิวเตอร์</h2>
                            <h2 class="text-black text-lg sm:text-2xl">ชื่ออาจารย์ที่ปรึกษา: ดร.เกษม ตริตระการ</h2>
                            <h2 class="text-black text-lg sm:text-2xl">ชื่อเจ้าของโครงงาน: นางสาวนูรุลซะห์ลี เจ๊ะและ,
                                นายณัฐภัทร ภูมิเฆม</h2>
                            <div class="flex flex-col sm:flex-row sm:space-x-3 mt-3">
                                <h2 class="text-black text-lg sm:text-2xl">สถานะ:</h2>
                                <h2
                                    class="border border-red-500 rounded-[4px] p-1 text-black text-[16px] sm:text-[20px]">
                                    ยังไม่ยื่นสอบหัวข้อ</h2>
                            </div>
                            <div class="mt-4">
                                <button class="bg-[#1c66d6] text-white py-2 px-4 rounded-lg">คอมเมนต์</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
/* ซ่อน scrollbar */
::-webkit-scrollbar {
    display: none;
}

/* ซ่อน scrollbar ใน Firefox */
.scrollbar-none {
    -ms-overflow-style: none;
    /* Internet Explorer 10+ */
    scrollbar-width: none;
    /* Firefox */
}
</style>
