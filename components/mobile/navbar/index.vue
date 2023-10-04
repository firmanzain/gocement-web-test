<template>
    <div class="navbar-top sticky top-0 md:hidden">
        <div class="container mx-auto flex items-center p-2">
            <div class="flex-1 inline-flex">
                <img src="/icons/navbar/arrow-left.png" class="mr-1" />
                <input class="w-full placeholder:text-slate-400 block bg-white border border-slate-300 rounded-md focus:outline-none focus:border-sky-500 focus:ring-sky-500 focus:ring-1 sm:text-sm pl-3 pr-3 shadow-sm" placeholder="Cari di gocement" type="text" name="search"/>
            </div>
            <div class="flex-1 inline-flex justify-end">
                <img src="/icons/navbar/Cart.png" class="mr-1 icon-right" />
                <img src="/icons/navbar/Share.png" class="mr-1 icon-right" />
                <img src="/icons/navbar/More.png" class="mr-1 icon-right" />
            </div>
        </div>
    </div>
</template>

<style>
    @import url("~/assets/sass/mobile/navbar.sass");
</style>