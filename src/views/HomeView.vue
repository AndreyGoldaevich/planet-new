<template>
    <section class="
    home xl:h-screen min-h-screen w-screen
    xl:bg-[url('@/assets/home/background-home-desktop.jpg')]
    lg:bg-[url('@/assets/home/background-home-tablet.jpg')]
    bg-[url('@/assets/home/background-home-mobile.jpg')]
    bg-cover
    bg-center">

        <router-link :to="{name: 'Destination'}" class="flex xl:items-end h-full xl:pb-36 xl:justify-between xl:flex-row xl:text-left flex-col text-center items-center">
            <div class="space-y-5 md:w-[450px] xl:ml-40 xl:mt-0 md:mt-52 mt-32 md:px-0 px-6">
                <div class="md:text-[28px]">ИТАК, ВЫ ХОТИТЕ ОТПРАВИТЬСЯ В</div>
                <div class="font-bellfair md:text-[150px] text-7xl">КОСМОС</div>
                <div class="md:text-xl text-base">Давайте посмотрим правде в глаза: если вы хотите отправиться в космос, вы могли бы с таким же успехом действительно отправиться в открытый космос, а не
                  парить на его краю. Что ж, сядьте поудобнее и расслабьтесь, потому что мы дадим вам поистине необычный опыт!</div>
            </div>
            <div class="z-[1] relative xl:mr-40 mx-auto font-bellfair md:h-64 md:w-64 h-[150px] w-[150px] rounded-full text-black lg:text-3xl text-xl bg-white flex items-center justify-center cursor-pointer xl:mt-0 md:mt-36 mt-20
            before:transition-all
            before:duration-300
            before:ease-in-out
            before:h-full
            before:w-full
            before:bg-white
            before:absolute
            before:rounded-full
            before:bg-blend-normal
            before:z-[-1]
            hover:before:scale-150
            hover:before:opacity-10
            xl:mb-0 mb-40
            "><div>ИССЛЕДОВАТЬ</div></div>
        </router-link>
    </section>
</template>

<script>
export default {}
</script>
<style scoped>

</style>
