<template>
  <div>
    <index-navbar />
    <section
      class="header relative pt-16 items-center flex h-screen max-h-860-px"
    >
      <div class="container mx-auto items-center flex flex-wrap">
        <div class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4">
          <div class="pt-32 sm:pt-0">
            <h2 class="font-semibold text-2xl text-blueGray-600">
              SOLUCIONES TECNOLOGICAS PIENCE-PCS.
            </h2>
            <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
              En  PIENCE PCS permanentemente  trabajamos en la búsqueda de nuevas ideas e  innovadoras formas  de  cumplir con  el objetivo  principal  que tenemos  como  empresa: ¡ Facilitarle su Gestión !
            </p>
            <div class="mt-12">
              <a
                href="https://wa.link/ms0vzg"
                target="_blank"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-emerald-500 active:bg-emerald-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                Contactanos 
              </a>
              <a
                href="#about"
                class="github-star ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
                
              >
                Sobre Nosotros
              </a>
            </div>
          </div>
        </div>
      </div>

      <img
        class="absolute top-0 b-auto right-0 pt-16 sm:w-6/12 -mt-48 sm:mt-0 w-10/12 max-h-860-px"
        src="../assets/img/pictureImg.svg"
        alt="..."
      />
    </section>

    <section id="section-two" class="mt-48 md:mt-40 pb-40 relative bg-blueGray-100">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon
            class="text-blueGray-100 fill-current"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>
      <div class="container mx-auto" >
        <div class="flex flex-wrap items-center">
          <div
            class=" w-12/12 md:w-6/12 lg:w-4/12 px-12 md:px-4 mr-auto ml-auto -mt-32"
          >
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg blue"
            >
              <img
                alt="..."
                src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=700&q=80"
                class="w-full  align-middle rounded-t-lg"
              />
              <blockquote class="blue relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="blue  fill-current"
                  ></polygon>
                </svg>
                <h4 class="text-xl font-bold text-white">
                  Lleva tu empresa a otro plano con nosotros
                </h4>
                <p id="about" class="text-md font-light mt-2 text-white">
                    Estamos certificados por ofimática en soporte y asesorías.
                    Actualizaciones de versión y capacitación a usuarios.
                    Desarrollo de reportes, implementación de nuevos módulos y específicos livianos para mejorar la herramienta.
                    Implementación de F.E. y realización de formatos para Facturación, Notas Crédito y Notas Debito.

                </p>
              </blockquote>
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4">
            <div class="flex flex-wrap">
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-sitemap"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Notas debito
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Implementacion y mejora en el sistema de notas debito 
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-drafting-compass"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Notas  Credito  
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Implementacion y mejora en el sistema de notas Credito
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col min-w-0 mt-4">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-newspaper"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">Soporte</h6>
                    <p class="mb-4 text-blueGray-500">
                      Soporte en línea y asesoría en el uso de la herramienta
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto">
                    <div
                      class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-file-alt"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Reportes
                    </h6>
                    <p class="mb-4 text-blueGray-500">
                      Reportes de ventas, compras, inventario, etc.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container mx-auto overflow-hidden pb-20">
        <div class="flex flex-wrap items-center">
          <div class="w-full md:w-4/12 px-12 md:px-4 ml-auto mr-auto mt-48">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
            >
              <i class="fas fa-sitemap text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal">
              Experiencia
            </h3>
            <p
              class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600"
            >
              Nuestra experiencia nos ha permitido llevar a cabo proyectos de
              gran complejidad, con una gran cantidad de requerimientos.
            </p>
            <div class="block pb-6">
              <span
                class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-white  last:mr-0 mr-2 mt-2"
                v-for="(item,idx) in  cardsInformation" :key="idx"
              >
                {{ item }}
              </span>              
            </div>
            <a
              href=""
              target="_blank"
              class="font-bold text-blueGray-700 hover:text-blueGray-500 ease-linear transition-all duration-150"
            >
              Contactanos
              <i class="fa fa-angle-double-right ml-1 leading-relaxed"></i>
            </a>
          </div>
          <div class="w-full md:w-5/12 px-4 mr-auto ml-auto mt-32">
            <div
              class="relative flex flex-col min-w-0 w-full mb-6 mt-48 md:mt-0"
            >
              <img
                alt="..."
                src="https://admin.catalogodesoftware.com/UserFiles/cso_files/multimedia/imagenes/producto/Ofima_Nomina_y_Gesti%C3%B3n_Humana_Ofima__Colombia.jpg"
                class="w-full align-middle rounded absolute shadow-lg max-w-100-px left-145-px -top-80-px z-3"
              />             
              <img
              v-if="resolutionDesktop>=1400"
                alt="..."
                :src="'https://www.ofima.mx/wp-content/uploads/2018/05/rp-enterprise-de-ofima-gestion-integral-en-tus-manos-2.jpg'"
                class="w-full align-middle rounded-lg absolute shadow-lg max-w-400-px left-0-px -top-100-px z-2"
              />
               
              <!-- <img
                alt="..."
                :src="componentBtnPink"
                class="w-full align-middle rounded absolute shadow-xl max-w-120-px left-195-px top-95-px"
              /> -->
            </div>
          </div>
        </div>
      </div>

      <div class="container mx-auto px-4 pb-32 pt-48">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-5/12 ml-auto px-12 md:px-4">
            <div class="md:pr-12">
              <div
                class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
              >
                <i class="fas fa-file-alt text-xl"></i>
              </div>
              <h3 class="text-3xl font-semibold">
                Ofima Experience
              </h3>
              <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
                This extension comes a lot of fully coded examples that help you
                get started faster. You can adjust the colors and also the
                programming language. You can change the text and images and
                you're good to go.
              </p>
              <ul class="list-none mt-6">
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-blueGray-50 mr-3"
                      >
                        <i class="fas fa-fingerprint"></i>
                      </span>
                    </div>
                    <div>
                      <h4 class="text-blueGray-500">
                        Built by Developers for Developers
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-blueGray-50 mr-3"
                      >
                        <i class="fab fa-html5"></i>
                      </span>
                    </div>
                    <div>
                      <h4 class="text-blueGray-500">
                        Carefully crafted code for Components
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xs font-semibold inline-block py-1 px-2 uppercase rounded-full text-blueGray-500 bg-blueGray-50 mr-3"
                      >
                        <i class="far fa-paper-plane"></i>
                      </span>
                    </div>
                    <div>
                      <h4 class="text-blueGray-500">
                        Dynamic Javascript Components
                      </h4>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>

          <div class="w-full md:w-6/12 mr-auto px-4 pt-24 md:pt-0">
            <img
              alt="..."
              class="max-w-full rounded-lg shadow-xl"
              style="
                transform: scale(1) perspective(1040px) rotateY(-11deg)
                  rotateX(2deg) rotate(2deg);
              "
              src="https://www.ofima.com/wp-content/uploads/2022/01/pantalla-dos.png"
            />
          </div>
        </div>
      </div>

      <div class="justify-center text-center flex flex-wrap mt-24">
        <div class="w-full md:w-6/12 px-12 md:px-4">
          <h2 class="font-semibold text-4xl">Piense SAS</h2>
          <p class="text-lg leading-relaxed mt-4 mb-4 text-blueGray-500">
           Asesorias contables y implementacion de mejoras en sistemas contables, En PIENSE SAS creamos un mundo de soluciones .
          </p>
        </div>
      </div>
    </section>
    <section class="block relative z-1 bg-blueGray-600">
      <div class="container mx-auto">
        <div class="justify-center flex flex-wrap">
          <div class="w-full lg:w-12/12 px-4 -mt-24">
            <div class="flex flex-wrap">
               <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Ofimatica
                </h5>
                <router-link to="/landing">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="landing"
                    />
                  </div>
                </router-link>
              </div>
              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Tecnologia
                </h5>
                <router-link to="/auth/login">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="login"
                    />
                  </div>
                </router-link>
              </div>

              <div class="w-full lg:w-4/12 px-4">
                <h5 class="text-xl font-semibold pb-4 text-center">
                  Servidores
                </h5>
                <router-link to="/profile">
                  <div
                    class="hover:-mt-4 relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg ease-linear transition-all duration-150"
                  >
                    <img
                      alt="..."
                      class="align-middle border-none max-w-full h-auto rounded-lg"
                      :src="profile"
                    />
                  </div>
                </router-link>
              </div>

             
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20 bg-blueGray-600 overflow-hidden">
      <div class="container mx-auto pb-64">
        <div class="flex flex-wrap justify-center">
          <div class="w-full md:w-5/12 px-12 md:px-4 ml-auto mr-auto md:mt-64">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
            >
              <i class="fas fa-code-branch text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal text-white">
              Nuestras garantias
            </h3>
            <p
              class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-400"
            >
              Simplemente
              <a
                href="https://tailwindcss.com/?ref=creativetim"
                class="text-blueGray-300"
                target="_blank"
              >
                Piense SAS
              </a>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ullam similique dignissimos placeat nobis repudiandae hic maiores accusamus rerum itaque voluptatum amet fugiat dicta inventore corporis sunt, molestiae excepturi cum alias?
            </p>
            <p
              class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-400"
            >
              Get it free on Github and please help us spread the news with a
              Star!
            </p>
            <a
              href=""
              target="_blank"
              class="github-star mt-4 inline-block text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
            >
              Contacto
            </a>
          </div>

          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto mt-32 relative">
            <img
              class="fab fa-github text-blueGray-700 text-55 absolute mt-32 right-50  opacity-80"
              src="https://cdn-icons-png.flaticon.com/512/1875/1875501.png"
            />
          </div>
        </div>
      </div>
    </section>

    <section class="pb-16 bg-blueGray-200 relative pt-32">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon
            class="text-blueGray-200 fill-current"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>

      <div class="container mx-auto">
        <div
          class="flex flex-wrap justify-center bg-white shadow-xl rounded-lg -mt-64 py-16 px-12 relative z-10"
        >
          <div class="w-full text-center lg:w-8/12">
            <p class="text-4xl text-center" id="about">
              <span role="img" aria-label="love">
                😍
              </span>
            </p>
            <h3 class="font-semibold text-3xl">
              ¿Quieres saber mas de nosotros?
            </h3>
            <p class="text-blueGray-500 text-lg leading-relaxed mt-4 mb-4">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam
              similique dignissimos placeat nobis repudiandae hic maiores
              accusamus rerum itaque voluptatum amet fugiat dicta inventore
              corporis sunt, molestiae excepturi cum alias?
            </p>
            <div class="sm:block flex flex-col mt-10">
              <a
                href=""
                target="_blank"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-2 bg-emerald-500 active:bg-emerald-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                Contactanos
              </a>
              <a
                href=""
                target="_blank"
                class="github-star sm:ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-blueGray-700 active:bg-blueGray-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                <i class="fab fa-github text-lg mr-1"></i>
                <span>Ver mas</span>
              </a>
            </div>
            <div class="text-center mt-16"></div>
          </div>
        </div>
      </div>
    </section>
    <footer-component />
  </div>
</template>
<script>
import IndexNavbar from "@/components/Navbars/IndexNavbar.vue";
import FooterComponent from "@/components/Footers/Footer.vue";

import patternVue from "@/assets/img/pattern_vue.png";
import componentBtn from "@/assets/img/component-btn.png";
import componentProfileCard from "@/assets/img/component-profile-card.png";
import componentInfoCard from "@/assets/img/component-info-card.png";
import componentInfo2 from "@/assets/img/component-info-2.png";
import componentMenu from "@/assets/img/component-menu.png";
import componentBtnPink from "@/assets/img/component-btn-pink.png";
import documentation from "@/assets/img/documentation.png";
import login from "@/assets/img/login.jpg";
import profile from "@/assets/img/profile.jpg";
import landing from "@/assets/img/landing.jpg";

export default {
    metaInfo() {
    return {
      title: "test meta data with vue",
      meta: [
        {
          vmid: "description",
          name: "description",
          content:
            "hello world, this is an example of adding a description with vueMeta",
        },
      ],
    };
  },
  data() {
    return {
      cardsInformation:[
        "facturaciòn",
        "Notas",
        "Sql server",
        "Soporte",
        "Tecnología",        
        "erp Ofimatica"
        
      ],
      patternVue,
      componentBtn,
      componentProfileCard,
      componentInfoCard,
      componentInfo2,
      componentMenu,
      componentBtnPink,
      documentation,
      login,
      profile,
      landing,
    };
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
  computed:{
    resolutionDesktop(){      
      return window.innerWidth;
    }
  }
  
};
</script>
<style>
.get-started {
  background-color: #0466C8;
}
.blue{
background-color: #0466C8;    
}
#section-two{
    margin-top: 300px;
}	

</style>
