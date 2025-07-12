n = int(input())
day_shifts = list(map(int, input().split()))
night_shifts = list(map(int, input().split()))
x = int(input())


day_shifts.sort()
night_shifts.sort(reverse=True)

total_overtime = 0

for day, night in zip(day_shifts, night_shifts):
    total_time = day + night
    if total_time > x:
        total_overtime += total_time - x


print(total_overtime * 100)
