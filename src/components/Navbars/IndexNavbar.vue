<template>
  <nav
    class="target__header top-0 fixed z-50 w-full flex flex-wrap items-center justify-between px-2 py-3 navbar-expand-lg bg-white shadow"
  >
    <div
      class="container px-4 mx-auto flex flex-wrap items-center justify-between"
    >
      <img class="target__logo sm:w-1/2 " src="../../assets/img/logo.jpg" alt="Piense Sas">
    
      <div
        class="w-full  mt-2  relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
      >        
          <p
            class="text-blueGray-700 text-sm font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercase mr-5"            
          >
            <img src="../../../public/logo.svg" alt="">
          </p>        
        <button
          class="cursor-pointer lg:bottom-10 text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden outline-none focus:outline-none"
          type="button"
          @click="setNavbarOpen"
        >
          <i class="fas fa-bars"></i>
        </button>
      </div>
      <div
        class="lg:flex flex-grow items-center"
        :class="[navbarOpen ? 'block' : 'hidden']"
        id="example-navbar-warning"
      >
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <index-dropdown />
          </li>        
          <li class="flex items-center">
            <button
              class="bg-blue-500  active:bg-blue-600 text-xs font-bold uppercase px-4 py-2 rounded shadow hover:shadow-lg outline-none focus:outline-none lg:mr-1 lg:mb-0 ml-3 mb-3 ease-linear transition-all duration-150"
              type="button"
              @click="$router.push('/landing')"
            >
              <i class="fas fa-id-card"></i>   Contactanos
            </button>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import IndexDropdown from "@/components/Dropdowns/IndexDropdown.vue";

export default {
  data() {
    return {
      navbarOpen: false,
    };
  },
  methods: {
    setNavbarOpen: function () {
      this.navbarOpen = !this.navbarOpen;
    },
  },
  components: {
    IndexDropdown,
  },
};
</script>
<style>

  .target__header{
    
  }
  .target__logo{
    height: 50px;
  }
</style>
