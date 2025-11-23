📱 Task 4: Make a Website Mobile-Friendly Using CSS Media Queries

This project focuses on converting an existing desktop-only webpage into a fully responsive, mobile-friendly layout using **CSS media queries**.

---

## ✅ **Objective**

Make the webpage look good on devices with smaller screens (phones/tablets) by applying responsive design techniques.

---

## 🛠️ **Tools Used**

* **HTML5**
* **CSS3 (Media Queries)**
* **VS Code**
* **Chrome DevTools (Device Toolbar)**

---

## 📂 **Project Structure**

```
project-folder/
│── index.html
│── style.css
└── README.md
```

---

## 📋 **Features Implemented**

✔ Responsive layout using `@media (max-width: 768px)`
✔ Navigation menu stacks vertically on mobile
✔ Images scale properly using `max-width: 100%`
✔ Columns change to a single-column layout
✔ Font sizes adjusted for smaller screens
✔ Overflow and horizontal scroll issues fixed

---

## 💻 **How to Run This Project**

1. Download or clone the project.
2. Open the project folder in **VS Code**.
3. Open **index.html** in your browser.
4. Use **Chrome DevTools → Toggle Device Toolbar** to test mobile view:

   * Press **Ctrl + Shift + I**
   * Press **Ctrl + Shift + M**

---

## 📱 **Responsive Design Breakdown**

### **Desktop View**

* Layout displayed in multiple columns
* Navigation displayed horizontally
* Images displayed at full resolution

### **Mobile View (max-width: 768px)**

* Navigation becomes vertical
* Columns stack into one
* Images adjust to container width
* Text and margins resize for readability


## 🧪 **Testing Steps**

1. Open Chrome → Right click → **Inspect**
2. Enable **Device Toolbar**
3. Test using:

   * iPhone 12
   * Pixel 7
   * iPad view
4. Fix any layout overflow or misalignment

---

## 📌 **Expected Output**

* The website should adapt smoothly to different screen sizes.
* No horizontal scrolling.
* Navigation and content readable on mobile.

---

## 🎯 **Learning Outcome**

By completing this task, you learn:

* How to apply media queries
* How to design responsive layouts
* Mobile-first design thinking
* Debugging mobile layout issues in DevTools
