<template>
    <!-- Section container -->
    <section class="bg-gray-50 flex justify-center w-full" id="page-section">
        <!-- inner content -->
        <div class="max-w-7xl flex flex-col w-full px-8 py-12 justify-center">
            <!-- Title Section -->
            <h2 class="pb-6 border-b border-b-gray-200 w-full">Page Section</h2>
            <!-- Cards Section -->
            <div class="space-y-6 sm:space-y-10">
                <div class="grid grid-cols-1 gap-3 mt-10 md:grid-cols-2 lg:grid-cols-3 ">
                    <NuxtLink to="/herosection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">Hero sections</NuxtLink>
                    <NuxtLink to="/oficialsection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">Oficial sections</NuxtLink>
                    <NuxtLink to="/eventssection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">Events sections</NuxtLink>
                    <NuxtLink to="/newssection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">News sections</NuxtLink>
                    <NuxtLink to="/projectsection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">Projects sections</NuxtLink>
                    <NuxtLink to="/programsection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">Program sections</NuxtLink>
                    
                    <!-- Tests -->
                    <!-- <div class="flex flex-col">
                        <h4 class="text-sm text-gray-700 my-2">Hero Sections</h4>
                        <NuxtLink to="/herosection" class="flex justify-center items-center overflow-hidden border border-gray-200 hover:shadow-sm rounded-lg h-full min-h-[250px] bg-white">Hero sections</NuxtLink>
                    </div> -->    
                </div>
            </div>
        </div>
    </section>
</template>