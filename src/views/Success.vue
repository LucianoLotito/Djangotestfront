<template>
    <div class="page-success">
        <div class="columns is-multiline">
            <div class="column is-12">
                <h1 class="title">
                    Thank you!
                </h1>

                <p>Your order will be processed within 48 hours</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Success',
    data() {
        return {

        }
    },
    mounted() {
        document.title = 'Success | I\'m Fuchsia'
    }
}
</script>

<style scoped>

</style>