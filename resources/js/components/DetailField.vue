<template>
    <div class="flex border-b border-40" style="padding-bottom: 5px">
        <h2>{{field.name}}</h2>
    </div>
</template>

<script>
export default {
    props: ['resource', 'resourceName', 'resourceId', 'field'],
}
</script>
