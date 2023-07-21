<template>
    <div :data-aos="animateFlip" data-aos-delay="300" class="flip-card my-5 mx-5" @mouseenter="hoverCard(true)"
        @mouseleave="hoverCard(false)">
        <div class="flip-card-inner" :class="{ 'is-hovered': isHovered }">
            <div class="flip-card-front rounded  border-2 flex items-center justify-center">
                <img class="m-auto flex items-center transform transition duration-500"
                    :src="require(`~/assets/img/sponsors/${url}`)" alt="sponsors" />
                <slot name="front"></slot>
            </div>
            <div class="flip-card-back  rounded  border-2  flex items-center justify-center">
                <div class="front-content ">
                    <base-button class="px-8 xl:px-10 py-3 mt-2 bg-gradient-to-r from-[#468ef9] to-[#0c66ee] text-white">
                        Visit
                    </base-button>
                </div>
                <slot name="back"></slot>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: "FlipCard",
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
        animateFlip: {
            type: String,
            default: 'fade-up',
        },
    },
    data() {
        return {
            isHovered: false,
        };
    },
    methods: {
        hoverCard(isHovered) {
            this.isHovered = isHovered;
        },
    }
};
</script>
  
<style scoped>
.flip-card-inner {
    transition: all 1s;
    transform-style: preserve-3d;
}

.flip-card .flip-card-inner.is-hovered .flip-card-front {
    transform: rotateY(180deg);
    transition: all 1s;
}


.flip-card .flip-card-inner.is-hovered .flip-card-back {
    transform: rotateY(360deg);
    transition: all 1s;
}

.flip-card .flip-card-inner .flip-card-front {
    transform: rotateY(0deg);
    transition: all 1s
}

.flip-card .flip-card-inner .flip-card-back {
    transform: rotateY(180deg);
    transition: all 1s
}

.flip-card-front,
.flip-card-back {
    position: absolute;
    backface-visibility: hidden;
    width: 11rem;
    height: 8rem;
    display: flex;
    padding: 10px;
}

.flip-card-back {
    background: #2563eb;
    color: rgb(255, 255, 255);
    transform: rotateY(180deg);
    transition: background-color 0.3s;
}

.flip-card {
    width: 11rem !important;
    height: 8rem !important;
}
</style>