<template>
    <nav class="bg-transparent dark:bg-gray-900 fixed w-full z-20 top-0 start-0  dark:border-gray-600">
        <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
            <a href="https://flowbite.com/" class="flex items-center space-x-3 rtl:space-x-reverse" draggable="false">
                <img src="/imgs/logo.svg" class="h-10" alt="Flowbite Logo">
                <spandark:text-white text-white
                    class="self-center text-2xl font-semibold whitespace-nowrap text-white ">PeakTech</spandark:text-white>
            </a>
            <div class="flex md:order-2 space-x-3 md:space-x-0 rtl:space-x-reverse">
                <button type="button"
                    class="bg-purple dark:text-white text-white hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Contact us</button>
                <button data-collapse-toggle="navbar-sticky" type="button"
                    class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                    aria-controls="navbar-sticky" aria-expanded="false">
                    <span class="sr-only">Open main menu</span>
                    <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none"
                        viewBox="0 0 17 14">
                        <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M1 1h15M1 7h15M1 13h15" />
                    </svg>
                </button>
            </div>
            <div class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1" id="navbar-sticky">
                <ul
                    class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-gray-100 rounded-lg md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0  dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
                    <li>
                        <a href="#"
                            class="block py-2 item-nav px-3 text-custom-gray bg-blue-700 rounded md:bg-transparent md:p-0 md:dark:text-blue-500"
                            aria-current="page">Home</a>
                    </li>
                    <li>
                        <a href="#"
                            class="block py-2 item-nav px-3 text-custom-gray rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-white-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Featire</a>
                    </li>
                    <li>
                        <a href="#"
                            class="block py-2 item-nav px-3 text-custom-gray rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-white-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Services</a>
                    </li>
                    <li>
                        <a href="#"
                            class="block py-2  item-nav px-3 text-custom-gray rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-white-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style>
.text-custom-gray {
    color: #737373;
    transition: ease .4s;
    position: relative;
}

.text-custom-gray::after {
    content: '';
    min-width: 100%;
    min-height: 1.5pt;
    position: absolute;
    bottom: -5px;
    opacity: 0;
    left: 0;
    transition: ease-in;
    background: #fff;
}

.text-custom-gray:hover {
    color: #fff;
}

.text-custom-gray:hover::after {
    opacity: 1;
    transition: ease-in-out .4s;
}
</style>