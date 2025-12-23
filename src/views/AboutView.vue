<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: "ABAP",
          imageUrl:
            "https://img.icons8.com/?size=100&id=38192&format=png&color=000000",
          status: "Advance",
        },
        {
          id: 15,
          name: "SAP Fiori/UI5",
          imageUrl:
            "https://img.icons8.com/?size=100&id=38192&format=png&color=000000",
          status: "Intermediate",
        },
        {
          id: 2,
          name: "HTML",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/1051/1051277.png",
          status: "Advanced",
        },
        {
          id: 3,
          name: "CSS",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/732/732190.png",
          status: "Advanced",
        },
        {
          id: 4,
          name: "NextJS",
          imageUrl:
            "https://img.icons8.com/?size=100&id=r2OarXWQc7B6&format=png&color=000000",
          status: "Advanced",
        },
        {
          id: 5,
          name: "Javascript",
          imageUrl:
            "https://cdn.icon-icons.com/icons2/2415/PNG/512/javascript_original_logo_icon_146455.png",
          status: "Advance",
        },

        {
          id: 6,
          name: "JAVA",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/226/226777.png",
          status: "Intermediate",
        },
        {
          id: 7,
          name: "Redux",
          imageUrl:
            "https://img.icons8.com/?size=100&id=jD-fJzVguBmw&format=png&color=000000",
          status: "Intermediate",
        },
        {
          id: 8,
          name: "C",
          imageUrl:
            "https://img.icons8.com/?size=100&id=shQTXiDQiQVR&format=png&color=000000",
          status: "Intermediate",
        },
        {
          id: 9,
          name: "NodeJS",
          imageUrl:
            "https://cdn.iconscout.com/icon/free/png-256/free-node-js-1174925.png",
          status: "Beginner",
        },
        {
          id: 10,
          name: "Tailwind",
          imageUrl:
            "https://upload.wikimedia.org/wikipedia/commons/d/d5/Tailwind_CSS_Logo.svg",
          status: "Advance",
        },
        {
          id: 11,
          name: "Bootstrap",
          imageUrl:
            "https://getbootstrap.com/docs/5.2/assets/brand/bootstrap-logo-shadow.png",
          status: "Intermediate",
        },
        {
          id: 12,
          name: "ReactJS",
          imageUrl:
            "https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png",
          status: "Intermediate",
        },
        {
          id: 13,
          name: "Android",
          imageUrl:
            "https://img.icons8.com/?size=100&id=114405&format=png&color=000000",
          status: "Beginner",
        },
      ],
      tools: [
        {
          id: 1,
          name: "Git",
          imageUrl:
            "https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png",
          status: "Version Control",
        },
        {
          id: 2,
          name: "GitHub",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/25/25231.png",
          status: "Git Hosting",
        },
        {
          id: 3,
          name: "NPM",
          imageUrl:
            "https://cdn.iconscout.com/icon/free/png-256/free-npm-3-1175132.png",
          status: "Package Manager",
        },
        {
          id: 4,
          name: "MySQL",
          imageUrl: "https://cdn-icons-png.flaticon.com/512/5968/5968313.png",
          status: "Database",
        },
        {
          id: 5,
          name: "NetBeans",
          imageUrl:
            "https://img.icons8.com/?size=100&id=4djt356tq8UO&format=png&color=000000",
          status: "IDE",
        },
        {
          id: 6,
          name: "Docker",
          imageUrl:
            "https://img.icons8.com/?size=100&id=bf6MKm9Uf7uu&format=png&color=000000",
          status: "Containerization",
        },
        {
          id: 7,
          name: "Android Studio",
          imageUrl:
            "https://img.icons8.com/?size=100&id=04OFrkjznvcd&format=png&color=000000",
          status: "IDE",
        },
        {
          id: 8,
          name: "Figma",
          imageUrl:
            "https://img.icons8.com/?size=100&id=8gfeOoqrHqJU&format=png&color=000000",
          status: "Design Tool",
        },
        {
          id: 9,
          name: "Postman",
          imageUrl:
            "https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg",
          status: "API Testing",
        },
        {
          id: 10,
          name: "Visual Studio Code",
          imageUrl:
            "https://img.icons8.com/?size=100&id=9OGIyU8hrxW5&format=png&color=000000",
          status: "IDE",
        },
        {
          id: 11,
          name: "MongoDB",
          imageUrl:
            "https://img.icons8.com/?size=100&id=cREyrHivHRHF&format=png&color=000000",
          status: "Database",
        },
        {
          id: 12,
          name: "SAP GUI",
          imageUrl:
            "https://img.icons8.com/?size=100&id=38192&format=png&color=000000",
          status: "IDE",
        },
        {
          id: 13,
          name: "Eclipse / ADT",
          imageUrl:
            "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxPRKX0s-1ztZVZON615ptWlAvtYho3dOptw&s", // Eclipse icon
          status: "ABAP Development IDE",
        },
        {
          id: 14,
          name: "SAP Logon",
          imageUrl:
            "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTuCFIAoNYtQoJ7p2B0zpvRNTMAmxMQDc173Q&s", //
          status: "ABAP Environment",
        },
      ],
    };
  },
};
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5"
  >
    <article data-page="about">
      <header>
        <div
          class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center"
        >
          About Me &nbsp;
          <div
            class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate"
            data-aos="zoom-in-left"
            data-aos-duration="600"
          ></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center"
      >
        <div class="flex justify-center items-center">
          <img
            class="w-40 h-40 rounded-full object-cover fadein-up"
            src="/img/avatar.jpg"
            alt="Foto"
          />
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp;&nbsp;&nbsp;Hi! I'm Duy Hoang Too, a developer from Đăk Nông,
            Việt Nam, passionate about both SAP ABAP and web development. With
            hands-on experience in customizing SAP solutions (RICEFW,
            SmartForms, BAPI...) and front-end web design, I enjoy building
            systems that are both efficient and user-friendly.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp;&nbsp;&nbsp;To me, coding is more than work—it's creativity in
            action. Whether writing ABAP logic or building responsive websites,
            my goal is to deliver reliable, attractive solutions that help
            businesses run better. Let’s connect if you need someone who can
            bridge ERP and UI together.
          </p>
        </div>
      </section>
    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div
          class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center"
        >
          <div
            class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate"
            data-aos="zoom-in-left"
            data-aos-duration="600"
          ></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul
            class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5"
          >
            <li class="mr-2">
              <button
                class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{
                  'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1,
                }"
                @click="activeTab = 1"
              >
                Tech Stack
              </button>
            </li>
            <li class="mr-2">
              <button
                class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{
                  'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2,
                }"
                @click="activeTab = 2"
              >
                Tools
              </button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div
            class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12"
          >
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3"
              >
                <div
                  class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in"
                >
                  <img
                    alt="HTML"
                    loading="lazy"
                    width="32"
                    height="32"
                    decoding="async"
                    data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]"
                    :src="item.imageUrl"
                    style="color: transparent"
                  />
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div
                    class="tech font-medium text-secondary transition-all duration-300 translate-y-0"
                  >
                    {{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm"
                  >
                    {{ item.status }}
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
          <div
            class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12"
          >
            <div v-for="item in tools" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3"
              >
                <div
                  class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in"
                >
                  <img
                    alt="HTML"
                    loading="lazy"
                    width="32"
                    height="32"
                    decoding="async"
                    data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]"
                    :src="item.imageUrl"
                    style="color: transparent"
                  />
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div
                    class="tech font-medium text-secondary transition-all duration-300 translate-y-0"
                  >
                    {{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm"
                  >
                    {{ item.status }}
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
