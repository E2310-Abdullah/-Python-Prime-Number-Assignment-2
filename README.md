# Python-Prime-Number-Assignment-2
Python


n = int(input("Enter the limit number:"))
prime = []
for num in range(2, n+1):
    status = True
    for i in range(2, num):
        if num % i == 0:
            status = False
    if status:
        prime.append(num)
print(prime)
