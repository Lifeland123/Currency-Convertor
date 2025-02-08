#Exchange rate in a ditionary
exchangerates = {
    "USD": {"GHS": 15.80, "EUR": 0.96, "USD": 1},
    "EUR": {"USD": 1.04, "GHS": 16.46, "EUR": 1},
    "GHS": {"USD": 0.063, "EUR": 0.061, "GHS": 1}
}

def main():
    print("Welcome to Currency Converter")
    print("Available currencies: GHS, USD, EUR")

    #Entering the currency the user wants to change
    fromcurrency = input("Enter the currency to convert from (GHS/USD/EUR): ").upper()

    #Entering the currency the user wants to change to
    tocurrency = input("Enter the currency to convert to (GHS/USD/EUR): ").upper()

    #Entering the amount
    amount = float(input("Enter the amount: "))

    if fromcurrency not in exchangerates or tocurrency not in exchangerates:
        print("Invalid currency choice")
        return

    result = amount * exchangerates[fromcurrency][tocurrency]
    print(f"{amount} {fromcurrency} = {result} {tocurrency}")

# Results being displayed
main()#Exchange rate in a ditionary
exchangerates = {
    "USD": {"GHS": 15.80, "EUR": 0.96, "USD": 1},
    "EUR": {"USD": 1.04, "GHS": 16.46, "EUR": 1},
    "GHS": {"USD": 0.063, "EUR": 0.061, "GHS": 1}
}

def main():
    print("Welcome to Currency Converter")
    print("Available currencies: GHS, USD, EUR")

    #Entering the currency the user wants to change
    fromcurrency = input("Enter the currency to convert from (GHS/USD/EUR): ").upper()

    #Entering the currency the user wants to change to
    tocurrency = input("Enter the currency to convert to (GHS/USD/EUR): ").upper()

    #Entering the amount
    amount = float(input("Enter the amount: "))

    if fromcurrency not in exchangerates or tocurrency not in exchangerates:
        print("Invalid currency choice")
        return

    result = amount * exchangerates[fromcurrency][tocurrency]
    print(f"{amount} {fromcurrency} = {result} {tocurrency}")

# Results being displayed
main()
