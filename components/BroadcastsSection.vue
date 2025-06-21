<template>
  <div class="border-b border-[#E6E6E6] w-full bg-white flex justify-center py-[48px] font-family-TWS AjaraTV Mt">
    <div class="w-[1220px] h-[318px]">


      <div class="flex justify-between items-center mb-[32px]">
        <div class="flex items-center gap-2">
          <span class="w-[6px] h-[28px] bg-[#FFC038] inline-block"></span>
          <h2 class="text-xl font-semibold text-black ">გადაცემები</h2>
        </div>
        <div class="flex items-center gap-[12px]">
          <button
            class="bg-[#F2F2F2] text-black text-sm font-medium px-[16px] py-[8px] rounded hover:bg-[#D9D9D9] transition-all duraction-300 ">
            ყველას ნახვა
          </button>
          <button
            class="bg-[#F2F2F2] w-[36px] h-[36px] rounded flex items-center justify-center text-black hover:bg-[#D9D9D9] transition-all duraction-300">
            <img src="../public/icons/arrow_left_icon.svg" alt="arrow_left" class=" " />
          </button>
          <button
            class="bg-[#F2F2F2] w-[36px] h-[36px] rounded flex items-center justify-center text-black hover:bg-[#D9D9D9] transition-all duraction-300">
            <img src="../public/icons/arrow_right_icon.svg" alt="arrow_left" class=" " />
          </button>
        </div>
      </div>


      <div class="flex justify-between items-start">

        <div class="w-[281px] h-[250px] flex flex-col justify-center items-start gap-[24px] ">
          <img src="../public/images/Broadcast1.png"
            class="w-[281px] h-[188px] object-cover rounded transition duration-300 hover:scale-110 " alt="show1" />
          <div>
            <h3 class="text-[16px] text-[#000000] font-semibold mb-[4px]">დიდი შესვენება</h3>
            <p class="text-[14px] text-[#808080]">ყოველდღე, 13:00 სთ</p>
          </div>
        </div>


        <div class="w-[281px] h-[250px] flex flex-col justify-center items-start gap-[24px]">
          <img src="../public/images/Broadcast2.jpg"
            class="w-[281px] h-[188px] object-cover rounded transition duration-300 hover:scale-110" alt="show2" />
          <div>
            <h3 class="text-[16px] text-[#000000] font-semibold mb-[4px]">ბიზნეს სტანდარტი</h3>
            <p class="text-[14px] text-[#808080]">შაბათი, 23:00 სთ</p>
          </div>
        </div>

        <div class="w-[281px] h-[250px] flex flex-col justify-center items-start gap-[24px]">
          <img src="../public/images/Broadcast3.png"
            class="w-[281px] h-[188px] object-cover rounded transition duration-300 hover:scale-110" alt="show3" />
          <div>
            <h3 class="text-[16px] text-[#000000] font-semibold mb-[4px]">დილის ტალღა</h3>
            <p class="text-[14px] text-[#808080]">ორშ - პარ, 08:30 სთ</p>
          </div>
        </div>

        <div class="w-[281px] h-[250px] flex flex-col justify-center items-start gap-[24px]">
          <img src="..//public/images/Broadcast4.jpg"
            class="w-[281px] h-[188px] object-cover rounded transition duration-300 hover:scale-110" alt="show4" />
          <div>
            <h3 class="text-[16px] text-[#000000] font-semibold mb-[4px]">არცევნები</h3>
            <p class="text-[14px] text-[#808080]">ოთხშაბათი, 12:00 სთ</p>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>