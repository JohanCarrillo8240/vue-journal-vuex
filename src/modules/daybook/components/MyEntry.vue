<template>
    <div class="entry-container mb-3 pointer p-2"
        @click="$router.push({name:'entry', params:{id:12}})">
        <div class="entry-tittle d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2023</span>
        </div>
        <div class="entry-description">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi suscipit distinctio, beatae deserunt ipsa aliquam optio fuga deleniti pariatur assumenda, porro corporis incidunt ad dignissimos quos earum dolore soluta ex!
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.entry-container{
    transition: 0.2s all ease-in;
    &:hover{
        background-color: lighten($color: grey, $amount: 45);
        transition: 0.2s all ease-in;
    }
    .entry-description{
        font-size: 12px;
    }
}
</style>