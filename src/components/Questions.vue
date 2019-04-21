<template>
    <div>
        Would you rather...
        <Options0></Options0>
        Would you rather...
        <Options1></Options1>
        Would you rather...
        <Options2></Options2>
    </div>
</template>

<script>
    import Options2 from "./Options2";
    import Options1 from "./Options1";
    import Options0 from "./Options0";

    export default {
        name: "Questions",
        components:{
            Options0,
            Options1,
            Options2
        }
    }
</script>

<style scoped>

</style>