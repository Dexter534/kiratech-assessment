<template>
  <div
    class="grid grid-cols-6 gap-4 justify-between p-4 shadow-md rounded-md my-4 border"
  >
    <div class="grid gap-6 grid-cols-2 col-start-1 col-span-2">
      <div class="w-2/3 flex">
        <p class="text-left my-auto">{{ dateRegistered }}</p>
      </div>

      <div class="w-1/3">
        <p class="text-left">{{ firstname }} {{ lastname }}</p>
      </div>
    </div>

    <div class="grid gap-6 grid-cols-2 col-start-4 col-span-2">
      <div class="w-2/4 flex">
        <p class="text-left w-2/4 my-auto">
          {{ capitalizeFirstLetter(gender) }}
        </p>
      </div>

      <div class="w-2/4 flex">
        <p class="text-left w-2/4 my-auto">{{ country }}</p>
      </div>
    </div>
    <div class="flex">
      <p class="text-right my-auto">{{ email }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: [
    "dateRegistered",
    "firstname",
    "lastname",
    "gender",
    "country",
    "email",
  ],
  methods: {
    capitalizeFirstLetter(string) {
      return string.charAt(0).toUpperCase() + string.slice(1);
    },
  },
};
</script>
