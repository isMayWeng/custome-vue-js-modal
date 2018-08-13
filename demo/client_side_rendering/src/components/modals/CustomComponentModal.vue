<template>
    <div>
        <div class="v--modal-body example-modal-content">
            <h1>This is a custom component</h1>
            <p>{{ text }}</p>
        </div>
        <div class="v--modal-footer">
            <button class="btn">Close this using name</button>
        </div>
    </div>
</template>

<script>
    export default {
        props: ['text']
    }
</script>
