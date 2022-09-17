<template>
    <div class="drawer drawer-mobile">
        <input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
        <div class="drawer-content">
            <!-- <label for="my-drawer-2" class="btn btn-primary drawer-button lg:hidden">Open drawer</label> -->
            <TheNavbar></TheNavbar>
            <div class="flex flex-col p-8">
                <slot />
            </div>
        </div>
        <div class="drawer-side">
            <label for="my-drawer-2" class="drawer-overlay"></label>
            <ul class="menu p-4 overflow-y-auto w-64 bg-base-200 text-base-content border-r flex flex-col gap-4">
                <NuxtLink class="text-2xl font-bold" to="/dashboard">MedanCMS</NuxtLink>

                <div class="flex flex-col gap-4">
                    <NuxtLink to="/dashboard/collections" class="flex gap-2 items-center p-2 hover:bg-base-300 cursor-pointer">
                        <svg width="20" height="20" viewBox="0 0 24 24">
                            <path fill="currentColor" d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2Z" />
                        </svg>
                        <span class="font-bold">Add Collection</span>
                    </NuxtLink>
                    <NuxtLink to="/dashboard/components" class="flex gap-2 items-center p-2 hover:bg-base-300 cursor-pointer">
                        <svg width="20" height="20" viewBox="0 0 24 24">
                            <path fill="currentColor" d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2Z" />
                        </svg>
                        <span class="font-bold">Add Components</span>
                    </NuxtLink>

                    <h2 class="text-md font-bold">Collections</h2>
                    <ul class="list-disc">
                        <li><NuxtLink to="/dashboard/collections/users" >Users</NuxtLink></li>
                        <li><NuxtLink to="/dashboard/collections/articles">Articles</NuxtLink></li>
                    </ul>
                    <h2 class="text-md font-bold">Components</h2>
                </div>
            </ul>
        </div>
    </div>
</template>