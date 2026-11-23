<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

## School of Engineering and Technology

<br>

<img width="154" height="157" alt="Mody_University_logo" src="https://github.com/user-attachments/assets/11e32514-7869-4f2d-afc9-b45171b58488" />


<br>

# PYTHON PROGRAMMING LAB

### LAB RECORD

<br><br>

**Student Name:** DIVYANSHI GOEL
**Enrollment Number:** 240036

<br>

**Faculty Name:** Dr. P. K. Bishnoi

<br><br>

**Mody University of Science and Technology**
**School of Engineering and Technology**
Lakshmangarh, Rajasthan

</div>

---

<div style="page-break-after: always;"></div>

# INDEX

# INDEX

<table style="width:100%; border-collapse:collapse;">
  <tr>
    <th style="width:10%;">S. No.</th>
    <th style="width:65%;">Program</th>
    <th style="width:25%;">Link</th>
  </tr>

  <tr>
    <td>1</td>
    <td>Addition of Two Numbers</td>
    <td><a href="#program-1-addition-of-two-numbers">Program 1</a></td>
  </tr>

  <tr>
    <td>2</td>
    <td>Largest of Three Numbers</td>
    <td><a href="#program-2-largest-of-three-numbers">Program 2</a></td>
  </tr>

  <tr>
    <td>3</td>
    <td>Factorial of a Number</td>
    <td><a href="#program-3-factorial-of-a-number">Program 3</a></td>
  </tr>

  <tr>
    <td>4</td>
    <td>Prime Number Check</td>
    <td><a href="#program-4-prime-number-check">Program 4</a></td>
  </tr>

  <tr>
    <td>5</td>
    <td>Fibonacci Series</td>
    <td><a href="#program-5-fibonacci-series">Program 5</a></td>
  </tr>
  <tr>
    <td>6</td>
    <td>bubble sort</td>
    <td><a href="#program-6-bubble-sort">Program 6</a></td>
  </tr>
  <tr>
    <td>7</td>
    <td>selection sort</td>
    <td><a href="#program-7-selection-sort">Program 7</a></td>
  </tr>
  <tr>
    <td>8</td>
    <td>insertion sort</td>
    <td><a href="#program-8-insertion-sort">Program 8</a></td>
  </tr>
  <tr>
    <td>9</td>
    <td> Number is positive,negative or zero</td>
    <td><a href="#program-9-Number-is-positive,negative-or-zero">Program 9</a></td>
  </tr>
  <tr>
    <td>10</td>
    <td>Day of the week</td>
    <td><a href="#program-10-day-of-the-week">Program 10</a></td>
  </tr>
  <tr>
    <td>11</td>
    <td>Simple Calculator</td>
    <td><a href="#program-11-Simple-Caculator">Program 11</a></td>
  </tr>
  <tr>
    <td>12</td>
    <td>Undirected Graph</td>
    <td><a href="#program-12-Undirected-Graph">Program 12</a></td>
  </tr>
  <tr>
    <td>13</td>
    <td>Directed Graph</td>
    <td><a href="#program-13-Directed-Graph">Program 13</a></td>
  </tr>
  <tr>
    <td>14</td>
    <td>Undirected Weighted Graph</td>
    <td><a href="#program-14-Undirected-Weighted-Graph">Program 14</a></td>
  </tr>
  <tr>
    <td>15</td>
    <td>Directed Weighted Graph</td>
    <td><a href="#program-15-Directed-Weighted-Graph">Program 15</a></td>
  </tr>
  <tr>
    <td>16</td>
    <td>BFS</td>
    <td><a href="#program-16-BFS">Program 16</a></td>
  </tr>
  <tr>
    <td>17</td>
    <td>DFS</td>
    <td><a href="#program-17-DFS">Program 17</a></td>
  </tr>
  
  <tr>
    <td>18</td>
    <td>Dijkstra's Algorithm</td>
    <td><a href="#program-18-Dijkstra's-Algorithm">Program 18</a></td>
  </tr>
  <tr>
    <td>19</td>
    <td>Bellman-Ford Algorithm</td>
    <td><a href="#program-19-Bellman-Ford-Algorithm">Program 19</a></td>
  </tr>
  
</table>


---
<div style="page-break-after: always;"></div>

# Program 1: Addition of Two Numbers

## Aim

To write a Python program to find the sum of two numbers.

## Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

sum = a + b

print("Sum =", sum)
```

## Sample Output

```text
Enter first number: 10
Enter second number: 20
Sum = 30
```
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5bd74bc0-ddb4-4295-87d6-dc97accbae54" />



[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 2: Largest of Three Numbers

## Aim

To write a Python program to find the largest among three numbers.

## Program

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    largest = a
elif b >= a and b >= c:
    largest = b
else:
    largest = c

print("Largest number =", largest)
```

## Sample Output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76edd186-3641-4ca2-96e9-bf904450f876" />


```text
Enter first number: 10
Enter second number: 25
Enter third number: 15
Largest number = 25
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 3: Factorial of a Number

## Aim

To write a Python program to calculate the factorial of a given number.

## Program

```python
n = int(input("Enter a number: "))

fact = 1

for i in range(1, n + 1):
    fact = fact * i

print("Factorial =", fact)
```

## Sample Output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/935b32d6-b197-4885-bf3d-6b5d3fe71320" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/760e4edf-a007-4985-829a-86b0ba3c51d5" />



```text
Enter a number: 5
Factorial = 120
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 4: Prime Number Check

## Aim

To write a Python program to check whether a given number is prime or not.

## Program

```python
n = int(input("Enter a number: "))

prime = True

if n < 2:
    prime = False
else:
    for i in range(2, n):
        if n % i == 0:
            prime = False
            break

if prime:
    print(n, "is a Prime Number")
else:
    print(n, "is not a Prime Number")
```

## Sample Output

```text
Enter a number: 7
7 is a Prime Number
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 5: Fibonacci Series

## Aim

To write a Python program to generate the Fibonacci series.

## Program

```python
n = int(input("Enter number of terms: "))

a = 0
b = 1

for i in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

## Sample Output

```text
Enter number of terms: 7
0 1 1 2 3 5 8
```


[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 6: Bubble sort 

## Aim

To write a Python program to sort numbers from bubble sort.

## Program

```python
import time

start=time.time()

def bubble_sort(arr):
    n = len(arr)

    for i in range(n):
        for j in range(0, n - i - 1):
            if arr[j] > arr[j + 1]:
                arr[j], arr[j + 1] = arr[j + 1], arr[j]

    return arr


print(bubble_sort([5, 2, 8, 1, 3]))
end=time.time()
print("execution time" , end-start)
```

## Sample Output

<img width="1548" height="446" alt="image" src="https://github.com/user-attachments/assets/efd4bc1a-f107-4b20-a3ec-5d911086bfc8" />


---

<div style="page-break-after: always;"></div>

# Program 7: selection sort 

## Aim

To write a Python program to sort numbers from selection sort.

## Program

```python
import time

start=time.time()

arr = [5, 3, 8, 4, 2]

for i in range(len(arr)):
    min_index = i
    for j in range(i + 1, len(arr)):
        if arr[j] < arr[min_index]:
            min_index = j

    arr[i], arr[min_index] = arr[min_index], arr[i]

print(arr)

end=time.time()
print("execution time" , end-start)

```

## Sample Output



<img width="1702" height="546" alt="image" src="https://github.com/user-attachments/assets/50d12352-d9e4-43a8-ab4d-41d053a47b33" />
---

<div style="page-break-after: always;"></div>

# Program 8: insertion sort 

## Aim

To write a Python program to sort numbers from insertion sort.

## Program

```python
import time

start=time.time()

arr = [5, 3, 8, 4, 2]

for i in range(1, len(arr)):
    key = arr[i]
    j = i - 1

    while j >= 0 and arr[j] > key:
        arr[j + 1] = arr[j]
        j -= 1

    arr[j + 1] = key

print(arr)


end=time.time()
print("execution time" , end-start)
```

## Sample Output


<img width="1683" height="1008" alt="image" src="https://github.com/user-attachments/assets/1fa325a6-9916-4e29-9b67-3d59cb22ca95" />
<div style="page-break-after: always;"></div>

<a id="program-9-merge-sort"></a>
Program 9: Merge Sort
Aim
Write a Python program to sort an array using Merge Sort and find its execution time and memory used.
Program
```python
import time
import tracemalloc

def merge_sort(arr):

    if len(arr) <= 1:
        return arr

    mid = len(arr) // 2

    left = merge_sort(arr[:mid])
    right = merge_sort(arr[mid:])

    result = []

    i = 0
    j = 0

    while i < len(left) and j < len(right):

        if left[i] < right[j]:
            result.append(left[i])
            i = i + 1

        else:
            result.append(right[j])
            j = j + 1

    result.extend(left[i:])
    result.extend(right[j:])

    return result


arr = [50, 30, 10, 40, 20]

tracemalloc.start()

start = time.time()

arr = merge_sort(arr)

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```
Sample Output
<img width="340" height="62" alt="image" src="https://github.com/user-attachments/assets/415dafbb-38f3-415a-9898-2ddb100174f5" />

Back to Index
---
<a id="program-10-quick-sort"></a>
Program 10: Quick Sort
Aim
Write a Python program to sort an array using Quick Sort and find its execution time and memory used.
Program
```python
import time
import tracemalloc

def quick_sort(arr):

    if len(arr) <= 1:
        return arr

    pivot = arr[0]

    left = []
    right = []

    for i in range(1, len(arr)):

        if arr[i] < pivot:
            left.append(arr[i])
        else:
            right.append(arr[i])

    return quick_sort(left) + [pivot] + quick_sort(right)


arr = [50, 30, 10, 40, 20]

tracemalloc.start()

start = time.time()

arr = quick_sort(arr)

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Sorted Array:", arr)
print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```
Sample Output
<img width="299" height="50" alt="image" src="https://github.com/user-attachments/assets/315c8f0d-3984-4b8b-ab23-2f77268a8890" />
Back to Index
---
<a id="program-11-Time-and-Memory-Comparison-of-all-Sortings"></a>
Program 11: Time and Memory Comparison of all Sortings
Aim
Implement Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort in Python. Calculate the execution time and memory usage of each algorithm and compare their performance using graphs.
Program
```python
import time
import matplotlib.pyplot as plt

# Original array
arr = [50, 30, 10, 40, 20, 70, 60, 80, 90, 100]


# ---------------- BUBBLE SORT ----------------

def bubble_sort(a):

    a = a.copy()

    n = len(a)

    for i in range(n):
        for j in range(n - i - 1):

            if a[j] > a[j + 1]:

                temp = a[j]
                a[j] = a[j + 1]
                a[j + 1] = temp

    return a


# ---------------- SELECTION SORT ----------------

def selection_sort(a):

    a = a.copy()

    n = len(a)

    for i in range(n):

        small = i

        for j in range(i + 1, n):

            if a[j] < a[small]:
                small = j

        temp = a[i]
        a[i] = a[small]
        a[small] = temp

    return a


# ---------------- INSERTION SORT ----------------

def insertion_sort(a):

    a = a.copy()

    n = len(a)

    for i in range(1, n):

        key = a[i]
        j = i - 1

        while j >= 0 and a[j] > key:

            a[j + 1] = a[j]
            j = j - 1

        a[j + 1] = key

    return a


# ---------------- MERGE SORT ----------------

def merge_sort(a):

    if len(a) <= 1:
        return a

    mid = len(a) // 2

    left = merge_sort(a[:mid])
    right = merge_sort(a[mid:])

    result = []

    i = 0
    j = 0

    while i < len(left) and j < len(right):

        if left[i] < right[j]:
            result.append(left[i])
            i += 1
        else:
            result.append(right[j])
            j += 1

    result.extend(left[i:])
    result.extend(right[j:])

    return result


# ---------------- QUICK SORT ----------------

def quick_sort(a):

    if len(a) <= 1:
        return a

    pivot = a[0]

    left = []
    right = []

    for i in range(1, len(a)):

        if a[i] < pivot:
            left.append(a[i])
        else:
            right.append(a[i])

    return quick_sort(left) + [pivot] + quick_sort(right)


# ---------------- FIND EXECUTION TIME ----------------

times = []

start = time.time()
bubble_sort(arr)
times.append(time.time() - start)

start = time.time()
selection_sort(arr)
times.append(time.time() - start)

start = time.time()
insertion_sort(arr)
times.append(time.time() - start)

start = time.time()
merge_sort(arr)
times.append(time.time() - start)

start = time.time()
quick_sort(arr)
times.append(time.time() - start)


# ---------------- PRINT TIME ----------------

print("Bubble Sort Time:", times[0])
print("Selection Sort Time:", times[1])
print("Insertion Sort Time:", times[2])
print("Merge Sort Time:", times[3])
print("Quick Sort Time:", times[4])


# ---------------- GRAPH ----------------

names = [
    "Bubble Sort",
    "Selection Sort",
    "Insertion Sort",
    "Merge Sort",
    "Quick Sort"
]

plt.bar(names, times)

plt.xlabel("Sorting Algorithms")
plt.ylabel("Execution Time")

plt.title("Comparison of Sorting Algorithms")

plt.xticks(rotation=20)

plt.grid()

plt.show()

```
Sample Output
<img width="311" height="53" alt="image" src="https://github.com/user-attachments/assets/f7f8fca7-2761-4e76-9c39-664cae37f09a" />
<img width="911" height="459" alt="image" src="https://github.com/user-attachments/assets/c0889196-962d-429a-817d-57d0bef9a7b5" />
Back to Index
---
<a id="program-12-linear-search"></a>
Program 12: Linear Search
Aim
Write a Python program to search for a given element in an array using Linear Search. Also calculate its execution time and memory usage.
Program
```python
import time
import tracemalloc

arr = [10, 20, 30, 40, 50]
value = 30

tracemalloc.start()

start = time.time()

found = False

for i in range(len(arr)):
    if arr[i] == value:
        print("Element found at position:", i)
        found = True
        break

if found == False:
    print("Element not found")

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```
Sample Output
<img width="293" height="56" alt="image" src="https://github.com/user-attachments/assets/97729835-b4cd-4c75-8e4e-129e0f99c13e" />
Back to Index
---
<a id="program-13-binary-search"></a>
Program 13: Binary Search
Aim
Write a Python program to search for a given element in a sorted array using Binary Search. Also calculate its execution time and memory usage.
Program
```python
import time
import tracemalloc

arr = [10, 20, 30, 40, 50]
value = 40

tracemalloc.start()

start = time.time()

low = 0
high = len(arr) - 1
found = False

while low <= high:

    mid = (low + high) // 2

    if arr[mid] == value:
        print("Element found at position:", mid)
        found = True
        break

    elif arr[mid] < value:
        low = mid + 1

    else:
        high = mid - 1

if found == False:
    print("Element not found")

end = time.time()

current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

print("Execution Time:", end - start, "seconds")
print("Memory Used:", current, "bytes")
print("Peak Memory:", peak, "bytes")

```
Sample Output
<img width="289" height="62" alt="image" src="https://github.com/user-attachments/assets/b1d80fb8-9198-4293-9c64-0b81cebb656a" />
Back to Index
---
<a id="program-14-Time-and-Memory-Comparison-of-linear-and-binary-searching"></a>
Program 14: Time and Memory Comparison of linear and binary searching
Aim
Write a Python program to compare the execution time of Linear Search and Binary Search and represent the comparison using a graph.
Program
```python
import time
import matplotlib.pyplot as plt

# Different input sizes
sizes = [1000, 5000, 10000, 20000, 50000]

linear_times = []
binary_times = []

for n in sizes:

    arr = list(range(n))
    value = n - 1

    # ---------------- Linear Search ----------------

    start = time.perf_counter()

    for i in range(len(arr)):
        if arr[i] == value:
            break

    end = time.perf_counter()

    linear_times.append(end - start)


    # ---------------- Binary Search ----------------

    start = time.perf_counter()

    low = 0
    high = len(arr) - 1

    while low <= high:

        mid = (low + high) // 2

        if arr[mid] == value:
            break

        elif arr[mid] < value:
            low = mid + 1

        else:
            high = mid - 1

    end = time.perf_counter()

    binary_times.append(end - start)


# Print results
print("Input Size        Linear Search                      Binary Search")

for i in range(len(sizes)):
    print(
        sizes[i],
        "        ",
        linear_times[i],
        "        ",
        binary_times[i]
    )


# ---------------- GRAPH ----------------

plt.plot(
    sizes,
    linear_times,
    marker='o',
    label="Linear Search"
)

plt.plot(
    sizes,
    binary_times,
    marker='o',
    label="Binary Search"
)

plt.xlabel("Input Size (n)")
plt.ylabel("Execution Time (seconds)")

plt.title("Linear Search vs Binary Search")

plt.legend()
plt.grid()

plt.show()

```
Sample Output
<img width="408" height="87" alt="image" src="https://github.com/user-attachments/assets/46db1611-d130-415e-beac-b101988b351c" />
<img width="479" height="355" alt="image" src="https://github.com/user-attachments/assets/0a74dcb3-82bd-426f-9118-4007ab780cf5" />

Back to Index
---
<a id="program-15-Time-and-Memory-Comparison-of-different-time-complexities"></a>
Program 15: Time and Memory Comparison of different time complexities
Aim
Write a Python program to demonstrate different time complexities and calculate execution time and memory usage.
Program
```python
# ============================================================

# ------------------------------------------------------------
# 1. O(1) - Constant Time
# ------------------------------------------------------------
print("\n========== O(1) - CONSTANT TIME ==========")

a = [10, 20, 30]
print("Array:", a)
print("First element:", a[0])


# ------------------------------------------------------------
# 2. O(log n) - Logarithmic Time
# ------------------------------------------------------------
print("\n========== O(log n) - LOGARITHMIC TIME ==========")

n = 16
original_n = n

while n > 1:
    n = n // 2

print("Original n:", original_n)
print("Value after repeated division:", n)


# ------------------------------------------------------------
# 3. O(sqrt(n)) - Square Root Time
# ------------------------------------------------------------
print("\n========== O(sqrt(n)) - SQUARE ROOT TIME ==========")

n = 10
i = 1

while i * i <= n:
    i += 1

print("n =", n)
print("Number of iterations:", i - 1)


# ------------------------------------------------------------
# 4. O(n) - Linear Time
# ------------------------------------------------------------
print("\n========== O(n) - LINEAR TIME ==========")

n = 5

for i in range(n):
    print("i =", i)


# ------------------------------------------------------------
# 5. O(n log n) - Linearithmic Time
# ------------------------------------------------------------
print("\n========== O(n log n) - LINEARITHMIC TIME ==========")

n = 4

for i in range(n):
    j = i

    while j > 1:
        j = j // 2

    print("i =", i, "final j =", j)


# ------------------------------------------------------------
# 6. O(n^2) - Quadratic Time
# ------------------------------------------------------------
print("\n========== O(n^2) - QUADRATIC TIME ==========")

n = 2

for i in range(n):
    for j in range(n):
        print("(", i, ",", j, ")")


# ------------------------------------------------------------
# 7. O(n^3) - Cubic Time
# ------------------------------------------------------------
print("\n========== O(n^3) - CUBIC TIME ==========")

n = 2

for i in range(n):
    for j in range(n):
        for k in range(n):
            print("(", i, ",", j, ",", k, ")")


# ------------------------------------------------------------
# 8. O(2^n) - Exponential Time
# ------------------------------------------------------------
print("\n========== O(2^n) - EXPONENTIAL TIME ==========")

def fun_exponential(n):

    if n == 0:
        return

    print(n)

    fun_exponential(n - 1)
    fun_exponential(n - 1)


print("Output for n = 3:")
fun_exponential(3)


# ------------------------------------------------------------
# 9. O(n!) - Factorial Time
# ------------------------------------------------------------
print("\n========== O(n!) - FACTORIAL TIME ==========")

from itertools import permutations

n = 2

for p in permutations(range(n)):
    print(p)


# ------------------------------------------------------------
# 10. EXECUTION TIME
# ------------------------------------------------------------
print("\n========== EXECUTION TIME ==========")

import time

start = time.time()

# Program
for i in range(1000000):
    pass

end = time.time()

print("Execution Time:", end - start, "seconds")


# ------------------------------------------------------------
# 11. MEMORY USED
# ------------------------------------------------------------
print("\n========== MEMORY USED ==========")

import tracemalloc

tracemalloc.start()

# Program
a = [i for i in range(100000)]

current, peak = tracemalloc.get_traced_memory()

print("Current Memory:", current, "bytes")
print("Peak Memory:", peak, "bytes")

tracemalloc.stop()


# ------------------------------------------------------------
# END
# ------------------------------------------------------------
print("\n==============================================")
print("       ALL COMPLEXITIES EXECUTED SUCCESSFULLY")
print("==============================================")
# ------------------------------------------------------------
# 12. GRAPH PLOT - COMPARISON OF TIME COMPLEXITIES
# ------------------------------------------------------------

import matplotlib.pyplot as plt

# Values of n
n_values = range(1, 11)

# Different time complexities
O_1 = [1 for n in n_values]
O_log_n = [__import__('math').log2(n) for n in n_values]
O_sqrt_n = [n ** 0.5 for n in n_values]
O_n = [n for n in n_values]
O_n_log_n = [n * __import__('math').log2(n) for n in n_values]
O_n2 = [n ** 2 for n in n_values]
O_n3 = [n ** 3 for n in n_values]
O_2n = [2 ** n for n in n_values]

# Plot
plt.figure(figsize=(10, 6))

plt.plot(n_values, O_1, marker='o', label='O(1)')
plt.plot(n_values, O_log_n, marker='o', label='O(log n)')
plt.plot(n_values, O_sqrt_n, marker='o', label='O(sqrt(n))')
plt.plot(n_values, O_n, marker='o', label='O(n)')
plt.plot(n_values, O_n_log_n, marker='o', label='O(n log n)')
plt.plot(n_values, O_n2, marker='o', label='O(n^2)')
plt.plot(n_values, O_n3, marker='o', label='O(n^3)')
plt.plot(n_values, O_2n, marker='o', label='O(2^n)')

plt.xlabel("Input Size (n)")
plt.ylabel("Number of Operations / Growth")
plt.title("Comparison of Time Complexities")

plt.legend()
plt.grid(True)

plt.show()

```
Sample Output
```text
========== O(1) - CONSTANT TIME ==========
Array: [10, 20, 30]
First element: 10

========== O(log n) - LOGARITHMIC TIME ==========
Original n: 16
Value after repeated division: 1

========== O(sqrt(n)) - SQUARE ROOT TIME ==========
n = 10
Number of iterations: 3

========== O(n) - LINEAR TIME ==========
i = 0
i = 1
i = 2
i = 3
i = 4

========== O(n log n) - LINEARITHMIC TIME ==========
i = 0 final j = 0
i = 1 final j = 1
i = 2 final j = 1
i = 3 final j = 1

========== O(n^2) - QUADRATIC TIME ==========
( 0 , 0 )
( 0 , 1 )
( 1 , 0 )
( 1 , 1 )

========== O(n^3) - CUBIC TIME ==========
( 0 , 0 , 0 )
( 0 , 0 , 1 )
( 0 , 1 , 0 )
( 0 , 1 , 1 )
( 1 , 0 , 0 )
( 1 , 0 , 1 )
( 1 , 1 , 0 )
( 1 , 1 , 1 )

========== O(2^n) - EXPONENTIAL TIME ==========
Output for n = 3:
3
2
1
1
2
1
1

========== O(n!) - FACTORIAL TIME ==========
(0, 1)
(1, 0)

========== EXECUTION TIME ==========
Execution Time: 0.09830784797668457 seconds

========== MEMORY USED ==========
Current Memory: 3993016 bytes
Peak Memory: 3993048 bytes

==============================================
       ALL COMPLEXITIES EXECUTED SUCCESSFULLY
==============================================

```
<img width="926" height="449" alt="image" src="https://github.com/user-attachments/assets/cccdedfc-0dc8-4ef6-8d7d-6dadf1b48c63" />

Back to Index
---

# Program 16: Number is positive,negative or zero

## Aim

To check whether a number is positive, negative, or zero

## Program

```python
n = int(input("Enter a number: "))

if n > 0:
    print("Positive")
elif n < 0:
    print("Negative")
else:
    print("Zero")
```
```text
Enter a number: 5
Factorial = 120
```

## Sample Output

<img width="766" height="545" alt="image" src="https://github.com/user-attachments/assets/4f21acea-455b-4c58-89c7-0b05823f5592" />

[Back to Index](#index)

---


<div style="page-break-after: always;"></div>

# Program 17: day of the week

## Aim
Write a program to input a number from 1 to 7 and display the corresponding day of the week.

## Program

```python
day = int(input("Enter a number (1-7): "))

if day == 1:
    print("Monday")
elif day == 2:
    print("Tuesday")
elif day == 3:
    print("Wednesday")
elif day == 4:
    print("Thursday")
elif day == 5:
    print("Friday")
elif day == 6:
    print("Saturday")
elif day == 7:
    print("Sunday")
else:
    print("Invalid input")

```

## Sample Output
````text
Enter a number (1-7): 3
Wednesday
````
<img width="1025" height="634" alt="image" src="https://github.com/user-attachments/assets/0e7372dc-903a-4d62-9442-c2d8b6e7d239" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)


# Program 18: Simple Calculator

## Aim
To write a Python program to perform basic arithmetic operations such as addition, subtraction, multiplication, and division using conditional statements.


## Program

```python
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

op = int(input("Choose operation (1-4): "))

if op == 1:
    print("Sum =", a + b)
elif op == 2:
    print("Difference =", a - b)
elif op == 3:
    print("Product =", a * b)
elif op == 4:
    if b != 0:
        print("Division =", a / b)
    else:
        print("Cannot divide by zero")
else:
    print("Invalid operation")

```

## Sample Output
````text
Enter first number: 10
Enter second number: 5
1. Addition
2. Subtraction
3. Multiplication
4. Division
Choose operation (1-4): 1
Sum = 15.0

````
<img width="834" height="612" alt="image" src="https://github.com/user-attachments/assets/4d1e88b9-a10e-4751-bcc1-43db71992bab" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 19: Undirected Graph

## Aim
To write a Python program to implement Undirected Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)
        node2.neighbors.append(node1)

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor in node.neighbors:
                print(neighbor.data, end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)

graph.print_graph()

```

## Sample Output

<img width="162" height="111" alt="image" src="https://github.com/user-attachments/assets/aa34702e-5c2b-404b-97e9-f8b582260897" />



---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 20: Directed Graph

## Aim
To write a Python program to implement Directed Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor in node.neighbors:
                print(neighbor.data, end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)

graph.print_graph()

```

## Sample Output

<img width="145" height="107" alt="image" src="https://github.com/user-attachments/assets/8955e538-00cf-4141-a5ba-a68d962a6249" />

---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 21: Undirected Weighted Graph

## Aim
To write a Python program to implement Undirected Weighted Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor, weight in node.neighbors:
                print(neighbor.data, "(", weight, ")", end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B, 5)
graph.add_edge(A, C, 3)
graph.add_edge(B, D, 7)
graph.add_edge(C, D, 2)

graph.print_graph()

```

## Sample Output

<img width="321" height="102" alt="image" src="https://github.com/user-attachments/assets/084f900d-dc96-43ba-a56f-c05b15043644" />

---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 15: Directed Weighted Graph

## Aim
To write a Python program to implement Directed Weighted Graph.


## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))
        node2.neighbors.append((node1, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, "->", end=" ")
            for neighbor, weight in node.neighbors:
                print(neighbor.data, "(", weight, ")", end=" ")
            print()


graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")

graph.add_edge(A, B, 5)
graph.add_edge(A, C, 3)
graph.add_edge(B, D, 7)
graph.add_edge(C, D, 2)

graph.print_graph()


```

## Sample Output

<img width="311" height="107" alt="image" src="https://github.com/user-attachments/assets/c36e5f3d-5335-46ab-9813-f0a4d6f50248" />


---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 16: BFS 

## Aim
To write a Python program to implement BFS.


## Program

```python

from collections import deque

class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)
        node2.neighbors.append(node1)

    def BFS(self, start):
        visited = set()
        queue = deque([start])
        visited.add(start)

        while queue:
            node = queue.popleft()
            print(node.data, end=" ")

            for neighbor in node.neighbors:
                if neighbor not in visited:
                    visited.add(neighbor)
                    queue.append(neighbor)


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add edges
graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)
graph.add_edge(D, E)

# BFS traversal
print("BFS Traversal:")
graph.BFS(A)


```

## Sample Output

<img width="175" height="37" alt="image" src="https://github.com/user-attachments/assets/6dd4842d-8630-4b2f-9d80-64d174b1a199" />



---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 17: DFS 

## Aim
To write a Python program to implement DFS.


## Program

```python


class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2):
        node1.neighbors.append(node2)
        node2.neighbors.append(node1)

    def DFS(self, start, visited=None):
        if visited is None:
            visited = set()

        visited.add(start)
        print(start.data, end=" ")

        for neighbor in start.neighbors:
            if neighbor not in visited:
                self.DFS(neighbor, visited)


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add edges
graph.add_edge(A, B)
graph.add_edge(A, C)
graph.add_edge(B, D)
graph.add_edge(C, D)
graph.add_edge(D, E)

# DFS traversal
print("DFS Traversal:")
graph.DFS(A)


```

## Sample Output

<img width="138" height="38" alt="image" src="https://github.com/user-attachments/assets/e1683683-f23b-4260-8b74-d97abf2f42a8" />




---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 18: Dijkstra's Algorithm

## Aim
To write a Python program to implement Dijkstra's Algorithm.


## Program

```python

import heapq

class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))
        node2.neighbors.append((node1, weight))

    def Dijkstra(self, start):
        dist = {node: float('inf') for node in self.nodes}
        dist[start] = 0

        pq = [(0, start.data, start)]

        while pq:
            d, _, node = heapq.heappop(pq)

            if d > dist[node]:
                continue

            for neighbor, weight in node.neighbors:
                new_dist = d + weight

                if new_dist < dist[neighbor]:
                    dist[neighbor] = new_dist
                    heapq.heappush(
                        pq, (new_dist, neighbor.data, neighbor)
                    )

        for node in self.nodes:
            print(start.data, "to", node.data, "=", dist[node])


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add weighted edges
graph.add_edge(A, B, 4)
graph.add_edge(A, C, 1)
graph.add_edge(B, D, 2)
graph.add_edge(C, D, 5)
graph.add_edge(D, E, 3)

# Dijkstra
print("Dijkstra Shortest Paths:")
graph.Dijkstra(A)


```

## Sample Output

<img width="235" height="101" alt="image" src="https://github.com/user-attachments/assets/bbc90cdd-f69b-4368-a008-810316dc4e7c" />





---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

# Program 18: Bellman-Ford Algorithm

## Aim
To write a Python program to implement Bellman-Ford Algorithm.


## Program

```python


class Node:
    def __init__(self, data):
        self.data = data


class Graph:
    def __init__(self):
        self.nodes = []
        self.edges = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    def add_edge(self, node1, node2, weight):
        self.edges.append((node1, node2, weight))

    def BellmanFord(self, start):
        dist = {node: float('inf') for node in self.nodes}
        dist[start] = 0

        # Relax edges V-1 times
        for _ in range(len(self.nodes) - 1):
            updated = False

            for u, v, weight in self.edges:
                if dist[u] != float('inf'):
                    if dist[u] + weight < dist[v]:
                        dist[v] = dist[u] + weight
                        updated = True

            if not updated:
                break

        # Check negative-weight cycle
        for u, v, weight in self.edges:
            if dist[u] != float('inf'):
                if dist[u] + weight < dist[v]:
                    print("Negative weight cycle detected!")
                    return

        for node in self.nodes:
            print(start.data, "to", node.data, "=", dist[node])


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add weighted directed edges
graph.add_edge(A, B, 4)
graph.add_edge(A, C, 5)
graph.add_edge(B, C, -2)
graph.add_edge(B, D, 4)
graph.add_edge(C, D, 3)
graph.add_edge(D, E, 2)

# Bellman-Ford
print("Bellman-Ford Shortest Paths:")
graph.BellmanFord(A)


```

## Sample Output

<img width="260" height="100" alt="image" src="https://github.com/user-attachments/assets/bccc3f7b-1f8d-4c68-bab9-28facffa508f" />






---

<div style="page-break-after: always;"></div>

[Back to Index](#index)

#Program Prim's algorithm
##Aim Write a Python program to find shortest paths using the Bellman-Ford algorithm and detect negative-weight cycles.
Program 24

```python

import time
import tracemalloc

tracemalloc.start()

# Start timer
start_time = time.perf_counter()


class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    # Undirected weighted edge
    def add_edge(self, node1, node2, weight):
        node1.neighbors.append((node2, weight))
        node2.neighbors.append((node1, weight))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, ":", end=" ")

            for i, (neighbor, weight) in enumerate(node.neighbors):
                print(f"{neighbor.data}({weight})", end="")

                if i < len(node.neighbors) - 1:
                    print(", ", end="")

            print()

    def prim(self, source):
        visited = set()
        mst = []
        total_weight = 0

        # Start from source node
        visited.add(source)

        # Repeat until all nodes are visited
        while len(visited) < len(self.nodes):
            min_edge = None
            min_weight = float('inf')

            # Find minimum-weight edge connecting
            # a visited node to an unvisited node
            for node in visited:
                for neighbor, weight in node.neighbors:
                    if neighbor not in visited and weight < min_weight:
                        min_weight = weight
                        min_edge = (node, neighbor, weight)

            # Graph is disconnected
            if min_edge is None:
                print("Graph is disconnected; MST not possible.")
                return None

            u, v, weight = min_edge

            visited.add(v)
            mst.append((u, v, weight))
            total_weight += weight

        return mst, total_weight


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add undirected weighted edges
graph.add_edge(A, B, 4)
graph.add_edge(A, C, 2)
graph.add_edge(B, D, 5)
graph.add_edge(C, D, 1)
graph.add_edge(D, E, 3)

# Print graph
graph.print_graph()

# Run Prim's Algorithm
result = graph.prim(A)

end_time = time.perf_counter()

# Get memory usage
current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

# Print Minimum Spanning Tree
if result is not None:
    mst, total_weight = result

    print("\nMinimum Spanning Tree:")

    for u, v, weight in mst:
        print(f"{u.data} - {v.data} = {weight}")

    print("Total MST weight:", total_weight)

print("\nPerformance:")
print(f"Execution time: {(end_time - start_time) * 1000:.6f} ms")
print(f"Current memory: {current / 1024:.2f} KB")
print(f"Peak memory: {peak / 1024:.2f} KB")

```
sample output
<img width="320" height="481" alt="image" src="https://github.com/user-attachments/assets/0c8752bc-4a64-4215-bb74-73bfe89212a4" />
back to index
<a id="program-25"></a>
Program Krushal alogorithm

Aim Write a Python program to find the Minimum Spanning Tree (MST) and its total weight using Kruskal’s algorithm.
Program 25
```python

import time
import tracemalloc

tracemalloc.start()
start_time = time.perf_counter()


class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = []
        self.edges = []

    def add_node(self, data):
        node = Node(data)
        self.nodes.append(node)
        return node

    # Undirected weighted edge
    def add_edge(self, u, v, weight):
        u.neighbors.append((v, weight))
        v.neighbors.append((u, weight))
        self.edges.append((weight, u, v))

    def print_graph(self):
        for node in self.nodes:
            print(node.data, ":", end=" ")
            print(", ".join(
                f"{v.data}({w})" for v, w in node.neighbors
            ))

    def kruskal(self):
        parent = {node: node for node in self.nodes}
        rank = {node: 0 for node in self.nodes}

        def find(node):
            if parent[node] != node:
                parent[node] = find(parent[node])
            return parent[node]

        def union(u, v):
            root_u = find(u)
            root_v = find(v)

            if root_u == root_v:
                return False

            if rank[root_u] < rank[root_v]:
                parent[root_u] = root_v
            elif rank[root_u] > rank[root_v]:
                parent[root_v] = root_u
            else:
                parent[root_v] = root_u
                rank[root_u] += 1

            return True

        mst = []
        total_weight = 0

        # Sort edges by weight
        sorted_edges = sorted(self.edges, key=lambda edge: edge[0])

        for weight, u, v in sorted_edges:
            if union(u, v):
                mst.append((u, v, weight))
                total_weight += weight

            if len(mst) == len(self.nodes) - 1:
                break

        if len(mst) != len(self.nodes) - 1:
            print("Graph is disconnected; MST not possible.")
            return None

        return mst, total_weight


# Create graph
graph = Graph()

A = graph.add_node("A")
B = graph.add_node("B")
C = graph.add_node("C")
D = graph.add_node("D")
E = graph.add_node("E")

# Add undirected weighted edges
graph.add_edge(A, B, 4)
graph.add_edge(A, C, 2)
graph.add_edge(B, D, 5)
graph.add_edge(C, D, 1)
graph.add_edge(D, E, 3)

# Print graph
graph.print_graph()

# Run Kruskal's Algorithm
result = graph.kruskal()

end_time = time.perf_counter()

# Get memory usage
current, peak = tracemalloc.get_traced_memory()
tracemalloc.stop()

# Print MST
if result is not None:
    mst, total_weight = result

    print("\nMinimum Spanning Tree:")

    for u, v, weight in mst:
        print(f"{u.data} - {v.data} = {weight}")

    print("Total MST weight:", total_weight)

# Performance
print("\nPerformance:")
print(f"Execution time: {(end_time - start_time) * 1000:.6f} ms")
print(f"Current memory: {current / 1024:.2f} KB")
print(f"Peak memory: {peak / 1024:.2f} KB")

```
sample output
<img width="482" height="492" alt="image" src="https://github.com/user-attachments/assets/ba8a8c17-ee2d-4ab4-8d7f-b29c72913a89" />
back to index
<a id="program-26"></a>
Program 26
```python

INF = float('inf')

n = int(input("Enter number of vertices: "))

print("Enter the adjacency matrix (use INF for no edge):")

dist = []

for i in range(n):
    row = input().split()
    dist.append([
        INF if x.upper() == "INF" else int(x)
        for x in row
    ])

for k in range(n):
    for i in range(n):
        for j in range(n):
            dist[i][j] = min(
                dist[i][j],
                dist[i][k] + dist[k][j]
            )

print("Shortest Distance Matrix:")

for row in dist:
    print(row)
```
Sample output
<img width="856" height="142" alt="image" src="https://github.com/user-attachments/assets/d8325371-aa96-44f9-a44d-3f8fe5ab3f7a" />

back to index
<a id="program-27"></a>
Program 27
```python

def greedy_knapsack():
    n = int(input("Enter number of items: "))

    weights = []
    profits = []

    # Input weights
    print("\nEnter weights of items:")
    for i in range(n):
        w = int(input(f"Weight of item {i+1}: "))
        weights.append(w)

    # Input profits
    print("\nEnter profits of items:")
    for i in range(n):
        p = int(input(f"Profit of item {i+1}: "))
        profits.append(p)

    # Input capacity
    capacity = int(input("\nEnter knapsack capacity: "))

    # Calculate profit/weight ratio
    items = []

    for i in range(n):
        ratio = profits[i] / weights[i]
        items.append((ratio, weights[i], profits[i], i+1))

    # Sort by decreasing ratio
    items.sort(reverse=True)

    total_profit = 0
    total_weight = 0

    print("\nSelected Items:")

    for ratio, weight, profit, item_no in items:

        if total_weight + weight <= capacity:
            total_weight += weight
            total_profit += profit

            print("Item:", item_no,
                  "Weight:", weight,
                  "Profit:", profit)

    print("\nTotal Weight:", total_weight)
    print("Total Profit:", total_profit)


# Function call
greedy_knapsack()

```
Sample Output
<img width="678" height="415" alt="image" src="https://github.com/user-attachments/assets/79ffabcc-3ccd-418b-acba-6a11e293a9c5" />

back to index
<a id="program-28"></a>
Program 28
```python

def fractional_knapsack():

    n = int(input("Enter number of items: "))

    weights = []
    profits = []

    # Input weights
    print("\nEnter weights of items:")
    for i in range(n):
        w = float(input(f"Weight of item {i+1}: "))
        weights.append(w)

    # Input profits
    print("\nEnter profits of items:")
    for i in range(n):
        p = float(input(f"Profit of item {i+1}: "))
        profits.append(p)

    # Input capacity
    capacity = float(input("\nEnter knapsack capacity: "))

    # Calculate profit/weight ratio
    items = []

    for i in range(n):
        ratio = profits[i] / weights[i]
        items.append((ratio, weights[i], profits[i], i+1))

    # Sort by descending ratio
    items.sort(reverse=True)

    total_profit = 0
    total_weight = 0

    print("\nSelected Items:")

    for ratio, weight, profit, item_no in items:

        if capacity <= 0:
            break

        if capacity >= weight:

            # Take complete item
            capacity -= weight
            total_weight += weight
            total_profit += profit

            print("Item:", item_no,
                  "Fraction: 1",
                  "Profit:", profit)

        else:

            # Take fractional item
            fraction = capacity / weight

            total_profit += profit * fraction
            total_weight += capacity

            print("Item:", item_no,
                  "Fraction:", round(fraction, 2),
                  "Profit:", round(profit * fraction, 2))

            capacity = 0

    print("\nTotal Weight:", round(total_weight, 2))
    print("Total Profit:", round(total_profit, 2))


# Main Program
fractional_knapsack()

```
Sample output
<img width="444" height="436" alt="image" src="https://github.com/user-attachments/assets/8e542e99-2320-493d-804e-e7e95e1b9dab" />
back to index






