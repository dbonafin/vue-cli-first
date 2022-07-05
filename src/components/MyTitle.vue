<template>
    <div>
        <h1> {{msg}} </h1>
    </div>
</template>

<script>
export default {
    name: "MyTitle",
    props: {
        msg: String
    }
}
</script>

<style>
h1 {
    color: darkgreen;
}

</style>