<template lang="">
<section class="relative w-full overflow-hidden min-h-screen 
   flex items-center">
    <div class="w-full px-5 sm:px-8 md:px-12 lg:px-8 max-w-5xl
   lg:max-w-7xl mx-auto relative z-10">
        <div class="grid lg:grid-cols-2 gap-10 xl:gap-14 items-center">
            <div class="flex flex-col md:mt-0 mt-20 justify-center">
                <div class="text-white lg:text-left" data-aos="fade-right">
                    <h1 class="text-white font-bold text-4xl 
                    md:text-5xl lg:text-6xl leading-tight">
                        Hi, I'm
                        <span class="text-transparent bg-clip-text bg-linear-to-r 
                        from-blue-400 to-cyan-400">Solomon</span>👋
                    </h1>
                    <p class="text-blue-200 font-medium text-lg md:text-xl
                     mt-4" data-aos="fade-right" data-aos-delay="100">Full Stack Developer</p>
                    <p class="text-gray-300 pt-6 text-center lg:text-left
                    mx-auto  max-w-xl text-lg leading-relaxed" data-aos="fade-right" data-aos-delay="200">
                        I build scalable web applications with modern technologies,
                        focusing on performance, clean architecture, and seamless user experience.
                    </p>
                    <div
                    class="flex items-center gap-4 pt-8 flex-col
                    sm:flex-row sm:w-max sm:mx-auto lg:mx-0"
                    data-aos="fade-right" data-aos-delay="300">
                    <button
                    class="px-8 md:px-10 py-4 rounded-xl relative group
                    w-full sm:w-max flex justify-center overflow-hidden
                     bg-linear-to-r from-blue-600 to-cyan-600
                     hover:from-blue-500 hover:to-cyan-500 transition-all
                      duration-300">
                    <span class="relative text-white flex items-center
                     font-semibold text-lg ">
                    Contact Me
                    <ArrowRightIcon class="w-5 h-5 ml-2
                     group-hover:translate-x-1 transition-transform duration-300"/>
                    </span>
                    </button>
                    <button
                    class="border-2 border-blue-400 px-8 md:px-10 
                    py-4 rounded-xl relative group w-full sm:w-max
                     flex justify-center hover:bg-blue-400/10 
                     transition-all duration-300">
                     <div class="flex items-center justify-center relative ">
                     <ArrowDownTrayIcon class="w-5 h-5 text-blue-400
                     group-hover:translate-y-1 transition-transform duration-300"/>
                     <span class="pl-3 text-blue-400 font-semibold text-lg">
                     Download CV
                     </span>
                        
                     </div>
                    </button>
                    </div>
                    <div class="flex items-center justify-center
                      lg:justify-start gap-8 pt-12 " 
                       data-aos="fade-right" data-aos-delay="400">
                        <div class="text-center">
                          <div class="text-2xl font-bold text-blue-400"> 10+</div>
                          <div class=" text-blue-200 text-sm ">Projects</div>
                        </div>
                        <div class="text-center">
                          <div class="text-2xl font-bold text-blue-400"> 3+</div>
                          <div class=" text-blue-200 text-sm ">Years</div>
                        </div>
                        <div class="text-center">
                          <div class="text-2xl font-bold text-blue-400"> 10+</div>
                          <div class=" text-blue-200 text-sm ">clients</div>
                        </div>
                    </div>
                </div>
                <!-- image -->
                <div class="lg:h-full flex justify-center items-center lg:justify-end mt-20">
                     <div class="relative w-full max-w-md lg:max-w-lg">
                        <div class="relative z-10 bg-linear-to-r
                         from-blue-600 to-cyan-600 shadow-2xl
                          rounded-[50%_40%_30%_60%/60%_30%_70%_30%]
                          p-4 backdrop-blur-sm border border-blue-500/30
                          -translate-y-6"
                          data-aos="zoom-in" data-aos-delay="500">
                          <div class = "rounded-xl overflow-hidden">
                              <img 
                              src="../../public/profile.png" 
                              alt="Solomon Full Stack Developer"
                              loading="lazy"
                              class="w-[500px] h-[500px] object-contain 
                                -translate-y-8 "/>
                          </div>
                        </div>
                        <div class="absolute top-0 right-0 w-10 h-10
                          bg-blue-400 rounded-full blur-sm opacity-6
                           animate-pulse"
                          data-aos="zoom-in" data-aos-delay="600">
                        </div>
                     </div>
                  
                </div>
            </div>
        </div>

    </div>
</section>
</template>

<script setup>
import { ArrowRightIcon, ArrowDownTrayIcon  } from '@heroicons/vue/16/solid'
</script>

<style lang="">

</style>
