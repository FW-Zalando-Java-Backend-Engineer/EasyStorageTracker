# 🚚 **EasyStorageTracker – Java Generics & GitHub Practice**

Welcome to the **EasyStorageTracker** assignment! You're about to build a mini Java system to simulate a smart storage manager that can hold different types of items — think of an Amazon-like warehouse but way smaller and way cooler. 🧺📦🧃

This project is perfect for **students new to Generics**, Java development, and GitHub collaboration.

---

## 🧰 Real-World Theme:
You’ve been hired by a startup building a smart inventory system. They need a way to store and retrieve items like books, gadgets, or snacks — safely and with reusable, type-safe code. That’s where your **Java Generics skills** come in!

---

## ✅ Learning Goals
By completing this project, you’ll practice:
- 🧪 **Generic classes** (e.g., `StorageUnit<T>`)
- 🧰 **Bounded types**
- 🔄 **Generic methods**
- 🧭 **Wildcards in collections**
- 💻 **Basic GitHub usage**
- 📁 **Modular Java structure**

---

## 📦 Assignment Requirements

### 🔹 Task 1: GitHub Setup (5 points)
- Create a **public GitHub repository** named: `EasyStorageTracker-YourName`.
- Add a `README.md` with a 2–3 sentence summary of your app.
- Push your final project code and any updates.

### 🔹 Task 2: Create a Generic Storage Class (10 points)
- Create a class called `StorageUnit<T>` that:
  - Can store a single item (`addItem`)
  - Can return that item (`getItem`)
- Make it reusable for different types of items (e.g., Book, Device, Snack).

### 🔹 Task 3: Build a Small Test App (10 points)
- Create a few item classes like `Book`, `Device`, `Snack`.
- In your `main()` method, demonstrate:
  - Creating `StorageUnit<Book>`, `StorageUnit<Device>` etc.
  - Adding and retrieving the items.

### 🔹 Task 4: Use a Generic Method (5 points)
- Write a static generic method like `<T> void displayItem(T item)` to print any item info.
- Use this in your test code.

### 🔹 Task 5: Add a Wildcard Method (5 points)
- Write a method that accepts `List<? extends Object>` and prints all stored items.

### 🔹 Bonus (Optional): Type Boundaries (2 bonus points)
- Create a bounded type like `<T extends Perishable>` to represent only perishable items (e.g., Milk, Cheese).

---

## 🗂️ Suggested File Structure
```
EasyStorageTracker/
├── src/
│   ├── model/
│   │   ├── Book.java
│   │   ├── Device.java
│   │   ├── Snack.java
│   ├── storage/
│   │   ├── StorageUnit.java
│   │   └── StorageUtils.java
│   └── main/
│       └── TrackerDemo.java
├── README.md
```

---

## 📥 Submission Guidelines
- Upload your project to GitHub under the specified repo name.
- Submit your **repository link** via your learning platform or email.

---

## 📚 Optional Reading
- [Java Generics Guide – Oracle](https://docs.oracle.com/javase/tutorial/java/generics/)
- [GitHub Getting Started](https://docs.github.com/en/get-started/quickstart)

---

Would you like this as a **downloadable README.md file** or a **starter GitHub repo template**? I can generate either one for you next!
