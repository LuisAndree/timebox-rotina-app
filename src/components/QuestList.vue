<template>
    <div class="container">
        <h1>Quest To-Do List</h1>

        <!-- Main Quest -->
        <div class="quest main-quest">
            <h2>Main Quest</h2>
            <ul>
                <li><input type="checkbox"> Save the Kingdom</li>
                <li><input type="checkbox"> Defeat the Dragon</li>
                <li><input type="checkbox"> Rescue the Princess</li>
            </ul>
        </div>

        <!-- Side Quests -->
        <div class="quest side-quest">
            <h2>Side Quests</h2>
            <ul>
                <li><input type="checkbox"> Gather 10 Healing Potions</li>
                <li><input type="checkbox"> Visit the Old Sage</li>
                <li><input type="checkbox"> Explore the Mystic Cave</li>
            </ul>
        </div>

    </div>
</template>

<script>
</script>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 300px;
    text-align: center;
}

h1 {
    margin-bottom: 20px;
    color: #333;
}

.quest {
    margin-bottom: 20px;
}

.quest h2 {
    background-color: #333;
    color: #fff;
    padding: 10px;
    border-radius: 5px;
    margin-bottom: 10px;
}

.main-quest h2 {
    background-color: #f15a24;
}

.side-quest h2 {
    background-color: #2d9cdb;
}

ul {
    list-style: none;
}

ul li {
    padding: 10px;
    background-color: #eaeaea;
    margin-bottom: 5px;
    border-radius: 5px;
    text-align: left;
}

ul li input[type="checkbox"] {
    margin-right: 10px;
}
</style>