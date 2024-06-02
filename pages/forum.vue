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
                <h1 class = "text-5xl font-semibold z-10">Forum Diskusi</h1>
                <span class = "text-xl uppercase opacity-60">Wujudkan remaja makmur bersama Lerasbarang</span>
            </div>
        </div>

        <img src = "/assets/images/blob.png" class = "absolute top-full -translate-y-full right-0 rotate-[90deg] -scale-y-[1] -z-[1] opacity-60">
        <img src = "/assets/images/blob.png" class = "absolute top-full right-0 -rotate-[90deg] -z-[1] opacity-60">

        <div class = "w-full h-full px-8 lg:px-16 mb-16 lg:mt-16 text-gray-700 flex flex-col gap-8">
            <h1 class = "text-4xl font-medium text-center">Topik Terbaru</h1>

            <button class = "px-8 py-2.5 bg-zinc-900 mt-2 w-fit rounded-md font-semibold text-lg text-slate-100 mx-auto">Buat baru</button>
        
            <div class = "flex flex-col lg:flex-row w-full gap-8">
                <div class = "flex flex-col gap-8 w-full">
                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah ngelem termasuk narkoba?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, quia sapiente magni aliquam delectus sunt quibusdam provident iste minus veniam dolorem nostrum saepe quo nobis, molestiae alias deserunt cumque aut!</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>
                    
                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah di Ngawi ada Ambatron?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum illum eius error enim odit, consectetur repellendus recusandae nam voluptas nemo sint dicta, quia dolore aut vero eos quaerat est unde?</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>

                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah di Ngawi ada Ambatron?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, quia sapiente magni aliquam delectus sunt quibusdam provident iste minus veniam dolorem nostrum saepe quo nobis, molestiae alias deserunt cumque aut!</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>

                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah di Ngawi ada Ambatron?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, quia sapiente magni aliquam delectus sunt quibusdam provident iste minus veniam dolorem nostrum saepe quo nobis, molestiae alias deserunt cumque aut!</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>
                </div>

                <div class = "flex flex-col gap-8 w-full">
                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah ngelem termasuk narkoba?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, quia sapiente magni aliquam delectus sunt quibusdam provident iste minus veniam dolorem nostrum saepe quo nobis, molestiae alias deserunt cumque aut!</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>
                    
                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah di Ngawi ada Ambatron?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum illum eius error enim odit, consectetur repellendus recusandae nam voluptas nemo sint dicta, quia dolore aut vero eos quaerat est unde?</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>

                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah di Ngawi ada Ambatron?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta, quia sapiente magni aliquam delectus sunt quibusdam provident iste minus veniam dolorem nostrum saepe quo nobis, molestiae alias deserunt cumque aut!</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>

                    <div class = "border border-slate-300 bg-white p-8 rounded-lg shadow-md flex flex-col gap-2">
                        <div class = "flex gap-2 text-sm opacity-70 items-center">
                            <span>Pertanyaan oleh Prof. Ironi</span>
                            <PhosphorIconDot size = "24" weight = "bold"/>
                            <span>20 Januari 2024</span>
                        </div>

                        <h2 class = "text-2xl font-medium mb-4">Apakah di Ngawi ada Ambatron?</h2>
                        <span class = "opacity-70 mb-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Culpa ullam quae alias sapiente, excepturi, minima ipsa, praesentium vero facilis necessitatibus animi quam mollitia corporis fugit blanditiis incidunt officia nesciunt? Minima!</span>
                    
                        <div class = "flex gap-4">
                            <PhosphorIconChatCenteredDots size = "24"/>
                            <span>2</span>

                            <PhosphorIconHeart size = "24" class = "ml-4"/>
                            <span>5</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <img src = "/assets/images/blob.png" class = "absolute top-[200%] opacity-60 -translate-y-full left-0 rotate-[90deg] -z-[1]">
        <img src = "/assets/images/blob.png" class = "absolute top-[200%] opacity-60 left-0 rotate-[90deg] -z-[1] -scale-x-[1]">

        <footer class = "w-full h-full bg-zinc-900 p-8 text-slate-100">
            <div class = "flex flex-col gap-2">
                <h3 class = "text-xl font-semibold">Lerasbarang</h3>
                <span class = "opacity-70">Wujudkan remaja makmur bersama Lerasbarang</span>
            </div>
        </footer>
    </div>
</template>