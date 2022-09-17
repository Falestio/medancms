<template>
    <div class="grid grid-cols-12 gap-6">
        <div class="col-span-4 shadow border">
            <div class="p-4 flex flex-col gap-4">
                <div class="flex items-center gap-2">
                    <h2 class="text-xl font-bold">Jenis Koleksi</h2>                
                    <span class="badge badge-primary">4</span>
                </div>
                <ul class="flex flex-col gap-4">
                    <li>
                        <button class="btn btn-ghost btn-active">Artikel</button>    
                    </li>
                    <li>
                        <button class="btn btn-ghost">Latihan</button>
                    </li>
                    <li>
                        <button class="btn btn-ghost">Latihan CLI</button>
                    </li>
                    <li>
                        <button class="btn btn-ghost">Pengguna</button>
                    </li>
                </ul>
            </div>
        </div>
        <div class="col-span-8 shadow border">
            <div class="p-4">
                <div>
                    <h2 class="text-xl font-bold">Artikel</h2>
                    <p class="text-md">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, dignissimos.</p>
                </div>
            </div>
        </div>
    </div>
</template>