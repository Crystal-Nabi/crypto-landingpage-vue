<template>
    <div :data-aos="animateCard" data-aos-delay="300"
        class="w-[24%] lg:flex-col bg-white border0 rounded-lg shadow dark:bg-gray-800 my-4"
        style="background: linear-gradient(169.4deg, #3984f4 -6.01%, #0cd3ff 36.87%, #2f7cf0 78.04%, #0e65e8 103.77%);">


        <div class="p-5  transform transition duration-500 hover:scale-110">
            <img class="w-32 h-32 ring-2 ring-gray-300 ring-gray-300 rounded-full m-auto my-5 transform transition duration-500 hover:scale-110"
                :src="require(`~/assets/img/speakers/${url}`)" alt="Rounded avatar" />
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-white dark:text-white text-center ">{{ name }}</h5>
        </div>
        <p class="mb-3 font-normal text-white text-[1.5rem] text-center">{{ description }}</p>

    </div>
</template>
<script>
export default {
    name: 'Card',
    props: {
        name: {
            type: String,
            default: 'Name',
        },
        description: {
            type: String,
            default: 'descrition',
        },
        url: {
            type: String,
            default: '',
        },
        animateCard: {
            type: String,
            default: 'fade-up',
        },
    }
}
</script>