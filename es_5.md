#es 5: da 10 a 1
number = int(input("dimmi sto numero"))

count = 10
while count > 0:
    result = number * count
    print(number, "x", count, "=", result)
    count -= 1
