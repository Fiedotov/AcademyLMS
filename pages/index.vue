<script>

export default {
    name: 'AcademyLogin',

    head() {
        return {
            title: 'Academy App Login',
            meta: [
                {
                    hid: 'Academy',
                    name: 'Academy',
                    content: 'Academy LMS.'
                }
            ]
        }
    },
}
</script>

<template>
    <div class="bg-[#008ce5] min-h-screen flex justify-center items-center">
        <div class="flex h-[80%] space-x-[70px]">
            <div class="relative rectangle-login w-[300px]">
                <img class="absolute top-[-30px] right-[-85px] w-[531px] h-[531px] !max-w-[fit-content]"
                    src="3d-icon-default.png" />
            </div>
            <div class="rectangle-form flex justify-center items-center">
                <div class="flex flex-col h-[70%] w-[70%] space-y-5">
                    <div class="text-[#006cb0] text-[24px] font-[700]">Hi! Let’s sign in</div>
                    <div class="space-y-5 pt-5">
                        <div class="sm:col-span-4">
                            <div class="mt-2">
                                <div
                                    class="flex rounded-full py-3 ring-1 ring-inset ring-gray-300 focus-within:ring-2 focus-within:ring-inset focus-within:ring-indigo-600 sm:max-w-md">
                                    <img src="user.svg" class="mt-[5px] w-[25px] h-[25px] ml-[20px]" />
                                    <input type="text" name="username" id="username" autocomplete="off"
                                        class="block flex-1 border-0 bg-transparent mr-5 py-1.5 pl-1 placeholder:text-[15px] outline-none"
                                        placeholder="Enter username">
                                </div>
                            </div>
                        </div>
                        
                        <div class="sm:col-span-4">
                            <div class="mt-2">
                                <div
                                    class="flex rounded-full py-3 ring-1 ring-inset ring-gray-300 focus-within:ring-2 focus-within:ring-inset focus-within:ring-indigo-600 sm:max-w-md">
                                    <img src="lock.svg" class="mt-[5px] w-[25px] h-[25px] ml-[20px]" />
                                    <input type="password" name="username" id="username" autocomplete="off"
                                        class="block flex-1 border-0 bg-transparent mr-5 py-1.5 pl-1 placeholder:text-[15px] outline-none"
                                        placeholder="Enter password">
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="flex justify-end items-center">
                        <a class="text-[#006cb0] text-[17px] font-[400]">Forgot Password?</a>
                    </div>
                    <div class="py-10">
                        <button type="submit"
                            class="flex w-full justify-center bg-[#008ce5] font-[700] px-3 py-4 rounded-full text-white shadow-2xl btn-shadow hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Sign
                            in</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.rectangle-login {
    background: linear-gradient(230.51deg,
            rgba(255, 255, 255, 0.22) 0%,
            rgba(255, 255, 255, 0.03) 100%);
    border-radius: 25.46px;
    border-width: 1.31px;
    border-style: solid;
    border-image: linear-gradient(190.42deg,
            rgba(255, 255, 255, 0.36) 0%,
            rgba(255, 255, 255, 0) 100%);
    backdrop-filter: blur(55.5px);
}

.rectangle-form {
    background: #ffffff;
    border-radius: 20px;
    width: 404px;
    height: 537px;
    position: relative;
    box-shadow: 0px 10px 20px 0px rgba(73, 87, 184, 0.1);
}

.btn-shadow {
    box-shadow: 1px 6px 0px 0px rgba(0, 108, 176, 1);
}</style>