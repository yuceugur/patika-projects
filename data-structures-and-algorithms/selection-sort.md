# PROJECT 1 -- SELECTION SORT PROJECT

## INSERTION SORT:
## List: [22,27,16,2,18,6]
### Step 1: 
Check first 2 elements, 22<27, so continue.
### Step 2: 
1. Check  second 2 elements, 27>16, then replace them.
2. New list: [22,16,27,2,18,6], 22>16, then replace them.
3. New list: [16,22,27,2,18,6]
### Step 3:
Check other 2 elements, 27>2, then replace them.
1. New list: [16,22,2,27,18,6], 22>2, then replace them.
2. New list: [16,2,22,27,18,6] 16>2, then replace them.
3. New list: [2,16,22,27,18,6]
### Step 4:
Check other 2 elements, 27>18, then replace them.
1. New list: [2,16,22,18,27,6], 22>18, then replace them.
2. New list: [2,16,18,22,27,6] 16<18, so continue.
### Step 5: 
Check other last 2 elements, 27>6, then replace them.
1. New list: [2,16,18,22,6,27], 22>6, then replace them.
2. New list: [2,16,18,6,22,27], 18>6, then replace them.
3. New list: [2,16,6,18,22,27], 16>6, then replace them.
4. New list: [2,6,16,18,22,27], 2<6, OUR LIST IS SORTED.

-------------------------------------------
Big-O = O(N)

-------------------------------------------
1-Average Case

-------------------------------------------

## SELECTION SORT:
## List: [7,3,5,8,2,9,4,15,6]
### Step 1: 
Find the minimum element of list and replace it with the element which is at index 0. So,

New list: [2,|3,5,8,7,9,4,15,6]
### Step 2:
List is ordered until |, so find the minimum element after | and replace it with the index 1. So,

New list: [2,3,|5,8,7,9,4,15,6]
### Step 3:
List iss ordered until |, so find the minimum element after | and replace it with the index 2. So,

New List: [2,3,5|,8,7,9,4,15,6]
### Step 4:
List iss ordered until |, so find the minimum element after | and replace it with the index 3. So,

New List: [2,3,5,6,|7,9,4,15,8]


First 4 element is ordered and 4th step is completed.

