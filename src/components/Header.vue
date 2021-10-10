<template>
    <div class="bg-white h-20 sticky top-0 z-50 grid grid-cols-3 shadow-md py-5 px-5">
        <div class="relative flex items-center my-auto ">
            <h2 class="font-semibold text-xl text-gray-500">Employee Manager</h2>
        </div>
        <div class="flex items-center border-2  rounded-full ">
            <input type="text" class="flex-grow pl-5 bg-transparent outline-none" placeholder="start your search">
            <img class="relative h-10 bg-red-400 rounded-full p-1 cursor-pointer"
             src="https://www.freeiconspng.com/thumbs/search-icon-png/search-icon-png-1.png" alt="search">
            
        </div>
        <div class="flex items-center justify-end">
           <img class="rounded-full h-10 cursor-pointer"
           src="https://media.istockphoto.com/vectors/power-turn-off-iconvector-illustration-vector-id1018739074?k=20&m=1018739074&s=612x612&w=0&h=ZQYQXO8jYpWkoJzyk-bA1Ki0uF_LqmV2VGz8Skl5OZ4="  alt="">
        </div>
    </div>
</template>
<script>


export default {
    name: 'Header',
    
}

</script>