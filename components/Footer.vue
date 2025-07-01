<template>
  <footer class="bg-gray-900 text-white py-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid md:grid-cols-4 gap-8">
        <div class="col-span-2">
          <div class="flex items-center space-x-2 mb-6">
            <span class="text-2xl font-bold">EPITECH Barcelona</span>
          </div>
          <p class="text-gray-400 mb-6 max-w-md">
            Your gateway to an amazing student experience in Barcelona.
            Discover, learn, and thrive in one of Europe's most vibrant cities.
          </p>
          <div class="flex space-x-4">
            <a
              href="https://www.instagram.com/epitech.spain/"
              class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  fill="currentColor"
                  d="M12 0C8.74 0 8.333.015 7.053.072C5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053C.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913a5.885 5.885 0 0 0 1.384 2.126A5.868 5.868 0 0 0 4.14 23.37c.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558a5.898 5.898 0 0 0 2.126-1.384a5.86 5.86 0 0 0 1.384-2.126c.296-.765.499-1.636.558-2.913c.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913a5.89 5.89 0 0 0-1.384-2.126A5.847 5.847 0 0 0 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071c1.17.055 1.805.249 2.227.415c.562.217.96.477 1.382.896c.419.42.679.819.896 1.381c.164.422.36 1.057.413 2.227c.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227a3.81 3.81 0 0 1-.899 1.382a3.744 3.744 0 0 1-1.38.896c-.42.164-1.065.36-2.235.413c-1.274.057-1.649.07-4.859.07c-3.211 0-3.586-.015-4.859-.074c-1.171-.061-1.816-.256-2.236-.421a3.716 3.716 0 0 1-1.379-.899a3.644 3.644 0 0 1-.9-1.38c-.165-.42-.359-1.065-.42-2.235c-.045-1.26-.061-1.649-.061-4.844c0-3.196.016-3.586.061-4.861c.061-1.17.255-1.814.42-2.234c.21-.57.479-.96.9-1.381c.419-.419.81-.689 1.379-.898c.42-.166 1.051-.361 2.221-.421c1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324a6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4s4 1.79 4 4s-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 0 1-2.88 0a1.44 1.44 0 0 1 2.88 0z"
                />
              </svg>
            </a>
            <a
              href="https://www.epitech-it.es/"
              class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="w-5 h-5"
                viewBox="0 0 24 24"
              >
                <path
                  fill="currentColor"
                  d="M16.36 14c.08-.66.14-1.32.14-2c0-.68-.06-1.34-.14-2h3.38c.16.64.26 1.31.26 2s-.1 1.36-.26 2m-5.15 5.56c.6-1.11 1.06-2.31 1.38-3.56h2.95a8.03 8.03 0 0 1-4.33 3.56M14.34 14H9.66c-.1-.66-.16-1.32-.16-2c0-.68.06-1.35.16-2h4.68c.09.65.16 1.32.16 2c0 .68-.07 1.34-.16 2M12 19.96c-.83-1.2-1.5-2.53-1.91-3.96h3.82c-.41 1.43-1.08 2.76-1.91 3.96M8 8H5.08A7.923 7.923 0 0 1 9.4 4.44C8.8 5.55 8.35 6.75 8 8m-2.92 8H8c.35 1.25.8 2.45 1.4 3.56A8.008 8.008 0 0 1 5.08 16m-.82-2C4.1 13.36 4 12.69 4 12s.1-1.36.26-2h3.38c-.08.66-.14 1.32-.14 2c0 .68.06 1.34.14 2M12 4.03c.83 1.2 1.5 2.54 1.91 3.97h-3.82c.41-1.43 1.08-2.77 1.91-3.97M18.92 8h-2.95a15.65 15.65 0 0 0-1.38-3.56c1.84.63 3.37 1.9 4.33 3.56M12 2C6.47 2 2 6.5 2 12a10 10 0 0 0 10 10a10 10 0 0 0 10-10A10 10 0 0 0 12 2Z"
                />
              </svg>
            </a>
            <a
              href="https://www.linkedin.com/company/epitech-spain/"
              class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors"
            >
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path
                  d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"
                />
              </svg>
            </a>
            <a
              class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-blue-600 transition-colors"
              href="https://www.youtube.com/@Epitech-Spain"
            >
              <svg
                fill="#ffffff"
                class="w-5 h-5"
                viewBox="0 0 32 32"
                version="1.1"
                xmlns="http://www.w3.org/2000/svg"
                stroke="#ffffff"
              >
                <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                <g
                  id="SVGRepo_tracerCarrier"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                ></g>
                <g id="SVGRepo_iconCarrier">
                  <title>youtube</title>
                  <path
                    d="M12.932 20.459v-8.917l7.839 4.459zM30.368 8.735c-0.354-1.301-1.354-2.307-2.625-2.663l-0.027-0.006c-3.193-0.406-6.886-0.638-10.634-0.638-0.381 0-0.761 0.002-1.14 0.007l0.058-0.001c-0.322-0.004-0.701-0.007-1.082-0.007-3.748 0-7.443 0.232-11.070 0.681l0.434-0.044c-1.297 0.363-2.297 1.368-2.644 2.643l-0.006 0.026c-0.4 2.109-0.628 4.536-0.628 7.016 0 0.088 0 0.176 0.001 0.263l-0-0.014c-0 0.074-0.001 0.162-0.001 0.25 0 2.48 0.229 4.906 0.666 7.259l-0.038-0.244c0.354 1.301 1.354 2.307 2.625 2.663l0.027 0.006c3.193 0.406 6.886 0.638 10.634 0.638 0.38 0 0.76-0.002 1.14-0.007l-0.058 0.001c0.322 0.004 0.702 0.007 1.082 0.007 3.749 0 7.443-0.232 11.070-0.681l-0.434 0.044c1.298-0.362 2.298-1.368 2.646-2.643l0.006-0.026c0.399-2.109 0.627-4.536 0.627-7.015 0-0.088-0-0.176-0.001-0.263l0 0.013c0-0.074 0.001-0.162 0.001-0.25 0-2.48-0.229-4.906-0.666-7.259l0.038 0.244z"
                  ></path>
                </g>
              </svg>
            </a>
          </div>
        </div>
        <div>
          <h3 class="font-bold text-lg mb-6">Quick Links</h3>
          <ul class="space-y-3">
            <li>
              <a
                @click="$router.push('/live-in-barcelona')"
                class="text-gray-400 hover:text-white transition-colors"
                >Live in Barcelona</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/explore-barcelona')"
                class="text-gray-400 hover:text-white transition-colors"
                >Explore Barcelona</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/tips-and-tricks')"
                class="text-gray-400 hover:text-white transition-colors"
                >Tips & Tricks</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/spanish-essentials')"
                class="text-gray-400 hover:text-white transition-colors"
                >Spanish Essentials</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/epitech-barcelona')"
                class="text-gray-400 hover:text-white transition-colors"
                >EPITECH Barcelona</a
              >
            </li>
          </ul>
        </div>
        <div>
          <h3 class="font-bold text-lg mb-6">Resources</h3>
          <ul class="space-y-3 hover:text-underline">
            <li>
              <a
                @click="
                  $router.push('/live-in-barcelona/administrative-formalities')
                "
                class="text-gray-400 hover:text-white hover:text-underline transition-colors"
                >Administrative Formalities</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/live-in-barcelona/accomodations')"
                class="text-gray-400 hover:text-white hover:text-underline transition-colors"
                >Housing Help</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/live-in-barcelona/lifestyle')"
                class="text-gray-400 hover:text-white hover:text-underline transition-colors"
                >Lifestyle
              </a>
            </li>
            <li>
              <a
                @click="$router.push('/live-in-barcelona/transports')"
                class="text-gray-400 hover:text-white hover:text-underline transition-colors"
                >Transportation</a
              >
            </li>
            <li>
              <a
                @click="$router.push('/tips-and-tricks')"
                class="text-gray-400 hover:text-white hover:text-underline transition-colors"
                >Emergency Contacts</a
              >
            </li>
          </ul>
        </div>
      </div>
      <div
        class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400"
      >
        <p>
          &copy; Made with ❤️ by Angel Halouane - EPITECH Barcelona. All rights
          reserved.
        </p>
      </div>
    </div>
  </footer>
</template>
