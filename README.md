stocks = {

"ААРЬ: 180,

"TSLA: 250,

"GOOG": 140

total = 0

n=int(input("Enter number of stocks: "))

for i in range(n):

name = input("Enter stock name: ").upper()

qty int(input("Enter quantity: ))

If name in stocks:

value = stocks[name] qty

total value

else:

print("Stock not available")

print("Total Investment Value=", total)

#Save to file

file open("portfolio.txt", "w")

file.write("Total Investment Value = " + str(total))

file.close()
