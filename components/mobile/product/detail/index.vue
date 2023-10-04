<template>
    <div class="product-detail md:hidden">
        <div class="container mx-auto flex items-center bg-white">
            <div class="flex-1">
                <img src="/product/product1.png" class="mr-1" />
            </div>
        </div>

        <div class="container mx-auto items-center p-2 bg-white">
            <div class="flex-1 inline-flex items-center ">
                <img src="/icons/pin.png" class="mr-1 mini-icon" />
                <p class="location">
                    Lokasi proyek <b>Jl. Semolowaru Utara 1/158B, Sukolilo</b>
                </p>
            </div>
            <div class="">
                <p class="price">
                    Rp 63.500
                </p>
                <p class="name mt-1">
                    Avian No Drop Cat Dinding | 1 Kg | Mocca
                </p>
                <div class="store inline-flex items-center mt-1">
                    <img src="/store/store1.png" class="mr-1 logo" /> NIPPON ASIA
                </div>
                <div class="price-grosir flex">
                    <div class="flex-1">
                        <p class="label">Harga Grosir</p>
                    </div>
                    <div class="flex-1 justify-end">
                        <p class="label text-right label-option inline-flex items-center">
                            Beli 5-10 produk Rp162.000
                            <img src="/icons/Right.png" class="ml-2" />
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <div class="container mx-auto items-center p-2 description bg-white mt-4 variant">
            <p class="mb-2">
                Varian Produk
            </p>
            
            <p>
                Pilih kemasan :
            </p>

            <div class="grid grid-cols-6 gap-2 grid-kemasan mt-2 mb-2">
                <div class="selected">1 kg</div>
                <div>4 kg</div>
                <div>20 kg</div>
            </div>

            <p>
                Pilih warna :
            </p>

            <div class="grid grid-cols-4 gap-2 grid-warna mt-2 mb-2">
                <div class="content-grid selected">
                    <div class="bg-color bg-[#AA4E25]"></div>
                    <div>Mocca</div>
                </div>
                <div class="content-grid">
                    <div class="bg-color bg-[#DABF26]"></div>
                    <div>Yellow Claw</div>
                </div>
                <div class="content-grid">
                    <div class="bg-color bg-[#FAA703]"></div>
                    <div>Golden Yellow</div>
                </div>
                <div class="content-grid">
                    <div class="bg-color bg-[#DF4812]"></div>
                    <div>Red</div>
                </div>
                <div class="content-grid">
                    <div class="bg-color bg-[#DFB57D]"></div>
                    <div>Yellow Claw</div>
                </div>
                <div class="content-grid">
                    <div class="bg-color bg-[#FAA703]"></div>
                    <div>Golden Yellow</div>
                </div>
                <div class="content-grid">
                    <div class="bg-color bg-[#DF4812]"></div>
                    <div>Red</div>
                </div>
                <div class="content-grid other-option">
                    <div class="inline-flex justify-center items-center">
                        <img src="/icons/eye.png" class="w-4 h-4"/>
                    </div>
                    <div>Lainnya</div>
                </div>
            </div>

            <p class="more-info mt-2">
                Lihat detail ukuran
            </p>

        </div>

        <div class="container mx-auto items-center p-2 description bg-white mt-4 description">
            <div class="">
                <p class="header mb-2">
                    Deskripsi Produk
                </p>

                <p class="body">
                    No Drop adalah cat pelapis anti bocor yang memiliki sifat elastis, kedap air serta sangat tahan cuaca sehingga sangat cocok untuk digunakan pada permukaan tembok, beton, asbes, galvanis/seng dan permukaan terakota.
                </p>

                <p class="header2 uppercase mt-2">
                    KEUNGGULAN PRODUK
                </p>

                <ul class="body">
                    <li>
                        Perlindungan Garansi 7 Tahun
                    </li>
                    <li>
                        Anti jamur dan lumut
                    </li>
                    <li>
                        Elastis
                    </li>
                    <li>
                        Daya tutup terbaik
                    </li>
                    <li>
                        Warna Dekoratif
                    </li>
                    <li>
                        Warna tidak mudah pudar
                    </li>
                    <li>
                        Tahan alkali dan efflorescence
                    </li>
                    <li>
                        Tahan cuaca- Kedap air
                    </li>
                    <li>
                        Memperbaiki retak
                    </li>
                </ul>

                <p class="header2 uppercase mt-2">
                    SPESIFIKASI PRODUK
                </p>

                <ul class="body">
                    <li>
                        Pengencer : Air Bersih
                    </li>
                    <li>
                        Hasil Akhir : Semi Gloss
                    </li>
                    <li>
                        Daya Sebar : 2 m²/kg/lapis
                    </li>
                    <li>
                        Waktu Pengeringan : 30 menit - 24 Jam
                    </li>
                    <li>
                        Jumlah Lapisan : 2-3 lapis
                    </li>
                    <li>
                        Ukuran : 1 Kg, 4 Kg, 20 Kg
                    </li>
                </ul>

                <p class="more-info mt-2">
                    Lihat lebih sedikit
                </p>

            </div>

        </div>

        <div class="container mx-auto items-center p-2 description bg-white mt-4 store-info mb-10">
            <div class="">
                <p class="header mb-2">
                    Informasi Toko
                </p>

                <div class="profile flex mb-2 items-center">
                    <div class="flex-none">
                        <img src="/store/store2.png" class="w-11" />
                    </div>
                    <div class="flex-1 text-left p-2">
                        <p class="profile-name">
                            TB. Sumber Rejeki Jaya Abadi Selalu Mantap
                        </p>
                        <p class="address inline-flex">
                            <img src="/icons/Pin2.png" class="w-4" /> Jarak: <span class="value">0.2 km</span> 
                            &nbsp;| 
                            <img src="/icons/Box.png" class="w-4" />Stok: <span class="value">120</span>
                        </p>
                    </div>
                </div>

                <div class="voucher flex mb-2">
                    <img src="/icons/Discount.png" class="ml-2 ic-discount" />
                    Voucher diskon s/d Rp50.000 tersedia
                    <img src="/icons/Right.png" class="ml-2" />
                </div>

                <button class="uppercase btn-secondary w-full rounded-sm" type="button">
                    Lihat Toko
                </button>
            </div>
        </div>
    </div>

    <div class="product-detail-footbar md:hidden sticky bottom-0">
        <div class="container mx-auto items-center p-2 align-middle inline-flex">
            <button class="btn-secondary rounded-sm h-10 w-20 btn-chat">
                <img src="/icons/chat.png" class="w-6"/>
            </button>
            <button class="btn-secondary rounded-sm h-10 w-full ml-2 uppercase">
                + Keranjang
            </button>
            <button class="btn-primary rounded-sm h-10 w-full ml-2 uppercase">
                Beli Sekarang
            </button>
        </div>
    </div>
</template>

<style>
    @import url("~/assets/sass/mobile/product/detail.sass");
</style>