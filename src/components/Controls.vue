<template>
    <div class="controls-container">
        <div class="field is-grouped buttons are-medium">
            <div :class="dropdownClasses" class="control">
                <div class="dropdown-trigger">
                    <button class="button list-selector" @click="toggleDropdown()" aria-haspopup="true" aria-controls="dropdown-menu">
                        <span>Select List</span>
                        <span class="icon is-small">
                            <i class="fas fa-angle-down" aria-hidden="true"></i>
                        </span>
                    </button>
                </div>
                <div class="dropdown-menu" id="dropdown-menu" role="menu">
                    <div class="dropdown-content">
                        <a href="#" class="dropdown-item">
                            Grocery List 1
                        </a>
                        <a class="dropdown-item">
                            Grocery List 2
                        </a>
                        <a href="#" class="dropdown-item is-active">
                            Active Grocery List
                        </a>
                        <a href="#" class="dropdown-item">
                            Grocery List 4
                        </a>

                    </div>
                </div>
            </div>
            <p class="control">
                <button class="button new-list">
                New List
                </button>
            </p>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            isActive: false
        }
    },
    computed: {
        dropdownClasses: function() {
            if (this.isActive) {
                return "dropdown is-active";
            } else {
                return "dropdown";
            }
        }
    },
    methods: {
        toggleDropdown: function() {
            this.isActive = !this.isActive;
        }
    }
}
</script>

<style lang="scss" scoped>
.is-grouped {
    justify-content: center;
    padding: 10px;
}
.new-list {
    background-color: $gold-light;
    color: $dark;
    border: $green-dark; 
}
.list-selector{
    background-color: $green-light;
    color: $dark; 
    border: $green-dark; 
}
.new-list, .list-selector {
    font-weight: bold;
}
.dropdown-content {
    background-color: $dark;
    border: 4px solid $dark;
    a {
        color: $green-light;
        font-weight: bold;
    }
}
.dropdown-item.is-active {
    background: $gold-light;
}
</style>