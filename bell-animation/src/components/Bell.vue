<script setup>

</script>

<template>
  <img src="../assets/notifications.svg" alt="bell">
</template>

<style scoped>
img{
    width: 150px;
    height: 150px;
    animation: bell 1.5s ease-in-out infinite alternate;

}

@keyframes bell {
    0% {

        transform: rotate(0deg);

    }

    5%, 15% {

        transform: rotate(25deg);

    }

    10%, 20% {

        transform: rotate(-25deg);

    }

    25%  {

        transform: rotate(0deg);

    }

    100% {

        transform: rotate(0deg);

    }
}
</style>