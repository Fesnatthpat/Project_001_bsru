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
                <AppNavbar-2 />

                <!-- box-item-PJ -->
                <div
                    class="bg-white relative flex flex-col items-center w-full max-w-[95%] sm:max-w-full md:w-[990px] lg:max-w-[990px] xl:max-w-[1200px] h-auto mt-5 rounded-2xl p-5">
                    <div class="text-[24px] sm:text-[30px] text-center mt-2">เสนอหัวข้อ</div>
                    <div class="mt-5 w-full">
                        <div class="border border-gray-400 w-full h-auto rounded-[5px] p-4 sm:p-5">
                            <div class="flex flex-col gap-y-3">
                                <div class="flex flex-col">
                                    <label class="text-black font-bold" for="">ชื่อหัวข้อ</label>
                                    <input class="border border-black rounded-sm p-2" type="text" placeholder="">
                                </div>
                                <div class="flex flex-col">
                                    <label class="text-black font-bold" for="">คู่โปรเจกค์</label>
                                    <input class="border border-black rounded-sm p-2" type="text" placeholder="">
                                </div>
                                <div class="flex flex-col">
                                    <label class="text-black font-bold" for="">ไฟล์สไลด</label>
                                    <input class="border border-black rounded-sm p-2" type="text" placeholder="">
                                </div>
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
