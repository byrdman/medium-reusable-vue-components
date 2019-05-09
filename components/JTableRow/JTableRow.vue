<template>
    <tr>
        <td v-for="(value, index) in values" :key="index">
            {{ value }}
        </td>
    </tr>
</template>

<script>
    export default {
        name: 'JTableRow',
        props: {
            values: {
                type: Array,
                required: true
            }
        }
    }
</script>