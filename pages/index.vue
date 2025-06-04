<template>
    <div>
        <HomeGrid />
        <!-- class="bg-red-900" -->
        <TitledSection title="უახლესი" :permalink="{ url: '#', title: 'ყველას ნახვა' }">
            <div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-5 gap-[42.5px]">
                <template v-for="i in 5" :key="i">
                    <ItemsNews :thumbnail="`https://picsum.photos/id/${i * 160}/200/300`"
                        title="რეგიონული განვითარების მინისტრის მოადგილეებად ლევან ზაუტაშვილი და ზაზა კვიციანი დაინიშნენ"
                        desc="მძიმე დანაშაული, როდესაც უცნობმა პირებმა გაძარცვეს ადგილობრივი მაღაზია..."
                        date="24 მარ 2025" />
                </template>
            </div>
        </TitledSection>
        <TitledSection title="გადაცემები" :permalink="{ url: '#', title: 'ყველას ნახვა' }" :has-arrow="true">
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-[20px]">
                <template v-for="i in 4" :key="i">
                    <ItemsShow :thumbnail="`https://picsum.photos/id/${i * 80}/200/300`" title="დიდი შესვენება"
                        desc="ყოველდდღ, 13:00 სთ" permalink="#" />
                </template>
            </div>
        </TitledSection>
        <TitledSection title="დამატებითი სიახლეები">
            <div class="grid grid-cols-7 gap-10">
                <!-- Left -->
                <div
                    class="flex flex-col justify-between font-ajaratv text-black text-[14px] tracking-[0.28px] col-span-2">
                    <template v-for="i in 4" :key="i">
                        <ItemsNews date="18 მარ 2025"
                            title="რეგიონული განვითარების მინისტრის მოადგილეებად ლევან ზაუტაშვილი და ზაზა კვიციანი დაინიშნენ"
                            desc="გიორგი მელაძე მიიწვიეს ახალი თანამდებობის დაკავების გიორგი მელაძე მიიწვიეს ახალი თანამდებობის დაკავების მიზნით გიორგი მელაძე მიიწვიეს ახალი თანამდებობის დაკავების მიზნით"
                            clamp="2" />
                    </template>
                </div>


                <div class="flex flex-col gap-6 items-center col-span-3">
                    <div class="flex flex-col gap-6 justify-center items-start max-w-[470px]">
                        <div class="rounded-lg aspect-[235/250] overflow-hidden">
                            <img src="../public/images/AddNews.png"
                                class="object-cover transition duration-300 hover:scale-110 w-full h-full">
                        </div>
                        <div>
                            <p class="text-xs text-adjara-gray font-adjara-nu mb-1">29 მარტი 2025</p>
                            <h3 class="text-2xl font-adjara-mt text-black leading-snug mb-2">
                                რეგიონული განვითარების მინისტრის მოადგილეებად ლევან ზაუტაშვილი და ზაზა კვიციანი
                                დაინიშნენ
                            </h3>
                            <p class="text-sm text-adjara-gray font-adjara-nu">
                                მნიშვნელოვანი დიპლომატიური შეხვედრა, სადაც სხვადასხვა ქვეყნის წარმომადგენლებმა...
                            </p>
                        </div>
                    </div>
                </div>

                <div class="ml-auto flex flex-col gap-[24px] col-span-2">
                    <template v-for="i in 2" :key="i">
                        <ItemsNews :thumbnail="`https://picsum.photos/id/${i * 160}/200/300`"
                            title="რეგიონული განვითარების მინისტრის მოადგილეებად ლევან ზაუტაშვილი და ზაზა კვიციანი დაინიშნენ"
                            desc="მძიმე დანაშაული, როდესაც უცნობმა პირებმა გაძარცვეს ადგილობრივი მაღაზია..."
                            date="24 მარ 2025" />
                    </template>
                </div>

            </div>
        </TitledSection>
        <!-- <AdditionalNews />
        <VideoList />
        <InterestingTopic />
        <FooterAdjara /> -->
    </div>
</template>
