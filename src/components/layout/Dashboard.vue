<template>
    <div class="bg-gray-800 text-white max-h-screen h-screen flex">
        <div class="w-32">
            <span class="font-semibold px-6 py-3 block">Skateboard</span>
            <nav class="p-6">
                <h3 class="opacity-50 uppercase font-semibold tracking-wider mb-6 text-xs">Menu</h3>
                <div class="space-y-6">
                    <div v-for="n of 10" class="flex items-center space-x-2">
                        <div class="bg-orange-500 p-1 rounded-lg">
                            <HomeIcon />
                        </div>
                        <span>Discover</span>
                    </div>
                </div>
            </nav>
        </div>
        <div class="border-2 border-red-500 flex-1">Content
            
        </div>
        </div>
</template>

<script lang="ts" setup>
import HomeIcon from '../icons/HomeIcon.vue';


</script>