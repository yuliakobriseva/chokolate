class Chocolate:
    def __init__(self, name, brand, flavor, price):
        self.name = name
        self.brand = brand
        self.flavor = flavor
        self.price = price

    def display_info(self):
        print(f"Chocolate: {self.name}")
        print(f"Brand: {self.brand}")
        print(f"Flavor: {self.flavor}")
        print(f"Price: ${self.price}")

# Example usage
if __name__ == "__main__":
    # Creating an instance of the Chocolate class
    my_chocolate = Chocolate(name="Dark Chocolate", brand="Lindt", flavor="Intense", price=3.99)

    # Displaying information about the chocolate
    my_chocolate.display_info()
