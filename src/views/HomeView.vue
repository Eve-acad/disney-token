<template>
  <div class="flex flex-col px-2 container mx-auto py-3">
    <div class="flex flex-wrap">
      <div class="grid grid-cols-2 lg:w-1/2 w-96 bg-orange-600">
        <div class="py-1 pl-2">WHAT'S ON TONIGHT</div>
        <div class="bg-yellow-600 text-end py-1 pr-2">00.00 P.PM.(E/P)</div>
      </div>

      <div class="bg-yellow-500 px-3 py-1">TV SCHEDULE</div>
      <div class="flex flex-end gap-4 bg-gray-500 pl-12 pr-3 py-1">
        <div>HELP</div>
        <div>SITEMAP</div>
      </div>
      <div class="flex bg-gray-300 px-3 py-1">
        <div>SEARCH</div>
        <input type="text" class="border outline-none" />
        <div>GO</div>
      </div>
    </div>

    <div class="flex flex-col md:grid grid-cols-9 gap-4 mt-8">

      <div class="flex flex-col w-full md:w-fit gap-4 md:col-span-2">
          <div class="bg-black p-2">
            <img src="@/assets/a.jpg" />
          </div>
          <div class="bg-black p-2">
            <img src="@/assets/a.jpg" />
          </div>

        <div class="bg-black p-2">
          <img src="@/assets/b.jpeg" class="w-full  md:h-52" />
        </div>
        <div class="bg-black p-2">
          <img src="@/assets/c.png" class="w-full md:h-44" />
        </div>
      </div>

      <div class="flex flex-col gap-3 w-full md:col-span-7">
        <div class="w-full grid grid-cols-5 gap-3">
          <div class="col-span-4 border">
            <img src="@/assets/d.png" class="w-full" />
          </div>
          <img src="@/assets/e.jpeg" class="w-full h-full" />
        </div>
        <div class="w-full grid grid-cols-5 gap-3">
          <div class="border"><img src="@/assets/e.jpeg" class="w-full h-52" /></div>
          <div class="border col-span-3"><img src="@/assets/e.jpeg" class="w-full h-52" /></div>
          <div class="border"><img src="@/assets/e.jpeg" class="w-full h-52" /></div>
        </div>
        <div class="w-full grid grid-cols-5 gap-3">
          <div class="border"><img src="@/assets/cn-black.png" class="w-full h-28" /></div>
          <div class="border col-span-3"><img src="@/assets/cn-black.png" class="w-full h-28" /></div>
          <div class="border"><img src="@/assets/cn-black.png" class="w-full h-28" /></div>
        </div>
        <div class="flex flex-col text-sm">

          <div> > PRIVACY POLICY</div>
          <div class="flex gap-1.5 flex-wrap">
            <div>> TRADEMARK INFORMATION</div>
            <div>> TERMS OF USE</div>
            <div>> PARENT GUIDE</div>
            <div>> TV PARENTAL GUIDELINES</div>
          </div>
          <div>USE OF THIS SITE SIGNIFIES YOUR AGREEMENT TO THE TERMS OF USE. @2020 CARTOON NETWORK. A TIME WARNER COMPANY.</div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts"></script>
