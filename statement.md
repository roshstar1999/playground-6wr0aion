#to find one's complement

num=5

temp=num

bit=1

while temp:

    num=num^bit #Xoring 1 with each bit once in a loop
    bit<<=1     
    temp>>= 1

    
print(num)
