<template>
    <div>
        <main class="flex justify-center p-10">
            <div class="rounded border shadow max-w-4xl">
                <div class="p-8 flex flex-col gap-4 w-full">
                    <h1 class="text-3xl font-bold">Login to your account</h1>
                    <div class="form-control flex flex-col gap-8">                 
                        <div class="form-control">
                            <label class="label">
                                <span class="label-text">Email</span>
                            </label>
                            <input type="text" placeholder="John@email.com" class="input input-bordered w-full" />                            
                        </div>                   
                        <div class="form-control">
                            <label class="label">
                                <span class="label-text">Password</span>
                            </label>
                            <input type="passwod" class="input input-bordered w-full" />                            
                        </div>                   
                        <button class="btn btn-primary">Mulai</button>
                    </div>
                </div>
            </div>
        </main>
    </div>
</template>