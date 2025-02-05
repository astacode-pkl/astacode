<template>
    <div>
        <!-- ========== HEADER ========== -->
        <header
            class="bg-white fixed top-0 border-b border-gray-200 flex flex-wrap md:justify-start md:flex-nowrap z-50 h-20 w-full pt-2 lg:pt-0">
            <nav
                class="relative max-w-[85rem] w-full md:flex md:items-center md:justify-between md:gap-3 mx-auto px-4 sm:px-6 lg:px-8 py-2">
                <!-- Logo w/ Navigasi Button -->
                <div class="flex items-center justify-between">
                        <a href="#" aria-label="Brand"><img src="/assets/img/logo.png" alt="logo" class="w-48"></a>
                    <!-- Navigasi Button -->
                    <div class="md:hidden">
                        <button type="button"
                            class="hs-collapse-toggle relative size-9 flex justify-center items-center text-sm font-semibold rounded-lg border border-gray-200 text-gray-800 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 disabled:opacity-50 disabled:pointer-events-none"
                            id="hs-header-classic-collapse" aria-expanded="false" aria-controls="hs-header-classic"
                            aria-label="Toggle navigation" data-hs-collapse="#hs-header-classic">
                            <svg class="hs-collapse-open:hidden size-4" xmlns="http://www.w3.org/2000/svg" width="24"
                                height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                                stroke-linecap="round" stroke-linejoin="round">
                                <line x1="3" x2="21" y1="6" y2="6" />
                                <line x1="3" x2="21" y1="12" y2="12" />
                                <line x1="3" x2="21" y1="18" y2="18" />
                            </svg>
                            <svg class="hs-collapse-open:block shrink-0 hidden size-4"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"
                                fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                                stroke-linejoin="round">
                                <path d="M18 6 6 18" />
                                <path d="m6 6 12 12" />
                            </svg>
                            <span class="sr-only">Toggle navigation</span>
                        </button>
                    </div>
                    <!-- End Navigasi Button -->
                </div>
                <!-- End Logo w/ Navigasi Button -->

                <!-- Navigasi -->
                <div id="hs-header-classic"
                    class="hs-collapse hidden overflow-hidden transition-all duration-300 basis-full grow md:block bg-white w-full pl-5"
                    aria-labelledby="hs-header-classic-collapse">
                    <div
                        class="overflow-hidden overflow-y-auto max-h-[75vh] [&::-webkit-scrollbar]:w-2 [&::-webkit-scrollbar-thumb]:rounded-full [&::-webkit-scrollbar-track]:bg-gray-100 [&::-webkit-scrollbar-thumb]:bg-gray-300">
                        <div
                            class="py-2 md:py-0 flex flex-col md:flex-row md:items-center md:justify-center gap-0.5 md:gap-1">
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#" aria-current="page">
                                Home
                            </a>
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#">
                                About
                            </a>
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#">
                                Services
                            </a>
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#">
                                Projects
                            </a>
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#">
                                Team
                            </a>
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#">
                                Blog
                            </a>
                            <a class="p-2 flex items-center text-sm text-gray-800 hover:text-blue-600 focus:outline-none focus:text-blue-600"
                                href="#">
                                Contact
                            </a>
                        </div>
                    </div>
                </div>
                <!-- End Navigasi -->
                <div class="button">
                    <a href="#"
                        class="py-3 pl-5 w-40 hidden md:inline-flex items-center text-sm text-center font-medium rounded-xl border border-transparent bg-blue-700 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none">
                        Free Consultation
                    </a>
                </div>
            </nav>
        </header>
        <!-- ========== END HEADER ========== -->
    </div>
</template>