<template>
    <tr>
        <!-- <TheHorario></TheHorario> -->
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
        <td contenteditable="true"></td>
    </tr>
</template>

<script>
// import TheHorario from './TheHorario.vue'
export default {
    name: 'TheTd',
    components: {
        // TheHorario,
    },
}
</script>

<style>
td {
    padding: 15px;
    border: 1px solid #ccc;
    text-align: center;
    width: 12.5%;
}

td[contenteditable="true"] {
    background-color: #f7f9fc;
    cursor: pointer;
}

td:hover {
    background-color: #e9ecef;
}

td:focus {
    background-color: #d1ecf1;
}
</style>