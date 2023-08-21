<script>
export default {
    name: 'jumbo',
}
</script>

<template>
    <div class="container">
        <div class="img-container">
            <img src="../assets/01.webp" alt="jumbo img morales">
        </div>
        <p>non è per niente facile questa roba</p>
    </div>
</template>

<style>
.container {
    display: flex;
    justify-content: center;
}
.img-container {
    height: 500px;
    width: 600px;
}

.img-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

p {
    position: absolute;
    font-size: .7rem;
}
</style>