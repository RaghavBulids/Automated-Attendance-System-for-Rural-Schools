# 🎓 Automated Attendance System for Rural Schools

## 📌 Project Overview
An offline, lightweight QR-based Attendance System designed specially for rural schools. 
Teachers scan unique student QR codes within a set timer (e.g., 15 minutes). Students not scanned within the time limit are automatically marked absent.

Attendance data is stored locally, can be exported as a CSV file, and is visualized with clean charts for immediate insights. The application is highly optimized for low-end devices and requires absolutely **no internet connection** to function.

---

## 🛠️ Testing the Project
You can test the system's scanning functionality using the demo dataset by following these steps:

1. **Visit the Generator**: Open [The QR Code Generator](https://www.the-qrcode-generator.com/) in your browser.
2. **Select Text Input**: Choose the **Plain Text** option on the website.
3. **Get Demo ID**: Copy any Student **ID** from the [Demo Student Data Catalog](#-demo-student-data-catalog) section below (e.g., `9A001` or `10B003`).
4. **Generate Code**: Paste the ID into the text box to generate the QR code.
5. **Scan & Verify**: Use your device's camera through this application to scan the generated code and verify the attendance log.

---

## 🚀 Features
* **📷 QR Code Attendance** – Lightning-fast scanning matching unique student IDs.
* **⏳ Custom Timer** – Configurable countdown timer that auto-marks unscanned students absent on expiry.
* **📊 Charts & Logs** – Dynamic charts showcasing daily attendance trends and visual metrics.
* **📱 Offline Friendly** – Zero network requests required; tailored specifically for low-end hardware.
* **💾 Local Storage** – Secure, persistent client-side data management using JSON and quick CSV export capability.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Libraries:** jsQR (QR code scanning engine), Chart.js (Data visualization dashboard)
* **Data Handling:** JSON (Local structure), CSV (Export formatting)

---

## 📚 Demo Student Data Catalog

### 🏫 Class 9

#### Section A


| ID | Name |
| :--- | :--- |
| 9A001 | Ramesh Kumar |
| 9A002 | Sita Devi |
| 9A003 | Amit Sharma |
| 9A004 | Priya Singh |
| 9A005 | Vikash Yadav |

#### Section B


| ID | Name |
| :--- | :--- |
| 9B001 | Sunita Kumari |
| 9B002 | Anil Verma |
| 9B003 | Sonal Patel |
| 9B004 | Raghav UB |
| 9B005 | Meera Jain |

#### Section C


| ID | Name |
| :--- | :--- |
| 9C001 | Rohit Gupta |
| 9C002 | Kavya Reddy |
| 9C003 | Arjun Singh |
| 9C004 | Pooja Sharma |
| 9C005 | Deepak Kumar |

### 🏫 Class 10

#### Section A


| ID | Name |
| :--- | :--- |
| 10A001 | Rajesh Patel |
| 10A002 | Sneha Agarwal |
| 10A003 | Manoj Kumar |
| 10A004 | Ritu Singh |
| 10A005 | Suresh Yadav |

#### Section B


| ID | Name |
| :--- | :--- |
| 10B001 | Anjali Sharma |
| 10B002 | Karan Verma |
| 10B003 | Nisha Gupta |
| 10B004 | Rahul Jain |
| 10B005 | Divya Reddy |

#### Section C


| ID | Name |
| :--- | :--- |
| 10C001 | Ashok Singh |
| 10C002 | Geeta Kumari |
| 10C003 | Vinod Sharma |
| 10C004 | Sunita Patel |
| 10C005 | Mukesh Kumar |

---

## 📝 Future Improvements
* ☁️ Decentralised Cloud/Backend hybrid integration for periodic syncing.
* 📲 Cross-platform Mobile App wrappers (Android/iOS) for field deployment.
* 🔗 Native Google Sheets & Microsoft Excel API sync layers.
