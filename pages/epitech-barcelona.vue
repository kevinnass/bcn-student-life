<template>
  <div class="min-h-screen bg-white">
    <Header />

    <!-- Hero Section -->
    <section class="py-10 lg:py-7">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
          <div
            class="inline-flex items-center px-4 py-2 bg-blue-100 text-blue-800 rounded-full text-sm font-medium mb-6"
          >
            <svg
              class="w-4 h-4 mr-2"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"
              ></path>
            </svg>
            EPITECH BARCELONA
          </div>
          <h1
            class="text-3xl lg:text-6xl font-bold text-gray-900 mb-8 leading-tight"
          >
            <span class="text-blue-300">{ </span> THE BEST OF
            <span class="text-blue-600">INNOVATION</span>
            <span class="text-blue-300"></span>
            <br class="hidden lg:block" />
            <span class="text-blue-300"></span> THE FUTURE OF
            <span class="text-blue-600">SOFTWARE</span>
            <span class="text-blue-300"> }</span>
          </h1>
        </div>

        <!-- Hero Image -->
        <div class="relative mb-8">
          <div class="text-center p-6">
            <h2 class="text-3xl font-bold text-gray-900 mb-4">
              Epitech: it's not just your education, but a revolution
            </h2>
            <p class="text-gray-700 text-lg">
              Founded in 1999 in Paris, Epitech is a world-leading educational
              institution in computer science and technology. With a unique
              focus on hands-on learning and collaboration, Epitech empowers its
              students to become leaders in the technology industry.
            </p>
          </div>
          <div class="relative overflow-hidden rounded-3xl shadow-2xl">
            <video
              src="/epitech-barcelona-campus.mp4"
              autoplay
              loop
              muted
              playsinline
              class="w-full lg:h-[650px] object-cover"
            ></video>
            <div
              class="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent"
            ></div>
            <div class="absolute bottom-8 left-8 right-8"></div>
          </div>
        </div>

        <!-- Mission Statement -->
        <div class="text-center mb-16">
          <div
            class="bg-gradient-to-r from-blue-50 to-purple-50 rounded-3xl p-8 lg:p-12"
          >
            <blockquote
              class="text-xl lg:text-2xl italic text-blue-600 font-bold max-w-4xl mx-auto"
            >
              "At Epitech, we train innovators and technology leaders with a
              unique focus on hands-on learning, collaboration and real-world
              problem solving."
            </blockquote>
          </div>
        </div>

        <!-- Student Council Section -->
        <div class="mb-20">
          <div
            class="relative bg-gradient-to-br from-orange-50 via-yellow-50 to-red-50 rounded-3xl p-8 lg:p-16 overflow-hidden"
          >
            <!-- Background Pattern -->
            <div class="absolute inset-0 opacity-10">
              <div class="absolute top-10 left-10 w-4 h-4 animate-pulse">
                🎉
              </div>
              <div class="absolute top-20 right-20 w-3 h-3 animate-pulse">
                🎉
              </div>
              <div class="absolute bottom-20 left-20 w-5 h-5 animate-pulse">
                🎉
              </div>
              <div class="absolute bottom-10 right-10 w-2 h-2 animate-pulse">
                🎉
              </div>
            </div>

            <div class="relative grid lg:grid-cols-2 gap-12 items-center">
              <!-- Content Side -->
              <div class="lg:order-1">
                <div
                  class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-orange-100 to-yellow-100 text-orange-800 rounded-full text-sm font-medium mb-6"
                >
                  <svg
                    class="w-4 h-4 mr-2"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"
                    ></path>
                  </svg>
                  STUDENT COUNCIL
                </div>

                <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-6">
                  The Heart of Our
                  <span
                    class="bg-gradient-to-r from-orange-600 to-red-600 bg-clip-text text-transparent"
                  >
                    Community
                  </span>
                </h2>

                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                  Our Student Council is the beating heart of EPITECH Barcelona!
                  These amazing students work tirelessly to create unforgettable
                  experiences, organize epic events, and build the incredible
                  community spirit that makes our campus feel like home.
                </p>

                <div class="space-y-4 mb-8">
                  <div class="flex items-start space-x-3">
                    <div
                      class="flex-shrink-0 w-6 h-6 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center"
                    >
                      <svg
                        class="w-3 h-3 text-white"
                        fill="none"
                        stroke="currentColor"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M5 13l4 4L19 7"
                        ></path>
                      </svg>
                    </div>
                    <p class="text-gray-700">
                      <strong>Activities:</strong> From volleyball, Marathons to
                      Foosball all the way to even Chess tournaments, we want to
                      keep our students active.
                    </p>
                  </div>
                  <div class="flex items-start space-x-3">
                    <div
                      class="flex-shrink-0 w-6 h-6 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center"
                    >
                      <svg
                        class="w-3 h-3 text-white"
                        fill="none"
                        stroke="currentColor"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M5 13l4 4L19 7"
                        ></path>
                      </svg>
                    </div>
                    <p class="text-gray-700">
                      <strong>Epic events:</strong> They organize BBQs, Karting
                      tournaments, Cinema nights and you definitely shouldn't
                      miss the infinite game nights!
                    </p>
                  </div>
                  <div class="flex items-start space-x-3">
                    <div
                      class="flex-shrink-0 w-6 h-6 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center"
                    >
                      <svg
                        class="w-3 h-3 text-white"
                        fill="none"
                        stroke="currentColor"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M5 13l4 4L19 7"
                        ></path>
                      </svg>
                    </div>
                    <p class="text-gray-700">
                      <strong>Student Voice:</strong> They represent your ideas
                      and make sure your voice is heard!
                    </p>
                  </div>
                  <div class="flex items-start space-x-3">
                    <div
                      class="flex-shrink-0 w-6 h-6 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center"
                    >
                      <svg
                        class="w-3 h-3 text-white"
                        fill="none"
                        stroke="currentColor"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M5 13l4 4L19 7"
                        ></path>
                      </svg>
                    </div>
                    <p class="text-gray-700">
                      <strong>Community Building:</strong> Creating connections
                      that last way beyond graduation!
                    </p>
                  </div>
                </div>

                <div class="flex flex-col sm:flex-row gap-4">
                  <a
                    href="https://www.instagram.com/epitech.sc.bcn/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-pink-500 to-purple-600 text-white rounded-full font-semibold hover:shadow-lg transform hover:-translate-y-1 transition-all duration-300"
                  >
                    <svg
                      class="w-5 h-5 mr-2"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 24 24"
                    >
                      <path
                        fill="currentColor"
                        d="M12 0C8.74 0 8.333.015 7.053.072C5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053C.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913a5.885 5.885 0 0 0 1.384 2.126A5.868 5.868 0 0 0 4.14 23.37c.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558a5.898 5.898 0 0 0 2.126-1.384a5.86 5.86 0 0 0 1.384-2.126c.296-.765.499-1.636.558-2.913c.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913a5.89 5.89 0 0 0-1.384-2.126A5.847 5.847 0 0 0 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071c1.17.055 1.805.249 2.227.415c.562.217.96.477 1.382.896c.419.42.679.819.896 1.381c.164.422.36 1.057.413 2.227c.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227a3.81 3.81 0 0 1-.899 1.382a3.744 3.744 0 0 1-1.38.896c-.42.164-1.065.36-2.235.413c-1.274.057-1.649.07-4.859.07c-3.211 0-3.586-.015-4.859-.074c-1.171-.061-1.816-.256-2.236-.421a3.716 3.716 0 0 1-1.379-.899a3.644 3.644 0 0 1-.9-1.38c-.165-.42-.359-1.065-.42-2.235c-.045-1.26-.061-1.649-.061-4.844c0-3.196.016-3.586.061-4.861c.061-1.17.255-1.814.42-2.234c.21-.57.479-.96.9-1.381c.419-.419.81-.689 1.379-.898c.42-.166 1.051-.361 2.221-.421c1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324a6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4s4 1.79 4 4s-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 0 1-2.88 0a1.44 1.44 0 0 1 2.88 0z"
                      />
                    </svg>
                    Follow on Instagram
                  </a>
                </div>
              </div>

              <!-- Polaroid Image Side -->
              <div class="lg:order-2 relative">
                <div class="relative max-w-md mx-auto">
                  <!-- Main Polaroid -->
                  <div
                    class="relative pb-16 bg-white rounded-2xl shadow-2xl transform -rotate-2 hover:rotate-0 transition-all duration-500 group"
                  >
                    <!-- Polaroid Image -->
                    <div class="relative rounded-lg">
                      <img
                        src="/student-council-polaroids.png"
                        alt="Student Council Memories"
                        class="w-full h-full rounded-2xl transition-transform duration-500"
                      />
                    </div>
                  </div>

                  <!-- Floating Mini Polaroids -->
                  <div
                    class="absolute -top-10 -left-10 bg-white p-2 pb-6 rounded-lg shadow-lg transform rotate-12 hover:rotate-6 transition-transform duration-300"
                  >
                    <div
                      class="w-16 h-16 bg-gradient-to-br from-pink-200 to-purple-200 rounded flex items-center justify-center"
                    >
                      <span class="text-2xl">🎉</span>
                    </div>
                    <p class="text-xs text-center mt-1 text-gray-600">Events</p>
                  </div>

                  <div
                    class="absolute -bottom-4 -right-4 bg-white p-2 pb-6 rounded-lg shadow-lg transform -rotate-12 hover:-rotate-6 transition-transform duration-300"
                  >
                    <div
                      class="w-16 h-16 bg-gradient-to-br from-blue-200 to-green-200 rounded flex items-center justify-center"
                    >
                      <span class="text-2xl">🤝</span>
                    </div>
                    <p class="text-xs text-center mt-1 text-gray-600">
                      Community
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Programs Section -->
        <div class="mb-20">
          <div class="text-center mb-12">
            <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">
              Our Programs
            </h2>
            <p class="text-xl text-gray-600 max-w-3xl mx-auto">
              Different programmes that respond to multidisciplinary motivations
            </p>
          </div>
          <div class="space-y-8">
            <!-- Bachelor + Master's Program -->
            <div
              class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition-all duration-300"
            >
              <div class="grid lg:grid-cols-2 gap-0">
                <div class="relative overflow-hidden">
                  <img
                    src="/ep3.jpg"
                    alt="EPITECH Program"
                    class="w-full h-64 lg:h-full object-cover hover:scale-105 transition-transform duration-300"
                  />
                  <div class="absolute top-4 left-4">
                    <div
                      class="bg-blue-600 text-white px-4 py-2 rounded-full text-sm font-medium"
                    >
                      EPITECH
                    </div>
                  </div>
                </div>
                <div class="p-8 lg:p-12 flex flex-col justify-center">
                  <h3 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                    Bachelor + Master's Degree in Software Development
                  </h3>
                  <p class="text-gray-600 text-lg leading-relaxed mb-6">
                    Students with a High School Diploma or Middle and Higher
                    Vocational training can study to become an expert in IT,
                    computer science and web programming.
                  </p>
                  <a
                    href="https://www.epitech-it.es/en/programmes/bachelor-masters-degree-in-computer-science/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-blue-600 to-purple-600 text-white rounded-full font-semibold hover:shadow-lg transform hover:-translate-y-1 transition-all duration-300"
                  >
                    Learn More
                    <svg
                      class="w-4 h-4 ml-2"
                      fill="none"
                      stroke="currentColor"
                      viewBox="0 0 24 24"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      ></path>
                    </svg>
                  </a>
                </div>
              </div>
            </div>

            <!-- Coding Academy Program -->
            <div
              class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition-all duration-300"
            >
              <div class="grid lg:grid-cols-2 gap-0">
                <div
                  class="p-8 lg:p-12 flex flex-col justify-center lg:order-1"
                >
                  <h3 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                    Web and Mobile Development Programme
                  </h3>
                  <p class="text-gray-600 text-lg leading-relaxed mb-6">
                    Full or part time course for adults with a high school
                    diploma or a minimum of 5 years' professional experience.
                  </p>
                  <a
                    href="https://www.epitech-it.es/en/programmes/coding-academy-in-barcelona/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-green-600 to-emerald-600 text-white rounded-full font-semibold hover:shadow-lg transform hover:-translate-y-1 transition-all duration-300"
                  >
                    Learn More
                    <svg
                      class="w-4 h-4 ml-2"
                      fill="none"
                      stroke="currentColor"
                      viewBox="0 0 24 24"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      ></path>
                    </svg>
                  </a>
                </div>
                <div class="relative overflow-hidden lg:order-2">
                  <img
                    src="/coding-academy.jpg"
                    alt="Coding Academy Program"
                    class="w-full h-64 lg:h-full object-cover hover:scale-105 transition-transform duration-300"
                  />
                  <div class="absolute top-4 left-4">
                    <div
                      class="bg-green-600 text-white px-4 py-2 rounded-full text-sm font-medium"
                    >
                      CODING ACADEMY
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <!-- Data Science Bootcamp -->
            <div
              class="bg-white rounded-3xl shadow-lg overflow-hidden hover:shadow-2xl transition-all duration-300"
            >
              <div class="grid lg:grid-cols-2 gap-0">
                <div class="relative overflow-hidden">
                  <img
                    src="/schneider-electrics.png"
                    alt="Data Science Bootcamp"
                    class="w-full h-64 lg:h-full object-cover hover:scale-105 transition-transform duration-300"
                  />
                  <div class="absolute top-4 left-4">
                    <div
                      class="bg-purple-600 text-white px-4 py-2 rounded-full text-sm font-medium"
                    >
                      SCHNEIDER ELECTRIC
                    </div>
                  </div>
                </div>
                <div class="p-8 lg:p-12 flex flex-col justify-center">
                  <h3 class="text-2xl lg:text-3xl font-bold text-gray-900 mb-4">
                    Data Science & AI Bootcamp
                  </h3>
                  <p class="text-gray-600 text-lg leading-relaxed mb-6">
                    Transform your career in just 4 months with our immersive
                    Data Science Bootcamp, 50% sponsored by Schneider Electric.
                  </p>
                  <a
                    href="https://www.epitech-it.es/epitech-schneider/"
                    target="_blank"
                    rel="noopener noreferrer"
                    class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-purple-600 to-pink-600 text-white rounded-full font-semibold hover:shadow-lg transform hover:-translate-y-1 transition-all duration-300"
                  >
                    Learn More
                    <svg
                      class="w-4 h-4 ml-2"
                      fill="none"
                      stroke="currentColor"
                      viewBox="0 0 24 24"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"
                      ></path>
                    </svg>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Core Values Section -->
      <div class="mb-20 p-20">
        <div class="text-center mb-16">
          <div
            class="inline-flex items-center px-4 py-2 bg-gradient-to-r from-blue-100 to-purple-100 text-blue-800 rounded-full text-sm font-medium mb-6"
          >
            <svg
              class="w-4 h-4 mr-2"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"
              ></path>
            </svg>
            OUR VALUES
          </div>

          <h2 class="text-3xl lg:text-5xl font-bold text-gray-900 mb-6">
            What Makes EPITECH
            <span
              class="bg-gradient-to-r from-blue-600 to-purple-600 bg-clip-text text-transparent"
            >
              Unique
            </span>
          </h2>

          <p class="text-xl text-gray-600 max-w-4xl mx-auto leading-relaxed">
            Our five core values shape everything we do - from how we teach to
            how we inspire the next generation of tech leaders
          </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-8">
          <!-- Innovation -->
          <div
            class="group bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-500 border border-gray-100 hover:border-blue-200 relative overflow-hidden"
          >
            <!-- Background Pattern -->
            <div
              class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-blue-50 to-purple-50 rounded-full transform translate-x-16 -translate-y-16 group-hover:scale-150 transition-transform duration-700"
            ></div>

            <div class="relative">
              <!-- Icon -->
              <div
                class="w-16 h-16 bg-gradient-to-r from-blue-500 to-purple-600 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"
              >
                <svg
                  class="w-8 h-8 text-white"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"
                  ></path>
                </svg>
              </div>

              <h3
                class="text-2xl font-bold text-gray-900 mb-4 group-hover:text-blue-600 transition-colors duration-300"
              >
                Innovation
              </h3>

              <p class="text-gray-600 leading-relaxed">
                We guide our students to the best of innovation, sharing with
                them the desire to change things and the world around us. A
                positive and constructive innovation that constantly takes into
                account the needs of people and society.
              </p>
            </div>
          </div>

          <!-- Initiative -->
          <div
            class="group bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-500 border border-gray-100 hover:border-green-200 relative overflow-hidden"
          >
            <!-- Background Pattern -->
            <div
              class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-green-50 to-emerald-50 rounded-full transform translate-x-16 -translate-y-16 group-hover:scale-150 transition-transform duration-700"
            ></div>

            <div class="relative">
              <!-- Icon -->
              <div
                class="w-16 h-16 bg-gradient-to-r from-green-500 to-emerald-600 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"
              >
                <svg
                  class="w-8 h-8 text-white"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M13 10V3L4 14h7v7l9-11h-7z"
                  ></path>
                </svg>
              </div>

              <h3
                class="text-2xl font-bold text-gray-900 mb-4 group-hover:text-green-600 transition-colors duration-300"
              >
                Initiative
              </h3>

              <p class="text-gray-600 leading-relaxed">
                The EPITECH student is in motion and is not part of a
                predetermined order. They move, propose, impose, advance,
                build... Taking initiative is the personal, but also collective,
                driving force of our students.
              </p>
            </div>
          </div>

          <!-- Independence -->
          <div
            class="group bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-500 border border-gray-100 hover:border-orange-200 relative overflow-hidden"
          >
            <!-- Background Pattern -->
            <div
              class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-orange-50 to-red-50 rounded-full transform translate-x-16 -translate-y-16 group-hover:scale-150 transition-transform duration-700"
            ></div>

            <div class="relative">
              <!-- Icon -->
              <div
                class="w-16 h-16 bg-gradient-to-r from-orange-500 to-red-600 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"
              >
                <svg
                  class="w-8 h-8 text-white"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"
                  ></path>
                </svg>
              </div>

              <h3
                class="text-2xl font-bold text-gray-900 mb-4 group-hover:text-orange-600 transition-colors duration-300"
              >
                Independence
              </h3>

              <p class="text-gray-600 leading-relaxed">
                At EPITECH, we value independence and autonomy. Our training is
                there to guide students and give them the best possible
                foundation to build their future. Each one evolves at their own
                pace, according to their own style and codes.
              </p>
            </div>
          </div>

          <!-- Individuality -->
          <div
            class="group bg-white rounded-3xl p-8 shadow-lg hover:shadow-2xl transition-all duration-500 border border-gray-100 hover:border-purple-200 relative overflow-hidden md:col-span-2 lg:col-span-1"
          >
            <!-- Background Pattern -->
            <div
              class="absolute top-0 right-0 w-32 h-32 bg-gradient-to-br from-purple-50 to-pink-50 rounded-full transform translate-x-16 -translate-y-16 group-hover:scale-150 transition-transform duration-700"
            ></div>

            <div class="relative">
              <!-- Icon -->
              <div
                class="w-16 h-16 bg-gradient-to-r from-purple-500 to-pink-600 rounded-2xl flex items-center justify-center mb-6 group-hover:scale-110 transition-transform duration-300"
              >
                <svg
                  class="w-8 h-8 text-white"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                  ></path>
                </svg>
              </div>

              <h3
                class="text-2xl font-bold text-gray-900 mb-4 group-hover:text-purple-600 transition-colors duration-300"
              >
                Individuality
              </h3>

              <p class="text-gray-600 leading-relaxed">
                EPITECH is made up of a multitude of profiles and capabilities.
                Since none of our students are the same, we have designed
                tailor-made courses, by modules and 100% projects.
              </p>
            </div>
          </div>
        </div>

        <!-- Values Stats -->
        <div
          class="mt-16 bg-gradient-to-r from-gray-50 to-blue-50 rounded-3xl p-8 lg:p-12"
        >
          <div class="text-center mb-2">
            <h3 class="text-2xl font-bold text-gray-900 mb-2">
              Our Values in Action
            </h3>
            <p class="text-gray-600">
              See how our core values translate into real student success
            </p>
          </div>

          <div class="grid grid-cols-2 md:grid-cols-5 gap-8">
            <div class="text-center">
              <div class="text-3xl font-bold text-blue-600 mb-2">100%</div>
              <div class="text-sm text-gray-600">Project-Based Learning</div>
            </div>
            <div class="text-center">
              <div class="text-3xl font-bold text-green-600 mb-2">25+</div>
              <div class="text-sm text-gray-600">Years of Innovation</div>
            </div>
            <div class="text-center">
              <div class="text-3xl font-bold text-orange-600 mb-2">15k+</div>
              <div class="text-sm text-gray-600">Alumni Worldwide</div>
            </div>
            <div class="text-center">
              <div class="text-3xl font-bold text-purple-600 mb-2">95%</div>
              <div class="text-sm text-gray-600">Employment Rate</div>
            </div>
            <div class="text-center">
              <div class="text-3xl font-bold text-yellow-600 mb-2">∞</div>
              <div class="text-sm text-gray-600">Possibilities</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <Footer />
  </div>
</template>

<style scoped>
.font-handwriting {
  font-family: "Kalam", "Comic Sans MS", cursive;
}
</style>
