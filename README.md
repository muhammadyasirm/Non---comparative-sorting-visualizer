# 🔢 Non-Comparative Sorting Visualizer

A **web-based interactive visualizer** that helps students understand **non-comparative sorting algorithms** step by step using **animations, counters, and auxiliary structures**.

This project is specially designed for **learning and teaching Data Structures & Algorithms (DSA)** in a **clear and visual way**.

---

## 🚀 Features

* 📊 **Visual bar representation** of array elements
* 🎯 Step-by-step animation of sorting process
* 🔁 Supports **Non-Comparative Sorting Algorithms**:

  * Counting Sort
  * Radix Sort
  * Bucket Sort
* 📈 Live **operation counters**:

  * Reads
  * Writes
  * Steps
* 🧠 Shows **auxiliary arrays** (Counting array, Position array, Buckets)
* 🔍 Highlights current element being processed
* 📝 Detailed **logs** for every step
* ♻️ Reset and restart anytime
* 📱 Responsive UI (works on mobile & desktop)

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling & animations
* **JavaScript (Vanilla)** – Logic & visualization

> ❌ No frameworks used (Pure JavaScript project)

---

## 📌 How to Use

1. Open the `index.html` file in any modern browser
2. Enter numbers separated by commas

   ```
   34, 12, 67, 23, 9
   ```
3. Click **Set Array**
4. Choose a sorting algorithm
5. Click **Start Sorting**
6. Watch the algorithm work step by step 🎉

---

## 🧮 Algorithms Explained

### 1️⃣ Counting Sort

* Uses a **counting array** to count occurrences
* Builds a **position array** to place elements
* Best for **small range integers**

**Time Complexity:** O(n + k)

---

### 2️⃣ Radix Sort

* Sorts numbers **digit by digit** (Units → Tens → Hundreds)
* Uses **buckets (0–9)** for each digit
* Very useful for large numbers

**Time Complexity:** O(d × (n + k))

---

### 3️⃣ Bucket Sort

* Distributes elements into multiple buckets
* Sorts each bucket individually
* Best for **uniformly distributed data**

**Time Complexity:** Average O(n)

---

## 📊 Visual Elements

* 🔵 **Blue Bars** → Unsorted elements
* 🟡 **Yellow Bar** → Currently processing
* 🟢 **Green Bars** → Sorted array
* 📦 Boxes → Auxiliary arrays / buckets

---

## 🎓 Educational Purpose

This project is perfect for:

* DSA students
* Beginners learning sorting algorithms
* Teachers explaining non-comparative sorting
* Visual learners

---

## 📂 Project Structure

```
index.html   → Complete project (HTML + CSS + JS)
README.md    → Project documentation
```

---

## 🔮 Future Improvements

* Add speed control slider
* Add more algorithms (e.g. Pigeonhole Sort)
* Dark mode
* Export steps as PDF

---

## 👨‍💻 Author

**Muhammad Yasir Mangrio**

> If you find this project helpful, ⭐ star it and share with others!

---

## 📜 License

This project is open-source and free to use for **learning and educational purposes**.
