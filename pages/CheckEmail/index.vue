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
                    src="Robotic Arm.png" />
            </div>
            <div class="rectangle-form flex justify-center items-center">
                <div class="flex flex-col h-[70%] w-[70%] space-y-5">
                    <div class="h-[80%] flex flex-col justify-center pb-10">
                        <div class="text-[#006cb0] text-[24px] font-[700] pb-8">
                            Check your email...
                        </div>
                        <div class="text-[#000000] text-[17px] font-[400] ">
                            Check your email and click the link to reset your password!
                        </div>
                    </div>
                    <div class="py-10">
                        <button type="submit"
                            class="flex w-full justify-center bg-[#008ce5] font-[700] px-3 py-4 rounded-full text-white shadow-2xl btn-shadow hover:bg-indigo-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Submit</button>
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