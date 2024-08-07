<template>
    <body class="">
        <div class="dark:bg-slate-800 dark:text-slate-300">
            <div>
                <h1 class="text-8xl font-bold text-center py-8">Mari Belajar 
                    <span class="bg-gradient-to-r from-blue-500 
                    to-teal-500 bg-clip-text text-transparent">TailwindCSS</span></h1>
        
                <section class="mb-10 bg-gradient-to-l from-emerald-400 via-teal-200 to-rose-400">
                    <h2 class="text-lg font-medium text-center">Spacing</h2>
                    <div class="m-4 bg-fuchsia-200">Margin</div>
                    <div class="p-4 bg-violet-300">Padding</div>
                </section>
        
                <section class="mb-10 bg-rose-200">
                    <h2 class="text-lg font-medium text-center">Sizing</h2>
                    <div class="w-32 h-32 bg-teal-200">Kotak 1</div>
                </section>
        
                <section class="font-inter max-w-3xl mx-auto">
                    <h2 class="mb-2 text-4xl font-bold text-center">Belajar Mengenai Typography pada TailwindCSS</h2>
                    <div class="mb-4 text-xl">30 Agustus 2023</div>
                    <p class="mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta deleniti, perspiciatis
                    quod recusandae aliquam quam saepe veniam quaerat accusamus odit officia ipsam nesciunt.
                    Voluptates dicta obcaecati mollitia corporis ea ipsam, excepturi itaque aspernatur placeat 
                    repudiandae laboriosam accusamus impedit debitis. Praesentium saepe perferendis quidem cumque 
                    mollitia suscipit nesciunt culpa ipsa deserunt?</p>
                    <blockquote class="mb-4 font-thin italic text-xl">"Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Omnis est distinctio error nam maiores consequatur possimus beatae at amet ratione."</blockquote>
                    <p class="mb-4">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quam autem illo doloremque, 
                    ullam natus ipsa iusto ipsum quas et eum quasi inventore cumque harum consequuntur, qui, ex hic aliquam esse.</p>
                </section>
            </div>
        
            <div class="max-w-xl h-96 bg-slate-300 mx-auto overflow-y-scroll bg-scroll
            mt-[42px]" style="background-image: url('https://source.unsplash.com/1000x600?computer');">
                <p class="p-6 text-2xl">Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem saepe, provident mollitia reprehenderit culpa, 
                    quae quisquam cupiditate voluptas ex magnam voluptatem ad quod nostrum neque. Deleniti aliquid dolores ea repudiandae 
                    porro harum aut possimus ad nobis odit saepe hic quis, praesentium, quae assumenda. Iste, quaerat rem sed voluptatibus 
                    dolorum ad inventore molestiae omnis voluptatum temporibus cum laboriosam possimus modi quisquam aliquid tempora mollitia 
                    voluptates reiciendis fugiat ipsam, porro blanditiis minima itaque quis? Voluptatum corporis exercitationem rem sed, maxime 
                    et quia distinctio inventore, totam perferendis optio nulla architecto necessitatibus possimus tempore ad est numquam 
                    adipisci? Commodi quo debitis minima odit nisi? Lorem ipsum, dolor sit amet consectetur adipisicing elit. Magnam pariatur 
                    commodi quas molestiae ex vero ab doloribus inventore. Aperiam at fugit doloremque nisi perspiciatis. Vero labore accusamus 
                    tempore culpa nesciunt fugit animi cumque obcaecati doloremque, nisi veritatis iste fugiat perspiciatis aperiam. Molestiae 
                    cupiditate maxime a fuga, accusamus, dicta quas doloremque ad ex accusantium, provident perspiciatis. Odio porro nesciunt 
                    facilis soluta quia omnis ducimus animi quaerat laboriosam culpa debitis architecto accusamus amet ab voluptates, a blanditiis 
                    saepe, voluptatem quas ratione beatae! Totam fuga eius odio cupiditate placeat ipsam, sint assumenda esse! Dignissimos minima 
                    autem iure, corporis quaerat veritatis eveniet cumque perspiciatis.
                </p>
            </div>
        
            <div class="mt-32 max-w-xl mx-auto h-96 bg-slate-300 bg-contain bg-no-repeat bg-center
            rounded-3xl shadow-lg shadow-slate-500 overflow-hidden border-8 flex" 
            style="background-image: url('/image/1.jpg');">
                <div class="w-[200px] h-[200px] bg-white/30 m-auto 
                rounded-full backdrop-blur-md"></div>
            </div>
        
            <hr class="my-20">
            
            <div class="flex items-center justify-center">
                <span class="text-sm text-slate-500 mr-2">Light</span>
                <input type="checkbox" id="toggle" class="hidden">
                <label for="toggle">
                    <div class="w-9 h-5 bg-slate-500 rounded-full flex items-center p-1 cursor-pointer">
                        <div class="w-4 h-4 bg-slate-200 rounded-full toggle-circle"></div>
                    </div>
                </label>
                <span class="text-sm text-slate-500 ml-2">Dark</span>
            </div>

            <button class="my-10 px-5 py-2 bg-sky-400 rounded-full mx-auto block font-inter 
            font-semibold text-white hover:bg-sky-500 active:bg-sky-600 
            focus:ring ring-sky-300 dark:bg-slate-300 dark:hover:bg-slate-100
            dark:text-slate-700">Simpan</button>
            
            <div class="max-w-lg p-5 my-10 mx-auto border border-slate-200 shadow-md rounded-md font-serif hover:bg-sky-300 dark:hover:bg-slate-300 group">
                <h5 class="mb-2 text-lg font-inter font-semibold text-slate-700 group-hover:text-white dark:group-hover:text-slate-700">My Card</h5>
                <p class="text-slate-600 group-hover:text-white selection:bg-lime-300 selection:text-slate-600
                first-line:uppercase first-line:tracking-wider dark:group-hover:text-slate-700
                first-letter:text-7xl first-letter:float-left first-letter:mr-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem adipisci hic perspiciatis 
                    atque praesentium a, quidem quia nam mollitia iste neque inventore unde saepe 
                    quam tempore id expedita sunt ad ut quae! Pariatur, odio quo?
                </p>
            </div>
        
            <div class="max-w-lg p-5 my-10 mx-auto border border-slate-300 rounded-lg shadow">
                <form>
                    <label for="email">
                        <span class="text-slate-600 font-semibold mb-1
                        after:content-['*'] after:text-pink-600 after:ml-0.5">Email</span>
                        <input type="email" id="email" placeholder="Masukkan Email"
                        class="px-4 py-2 border shadow rounded w-full block text-sm placeholder:text-slate-300
                        mt-1 focus:outline-none focus:ring-sky-300 focus:ring-1 focus:border-sky-500
                        invalid:text-pink-700 invalid:focus:ring-pink-700
                        invalid:focus:border-pink-700 peer" />
                        <p class="text-pink-600 text-sm m-1 invisible peer-invalid:visible
                        ">Email tidak valid</p>
                    </label>
                </form>
            </div>

            <hr class="my-20">

            <div class="flex">
                <div class="w-40 h-40 bg-sky-500 m-auto rounded-lg shadow-lg
                hover:rotate-180 origin-top-left transition">
                </div>

                <div class="w-40 h-40 visible m-auto group">
                    <div class="w-40 h-40 bg-sky-500 rounded-lg shadow 
                    group-hover:skew-x-6 group-hover:rotate-180 origin-top-left transition"></div>
                </div>

                <div class="w-40 h-40 bg-pink-500 m-auto rounded-full animate-bounce"></div>
            </div>

            <hr class="my-20 border-slate-600">

            <div class="container">
                <div class="border rounded-lg shadow p-10">
                    <img src="/image/1.jpg" width="150" class="float-left mr-3">
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolorum molestiae qui, assumenda ratione deleniti illum nihil dolore, sequi veniam mollitia rerum architecto! Quo doloremque quaerat, nulla aliquam earum cum ipsam nesciunt debitis perspiciatis totam quibusdam quas, sunt deleniti ullam eius consequatur consectetur dolorum pariatur blanditiis ducimus culpa qui ut distinctio!</p>
                </div>
            </div>

            <div class="container mx-auto border rounded-lg shadow-lg p-10 mt-20 columns-3">
                <img src="https://source.unsplash.com/600x400"
                alt="Image" class="mb-4">
                <img src="https://source.unsplash.com/600x400"
                alt="Image" class="mb-4">
                <img src="https://source.unsplash.com/600x400"
                alt="Image" class="mb-4">
                <img src="https://source.unsplash.com/600x400"
                alt="Image" class="mb-4">
                <img src="https://source.unsplash.com/600x400"
                alt="Image" class="mb-4">
                <img src="https://source.unsplash.com/600x400"
                alt="Image" class="mb-4">
            </div>

            <hr class="my-20 border-slate-600">


            <div class="container font-inter mx-auto max-w-md sm:max-w-xl md:max-w-5xl lg:flex lg:max-w-full lg:p-0">
                <div class="lg:p-12 flex-1">
                    <h3 class="font-semibold text-4xl sm:text-5xl md:text-6xl">Ri<span class="text-sky-500">zal</span> Nugroho</h3>
                    <img src="image/1.jpg" alt="Laptop"
                    class="rounded-lg shadow-lg mt-4 sm:mt-6 lg:hidden">
                    <h2 class="text-2xl font-semibold text-slate-700 mt-6 sm:text-4xl sm:mt-8">Belajar programing dengan TailwindCSS</h2>
                    <p class="text-slate-600 mt-2 sm:text-xl sm:mt-4 sm:w-full">Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, necessitatibus consequatur aspernatur minima, maiores nisi nam earum expedita fugiat ullam ad provident atque corrupti quae eos voluptatem corporis temporibus molestiae?</p>
                    <div class="mt-4 sm:mt-6">
                        <a href="#" class="bg-red-500 p-2 rounded-lg text-white font-semibold uppercase tracking-wider sm:text-base">Subcribe</a>
                    </div>
                </div>
                <div class="hidden lg:flex lg:w-1/2">
                    <img src="image/1.jpg" alt="" class="object-cover rounded-l-full">
                </div>
            </div>

            <div class="mt-20 mb-10 text-2xl font-bold text-slate-700 text-center">My Galery</div>

            <div class="container mx-auto px-6 font-inter sm:flex sm:flex-wrap 
                sm:gap-6 sm:justify-evenly">

                <div class="rounded-lg shadow-lg overflow-hidden mb-10
                sm:mb-0 sm:w-64 md:w-80 lg:w-72">
                    <img src="https://source.unsplash.com/600x400" alt=""
                        class="w-full">
                    <div class="px-6 py-4">
                        <div class="font-bold text-xl text-slate-600 mb-2">Image Title</div>
                        <p class="text-sm text-slate-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto, iure. Non quos suscipit ullam autem repellat quam possimus iure ad?</p>
                    </div>
                </div>

                <div class="rounded-lg shadow-lg overflow-hidden mb-10
                sm:mb-0 sm:w-64 md:w-80 lg:w-72">
                    <img src="https://source.unsplash.com/600x400" alt=""
                        class="w-full">
                    <div class="px-6 py-4">
                        <div class="font-bold text-xl text-slate-600 mb-2">Image Title</div>
                        <p class="text-sm text-slate-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto, iure. Non quos suscipit ullam autem repellat quam possimus iure ad?</p>
                    </div>
                </div>

                <div class="rounded-lg shadow-lg overflow-hidden mb-10
                sm:mb-0 sm:w-64 md:w-80 lg:w-72">
                    <img src="https://source.unsplash.com/600x400" alt=""
                        class="w-full">
                    <div class="px-6 py-4">
                        <div class="font-bold text-xl text-slate-600 mb-2">Image Title</div>
                        <p class="text-sm text-slate-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto, iure. Non quos suscipit ullam autem repellat quam possimus iure ad?</p>
                    </div>
                </div>

                <div class="rounded-lg shadow-lg overflow-hidden mb-10
                sm:mb-0 sm:w-64 md:w-80 lg:w-72">
                    <img src="https://source.unsplash.com/600x400" alt=""
                        class="w-full">
                    <div class="px-6 py-4">
                        <div class="font-bold text-xl text-slate-600 mb-2">Image Title</div>
                        <p class="text-sm text-slate-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto, iure. Non quos suscipit ullam autem repellat quam possimus iure ad?</p>
                    </div>
                </div>

                <div class="rounded-lg shadow-lg overflow-hidden mb-10
                sm:mb-0 sm:w-64 md:w-80 lg:w-72">
                    <img src="https://source.unsplash.com/600x400" alt=""
                        class="w-full">
                    <div class="px-6 py-4">
                        <div class="font-bold text-xl text-slate-600 mb-2">Image Title</div>
                        <p class="text-sm text-slate-600">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iusto, iure. Non quos suscipit ullam autem repellat quam possimus iure ad?</p>
                    </div>
                </div>
            </div>

            <div class="mt-64 p-2 font-inter grid grid-cols-2 gap-2 md:grid-cols-4 md:gap-3 md:transition-all">
                <h2 class="text-xl font-semibold text-slate-700 md:row-start-2 md:col-start-4 md:flex">
                    <span class="self-center">Welcome to Kulineran</span></h2>
                <div class="text-lg font-bold text-slate-600 md:row-start-2 md:col-start-2 md:flex"><span class="self-end">@rizalnugroho</span></div>

                <div class="group grid-card">
                    <div class="w-full h-full bg-[url('image/grid/1.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card md:col-start-3">
                    <div class="w-full h-full bg-[url('image/grid/2.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card">
                    <div class="w-full h-full bg-[url('image/grid/3.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card">
                    <div class="w-full h-full bg-[url('image/grid/4.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card">
                    <div class="w-full h-full bg-[url('image/grid/5.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card md:col-start-2">
                    <div class="w-full h-full bg-[url('image/grid/6.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card md:col-start-4">
                    <div class="w-full h-full bg-[url('image/grid/7.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card">
                    <div class="w-full h-full bg-[url('image/grid/8.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card md:col-start-3 ">
                    <div class="w-full h-full bg-[url('image/grid/9.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
                <div class="group grid-card md:col-start-3">
                    <div class="w-full h-full bg-[url('image/grid/10.jpg')] bg-cover bg-center absolute group-hover:scale-125
                    transition-all duration-500"></div>
                </div>
            </div>
        
            <div class="h-96"></div>
        </div>
    </body>
</template>

<script setup lang="ts">
/* const checkbox = document.querySelector('#toggle');
const body = document.querySelector('body');

checkbox?.addEventListener('click', function()
{
    checkbox.checked ? body.classList.add('dark') :
    body.classList.remove('dark');
}) */
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@200;400;600;700;900&family=Quicksand&display=swap');
  #toggle:checked ~ label div.toggle-circle{
    @apply translate-x-3
  }
</style>
