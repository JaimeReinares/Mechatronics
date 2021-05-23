# Mechatronics
sum_even = 0
sum_odd = 0
div_even = 0
div_odd = 0

number = int(input("Type a number: "))

while number >= 0:
    if number %2==0:
        sum_even = sum_even + number
        div_even = div_even + 1


if div_even!=0:
    arit_even = float(sum_even / div_even)
    print("The arithmetic mean of the even numbers entered is: %.2f" % arit_even)


if div_odd!=0:
    arit_odd = float(sum_odd / div_odd)
    print("The arithmetic mean of the odd numbers entered is: %.2f" % arit_odd)
