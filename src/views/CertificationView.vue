<template>
  <div class="px-5 py-10 md:px-16 md:py-14 text-left text-white mx-3">
    <div class="text-center mb-12">
      <h2 class="text-3xl font-bold mb-2">🎓 My Certifications</h2>
      <p class="text-sm text-amber-200">
        Explore my academic achievements and certifications
      </p>
    </div>

    <!-- Coursera Specializations -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-5 fade-zoom-in">
      <div
        v-for="(cert, index) in courseraCerts"
        :key="'coursera-' + index"
        class="rounded-xl border border-[#383838] bg-[#1e1e1f] p-5 hover:bg-[#282828] transition-transform duration-300 transform hover:-translate-y-2"
      >
        <a
          :href="cert.link"
          target="_blank"
          rel="noopener noreferrer"
          class="block"
        >
          <div
            class="text-lg font-semibold text-amber-50 hover:text-amber-300 transition"
          >
            {{ cert.title }}
          </div>
          <div class="text-xs text-gray-400 mt-1">
            {{ cert.issuer }}
          </div>
          <div class="text-[11px] text-amber-200 mt-2 underline">
            View Certificate →
          </div>
        </a>
      </div>
    </div>

    <!-- Academic Honors -->
    <div class="mt-16">
      <h3 class="text-2xl font-semibold mb-4">📘 Academic Honors</h3>
      <div class="overflow-x-auto rounded-xl border border-[#383838]">
        <table class="min-w-full table-auto text-sm text-left">
          <thead class="bg-[#2c2c2d] text-amber-300">
            <tr>
              <th class="px-4 py-3 border-b border-gray-600">Semester</th>
              <th class="px-4 py-3 border-b border-gray-600">
                Certificate Type
              </th>
              <th class="px-4 py-3 border-b border-gray-600">Link</th>
            </tr>
          </thead>
          <tbody class="text-amber-50 bg-[#1e1e1f]">
            <tr
              v-for="(honor, index) in academicHonors"
              :key="'honor-' + index"
              class="hover:bg-gradient-to-r hover:from-[#2a2a2b] hover:to-[#3a3a3b] transition duration-200"
            >
              <td class="px-4 py-3 border-b border-gray-700">
                {{ honor.semester }}
              </td>
              <td class="px-4 py-3 border-b border-gray-700">
                {{ honor.type }}
              </td>
              <td class="px-4 py-3 border-b border-gray-700">
                <a
                  :href="honor.link"
                  target="_blank"
                  class="text-blue-400 hover:underline hover:text-blue-300 font-medium flex items-center gap-1"
                >
                  📎 View Certificate
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- University Activities -->
    <div class="mt-16">
      <h3 class="text-2xl font-semibold mb-4">🎯 University Activities</h3>
      <div class="overflow-x-auto rounded-xl border border-[#383838]">
        <table class="min-w-full table-auto text-sm text-left">
          <thead class="bg-[#2c2c2d] text-amber-300">
            <tr>
              <th class="px-4 py-3 border-b border-gray-600">Semester</th>
              <th class="px-4 py-3 border-b border-gray-600">Activity</th>
            </tr>
          </thead>
          <tbody class="text-amber-50 bg-[#1e1e1f]">
            <tr
              v-for="(activity, index) in universityActivities"
              :key="'activity-' + index"
              class="hover:bg-gradient-to-r hover:from-[#2a2a2b] hover:to-[#3a3a3b] transition duration-200"
            >
              <td class="px-4 py-3 border-b border-gray-700">
                {{ activity.semester }}
              </td>
              <td class="px-4 py-3 border-b border-gray-700">
                {{ activity.description }}
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      courseraCerts: [
        {
          title: "Java Enterprise Edition",
          issuer: "LearnQuest",
          link: "https://coursera.org/share/1f6e54aada47520238f00ba6e5237d45",
        },
        {
          title: "Project Management Principles and Practices",
          issuer: "University of California, Irvine",
          link: "https://coursera.org/share/fbca135cfa167faf752984d56d4ad033",
        },
        {
          title: "User Experience Research and Design",
          issuer: "University of Michigan",
          link: "https://coursera.org/share/770f3f353ce6de1be52786ec9787f668",
        },
        {
          title: "Software Development Lifecycle",
          issuer: "University of Minnesota",
          link: "https://coursera.org/share/fc2d685e7033e8255f2280305ff0dc83",
        },
        {
          title: "CertNexus Certified Ethical Emerging Technologist",
          issuer: "CertNexus",
          link: "https://coursera.org/share/60930fa4eaf454c5df0190ef14da88b4",
        },
        {
          title: "Academic English: Writing",
          issuer: "University of California, Irvine",
          link: "https://coursera.org/share/4fcc577953750a68a1f5bcf0562157ba",
        },
        {
          title: "Web Design for Everybody",
          issuer: "University of Michigan",
          link: "https://coursera.org/share/7bfbe6f270dd25227b07176a76100585",
        },
        {
          title: "Computer Communications",
          issuer: "University of Colorado System",
          link: "https://coursera.org/share/bf702fa29412551ce9a875883baf72f2",
        },
        {
          title: "Academic Skills for University Success",
          issuer: "The University of Sydney",
          link: "https://coursera.org/share/c189457100acc409b2fb30fe16ebac9b",
        },
      ],
      academicHonors: [
        {
          semester: "Summer 2025",
          type: "Excellent Student",
          link: "https://fap.fpt.edu.vn/temp/f181d845-4833-42bb-8989-f0f55db17886.pdf",
        },
        {
          semester: "Spring 2025",
          type: "Excellent Student",
          link: "https://fap.fpt.edu.vn/temp/0a4262e3-1f81-496c-9881-f20c69b252a3.pdf",
        },
        {
          semester: "Fall 2024",
          type: "OJT Certificate – On the Job Training ",
          link: "https://fap.fpt.edu.vn/temp/f955a9c3-28a5-4c8e-b76d-4ec9cccad21d.pdf",
        },
        {
          semester: "Spring 2024",
          type: "Excellent Student",
          link: "https://fap.fpt.edu.vn/temp/75dfc389-89b3-4f76-b9b7-8c3009d908e7.pdf",
        },
      ],
      universityActivities: [
        {
          semester: "Fall 2022",
          description: "Certificate member Bro & Sis FPTU 2022 ",
        },
        {
          semester: "Fall 2023",
          description: "Top 20 Bro & Sis FPTU 2023 ",
        },
        {
          semester: "Fall 2025",
          description: "Certificate member Bro & Sis FPTU 2025 ",
        },
      ],
    };
  },
};
</script>
<style scoped>
.fade-zoom-in {
  animation: fadeZoomIn 1s ease-in-out;
}
@keyframes fadeZoomIn {
  from {
    opacity: 0;
    transform: scale(0.9);
  }
  to {
    opacity: 1;
    transform: scale(1);
  }
}
</style>
