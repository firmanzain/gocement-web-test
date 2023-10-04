<template>
    <div class="navbar-middle hidden md:block">
        
        <div class="container mx-auto flex items-center pt-2">

            <div class="flex-none w-64">
                <img src="/icons/navbar/Logo.png" class="logo" />
            </div>
            <div class="flex-1 inline-flex ml-1 mr-1">
                <button type="button" class="btn-other rounded-md mr-1">
                    <img src="/icons/navbar/Menu.png" />
                </button>
                <input class="placeholder:text-slate-400 block bg-white w-full border border-slate-300 rounded-md py-2 pl-9 pr-3 shadow-sm focus:outline-none focus:border-sky-500 focus:ring-sky-500 focus:ring-1 sm:text-sm" placeholder="Cari kebutuhan proyekmu" type="text" name="search"/>
                <button type="button" class="btn-search rounded-md ml-1 mr-1">
                    <img src="/icons/navbar/Search.png" />
                </button>
            </div>
            <div class="flex-none inline-flex justify-end">
                <button type="button" class="btn-other rounded-md mr-1">
                    <img src="/icons/navbar/Cart.png" />
                </button>
                <button type="button" class="btn-other rounded-md mr-1">
                    <img src="/icons/navbar/Bell.png" />
                </button>
                <button type="button" class="btn-signup text-white uppercase text-sm tracking-wide">
                    Daftar | Login
                </button>
            </div>

        </div>

        <div class="container mx-auto flex items-center pt-2">
            <div class="flex-none w-64"></div>
            <div class="flex-1 inline-flex ml-1 mr-1 text-center product-trends justify-center items-center">
                <ul class="inline-flex mt-2">
                    <li v-for="item in productTrends" :key="item">{{ item }}</li>
                </ul>
            </div>
            <div class="flex-none w-64"></div>
        </div>

    </div>
</template>

<style>
    @import url("~/assets/sass/desktop/navbar/body.sass");
</style>

<script>
    export default {
        data() {
            return {
                productTrends: ['Acian', 'Avian', 'Bata Merah', 'Besi', 'Drymix', 'Semen', 'Paku', 'Galvanum', 'Pelamir', 'Pipa', 'Insulasi']
            };
        }
    }
</script>