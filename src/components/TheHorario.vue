<template >
    <td :key="horarios.id"> {{ horarios[id].horas }}:{{horarios[id].minutos}} - {{ horarios[id + 1].horas }}:{{horarios[id + 1].minutos}}
    </td>

</template>

<script>
export default {
    name: 'TheHorario',
    components: {

    },
    data() {
        return {
            horarios: [
                {
                    "id": 0,
                    "horas": "07",
                    "minutos": "00",
                },
                {
                    "id": 1,
                    "horas": "08",
                    "minutos": "00",
                },
                {
                    "id": 2,
                    "horas": "09",
                    "minutos": "00",
                },
                {
                    "id": 4,
                    "horas": "10",
                    "minutos": "00",
                },
                {
                    "id": 5,
                    "horas": "11",
                    "minutos": "00",
                },
                {
                    "id": 6,
                    "horas": "12",
                    "minutos": "00",
                },
                {
                    "id": 7,
                    "horas": "13",
                    "minutos": "00",
                },
                {
                    "id": 8,
                    "horas": "14",
                    "minutos": "00",
                },
                {
                    "id": 9,
                    "horas": "15",
                    "minutos": "00",
                },
                {
                    "id": 10,
                    "horas": "16",
                    "minutos": "00",
                },
                {
                    "id": 11,
                    "horas": "17",
                    "minutos": "00",
                },
                {
                    "id": 12,
                    "horas": "18",
                    "minutos": "00",
                },
                {
                    "id": 13,
                    "horas": "19",
                    "minutos": "00",
                },
                {
                    "id": 14,
                    "horas": "20",
                    "minutos": "00",
                },
                {
                    "id": 15,
                    "horas": "21",
                    "minutos": "00",
                },
                {
                    "id": 16,
                    "horas": "22",
                    "minutos": "00",
                },
                {
                    "id": 17,
                    "horas": "23",
                    "minutos": "00",
                },

            ]
        };
    }
}
</script>

<style></style>