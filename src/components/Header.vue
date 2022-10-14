<template>
    <div class="row">
        <div class="col-12 col-md-3">
            <h1>app vue</h1>

        </div>
        <div class="col-12 col-md-6">
            <img :src="url" :alt="alt" width="100">
        </div>
    </div>
    <hr>
</template>

<script>
    export default {
        data: () => ({
            url: "",
            alt: "Vue.js",
        }),
    };
</script>