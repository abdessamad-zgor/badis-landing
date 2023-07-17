<script lang="ts">
import pic1 from "$lib/assets/bg-sitna(7).png";

import pic2 from "$lib/assets/bg-sitna(8).png";

import pic3 from "$lib/assets/bg-sitna(9).png";
//    import {onMount} from "svelte";


//onMount(()=>{
//
//console.log(window.innerWidth)
//console.log(window.innerHeight)
//    })
</script>
<main>
<section id="banner" class="w-full min-h-screen border-8 border-[#3c7f72] ">
<h1 class="w-7/12 p-12 text-center text-teal-900 text-shadow text-9xl font-kanit">Badis.</h1>
<h2 class="px-12 text-3xl"> le Web comme vous le jamais vue!</h2>
</section>

<section id="banner2" class="flex flex-col items-center w-full min-h-screen  border-8 border-[#3c7f72] ">
    <h1 class="py-4 text-6xl text-[#3c7f72] text-center underline font-kanit text-shadow decoration-8">? Por Que</h1>
    
<p class="w-5/12 px-2 py-8 text-3xl text-center backdrop-blur">
   empowering creators, one man bisinesses, au but de créer et encourager des business enoovant de ce librer de monotonne et arnatique et creant des agent de valeur et ameliorer la qualite des vie des autres.
</p>
</section>
<section id="banner3" class="flex flex-col items-center justify-center w-full min-h-screen  border-8 border-[#3c7f72] ">
    <h1 class="pb-32 text-6xl text-[#3c7f72]  text-center underline font-kanit text-shadow decoration-8">Nos Packets</h1>
    <div class="flex flex-col items-center justify-center px-12 md:flex-row gap-8">

    <div class="flex flex-col items-center justify-center w-1/3 px-4 py-8 shadow-lg backdrop-blur rounded-xl">
        <div class="flex flex-row items-center justify-center">
            <img src={pic1} alt="light bulb" class="w-1/4">
            <h1 class="text-2xl font-bold text-lime-900">Packet Swipes</h1>
        </div>
        <div>
        <ul>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Presence social media.</li>

        <li><span class="text-6xl leading-3 text-shadow">.</span>L'audio-visual.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Product Design.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Branding.</li>
        </ul>
        </div>
    </div>
    <div class="flex flex-col items-center justify-center w-1/3 py-8 shadow-lg backdrop-blur rounded-xl">

        <div class="flex flex-row items-center justify-center">
            <img src={pic2} alt="light bulb" class="w-1/4">
            <h1 class="text-2xl font-bold text-lime-900">Packet Digital</h1>
        </div>
        <div>
        <ul>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Site Web Plain.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Site E-commerce, Reservation.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Software Interne.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Applications Mobile.</li>
        </ul>
        </div>
    </div>
    <div class="flex flex-col items-center justify-center w-1/3 py-8 shadow-lg backdrop-blur rounded-xl">

        <div class="flex flex-row items-center justify-center">
            <img src={pic3} alt="light bulb" class="w-1/4">
            <h1 class="text-2xl font-bold text-bold text-lime-900">Packet NetWork</h1>
        </div>
        <div>
        <ul>
        <li><span class="text-6xl leading-3 text-shadow">.</span>fournisseurs et collaborateurs.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Programmes de Support Finnaciere.</li>
        <li><span class="text-6xl leading-3 text-shadow">.</span>Stands et Access au Evenements.</li>
        </ul>
        </div>
    </div>
    </div>
</section>

<section id="banner4" class="flex flex-col items-center w-full min-h-screen  border-8 border-[#3c7f72] ">
    <h1 class="py-4 text-6xl text-[#3c7f72] text-center underline font-kanit text-shadow decoration-8">Contactez-nous</h1>
    <form class="flex flex-col w-6/12 px-32 py-8 rounded shadow-lg gap-4 backdrop-blur" action="">
        <div class="flex flex-col-reverse">
        <input type="text"  class="peer border input-shadow w-full backdrop-blur p-2 shadow-md rounded bg-transparent border-[#3c7f7298] focus:border-[#3c7f72]" placeholder="Nom complet... ">
        <label class="invisible peer-focus:visible text-sm font-bold text-[#3c7f7298]">Comment vous vous appelez?</label>
        </div>

        <div class="flex flex-col-reverse">
        <input type="text" class="peer border input-shadow w-full p-2 rounded bg-transparent border-[#3c7f7298] focus:border-[#3c7f72]" placeholder="Email...">
        <label class="invisible peer-focus:visible text-sm font-bold text-[#3c7f7298]">Votre email?</label>
        </div>

        <div class="flex flex-col-reverse">
        <textarea type="text" style="resize: none;" placeholder="Parlez-nous de vous idées!" class="peer border input-shadow w-full rounded bg-transparent border-[#3c7f7298] focus:border-[#3c7f72] p-2"></textarea>
        <label class="invisible peer-focus:visible text-sm font-bold text-[#3c7f7298]">Parlez nous de vos idées!</label>
        </div>
        <div class="py-4"><input type="submit" value="Envoyer" class="text-md input-shadow bg-[#3c7f72] text-white rounded-sm px-8 py-4 "></div>
    </form>
</section>
</main>

<style>
#banner{
    background-image: url("/bg-sitna(1).png");
    background-size: cover;
}

#banner2{
    background-image: url("/bg-sitna(2).png");
    background-size: cover;
}


#banner3{
    background-image: url("/bg-sitna(3).png");
    background-size: cover;
}


#banner4{
    background-image: url("/bg-sitna(4).png");
    background-size: cover;
}

.text-shadow{
    text-shadow: -5px -5px 0 #3c7f7298;
}

.input-shadow{
        box-shadow: -5px 3px #3c7f7298;
    }

</style>
