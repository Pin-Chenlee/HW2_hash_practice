# HW2_hash_practice
path =r'C:\Users\User\Documents\hw2_data.txt'
with open('hw2_data.txt','r') as f:
    lines = f.readlines()
    data = {}
    for line in lines:
        data[line]=0
    for line in lines:
            data[line] = data[line]+1
for i in data:
    print(i,data[i])
