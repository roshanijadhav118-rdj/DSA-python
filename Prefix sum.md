arr = [2,4,6,8,10]
prefix sum = [2,6,12,20,30]

that is prefix[i] = prefix[i-1] + arr[i]

Skeleton code for prefix sum :-

arr = [2,4,6,8,10]
prefix = [0] * len(arr)
prefix[0] = arr[0]
for i in range (1,len(arr)):
    prefix[i] = prefix[i-1] + arr[i]
print(prefix)
