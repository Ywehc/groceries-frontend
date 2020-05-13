<template>
    <div class="list-wrapper">
        <div class="list-background">
            <div class="list-heading">
                <h2 class="list-name">Selected List Name</h2> 
                <span class="delete-list"><i class="fas fa-trash"></i></span>
            </div>          
            <table class="table is-bordered is-narrow">
                <tbody>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
                    </tr>
                    <tr>
                        <th class="quantity">1</th>
                        <td class="item">Kettle Chips</td>
                        <td class="cross"><i class="far fa-check-circle"></i></td>
                        <td class="remove"><i class="fas fa-minus-circle"></i></td>
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
    padding-top: 20px;
}
.list-background {
    width: 86%;
    max-width: 700px;
    border: 4px solid $dark;
    border-radius: 15px;
    margin: auto;
    padding: 4px;
    background-color: $green-dark;
}
.list-heading {
    display: flex;
    justify-content: space-between;
    background: $dark;
    padding: 10px;
}
.list-name {
    color: $gold-light;
    text-align: center;
    background-color: $dark;
    font-weight: bold;
    font-size: 20px;
}
.fa-trash {
    color: $green-dark;
    font-size: 120%;
    padding: 4px;
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
.item {
    width: 70%;
}
.cross, .remove, .quantity {
    width: 10%;
}
.fa-check-circle {
    color: $green-dark;
}

@media screen and (min-width: 768px) {
  .list-wrapper {
      background-position-y: 85%;
      min-height: 600px;
      padding-top: 100px;
      border-radius: 15px;
  }
  .list-background {
      background-color: $dark;
  }
}
</style>