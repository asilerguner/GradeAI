# GradeAI – Quick Start Guide

## 🚀 How to Run

Follow these simple steps to launch the app locally:

### 1. Open File Explorer in Project Folder

* Navigate to your project directory.
* In the address bar, type:

  ```
  cmd
  ```
* Press **Enter** to open Command Prompt in that folder.

---

### 2. Start Local Server

Run the following command:

```
python -m http.server 8000
```

---

### 3. Open in Browser

* Open **Google Chrome** (or any browser)
* Go to:

  ```
  http://localhost:8000/GradeAI.html
  ```

---

## ✅ Notes

* Make sure Python is installed and added to PATH.
* Port `8000` must be available.
* Keep the Command Prompt window open while using the app.

---

## 🛠 Troubleshooting

* **Port already in use**

  * Try a different port:

    ```
    python -m http.server 8080
    ```

    Then open:

    ```
    http://localhost:8080/GradeAI.html
    ```

* **Page not loading**

  * Ensure you're in the correct folder
  * Check file name: `GradeAI.html`

---

## 📌 That’s it!

You’re ready to use GradeAI locally 🎉
