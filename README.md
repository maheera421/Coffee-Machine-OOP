# Coffee-Machine-OOP
# 🚀 Code Description:

The provided code is a Python script that simulates a coffee machine program. It allows users to interact with the coffee machine by selecting drinks from a menu, checking the machine's resources, making payments, and ultimately receiving their desired drinks. The program operates in a loop until the user decides to turn it off.

# 🔐 Code Specification:

1. The code imports three classes: `Menu`, `CoffeeMaker`, and `MoneyMachine`.

2. It initializes instances of these classes: `menu`, `coffee_maker`, and `money_machine`.

3. The program uses a `while` loop to keep running until the variable `is_on` becomes `False`.

4. Inside the loop, it presents the user with a list of available drink options retrieved using `menu.get_items()`. The user is prompted to enter their choice.

5. If the user inputs "off," the `is_on` variable becomes `False`, and the program terminates.

6. If the user inputs "report," the program calls `coffee_maker.report()` and `money_machine.report()` to display the current status of the coffee machine's resources and profits.

7. If the user selects a specific drink, the program checks if there are sufficient resources to make that drink using `coffee_maker.is_resource_sufficient(drink)`. It also checks if the user has enough money to purchase the drink using `money_machine.make_payment(drink.cost)`.

8. If both resource sufficiency and payment are met, the program proceeds to make the coffee using `coffee_maker.make_coffee(drink)`.


