# 🚀 Merge Sort Algorithm

A complete implementation and explanation of the **Merge Sort** algorithm using Python.

---

## 📌 Overview

Merge Sort is a **divide-and-conquer** sorting algorithm that:

* Splits the array into halves recursively
* Sorts each half
* Merges them back in sorted order

✔ Stable
✔ Predictable performance
✔ Time Complexity: **O(n log n)**

---

## 🧠 How It Works

1. Divide the array into two halves
2. Recursively sort both halves
3. Merge the sorted halves

---

## 🌳 Example

Input:

```
[38, 27, 43, 3, 9, 82, 10]
```

Output:

```
[3, 9, 10, 27, 38, 43, 82]
```
---

## 📊 Complexity Analysis

| Case    | Time Complexity |
| ------- | --------------- |
| Best    | O(n log n)      |
| Average | O(n log n)      |
| Worst   | O(n log n)      |

**Space Complexity:** O(n)

---

## ⚖️ Advantages

* Efficient for large datasets
* Stable sorting algorithm
* Consistent performance

---

## ❌ Disadvantages

* Requires extra memory
* Slower than Quick Sort in practice

---

## 🧪 Example Run

```
Input:  [5, 2, 4, 1]
Output: [1, 2, 4, 5]
```

---

## Merge Sort Visualization(Tree Diagram)
Input: [38, 27, 43, 3, 9, 82, 10]
* Splitting Phase(Divide)
                    [38,27,43,3,9,82,10]
                   /                     \
        [38,27,43]                      [3,9,82,10]
         /      \                      /           \
     [38]   [27,43]              [3,9]         [82,10]
             /    \               /  \           /   \
          [27]  [43]          [3]  [9]       [82]  [10]

At the bottom, every element is now individually sorted

* Merging Phase(Conquer)
Now we merge step by step:
[27] + [43] → [27,43]
[38] + [27,43] → [27,38,43]

[3] + [9] → [3,9]
[82] + [10] → [10,82]
[3,9] + [10,82] → [3,9,10,82]

Final:
[27,38,43] + [3,9,10,82]
→ [3,9,10,27,38,43,82]

---

## 📚 Applications

* Sorting large datasets
* External sorting
* Linked list sorting
* Counting inversions

---

## 🏁 Conclusion

Merge Sort is a reliable and efficient sorting algorithm with guaranteed **O(n log n)** performance, making it a great choice for stable and large-scale sorting tasks.

---

