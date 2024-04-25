<template>
  <div
    class="fixed h-screen w-screen inset-0 bg-gray-500 bg-opacity-75 transition-opacity border-2"
  ></div>
  <div class="fixed inset-0 z-10 w-screen">
    <div class="flex justify-center text-center min-h-full items-center">
      <div class="h-72 w-[600px] bg-white rounded-md p-10">
        <div class="flex justify-between">
          <h2 class="text-left font-bold text-2xl mb-4">
            {{ user.name.first }} {{ user.name.last }}
          </h2>

          <button class="h-2" @click="$emit('close')">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M6 18 18 6M6 6l12 12"
              />
            </svg>
          </button>
        </div>

        <div class="grid grid-cols-2 gap-4 justify-start">
          <div>
            <p class="text-left font-light text-gray-400">Date:</p>
          </div>
          <div>
            <p class="text-left">{{ formatDate(user.registered.date) }}</p>
          </div>

          <div><p class="text-left font-light text-gray-400">Gender:</p></div>
          <div>
            <p class="text-left">{{ capitalizeFirstLetter(user.gender) }}</p>
          </div>

          <div><p class="text-left font-light text-gray-400">Location:</p></div>
          <div>
            <p class="text-left">{{ user.location.country }}</p>
          </div>

          <div><p class="text-left font-light text-gray-400">Email:</p></div>
          <div>
            <p class="text-left">{{ user.email }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  emits: ["close"],
  props: ["user"],
  methods: {
    formatDate(originalDate) {
      let dateObj = new Date(originalDate);
      const options = { year: "numeric", month: "short", day: "2-digit" };
      const formattedDate = dateObj.toLocaleDateString("en-gb", options);
      return formattedDate;
    },
    capitalizeFirstLetter(string) {
      return string.charAt(0).toUpperCase() + string.slice(1);
    },
  },
};
</script>
