n = int(input())
swifts = [int(i) for i in input().split()]
semaphores = [int(i) for i in input().split()]

swiftsSum = 0
semaphoresSum = 0
K = 0
day = 0

for i in range(n):
    day += 1
    swiftsSum += swifts[i]
    semaphoresSum += semaphores[i]

    if swiftsSum == semaphoresSum:
        K = day

print(K)
