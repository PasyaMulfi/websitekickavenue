<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
        <template #logo>
            <NavbarLogo link="https://www.google.com/" alt="Flowbite logo"
                image-url="https://play-lh.googleusercontent.com/7CL8WfXiGVF_GO-KQv65qTAryEjbqvLm8RLOdhjRUTsITwypN6Ynx0gJ1t3zrqSmUO0=w240-h480-rw">
                kickavenue
            </NavbarLogo>
        </template>
        <template #default="{ isShowMenu }">
            <NavbarCollapse :isShowMenu="isShowMenu">
                <NavbarLink is-active>Home</NavbarLink>
                <NavbarLink>Sneakers</NavbarLink>
                <NavbarLink>Apparel</NavbarLink>
                <NavbarLink>Contact</NavbarLink>
            </NavbarCollapse>
        </template>
        <template #right-side>
            <button type="button"
                class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Login</button>
                 <br>
                 <button type="button"
                    class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Sign Up</button>
        </template>
    </Navbar></template>
