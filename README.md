# ☕ CupCode – Web Café Billing App (Jupyter Notebook Version)

**CupCode** is a responsive **web-based café billing application** created entirely inside a **Jupyter Notebook** using HTML, CSS, and JavaScript embedded within notebook cells.  
It provides a simple, browser-based interface for selecting menu items, calculating total bills, and generating **printable or downloadable receipts** — all without needing an external server or backend.

---

## 🚀 Features

✅ **Interactive Café Billing System** – Run directly inside Jupyter Notebook.  
✅ **Instant Bill Calculation** – Automatically calculates subtotal, GST (5%), and grand total.  
✅ **Printable Invoice / Download Receipt** – Uses the browser print feature to create a professional bill.  
✅ **Fully Frontend-Based** – Uses HTML, CSS, and JavaScript without any backend or database.  
✅ **Responsive Layout** – Works on desktop and mobile browsers when rendered in notebook output.

---

## 🧰 Technologies Used

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Web page structure |
| **CSS3** | Styling and responsive layout |
| **JavaScript (ES6)** | Dynamic bill generation and printing |
| **Jupyter Notebook** | Hosting and running HTML-JS app in a single file |
| **Browser Print API** | Generate a printable/downloadable receipt |

---

## 📁 Project Structure
CupCode_Jupyter/
│
├── CupCode_Billing_App.ipynb # Jupyter Notebook file with HTML, CSS & JS
├── README.md # Project documentation
└── assets/ (optional) # Any images or screenshots for documentation


---

## ⚙️ How to Run the Project

### 🧩 Prerequisites
Make sure you have:
- **Python 3.8+**
- **Jupyter Notebook or JupyterLab**
- A modern web browser (Chrome, Edge, or Firefox)

### ▶️ Steps to Run

1. Open **Anaconda Navigator** or your **terminal**.  
2. Launch **Jupyter Notebook**.  
3. Navigate to the project folder (`CupCode_Jupyter`).  
4. Open the file **`CupCode_Billing_App.ipynb`**.  
5. Run all cells (`Kernel → Restart & Run All`).  
6. The web-based billing app will render directly below the cell output area.

You’ll see a web interface with café menu items, input boxes for quantity, and buttons to:
- **💰 Calculate Bill**
- **🧾 Print / Download Receipt**

---

## 🧾 Receipt Generation

When you click **🧾 Print / Download Receipt**:
- A new browser print window opens.
- Automatically includes:
  - Café name and developer info.
  - Current date and time.
  - Itemized bill with price, quantity, and total.
  - GST (5%) and grand total.
- You can **print directly** or **choose “Save as PDF”** to download.

---

## 💡 Example Output

☕ CupCode – Café Billing App

Item Qty Price Total
Cappuccino 2 ₹120 ₹240
Cold Coffee 1 ₹150 ₹150

Subtotal: ₹390
GST (5%): ₹19.50
Grand Total: ₹409.50

Thank you for visiting CupCode Café ☕
Developed by: Khushi S Pillay


---

## 🎯 Learning Objectives

This project demonstrates:
- Embedding web technologies (HTML, CSS, JS) inside Jupyter cells.  
- Dynamic front-end computation using pure JavaScript.  
- Using browser APIs for printing/downloading receipts.  
- Responsive design concepts applied within notebook rendering.  
- Integration of frontend logic within Python data science tools (Jupyter).

---

## 🧠 Future Enhancements

🔹 Add customer name & bill number fields.  
🔹 Introduce discounts or coupon code support.  
🔹 Connect to backend (Node.js / Flask / PHP) with database.  
🔹 Include UPI/QR-based payment system.  
🔹 Export billing data to CSV or Excel format automatically.

---

## 👩‍💻 Developer Information

**Developer:** Khushi S Pillay  
🎓 MCA Student – JD College of Engineering and Management, Nagpur  
💻 Project: *CupCode – Web Café Billing App (Notebook Version)*  
🧠 Skills: HTML | CSS | JavaScript | Python | Jupyter | MySQL  

---

## 📜 License

This project is **open-source** and free to use for educational and learning purposes.  
Feel free to modify, extend, or integrate it into your own café billing solutions.

---

## 💬 Acknowledgment

Special thanks to all mentors, teachers, and peers who supported the development of this mini-project.  
This notebook demonstrates how frontend web applications can be integrated and run interactively in data science environments.

---

**☕ CupCode – Brewed with Code and Creativity!**
