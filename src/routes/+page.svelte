<script lang="ts">
	import Navbar from "$lib/components/Navbar.svelte";
	import Projects from "$lib/components/Projects.svelte";
	import Skills from "$lib/components/Skills.svelte";


</script> 
<div class=" mt-6 "> 
<Navbar/> 
</div>
<div class="ml-40 mt-20">
    <div class="flex  gap-x-72">
<div class="flex flex-col  justify-between"> 
    
    <h1 class="text-3xl  font-bold "> Hi I'm </h1>
    <h1 class="text-3xl  font-bold">Kasyap Dharanikota</h1>
    <h2 class="text-xl text-gray-400 font-normal pt-5">Software developer with expertise in FullStack Development and Devops</h2>
    </div>
    <img class="w-36 h-36 rounded-full" src="git.jpg" /> 

      </div>
<div class="flex gap-3  mt-10 flex-wrap ">

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
  <img  class="h-96 w-96 mt-20 mx-auto" alt="computer" src="computer.jpeg" /> 

  <Projects /> 
  

        

        
  
 

    

 <style> 
 
 </style> 

