<template>
  <div class="mb-4 flex">
    <div
      class="z-30 relative items-center justify-center w-full w-screen h-screen"
    >
      <div>
        <div class="inset-0 h-screen">
         
          <img src="~/static/Urshey.jpg"/>
        </div>

        <div class="absolute inset-0 z-40 flex justify-between h-full px-8">
          <div class="relative z-20 w-full h-24 pt-2">
            <div class="flex items-center justify-between h-full w-full">
              <img
                src="uico.png"
                class="w-auto h-12"
              />

              <div
                id="nav"
                class="
                  text-white
                  absolute
                  top-0
                  left-0
                  hidden
                  block
                  w-full
                  mt-20
                  border-b border-gray-200
                  sm:border-none
                  sm:px-5
                  sm:block
                  sm:relative
                  sm:mt-0
                  sm:px-0
                  sm:w-auto
                "
              >
                <nav
                  class="
                    flex flex-col
                    items-center
                    py-3
                    text-black
                    sm:flex-row sm:bg-transparent sm:border-none sm:py-0
                  "
                >
                  <a
                    href="#about"
                    class="
                      px-1
                      mb-1 mb-5
                      mr-0
                      text-base
                      sm:mb-0 sm:mr-4
                      lg:mr-8
                    "
                    >About</a
                  >
                  <a
                    href="#audio"
                    class="
                      px-1
                      mb-1 mb-5
                      mr-0
                      text-base
                      sm:mb-0 sm:mr-4
                      lg:mr-8
                    "
                    >Player</a
                  >
                  <a
                    href="#gallery"
                    class="
                      px-1
                      mb-1 mb-5
                      mr-0
                      text-base
                      sm:mb-0 sm:mr-4
                      lg:mr-8
                    "
                    >Gallery</a
                  >
                </nav>
              </div>

              <div
                id="nav-mobile-btn"
                class="
                  absolute
                  top-0
                  right-0
                  z-50
                  block
                  w-6
                  mt-8
                  mr-10
                  cursor-pointer
                  select-none
                  sm:hidden sm:mt-10
                "
              >
                <span
                  class="
                    block
                    w-full
                    h-1
                    mt-2
                    duration-200
                    transform
                    bg-black
                    rounded-full
                    sm:mt-1
                  "
                ></span>
                <span
                  class="
                    block
                    w-full
                    h-1
                    mt-1
                    duration-200
                    transform
                    bg-white
                    rounded-full
                  "
                ></span>
              </div>
            </div>
          </div>
        </div>

        <div
          class="
            absolute
            inset-0
            z-20
            flex
            items-center
            justify-center
            h-screen
            w-full
             bg-opacity-50
          "
        ></div>
        <div
          data-aos="flip-down"
          class="
            absolute
            inset-0
            z-30
            container
            flex flex-col
            items-center
            justify-center
            h-full
            max-w-6xl
            pl-0
            mx-auto
            sm:pl-8
            xl:pl-0
            md:flex-row md:justify-between
          "
        >
          <div class="flex flex-col items-center justify-center mx-auto">
            <div class="relative text-center">
                <img src="~/static/ursheylogo.png"/>
              <h1
                class="
                  text-white
                  relative
                  mb-4
                  text-4xl
                  font-bold font-sans
                  italic
                  leading-none
                  text-center
                  lg:text-1xl
                  xl:text-1xl
                "
              >
                Travel & Ghosts</span>
              </h1>
              <p
                class="
                  text-gray-400 text-sm
                  lg:text-4xl lg:text-center
                  font-sans
                  italic
                "
              > 
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
