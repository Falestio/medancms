<template>
    <div class="grid grid-cols-12 gap-6">
        <div class="col-span-12 flex justify-between items-center">
            <h1 class="text-2xl font-bold">Artikel Pertama</h1>
            <div class="flex gap-4">
                <button class="btn btn-secondary">Publikasikan</button>
                <button class="btn btn-primary">Simpan</button>
            </div>
        </div>
        <div class="col-span-9 shadow border">
            <div class="p-4 flex flex-col gap-4">
                <div class="form-control">
                    <label class="label">
                        <span class="label-text font-bold">Content</span>
                    </label>
                    <textarea class="textarea textarea-bordered h-24"></textarea>
                </div>
                <div class="form-control w-full max-w-xs">
                    <label class="label">
                        <span class="label-text">Like</span>
                    </label>
                    <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs" />
                </div>
            </div>
        </div>
        <div class="col-span-3 shadow border">
            <div class="flex flex-col gap-4">
                <div class="flex flex-col">
                    <NuxtLink class="flex gap-2 items-center py-2 px-4 hover:bg-base-300" to="/dashboard/collections/articles/editor">
                        <svg width="20" height="20" viewBox="0 0 24 24"><path fill="currentColor" d="M4 2h16a2 2 0 0 1 2 2v16a2 2 0 0 1-2 2H4c-1.08 0-2-.9-2-2V4a2 2 0 0 1 2-2m0 2v7h7V4H4m0 16h7v-7H4v7m16 0v-7h-7v7h7m0-16h-7v7h7V4Z"/></svg>
                        Edit appereance
                    </NuxtLink>
                    <NuxtLink class="flex gap-2 items-center py-2 px-4 hover:bg-base-300" to="/dashboard/collections/articles/editor">
                        <svg width="20" height="20" viewBox="0 0 24 24"><path fill="currentColor" d="M19.9 12.66a1 1 0 0 1 0-1.32l1.28-1.44a1 1 0 0 0 .12-1.17l-2-3.46a1 1 0 0 0-1.07-.48l-1.88.38a1 1 0 0 1-1.15-.66l-.61-1.83a1 1 0 0 0-.95-.68h-4a1 1 0 0 0-1 .68l-.56 1.83a1 1 0 0 1-1.15.66L5 4.79a1 1 0 0 0-1 .48L2 8.73a1 1 0 0 0 .1 1.17l1.27 1.44a1 1 0 0 1 0 1.32L2.1 14.1a1 1 0 0 0-.1 1.17l2 3.46a1 1 0 0 0 1.07.48l1.88-.38a1 1 0 0 1 1.15.66l.61 1.83a1 1 0 0 0 1 .68h4a1 1 0 0 0 .95-.68l.61-1.83a1 1 0 0 1 1.15-.66l1.88.38a1 1 0 0 0 1.07-.48l2-3.46a1 1 0 0 0-.12-1.17ZM18.41 14l.8.9l-1.28 2.22l-1.18-.24a3 3 0 0 0-3.45 2L12.92 20h-2.56L10 18.86a3 3 0 0 0-3.45-2l-1.18.24l-1.3-2.21l.8-.9a3 3 0 0 0 0-4l-.8-.9l1.28-2.2l1.18.24a3 3 0 0 0 3.45-2L10.36 4h2.56l.38 1.14a3 3 0 0 0 3.45 2l1.18-.24l1.28 2.22l-.8.9a3 3 0 0 0 0 3.98Zm-6.77-6a4 4 0 1 0 4 4a4 4 0 0 0-4-4Zm0 6a2 2 0 1 1 2-2a2 2 0 0 1-2 2Z"/></svg>
                        Edit fields
                    </NuxtLink>
                    <NuxtLink class="flex gap-2 items-center py-2 px-4 hover:bg-base-300" to="/dashboard/collections/articles/editor">
                        <svg width="20" height="20" viewBox="0 0 24 24"><path fill="currentColor" d="M9 3v1H4v2h1v13a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6h1V4h-5V3H9m0 5h2v9H9V8m4 0h2v9h-2V8Z"/></svg>
                        Delete this entry
                    </NuxtLink>
                </div>
            </div>
        </div>
    </div>
</template>