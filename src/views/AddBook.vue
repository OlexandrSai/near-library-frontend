<template>
  <header class="">
        <div class="container mx-auto py-4 text-gray-900">
            <nav class="hidden md:flex justify-between items-center">
                <a href="#" class="text-lg font-medium">NEAR-Library</a>
                <ul class="flex space-x-6 text-lg">
                    <li class=""><a href="#" class="hover:underline">Home</a></li>
                    <li class=""><a href="#" class="hover:underline">Category</a></li>
                    <li class=""><a href="#" class="hover:underline">Books</a></li>
                </ul>
                <a href="#" class="border border-gray-900 hover:bg-gray-900 hover:text-white transition-colors duration-500 py-2 px-4">Nazar Nyzhnyk</a>
            </nav>
            <nav class="flex md:hidden justify-between px-4">
                <a href="#" class="text-lg font-medium">NEAR-Library</a>
                <a href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7" />
                    </svg>
                </a>
            </nav>
        </div>
    </header>
    <section class="bg-orange-100">
        <div class="container mx-auto py-8 ">
            <a href="#" class="flex items-center text-blue-500 hover:underline ml-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16l-4-4m0 0l4-4m-4 4h18" />
                </svg>
                back to profile
            </a>
            <div class="grid grid-cols-12 mt-8">
                <div class="md:col-span-1 lg:col-span-2"></div>
                <div class="col-span-12 lg:col-span-8">
                    <h2 class="text-center text-2xl">Book information</h2>
                    <hr class="w-1/2 mx-auto border border-gray-900 my-6">
                    <form action="" class="w-full bg-white px-4 md:px-24 space-y-6 py-6">
                        <div class="block space-y-2">
                            <label for="name" class="text-lg">Book name</label>
                            <input type="text" id="name" class="outline-none border border-gray-900 pl-6 py-2 w-full" placeholder="Write here">
                        </div>
                        <div class="block space-y-2">
                            <label for="author" class="text-lg">Author</label>
                            <input type="text" id="author" class="outline-none border border-gray-900 pl-6 py-2 w-full" placeholder="Write here">
                        </div>
                        <div class="block space-y-2">
                            <label for="desc" class="text-lg">Description</label>
                            <input type="text" id="desc" class="outline-none border border-gray-900 pl-6 py-2 w-full" placeholder="Write here">
                        </div>
                        <div class="block space-y-2">
                            <label for="page" class="text-lg">Num page</label>
                            <input type="text" id="page" class="outline-none border border-gray-900 pl-6 py-2 w-full" placeholder="Write here">
                        </div>
                        <div class="">
                            <a href="#" class="block py-2 text-center border border-gray-900 hover:bg-gray-900 hover:text-white transition-colors duration-500">+ add book cover</a>
                        </div>
                        <div class="mt-4">
                            <a href="#" class="block py-2 text-center border border-gray-900 font-medium hover:bg-gray-900 hover:text-white transition-colors duration-500">Add book</a>
                        </div>
                    </form>
                </div>
                <div class="md:col-span-1 lg:col-span-2"></div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>