<template>
<div class="fixed bg-blue-200"> 
<div class="pt-5 pl-5 pb-5 pr-5 space-x-2  ">
    <button class="pr-8 pl-8
    bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
     ADD
    </button>
<button class="pr-8 pl-8
    bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
     Delete
    </button>

</div>
    <div class="max-w-xs bg-purple-200 h-screen rounded-lg " >
        <h1 class="text-xl pl-5 pt-2 shadow-md cursor-pointer ">View </h1>
        
         <h1  class="text-xl pl-5 pt-2 cursor-pointer ">Time Info</h1>
         <h1 class="text-xl pl-5 pt-2 shadow-md cursor-pointer ">Salary Info</h1>
         <h1 class="text-xl pl-5 pt-2 cursor-pointer ">Working History</h1>
         <h1 class="text-xl pl-5  pt-2 shadow-md cursor-pointer ">Emergrncy Contact</h1>

    
    </div>
</div>
</template>

<script>

export default {
    name:'Sidebar',
   
    
}
</script>