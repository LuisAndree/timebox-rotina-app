<template>
    <div class="container">
        <table>
            <thead>
                <tr>
                    <th>Horário</th>
                    <th>Segunda</th>
                    <th>Terça</th>
                    <th>Quarta</th>
                    <th>Quinta</th>
                    <th>Sexta</th>
                    <th>Sábado</th>
                    <th>Domingo</th>
                </tr>
            </thead>
            <tbody>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
                <TheTr></TheTr>
            </tbody>
        </table>
        <!-- <div><QuestList></QuestList></div> -->
        
    </div>
</template>

<script>
import TheTr from './TheTr.vue'
// import QuestList from './QuestList.vue'
export default {
    components: {
        TheTr,
        // QuestList
    },
}
</script>

<style scoped>
table {
    width: 100%;
    border-collapse: collapse;
    table-layout: fixed;
}

th,

td {
    padding: 15px;
    border: 1px solid #ccc;
    text-align: center;
    width: 12.5%;
}

th {
    background-color: #007bff;
    color: white;
}

tbody tr:nth-child(odd) .tdclass {
    background-color: #f7f9fc;
}

tbody tr:nth-child(even) .tdclass {
    background-color: #e3e7ea;
}
</style>
