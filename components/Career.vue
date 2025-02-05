<template>
  <div>
    <!-- Hire Us -->
    <div
      class="max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-14 mx-auto mt-20"
    >
      <div class="max-w-xl mx-auto">
        <div class="text-center">
          <h1 class="text-3xl font-bold text-gray-800 sm:text-4xl">
            Astacode Career
          </h1>
          <p class="mt-1 text-gray-600">lets join with our team</p>
        </div>

        <div class="mt-12">
          <!-- Form -->
          <form>
            <div class="grid gap-4 lg:gap-6">
              <!-- Grid -->
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 lg:gap-6">
                <div>
                  <label class="block mb-2 text-sm text-gray-700 font-medium"
                    >First Name</label
                  >
                  <input
                    type="text"
                    class="py-3 px-4 block w-full border-black rounded-lg text-sm"
                  />
                </div>

                <div>
                  <label class="block mb-2 text-sm text-gray-700 font-medium"
                    >Last Name</label
                  >
                  <input
                    type="text"
                    class="py-3 px-4 block w-full border-black rounded-lg text-sm"
                  />
                </div>
              </div>
              <!-- End Grid -->

              <div>
                <label class="block mb-2 text-sm text-gray-700 font-medium"
                  >Email</label
                >
                <input
                  type="email"
                  class="py-3 px-4 block w-full border-black rounded-lg text-sm"
                />
              </div>

              <div>
                <label class="block mb-2 text-sm text-gray-700 font-medium"
                  >Phone</label
                >
                <input
                  type="number"
                  class="py-3 px-4 block w-full border-black rounded-lg text-sm"
                />
              </div>
            </div>
            <!-- End Grid -->

            <div class="mt-6 grid">
              <button
                type="submit"
                class="w-full py-3 px-4 inline-flex justify-center items-center gap-x-2 text-sm font-medium rounded-lg border border-transparent bg-blue-600 text-white hover:bg-blue-700 focus:outline-none focus:bg-blue-700 disabled:opacity-50 disabled:pointer-events-none"
              >
                Send
              </button>
            </div>
          </form>
          <!-- End Form -->
        </div>
      </div>
    </div>
    <!-- End Hire Us -->
  </div>
</template>
