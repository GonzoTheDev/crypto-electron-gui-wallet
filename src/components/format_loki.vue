<template>
<span>
    {{ value }} CRYPTO
</span>
</template>

<script>
export default {
    name: "FormatLoki",
    props: {
        amount: {
            required: true
        },
        round: {
            type: Boolean,
            required: false,
            default: false
        },
        rawValue: {
            type: Boolean,
            required: false,
            default: false
        }
    },
    computed: {
        value () {
            let value = this.amount / 1e12
            if(this.round)
                value = value.toFixed(3)
            return this.rawValue ? value : value.toLocaleString()
        }

    }
}
</script>

<style>
</style>
