### Task-1 (Module 20-6)

Define a function that simulates calling the waiter to get the menu

**Output:**

<br>

    Waiter, please bring the menu.
    Menu: [ 'Starter', 'Main Course', 'Dessert', 'Beverages' ]

**Solution**
<br>

        function callWaiter() {

        console.log("Waiter, please bring the menu.");

        var menu = ["Starter", "Main Course", "Dessert", "Beverages"];
        return menu;

        }


        var menuItems = callWaiter();
        console.log("Menu:", menuItems);

---
