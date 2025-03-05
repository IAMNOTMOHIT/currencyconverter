# 💰 Real-Time Currency Converter

The **Real-Time Currency Converter** is a web-based tool that provides quick and accurate currency conversions using **live exchange rates** from a free API. It is built for **speed, efficiency, and ease of use**, making it a practical solution for financial and business-related calculations.

---

## 🚀 Features

✔️ Fetches **real-time exchange rates** from a free API.  
✔️ Simple and **lightweight UI** for quick conversions.  
✔️ **Java-based backend** for secure API communication.  
✔️ **Responsive design** for both desktop & mobile.  
✔️ **Optimized API usage** to stay within free-tier limits.  

---

## 🛠️ Technologies Used

### **Frontend:**
- **HTML5** – Provides structure and content.
- **CSS3** – Enhances UI with styling.
- **JavaScript (ES6)** – Handles user interaction & API communication.

### **Backend:**
- **Java Servlets** – Manages server-side logic & API requests.
- **Apache Tomcat** – Hosts the backend server.

### **API:**
- **Free Currency Exchange API** – Fetches real-time exchange rates.

### **Development Tools:**
- **Eclipse IDE** – Used for coding & debugging.

---

## ⚙️ How It Works

1️⃣ User selects the **currencies** and enters the **amount** on the frontend.  
2️⃣ A request is sent to the backend (**Java Servlets**).  
3️⃣ The backend fetches **real-time exchange rates** from the API.  
4️⃣ The **converted amount** is sent back to the frontend and displayed **instantly**.  

---

## 📥 Installation & Setup

### **🔹 Prerequisites**
Ensure you have the following installed:

- **Java Development Kit (JDK) 11+**
- **Apache Maven 3.6+**
- **Apache Tomcat 9+**

---

### **🔹 Steps to Run Locally**

1️⃣ **Clone the repository:**
```sh
git clone https://github.com/yourusername/realtime-currency-converter.git
cd realtime-currency-converter

mvn clean package

cp target/realtime-currency-converter.war /path-to-tomcat/webapps/

http://localhost:8080/realtime-currency-converter
