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
        <div class="flex justify-center">
            <div class="py-12">
                <div class="h-64 w-64 bg-gray-900 rounded-full flex items-center justify-center mx-auto">
                    <p class="text-white">No image here</p>
                </div>
                <h2 class="mt-2 text-center text-xl text-gray-900">Nazar Nyzhnyk</h2>
                <h3 class="text-center text-lg text-gray-700">nazarh2onyzhnyk.near</h3>
                <p class="mt-2 text-center text-xl text-gray-900">12 books in property</p>
                <div class="block md:flex space-y-4 md:space-y-0 md:space-x-8 mt-6">
                    <a href="#" class="block border border-gray-900 py-2 w-72 text-center text-gray-900 hover:bg-gray-900 hover:text-white transition-colors duration-500">
                        Add new book
                    </a>
                    <a href="#" class="block border border-gray-900 py-2 w-72 text-center text-gray-900 hover:bg-gray-900 hover:text-white transition-colors duration-500">
                        Edit profile
                    </a>
                    <a href="#" class="block border border-gray-900 py-2 w-72 text-center text-gray-900 hover:bg-gray-900 hover:text-white transition-colors duration-500">
                        Logout
                    </a>
                </div>
            </div>
        </div>
    </section>
    <section class="my-8">
        <div class="container mx-auto px-4 md:px-0">
            <div class="block md:flex items-center justify-between">
                <div class="flex items-center my-8 space-x-8">
                    <h3 class="text-gray-900 text-2xl">My books</h3>
                    <hr class="mt-1 w-56 border border-gray-900">
                </div>
                <div class="ml-auto md:ml-0">
                    <ul class="flex items-center space-x-4 text-blue-500">
                        <li class="">
                            <a href="#" class="flex items-center hover:underline">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4" />
                                </svg>
                                Name
                            </a>
                        </li>
                        <li class="">
                            <a href="#" class="flex items-center hover:underline">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4" />
                                </svg>
                                Date
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="space-y-6">
                <div class="grid grid-cols-2 md:grid-cols-6">
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p> 
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-6">
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p> 
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                    <a href="#" class="block w-full px-4 mt-4 md:mt-0">
                        <img src="./img/book.png" alt="book" class="w-full">
                        <h4 class="mt-2 font-medium text-gray-900">Beneath a Scarlet Sky</h4>
                        <p class="text-sm text-gray-700">Mark Sullivan</p>
                    </a>
                </div>
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