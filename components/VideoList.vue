<template>
  <div class="bg-[#1A1A1A] text-white  flex justify-center w-full py-[64px]">
    <div class="w-[1220px] h-[796px] ">


      <div class="w-full flex justify-between items-center mb-[64px]">

        <div class="flex items-center gap-2">
          <span class="w-[6px] h-[28px] bg-[#FFC038] inline-block"></span>
          <h2 class="text-xl font-bold">ვიდეო</h2>
        </div>

     
        <div class="flex gap-[12px]">
          <span class=" rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300">ყველა</span>
          <span class=" rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300">გადაცემები</span>
          <span class=" rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300">დოკუმენტური</span>
          <span class=" rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300">საბავშვო</span>
          <span class=" rounded-full px-[14px] py-[6px] text-sm text-white backdrop-blur-sm bg-[rgba(255,255,255,0.1)]  hover:bg-[#808080] transition-all duraction-300">ლაივი</span>
        </div>

        <button class="bg-[#FFC038] text-black text-sm font-semibold px-[16px] py-[8px] rounded-[6px] hover:bg-[#ff7e38] transition-all duration-300">
          ყველას ნახვა
        </button>
      </div>


      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-[32px]">

        <!-- CARD 1 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden ">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/Vid1.jpg" alt="" class="w-full h-full object-cover rounded-lg " />
            <div class="absolute inset-0 flex items-center justify-center  ">
              <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">რეგიონი</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">24 მარტი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              დაბა სტეფანწმინდაში მომხდარ მკვლელობის ფაქტთან დაკავშირებით ორი პირი დააკავეს
            </p>
          </div>
        </div>

        <!-- CARD 2 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid2.jpg" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
             <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">ველორბოლა</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">01 აპრილი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              ბათუმი - გოდერძის უღელტეხილის მონაკვეთზე მსუბუქი ავტოტრანსპორტის მოძრაობა აღდგა
            </p>
          </div>
        </div>

        <!-- CARD 3 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid3.jpg" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">მოგზაურობა</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">29 მარტი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              მოლაპარაკებების მორიგი რაუნდი ომანში
            </p>
          </div>
        </div>

        <!-- CARD 4 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid4.png" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">ფეხბურთი</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">24 მარტი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              დედა სანდრინელიძის მომზადებული კერძებით, ფესტივალი დასრულდა მღელვარე დღით
            </p>
          </div>
        </div>

        <!-- CARD 5 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid5.jpg" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">ფეხბურთი</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">24 მარტი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              დაბა სტეფანწმინდაში მომხდარ მკვლელობის ფაქტთან დაკავშირებით ორი პირი დააკავეს
            </p>
          </div>
        </div>

        <!-- CARD 6 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid6.png" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">მოგზაურობა</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">29 მარტი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              მოლაპარაკებების მორიგი რაუნდი ომანში
            </p>
          </div>
        </div>

        <!-- CARD 7 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid7.jpg" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
             <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">რეგიონი</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">24 მარტი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              დაბა სტეფანწმინდაში მომხდარ მკვლელობის ფაქტთან დაკავშირებით ორი პირი დააკავეს
            </p>
          </div>
        </div>

        <!-- CARD 8 -->
        <div class="bg-[#1A1A1A] rounded overflow-hidden">
          <div class="relative aspect-[14/9] transition duration-300 hover:scale-110 ">
            <img src="../public/images/vid8.jpg" alt="" class="w-full h-full object-cover rounded-lg" />
            <div class="absolute inset-0 flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" width="49" height="48" viewBox="0 0 49 48" fill="none">
  <path opacity="0.5" fill-rule="evenodd" clip-rule="evenodd" d="M19.4178 32.3175V15.6578L32.5353 23.9877L19.4178 32.3175ZM24.3335 0C11.1003 0 0.333496 10.7668 0.333496 24C0.333496 37.2332 11.1003 48 24.3335 48C37.5667 48 48.3335 37.2332 48.3335 24C48.3335 10.7668 37.5667 0 24.3335 0Z" fill="white"/>
</svg>
            </div>
          </div>
          <div class="pt-[16px]  text-left">
            <h3 class="text-[#f3b933] font-semibold text-sm mb-[12px]">ველორბოლა</h3>
            <p class="text-[#808080] font-ajaratv text-[12px] font-normal not-italic leading-[normal] tracking-[0.045em] mb-[12px]">01 აპრილი 2025</p>
            <p class="text-grayText font-ajaratv text-[12px] font-normal not-italic leading-normal tracking-wide72">
              ბათუმი - გოდერძის უღელტეხილის მონაკვეთზე მსუბუქი ავტოტრანსპორტის მოძრაობა აღდგა
            </p>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>
