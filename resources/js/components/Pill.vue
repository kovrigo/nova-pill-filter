<template>

    <div class="pill"
         :class="{ 'active': active, '': !active }">

        <slot/>

    </div>

</template>

<script>

    export default {
        name: 'Pill',
        props: {
            active: {
                type: Boolean,
                required: true
            }
        }
    }

</script>
