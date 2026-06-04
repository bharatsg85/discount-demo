price = int(input("enter your price here - "))
qty = int(input("enetr your qty here - "))

amount = price * qty

if amount > 10000:
    print("10% discount applicable")
    discount = amount * 10 / 100

elif amount > 5000:
    print("5% discount applicable")
    discount = amount * 5 / 100

elif amount > 2000:
    print("2% discount applicable")
    discount = amount * 2 / 100

elif amount > 1000:
    print("1% discount applicable")
    discount = amount * 1 / 100

else:
    discount = 0

amount = amount - discount

print("Amount payable:", amount)
