<template>
    <section class="border-b border-gray-500 pb-8 my-6 items-center justify-start w-full">
        <div>
            <h1 class="text-2xl font-semibold">Hello Joao!</h1>
            <p class="text-sm font-light">Welcome to your dashboad</p>
        </div>
        <div class="flex mx-9 mt-5">
            <div class="mx-3">
                <p>Add Calories</p>
                <p class="text-sm font-light">Lorem, ipsum dolor</p>
                <div class="flex flex-col">
                    <div class="my-3 flex">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                    </div>
                    <div class="my-3 flex">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                    </div>
                    <button class="bg-gray-300 p-2 text-gray-600 font-bold hover:bg-green-500 hover:text-white">ADD</button>
                </div>
            </div>
            <div class="mx-9">
                <p>Add Weight</p>
                <p class="text-sm font-light">Lorem, ipsum dolor</p>
                <div class="flex flex-col">
                    <div class="my-3 flex">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                    </div>
                    <div class="my-3 flex">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                        <input class="p-1 border-gray-600 border mx-1 rounded-sm" type="text" name="" id="" placeholder="Title">
                    </div>
                    <button class="bg-gray-300 p-2 text-gray-600 font-bold hover:bg-green-500 hover:text-white">ADD</button>
                </div>
            </div>
        </div>
    </section>
</template>

<script>

export default{
    name: 'MainDash'
}

</script>

<style scoped>
</style>