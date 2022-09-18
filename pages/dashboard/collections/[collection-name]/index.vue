<script setup>
    
</script>

<template>
    <div class="grid grid-cols-12 gap-6">
        <div class="col-span-12 shadow border">
            <div class="p-8 flex flex-col gap-4">
                <div>
                    <h2 class="text-xl font-bold">Artikel</h2>
                    <p class="text-md">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi, dignissimos.</p>
                </div>
                <div class="flex gap-4 self-end">
                    <h3 class="text-lg font-bold">6 Fields</h3>
                    <button class="btn btn-primary btn-sm">+ Add Fields</button>
                </div>

                <ul class="flex flex-col gap-4">
                    <li class="grid grid-cols-12 border-b p-2">
                        <div class="col-span-10 flex gap-4">
                            <p class="text-md font-bold">Content</p>
                            <span class="badge badge-secondary">Markdown</span>
                        </div>
                        <div class="flex gap-2 col-span-2 justify-end">
                            <svg width="20" height="20" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M20.71 7.04c.39-.39.39-1.04 0-1.41l-2.34-2.34c-.37-.39-1.02-.39-1.41 0l-1.84 1.83l3.75 3.75M3 17.25V21h3.75L17.81 9.93l-3.75-3.75L3 17.25Z"
                                />
                            </svg>
                            <svg width="20" height="20" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M9 3v1H4v2h1v13a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6h1V4h-5V3H9M7 6h10v13H7V6m2 2v9h2V8H9m4 0v9h2V8h-2Z"
                                />
                            </svg>
                        </div>
                    </li>
                    <li class="grid grid-cols-12 border-b p-2">
                        <div class="col-span-10 flex gap-4">
                            <p class="text-md font-bold">Author</p>
                            <span class="badge badge-accent">Text</span>
                        </div>
                        <div class="flex gap-2 col-span-2 justify-end">
                            <svg width="20" height="20" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M20.71 7.04c.39-.39.39-1.04 0-1.41l-2.34-2.34c-.37-.39-1.02-.39-1.41 0l-1.84 1.83l3.75 3.75M3 17.25V21h3.75L17.81 9.93l-3.75-3.75L3 17.25Z"
                                />
                            </svg>
                            <svg width="20" height="20" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M9 3v1H4v2h1v13a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6h1V4h-5V3H9M7 6h10v13H7V6m2 2v9h2V8H9m4 0v9h2V8h-2Z"
                                />
                            </svg>
                        </div>
                    </li>
                    <li class="grid grid-cols-12 border-b p-2">
                        <div class="col-span-10 flex gap-4">
                            <p class="text-md font-bold">Like</p>
                            <span class="badge badge-primary">Number</span>
                        </div>
                        <div class="flex gap-2 col-span-2 justify-end">
                            <svg width="20" height="20" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M20.71 7.04c.39-.39.39-1.04 0-1.41l-2.34-2.34c-.37-.39-1.02-.39-1.41 0l-1.84 1.83l3.75 3.75M3 17.25V21h3.75L17.81 9.93l-3.75-3.75L3 17.25Z"
                                />
                            </svg>
                            <svg width="20" height="20" viewBox="0 0 24 24">
                                <path
                                    fill="currentColor"
                                    d="M9 3v1H4v2h1v13a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V6h1V4h-5V3H9M7 6h10v13H7V6m2 2v9h2V8H9m4 0v9h2V8h-2Z"
                                />
                            </svg>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
        <div class="col-span-12 shadow border">
            <div class="p-8 flex flex-col gap-4">
                <div class="flex gap-4 self-end">
                    <h3 class="text-lg font-bold">3 Articles</h3>
                    <button class="btn btn-primary btn-sm">+ Add Article</button>
                </div>
                <div class="overflow-x-auto">
                    <table class="table w-full">
                        <!-- head -->
                        <thead>
                            <tr>
                                <th>id</th>
                                <th>Author</th>
                                <th>Created At</th>
                                <th>Updated At</th>
                                <th>Status</th>
                            </tr>
                        </thead>
                        <tbody>
                            <!-- row 1 -->
                            <tr>
                                <th>1</th>
                                <td>Cy Ganderton</td>
                                <td>Quality Control Specialist</td>
                                <td>Blue</td>
                                <td><span class="badge badge-success">Published</span></td>
                            </tr>
                            <!-- row 2 -->
                            <tr>
                                <th>2</th>
                                <td>Hart Hagerty</td>
                                <td>Desktop Support Technician</td>
                                <td>Purple</td>
                                <td><span class="badge badge-success">Published</span></td>
                            </tr>
                            <!-- row 3 -->
                            <tr>
                                <th>3</th>
                                <td>Brice Swyre</td>
                                <td>Tax Accountant</td>
                                <td>Red</td>
                                <td><span class="badge badge-success">Published</span></td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>