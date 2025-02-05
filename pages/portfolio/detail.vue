<template>
    <div class="container mx-auto max-w-5xl px-4 sm:px-6 lg:px-8 font-poppins">
        <div class="grid grid-cols-12 gap-8 p-3">
            <!-- Image Section -->
            <div class="col-span-12 md:col-span-8 w-full order-1">
                <img src="assets/img/project1.png" alt="portfolio.title" data-aos="fade-up" class="w-full h-48 sm:h-64 md:h-80 lg:h-96 
           object-cover 
           border 
           rounded-2xl 
           shadow-md 
           mb-6 
           transition-all 
           duration-300">

                <div>
                    <h1 class="text-3xl text-sky-600" data-aos="fade-down">Dialogoo Pos</h1>
                    <p class="text-gray-600 mt-2 text-sm">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum
                        libero, quo officia delectus commodi itaque molestiae voluptas cupiditate nam, quibusdam rem
                        am
                    </p>
                </div>
            </div>

            <!-- Card Section -->
            <div data-aos="fade-down"
                class="col-span-12 md:col-span-4 w-full flex flex-col bg-white border shadow-lg  rounded-xl order-2">
                <div class="bg-sky-500 w-full rounded-t-xl p-3">
                    <h2 class="text-lg text-white text-center font-semibold tracking-wide">Project Info</h2>
                </div>

                <div class="p-6 space-y-4">
                    <div class="flex flex-col space-y-1 pb-3 border-b border-gray-100">
                        <span class="text-sm text-gray-500 font-medium">Client</span>
                        <span class="text-base text-gray-800">Client Name</span>
                    </div>

                    <div class="flex flex-col space-y-1 pb-3 border-b border-gray-100">
                        <span class="text-sm text-gray-500 font-medium">Category</span>
                        <span class="text-base text-gray-800">Web Development</span>
                    </div>

                    <div class="flex flex-col space-y-1 pb-3 border-b border-gray-100">
                        <span class="text-sm text-gray-500 font-medium">Location</span>
                        <span class="text-base text-gray-800">Indonesia</span>
                    </div>

                    <div class="flex flex-col space-y-1">
                        <span class="text-sm text-gray-500 font-medium">Created</span>
                        <span class="text-base text-gray-800">January 2024</span>
                    </div>
                </div>
            </div>

            <!-- Challenge Section -->
            <div class="col-span-12 md:col-span-8 w-full order-3">
                <h1 class="text-3xl  text-sky-600 mb-4" data-aos="fade-up">Our Challenge</h1>
                <p class="text-gray-600 mb-6 text-sm">
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum
                    libero, quo officia delectus commodi itaque molestiae voluptas cupiditate nam, quibusdam rem
                    amet iusto quas fuga voluptatem ducimus non. Earum, facilis.
                </p>

                <!-- Features List -->
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-6">
                    <div class="flex items-center space-x-3">
                        <svg class="w-5 h-5 text-sky-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <span class="text-black">Best Price</span>
                    </div>

                    <div class="flex items-center space-x-3">
                        <svg class="w-5 h-5 text-sky-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <span class="text-black">Dedicated Team</span>
                    </div>

                    <div class="flex items-center space-x-3">
                        <svg class="w-5 h-5 text-sky-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <span class="text-black">24/7 Available For Contact</span>
                    </div>

                    <div class="flex items-center space-x-3">
                        <svg class="w-5 h-5 text-sky-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <span class="text-black">100% Satisfaction</span>
                    </div>

                    <div class="flex items-center space-x-3">
                        <svg class="w-5 h-5 text-sky-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <span class="text-black">Best Quality</span>
                    </div>

                    <div class="flex items-center space-x-3">
                        <svg class="w-5 h-5 text-sky-500" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                        </svg>
                        <span class="text-black">Fast Work</span>
                    </div>
                </div>
            </div>

            <!-- Result -->
            <div class="col-span-12 md:col-span-8 w-full order-3">
                <h1 class="text-3xl text-sky-600 mb-4">The Result of Project</h1>
                <p class="text-gray-600 mb-6 text-sm">
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum
                    libero, quo officia delectus commodi itaque molestiae voluptas cupiditate nam, quibusdam rem
                    amet iusto quas fuga voluptatem ducimus non. Earum, facilis.
                </p>


            </div>
        </div>

        <!-- Next Project Section -->
        <div class="mt-16 mb-10">
            <nuxt-link to="/portfolio"
                class="group relative block rounded-2xl overflow-hidden bg-white border border-sky-200 shadow-sm hover:shadow-md transition-all duration-300 hover:-translate-y-1">
                <div class="absolute inset-0 transition-opacity group-hover:opacity-20"></div>

                <div class="relative flex items-center justify-between p-8">
                    <div class="flex items-center space-x-4">
                        <!-- Thumbnail -->
                        <div class="w-16 h-16 rounded-lg overflow-hidden">
                            <img src="assets/img/project2.png" alt="Next Project"
                                class="w-full h-full object-cover transform group-hover:scale-110 transition-transform duration-300">
                        </div>

                        <!-- Text -->
                        <div class="text-black">
                            <p class="text-sm opacity-80">Next Project</p>
                            <h3 class="text-xl text-sky-600 mt-1">Sistem Event Perdosi</h3>
                        </div>
                    </div>

                    <!-- Arrow -->
                    <div class="flex items-center text-sky-500 space-x-2">
                        <span class="text-sm font-medium ">
                            View Project
                        </span>
                        <svg class="w-6 h-6 transform transition-transform group-hover:translate-x-2" fill="none"
                            stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M17 8l4 4m0 0l-4 4m4-4H3" />
                        </svg>
                    </div>
                </div>
            </nuxt-link>
        </div>
    </div>
</template>

<style>
/* Import Poppins font */
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');

/* Define font family */
.font-poppins {
    font-family: 'Poppins', sans-serif;
}
</style>