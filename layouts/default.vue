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

                <div>
                    <NuxtLink to="/dashboard/collections" class="flex items-center justify-between">
                        <h2 class="text-md font-bold">Collections</h2>
                        <button class="btn btn-circle btn-xs btn-ghost">
                            <svg width="24" height="24" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M12 19q-.425 0-.712-.288Q11 18.425 11 18v-5H6q-.425 0-.713-.288Q5 12.425 5 12t.287-.713Q5.575 11 6 11h5V6q0-.425.288-.713Q11.575 5 12 5t.713.287Q13 5.575 13 6v5h5q.425 0 .712.287q.288.288.288.713t-.288.712Q18.425 13 18 13h-5v5q0 .425-.287.712Q12.425 19 12 19Z"
                                />
                            </svg>
                        </button>
                    </NuxtLink>
                    <ul class="list-disc">
                        <li><NuxtLink>Users</NuxtLink></li>
                        <li><NuxtLink>Articles</NuxtLink></li>
                    </ul>
                    <div class="flex items-center justify-between">
                        <h2 class="text-md font-bold">Components</h2>
                        <button class="btn btn-circle btn-xs btn-ghost">
                            <svg width="24" height="24" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M12 19q-.425 0-.712-.288Q11 18.425 11 18v-5H6q-.425 0-.713-.288Q5 12.425 5 12t.287-.713Q5.575 11 6 11h5V6q0-.425.288-.713Q11.575 5 12 5t.713.287Q13 5.575 13 6v5h5q.425 0 .712.287q.288.288.288.713t-.288.712Q18.425 13 18 13h-5v5q0 .425-.287.712Q12.425 19 12 19Z"
                                />
                            </svg>
                        </button>
                    </div>
                </div>
            </ul>
        </div>
    </div>
</template>