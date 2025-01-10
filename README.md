# first-project
#revenue 
bub = 202
tof = 118
ice = 2250
milk = 1680
dou = 1075
pan = 80
#total revenue
total = bub + tof + ice + milk + dou + pan



#printing the result
print(f"""Earned amount:
Bubblegum: ${bub}
Toffee: ${118}
Ice cream: ${ice}
Milk chocolate: ${milk}
Doughnut: ${dou}
Pancake: ${pan}

Income: ${total}.f(.1)""")

s_expenses = int(input("Staff expenses"))
o_expenses = int(input("Other expenses"))

net_income = total - s_expenses - o_expenses
print(f"""Staff expense:
 ${s_expenses}
 Other expenses:
 ${o_expenses}
 Net income: ${net_income}""")


