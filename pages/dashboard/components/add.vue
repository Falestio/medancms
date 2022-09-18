<template>
    <div class="flex flex-col gap-8">
        <!-- MODAL 1 -->
        <input type="checkbox" id="add-field-modal" class="modal-toggle" />
        <div class="modal">
            <div class="modal-box max-w-4xl relative p-0">
                <div class="p-6 bg-base-200 flex justify-between">
                    <p class="text-xl font-bold">Add new Component</p>
                    <label for="add-field-modal" class="btn btn-sm btn-circle">✕</label>
                </div>
                <div class="p-6">
                    <h3 class="text-lg font-bold mb-4">Add a field</h3>
                    <div class="grid grid-cols-2 gap-6">
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                        <div class="p-2 flex gap-4 border shadow rounded">
                            <span class="badge">Rich Text</span>
                            <p>Rich Text Editor & Markdown Support</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Modal 2 -->
        <input type="checkbox" id="add-field-modal2" class="modal-toggle" />
        <div class="modal">
            <div class="modal-box relative max-w-4xl p-0">
                <div class="p-6 bg-base-200 flex justify-between">
                    <p class="text-xl font-bold">Add fields for Article</p>
                    <label for="add-field-modal2" class="btn btn-sm btn-circle">✕</label>
                </div>
                <div class="p-6">
                    <div class="form-control w-full max-w-xs mb-6">
                        <label class="label">
                            <span class="label-text font-bold">Field Name</span>
                        </label>
                        <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs" />
                    </div>
                    <div class="grid grid-cols-2 gap-6">
                        <div class="form-control">
                            <div class="flex gap-2">
                                <input type="checkbox" class="checkbox" />
                                <p class="text-md font-bold">Nilai Unik</p>
                            </div>
                            <p class="text-md">Lorem ipsum dolor sit.</p>
                        </div>
                        <div class="form-control">
                            <div class="flex gap-2">
                                <input type="checkbox" class="checkbox" />
                                <p class="text-md font-bold">Nilai Unik</p>
                            </div>
                            <p class="text-md">Lorem ipsum dolor sit.</p>
                        </div>
                        <div class="form-control">
                            <div class="flex gap-2">
                                <input type="checkbox" class="checkbox" />
                                <p class="text-md font-bold">Nilai Unik</p>
                            </div>
                            <p class="text-md">Lorem ipsum dolor sit.</p>
                        </div>
                        <div class="form-control">
                            <div class="flex gap-2">
                                <input type="checkbox" class="checkbox" />
                                <p class="text-md font-bold">Nilai Unik</p>
                            </div>
                            <p class="text-md">Lorem ipsum dolor sit.</p>
                        </div>
                        <div class="form-control">
                            <div class="flex gap-2">
                                <input type="checkbox" class="checkbox" />
                                <p class="text-md font-bold">Nilai Unik</p>
                            </div>
                            <p class="text-md">Lorem ipsum dolor sit.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="flex items-center gap-8">
            <h1 class="text-2xl font-bold">Add new component</h1>
            <button class="btn btn-primary btn-sm">Save</button>
        </div>
        <div class="shadow rounded p-4 flex flex-col gap-8">
            <div class="flex flex-col gap-4">
                <h2 class="text-xl font-bold">Basic Information</h2>
                <div class="form-control w-full max-w-xs">
                    <label class="label">
                        <span class="label-text font-bold">Collection name</span>
                    </label>
                    <input type="text" placeholder="Type here" class="input input-bordered w-full max-w-xs" />
                </div>
                <div class="flex gap-4">
                    <h2 class="text-xl font-bold">Fields</h2>
                    <label for="add-field-modal" class="btn btn-primary btn-sm">Add field</label>
                    <label for="add-field-modal2" class="btn modal-button">add field 2</label>
                </div>
                <div class="overflow-x-auto">
                    <table class="table w-full">
                        <!-- head -->
                        <tbody>
                            <!-- row 1 -->
                            <tr>
                                <th>1</th>
                                <td>Cy Ganderton</td>
                                <td>Quality Control Specialist</td>
                                <td>Blue</td>
                            </tr>
                            <!-- row 2 -->
                            <tr>
                                <th>2</th>
                                <td>Hart Hagerty</td>
                                <td>Desktop Support Technician</td>
                                <td>Purple</td>
                            </tr>
                            <!-- row 3 -->
                            <tr>
                                <th>3</th>
                                <td>Brice Swyre</td>
                                <td>Tax Accountant</td>
                                <td>Red</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>