<template>
  <div class="md:container md:mx-auto">
    <nav>
      <div class="flex justify-between">
        <img alt="Kiratech Logo" src="./assets/logo.png" class="h-16" />

        <div class="flex mt-5">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6 mr-3"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M14.857 17.082a23.848 23.848 0 0 0 5.454-1.31A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6 9v.75a8.967 8.967 0 0 1-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 0 1-5.714 0m5.714 0a3 3 0 1 1-5.714 0"
            />
          </svg>

          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6 mr-3"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M9.594 3.94c.09-.542.56-.94 1.11-.94h2.593c.55 0 1.02.398 1.11.94l.213 1.281c.063.374.313.686.645.87.074.04.147.083.22.127.325.196.72.257 1.075.124l1.217-.456a1.125 1.125 0 0 1 1.37.49l1.296 2.247a1.125 1.125 0 0 1-.26 1.431l-1.003.827c-.293.241-.438.613-.43.992a7.723 7.723 0 0 1 0 .255c-.008.378.137.75.43.991l1.004.827c.424.35.534.955.26 1.43l-1.298 2.247a1.125 1.125 0 0 1-1.369.491l-1.217-.456c-.355-.133-.75-.072-1.076.124a6.47 6.47 0 0 1-.22.128c-.331.183-.581.495-.644.869l-.213 1.281c-.09.543-.56.94-1.11.94h-2.594c-.55 0-1.019-.398-1.11-.94l-.213-1.281c-.062-.374-.312-.686-.644-.87a6.52 6.52 0 0 1-.22-.127c-.325-.196-.72-.257-1.076-.124l-1.217.456a1.125 1.125 0 0 1-1.369-.49l-1.297-2.247a1.125 1.125 0 0 1 .26-1.431l1.004-.827c.292-.24.437-.613.43-.991a6.932 6.932 0 0 1 0-.255c.007-.38-.138-.751-.43-.992l-1.004-.827a1.125 1.125 0 0 1-.26-1.43l1.297-2.247a1.125 1.125 0 0 1 1.37-.491l1.216.456c.356.133.751.072 1.076-.124.072-.044.146-.086.22-.128.332-.183.582-.495.644-.869l.214-1.28Z"
            />
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15 12a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
            />
          </svg>

          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6 mr-3"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M15.75 9V5.25A2.25 2.25 0 0 0 13.5 3h-6a2.25 2.25 0 0 0-2.25 2.25v13.5A2.25 2.25 0 0 0 7.5 21h6a2.25 2.25 0 0 0 2.25-2.25V15m3 0 3-3m0 0-3-3m3 3H9"
            />
          </svg>
        </div>
      </div>
    </nav>
  </div>

  <!-- A bit of styling errors here, having trouble setting responsive breakpoints -->
  <section class="bg-cyan-600 relative h-44 mt-8 w-full">
    <div class="md:container md:mx-auto flex absolute top-8 left-44">
      <img alt="Profile picture" src="./assets/Avatar.png" class="h-44" />

      <div class="flex mt-12">
        <div class="ml-5">
          <h1 class="font-bold text-4xl text-white">John Doe</h1>
          <h2 class="text-white font-light text-sm">Last online: 2 days ago</h2>
        </div>

        <div class="ml-5 mt-5">
          <button
            class="bg-white text-cyan-600 hover:bg-cyan-600 hover:text-white hover:border font-bold py-2 px-4 rounded"
          >
            <span class="inline-flex align-middle">
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
                  d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"
                />
              </svg>

              <span class="ml-2"> Send Message </span>
            </span>
          </button>
          <button
            class="border bg-cyan-600 hover:bg-white text-white hover:text-cyan-600 font-bold py-2 px-4 rounded ml-4"
          >
            <span class="inline-flex align-middle">
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
                  d="M12 4.5v15m7.5-7.5h-15"
                />
              </svg>

              <span class="ml-2"> Add Friend </span>
            </span>
          </button>
        </div>
      </div>
    </div>
  </section>

  <!-- Sorting Function, sorts by date -->
  <div class="md:container md:mx-auto">
    <div class="mt-14 text-left">
      <p class="font-bold text-cyan-600">Sort by Date</p>
      <div>
        <label class="mr-2" for="asc">Ascending</label>
        <input
          class="mr-4"
          id="asc"
          type="radio"
          value="asc"
          v-model="sortValue"
        />
        <label class="mr-2" for="dsc">Descending</label>
        <input
          class="mr-4"
          id="dsc"
          type="radio"
          value="dsc"
          v-model="sortValue"
        />
      </div>
    </div>

    <!-- Beginning of user table, table headings -->
    <div
      class="grid grid-cols-6 gap-4 justify-between p-4 shadow-sm rounded-md my-4 text-slate-300 font-normal text-sm"
    >
      <div class="grid gap-6 grid-cols-2 col-start-1 col-span-2">
        <div class="w-2/3">
          <p class="text-left">Date Registered</p>
        </div>

        <div class="w-1/3">
          <p class="text-left">Name</p>
        </div>
      </div>

      <div class="grid gap-6 grid-cols-2 col-start-4 col-span-2">
        <div class="w-2/4">
          <p class="text-left">Gender</p>
        </div>

        <div class="w-2/4">
          <p class="text-left">Country</p>
        </div>
      </div>

      <div class="col-span-1">
        <p class="text-right">Email</p>
      </div>
    </div>

    <!-- Individual user rows -->
    <user-record
      v-for="(user, index) in users"
      :key="user.registered.date"
      :dateRegistered="formatDate(user.registered.date)"
      :firstname="user.name.first"
      :lastname="user.name.last"
      :gender="user.gender"
      :country="user.location.country"
      :email="user.email"
      @click="openModal(index)"
    ></user-record>

    <!-- User record modal -->
    <user-modal
      v-if="modalOpened"
      @close="closeModal"
      :user="selectedUser"
    ></user-modal>

    <button
      class="bg-cyan-700 hover:bg-cyan-500 text-white font-bold py-2 px-4 rounded mb-5"
      @click="loadData()"
    >
      <span class="inline-flex align-middle">
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
            d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0 3.181 3.183a8.25 8.25 0 0 0 13.803-3.7M4.031 9.865a8.25 8.25 0 0 1 13.803-3.7l3.181 3.182m0-4.991v4.99"
          />
        </svg>

        <span class="ml-2">Refresh</span>
      </span>
    </button>
  </div>
</template>

<script>
import UserModal from "./components/UserModal.vue";
import UserRecord from "./components/UserRecord.vue";

export default {
  name: "App",
  components: { UserRecord, UserModal },
  data() {
    return {
      isDataFetched: false,
      users: [],
      selectedUser: null,
      modalOpened: false,
      sortValue: null,
    };
  },
  watch: {
    // Radio buttons are binded to this.sortValue, if the value changes, sort asc or dsc
    sortValue(value) {
      let sortedUsers = [];

      if (value === "dsc") {
        sortedUsers = this.users.sort((a, b) => {
          return new Date(b.registered.date) - new Date(a.registered.date);
        });
      } else {
        sortedUsers = this.users.sort((a, b) => {
          return new Date(a.registered.date) - new Date(b.registered.date);
        });
      }

      this.users = sortedUsers;
    },
  },
  methods: {
    loadData() {
      this.users = [];
      fetch("https://randomuser.me/api/?results=20")
        .then((response) => {
          if (response.ok) {
            return response.json();
          }
        })
        .then((data) => {
          this.users = data.results;
        });
    },
    openModal(userIndex) {
      // Receives array index of user, passes assigns user object to selectedUser
      // selectedUser is passed as prop to modal
      this.modalOpened = true;
      this.selectedUser = this.users[userIndex];
    },
    closeModal() {
      // close event emitted from modal runs this function
      this.modalOpened = false;
    },
    formatDate(originalDate) {
      let dateObj = new Date(originalDate);
      const options = { year: "numeric", month: "short", day: "2-digit" };
      const formattedDate = dateObj.toLocaleDateString("en-gb", options);
      return formattedDate;
    },
  },
  // Data is fetched on mount
  mounted() {
    if (!this.isDataFetched) {
      this.loadData();
      this.isDataFetched = true;
    }
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
