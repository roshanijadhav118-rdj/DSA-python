•••••••Flow of sliding window concept:-

WINDOW SIZE = k

Start
  ↓
Create first window
  ↓
Calculate its state
  ↓
Move right
  ↓
ADD new element
  ↓
REMOVE old element
  ↓
Calculate/update answer
  ↓
Repeat


••••••Skeleton code for sliding window:-

window = sum(nums[:k])
answer = window

for right in range(k, len(nums)):
    window += nums[right]
    window -= nums[right - k]

    answer = max(answer, window)
