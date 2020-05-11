<template>
    <div class="list-wrapper">
        <div class="list-background">
            <h2 class="list-name">Selected List Name</h2> 
            <table class="table is-bordered is-narrow">
                <thead>
                    <tr>
                        <th>Quantity</th>
                        <th>Item</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                    <tr>
                        <th>1</th>
                        <td>Kettle Chips</td>
                    </tr>
                </tbody>
            </table>
        </div>             
    </div>
</template>

<style lang="scss" scoped>
.list-wrapper {
    background-image: url("../assets/produce.jpg");
    background-size: cover;
    min-height: 600px;
    padding: 20px;
}
.list-background {
    width: 260px;
    border: 4px solid $dark;
    border-radius: 15px;
    margin: auto;
}
.list-name {
    color: $gold-light;
    text-align: center;
    background-color: $dark;
    font-weight: bold;
    font-size: 26px;
    padding: 8px;
}
.table {
    width: 100%;
    background-color: $green-light;
    color: $dark;
}
.table td, .table th {
    border: 1px solid $green-dark;
    text-align: center;
}
td {
    width: 220px;
}
</style>