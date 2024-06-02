<script setup lang = "ts">
    useHead({
        title: 'Lerasbarang | Lembaga Remaja Bebas Narkoba'
    })
</script>

<template>
    <div class = "w-full h-full min-h-screen flex flex-col">
        <div class = "relative m-8 mb-0 max-sm:block hidden">
            <img src = "/assets/images/cover.webp" class = "rounded-xl shadow-xl brightness-50">
        
            <div class = "absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2">
                <img src = "/assets/images/logo.png" class = "w-64">
            </div>
        </div>

        <div class = "w-[calc(100%-4rem)] h-[calc(100vh-4rem)] bg-orange-100 rounded-lg shadow shadow-xl flex flex-col gap-4 text-gray-700 relative m-8 rounded-xl gradient">
            <img src = "/assets/images/cover.webp" class = "max-sm:hidden object-cover right-0 rounded-xl w-[60%] select-none w-full h-full absolute brightness-[.9]">
            <div class = "gradient max-sm:hidden hero w-full h-full absolute rounded-xl">

            </div>

            <div class = "absolute left-8 top-8 hidden lg:block">
                <img src = "/assets/images/logo.png" class = "w-24">
            </div>

            <div class = "z-10 lg:px-16 px-8 lg:w-1/2 flex flex-col gap-2 text-slate-100 my-auto">
                <span class = "text-xl uppercase opacity-60">Wujudkan remaja makmur bersama Lerasbarang</span>
                <h1 class = "text-5xl font-semibold z-10">Hidup Sehat Aktif Tanpa Narkoba</h1>

                <span class = "text-xl mt-6">Bersama Lerasbarang, Jalani gaya hidup sehat aktif bebas narkoba demi remaja emas Indonesia!</span>
                <button class = "px-8 py-2.5 bg-zinc-900 mt-2 w-fit rounded-md font-semibold text-lg">Lihat</button>
            </div>
        </div>

        <img src = "/assets/images/blob.png" class = "absolute top-full -translate-y-full right-0 rotate-[90deg] -scale-y-[1] -z-[1] opacity-60">
        <img src = "/assets/images/blob.png" class = "absolute top-full right-0 -rotate-[90deg] -z-[1] opacity-60">
       
        <div class = "flex gap-16 flex-col lg:flex-row items-center text-gray-700 px-8 lg:px-16 max-sm:text-center">
            <div class = "relative scale lg:w-1/2">
                <img src = "https://cdn3d.iconscout.com/3d/premium/thumb/drug-8471069-6722819.png?f=webp" class = "brightness-[0.8]">
                <img src = "https://static.vecteezy.com/system/resources/previews/009/370/595/original/3d-forbidden-sign-png.png" class = "absolute top-0 scale-[0.75]">
            </div>

            <div class = "w-full flex flex-col gap-8 my-auto mb-16">
                <h1 class = "text-4xl font-medium">Kenalan yuk dengan Lerasbarang!</h1>
                <span class = "text-xl">Lerasbarang adalah LSM (lembaga swadaya masyarakat) non-profit yang didirikan dengan tujuan untuk membantu remaja menghindari bahaya-bahaya dari narkotika dan obat-obatan terlarang.</span>
            </div>
        </div>

        <img src = "/assets/images/blob.png" class = "absolute top-[200%] opacity-60 -translate-y-full left-0 rotate-[90deg] -z-[1]">
        <img src = "/assets/images/blob.png" class = "absolute top-[200%] opacity-60 left-0 rotate-[90deg] -z-[1] -scale-x-[1]">

        <div class = "w-full h-full px-8 lg:px-16 mb-16 lg:mt-16 text-gray-700 flex flex-col gap-8">
            <h1 class = "text-4xl font-medium text-center">Konten Terbaru</h1>

            <div class = "w-full h-[50vh] lg:h-screen">
                <iframe class = "w-full h-full rounded-xl shadow-lg" src="https://www.youtube.com/embed/WZTVfkYYxTE?si=BqcgOQmmKv-8TPlU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>

            <div class = "flex flex-col lg:flex-row gap-8">
                <div class = "border border-slate-300 p-8 rounded-lg shadow-md flex gap-8 items-center max-sm:flex-col flex-row">
                    <img src = "https://cdn.britannica.com/50/123550-050-885369B3/Prozac-pills.jpg" class = "w-32 h-32 max-sm:w-full max-sm:h-64 rounded-md object-cover">

                    <div class = "flex flex-col justify-center gap-4">
                        <h3 class = "font-semibold text-xl">5 Jenis Narkoba yang Sering Disalahgunakan</h3>
                        <span class = "text-sm opacity-70">Narkoba pada dasarnya merupakan suatu Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur optio atque eos, rem dolor tempore ipsum porro, nam, excepturi id totam iure sed provident laboriosam dignissimos nemo cupiditate rerum vero.</span>

                        <div class = "flex gap-2 opacity-70 items-center">
                            <PhosphorIconCalendar size = "24"/>
                            <span>24 Jan 2024</span>

                            <PhosphorIconUser size = "24" class = "ml-6"/>
                            <span>Admin</span>
                        </div>
                    </div>
                </div>

                <div class = "border border-slate-300 p-8 rounded-lg shadow-md flex gap-8 items-center max-sm:flex-col flex-row">
                    <img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxefLPHZUuHyjuqsRV95EnKxKTHs6hac_R8g&s" class = "w-32 h-32 max-sm:w-full max-sm:h-64 rounded-md object-cover">

                    <div class = "flex flex-col justify-center gap-4">
                        <h3 class = "font-semibold text-xl">Ciri-ciri Pergaulan yang Melibatkan Narkoba</h3>
                        <span class = "text-sm opacity-70">Tentunya sebgai remaja, Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem, facere. Veniam perspiciatis saepe officia quia quos. Animi, esse dolorum aliquam quas iste odio minus. Culpa vero repellat nostrum repellendus dicta.</span>

                        <div class = "flex gap-2 opacity-70 items-center">
                            <PhosphorIconCalendar size = "24"/>
                            <span>27 Jan 2024</span>

                            <PhosphorIconUser size = "24" class = "ml-6"/>
                            <span>Admin</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class = "w-full h-full px-8 lg:px-16 mb-16 text-gray-700 flex flex-col gap-8">
            <h1 class = "text-4xl font-medium text-center">Program Kerja</h1>
        
            <div class = "grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class = "border border-slate-300 rounded-lg shadow-md bg-white">
                    <img src = "https://akcdn.detik.net.id/detikevent/blog_16890522620.jpg?w=598" class = "rounded-t-lg select-none h-64 w-full object-cover">
                    <div class = "p-8 relative flex flex-col gap-4">
                        <h3 class = "text-2xl font-medium">Seminar</h3>
                        <span>Lerasbarang menghadirkan pembicara berkualitas yang profesional pada bidangnya untuk memberikan informasi bagi peserta.</span>
                    </div>
                </div>

                <NuxtLink class = "border border-slate-300 rounded-lg shadow-md bg-white" to = "/forum">
                    <img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTr8aYTEpnn0R2MYJjvgGHi_2TY-lrp-2Dz-g&s" class = "rounded-t-lg select-none h-64">
                    <div class = "p-8 relative flex flex-col gap-4">
                        <h3 class = "text-2xl font-medium">Web Forum</h3>
                        <span>Lerasbarang membuka forum diskusi online bagi para remaja untuk berdiskusi mengenai masalah narkoba.</span>
                    </div>
                </NuxtLink>

                <div class = "border border-slate-300 rounded-lg shadow-md bg-white">
                    <img src = "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSJ0F4eN4SasrzAUgk6M7rzuMswyrlRV2QaUQ&s" class = "rounded-t-lg select-none h-64 w-full object-cover">
                    <div class = "p-8 relative flex flex-col gap-4">
                        <h3 class = "text-2xl font-medium">Pengawasan Toko Obat</h3>
                        <span>Lerasbarang bekerja sama dengan instansi terkait untuk melakukan pengawasan terhadap toko obat.</span>
                    </div>
                </div>
            </div>
        </div>

        <div class = "w-full h-full px-8 lg:px-16 mb-16 text-gray-700 flex flex-col gap-8">
            <h1 class = "text-4xl font-medium text-center">Layanan Eksternal</h1>

            <div class = "grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class = "border border-slate-300 rounded-lg shadow-md bg-white">
                    <img src = "https://mysiloam-api.siloamhospitals.com/public-asset/website-cms/website-cms-16933806421182835.webp" class = "rounded-t-lg select-none">
                    <div class = "p-8 relative flex flex-col gap-4">
                        <div class = "absolute top-0 -translate-y-1/2 right-8 shadow-md bg-[#8065f9] text-slate-100 px-6 py-3 rounded-full font-semibold ">Rp. 200.000</div>

                        <h3 class = "text-2xl font-medium">Konsultasi Psikolog</h3>
                        <span>Lerasbarang bekerja sama dengan psikolog untuk memberikan bantuan bagi anggota yang membutuhkan.</span>
                    </div>
                </div>
            </div>
        </div>

        <div class = "w-full h-full px-8 lg:px-16 mb-16 text-gray-700 flex flex-col gap-8">
            <h1 class = "text-4xl font-medium text-center">Tim Lerasbarang</h1>

            <div class = "grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Nikolaus Wahyu F. H.</h2>
                        <p class = "text-center">Ketua Operasional</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Timothy Suharli</h2>
                        <p class = "text-center">Sekretaris</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Manuel Christian</h2>
                        <p class = "text-center">Bendahara</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Christian Marino A. M.</h2>
                        <p class = "text-center">Koordinator Divisi Pengawasan</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Eduardo Fatan Naito F.</h2>
                        <p class = "text-center">Koordinator Divisi Penyuluhan</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Dariel Grevan A.</h2>
                        <p class = "text-center">Tim IT</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Hansen Salim</h2>
                        <p class = "text-center">Tim Humas</p>
                    </div>
                </div>

                <div class = "w-full h-full flex flex-col rounded-xl">
                    <div class = "w-full h-[132px] relative bg-[#8065f9] rounded-t-xl shadow-lg">
                        <div class = "w-[164px] h-[164px] bg-slate-50 border border-slate-300 rounded-full absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 shadow-md bg-slate-50">
                            <img alt = "Profile" src= "/assets/images/dicky.png" class = "w-[164px] h-[200px] object-contain h-auto absolute bottom-0 rounded-b-full">
                        </div>
                    </div>
                    
                    <div class = "w-full h-max px-8 pb-8 rounded-b-xl pt-[98px] text-center border border-slate-300">
                        <h2 class = "text-2xl font-semibold">Dicky Darma</h2>
                        <p class = "text-center">Korordinator Divisi Dana</p>
                    </div>
                </div>
            </div>
        </div>

        <footer class = "w-full h-full bg-zinc-900 p-8 text-slate-100">
            <div class = "flex flex-col gap-2">
                <h3 class = "text-xl font-semibold">Lerasbarang</h3>
                <span class = "opacity-70">Wujudkan remaja makmur bersama Lerasbarang</span>
            </div>
        </footer>
    </div>
</template>