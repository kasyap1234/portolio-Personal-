<script lang="ts">
	import Navbar from "$lib/components/Navbar.svelte";
	import Skills from "$lib/components/Skills.svelte";


</script> 
<div class=" mt-6 "> 
<Navbar/> 
</div>
<div class="container flex-column flex-wrap">
<div class=" ml-40 container "> 
    <div class="container  mt-20  flex flex-column   "> 
        <div> 
        <h1 class="text-2xl mt-4 ml-10 font-medium text-gray-100"> Hi I'm    </h1>
        <h1 class="text-2xl mt-4 ml-10 font-medium text-gray-100"> Kasyap Dharanikota </h1>
        <p class="text-gray-400 ml-10 mt-4"> I am a full stack software developer with a passion for building software that is both functional and scalable. </p>
        

        </div>
                
        

        </div>
  
 <div class="flex gap-3 ml-10 mt-10 flex-wrap">

    <Skills skill='golang' /> 
    <Skills skill='nodejs' /> 
    <Skills skill='react' />
    <Skills skill='svelte' />
    <Skills skill='python' />
    <Skills skill='AWS' />
    <Skills skill='firebase' />
    <Skills skill='mongodb' /> 
    <Skills skill='postgresql' />
    <Skills skill='Docker' /> 
    <Skills skill='kubernetes' />
    <Skills skill='git' />
    <Skills skill='github' />
    <Skills skill='Linux' /> 
    <Skills skill='TailwindCSS' /> 
    <Skills skill='nestjs'/> 

    </div>
    </div>
  </div>
 <style> 
 
 </style> 

