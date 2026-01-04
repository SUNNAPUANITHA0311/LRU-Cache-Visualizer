# LRU Cache Visualizer

A web-based **visualizer for the Least Recently Used (LRU) Cache algorithm**, built with **HTML, CSS, and JavaScript**. This tool allows you to interactively insert, access, and evict cache items while seeing the state of the cache in real-time.

---

## 🔹 Features

- **Visual Cache Representation:** Shows items in cache with MRU (Most Recently Used) and LRU (Least Recently Used) highlights.
- **Interactive Operations:**
  - **PUT (Key, Value):** Insert or update an item in the cache.
  - **GET (Key):** Access an item, moving it to the MRU position.
- **Eviction Handling:** Automatically removes the least recently used item when the cache exceeds its capacity.
- **Log History:** Tracks all operations with timestamps.
- **Responsive UI:** Works on desktop and mobile screens.
- **Clear and Modern Design:** Uses gradients, badges, and panels for intuitive visualization.

---

## 🔹 Demo

You can see the cache state update dynamically as you perform operations.  
- **MRU** (Most Recently Used) items are marked with a cyan badge.
- **LRU** (Least Recently Used) items are marked with a red badge.

---

## 🔹 Usage

1. Open `index.html` in a browser.
2. Set the **cache capacity** using the input at the top.
3. Perform cache operations:
   - **PUT:** Enter a key and value, then click **Insert / Update**.
   - **GET:** Enter a key to access, then click **Access**.
4. Watch the cache visualization and log history update in real-time.
5. Click **Reset** to clear the cache.

---

## 🔹 Project Structure
lru-cache-visualizer/
│
└─ index.html


---

## 🔹 Technologies Used

- **HTML5**
- **CSS3** (with CSS variables and modern layout techniques)
- **JavaScript** (ES6 Classes for LRU logic)

---

## 🔹 How It Works

- The LRU cache is implemented using a **doubly-linked list** and a **Map** for O(1) access.
- **PUT Operation:** Adds or updates an item at the front (MRU). Evicts LRU if the cache is full.
- **GET Operation:** Accesses an item and moves it to the MRU position. If not found, it registers a cache miss.
- The cache visualization dynamically updates based on the internal linked list.

---

## 🔹 Screenshot

<img width="1880" height="872" alt="image" src="https://github.com/user-attachments/assets/20fae956-ab95-4940-8e80-d3c0d29e9671" />
---
## 🔹 License
This project is **MIT Licensed**. Feel free to use, modify, and share.

