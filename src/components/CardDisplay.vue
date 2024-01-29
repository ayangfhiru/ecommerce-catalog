<template>
    <div class="card">
        <div class="element">
            <div class="image">
                <img src="" alt="" class="img">
            </div>
            <div class="desc">
                Lorem ipsum dolor sit amet consectetur, adipisicing elit. Autem, inventore!
            </div>
        </div>
    </div>
</template>

<style scoped>
.card {
    width: 1034px;
    height: 350px;
    border-radius: 10px;
    background-color: yellow;
    padding: 20px;
    box-sizing: border-box;
}

.element {
    display: flex;
    justify-content: space-between;
}

.image {
    width: 300px;
    background-color: blue;
}

.desc {
    width: 550px;
    border-radius: 4px;
    background-color: pink;
}
</style>