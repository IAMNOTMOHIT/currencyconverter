# currencyconverter
Real time Currency Conversion
The Real-Time Currency Converter is a web-based tool that provides quick and accurate currency conversions using live exchange rates from a free API. It is built for speed, efficiency, and ease of use, making it a practical solution for financial and business-related calculations.

Features
 Fetches real-time exchange rates from a free API.
 Simple and lightweight UI for quick conversions.
 Java-based backend for secure API communication.
 Responsive design for both desktop & mobile.
 Optimized API usage to stay within free-tier limits.

Technologies Used
Frontend:
HTML5 – Provides structure and content.
CSS3 – Enhances UI with styling.
JavaScript (ES6) – Handles user interaction & API communication.
Backend:
Java Servlets – Manages server-side logic & API requests.
Apache Tomcat – Hosts the backend server.
API:
Free Currency Exchange API – Fetches real-time exchange rates.
Development Tools:
Eclipse IDE – Used for coding & debugging.

How It Works
User selects the currencies and enters the amount on the frontend.
A request is sent to the backend (Java Servlets).
The backend fetches real-time exchange rates from the API.
The converted amount is sent back to the frontend and displayed instantly.

📥 Installation & Setup
🔹 Prerequisites
Ensure you have the following installed:

Java Development Kit (JDK) 11+
Apache Maven 3.6+
Apache Tomcat 9+
🔹 Steps to Run Locally
1️⃣ Clone the repository:

sh
Copy
Edit
git clone https://github.com/yourusername/realtime-currency-converter.git
cd realtime-currency-converter
2️⃣ Build the project using Maven:

sh
Copy
Edit
mvn clean package
3️⃣ Deploy the WAR file to Tomcat:

sh
Copy
Edit
cp target/realtime-currency-converter.war /path-to-tomcat/webapps/
4️⃣ Start Tomcat and access the app:
Open your browser and visit:

bash
Copy
Edit
http://localhost:8080/realtime-currency-converter

Challenges & Solutions
🔹 API Rate Limits – Implemented request optimization to stay within free-tier restrictions.
🔹 Slow API Responses – Cached the last successful request to improve speed.
🔹 Responsive UI Issues – Ensured proper layouts for different screen sizes.
🔹 Error Handling – Added fallback messages in case API data is unavailable.

 Future Improvements 🚀
✅ Historical Exchange Rate Tracking – View past exchange rates.
✅ Advanced API Integration – Improve accuracy with a premium API.
✅ Multi-Language Support – Cater to a global audience.

Contributing
We welcome contributions! To contribute:

Fork the repository
Create a new feature branch (feature-new)
Commit your changes (git commit -m "Added new feature")
Push to your branch (git push origin feature-new)
Open a pull request
📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

