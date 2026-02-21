 Sucreapp - Logistics Hub (Scanner Edition)

Sucreapp is a lightweight, web-based logistics management tool designed for fast package logging using barcode scanners. It integrates directly with Google Sheets for real-time data storage and features automated PDF reporting.

Features
* **Barcode Scanner Optimized:** Auto-submits logs when a barcode is scanned.
* **Real-time Logging:** Connects to a Google Apps Script backend to store data in Google Sheets.
* **Search & Filter:** Quickly find packages by date or Tracking ID.
* **PDF Export:** Generate daily reports instantly using `jsPDF`.
* **Audio Feedback:** Success sounds to confirm scans in busy environments.

 Setup & Installation
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/oluakinG/Sucreapp.git](https://github.com/oluakinG/Sucreapp.git)
    ```
2.  **Backend Configuration:**
    * Create a Google Sheet.
    * Deploy a Google Apps Script as a Web App.
    * Replace the `APP_URL` constant in `index.html` with your deployment URL.
3.  **Deployment:**
    * Go to **Settings > Pages** in this repository.
    * Set the source to the `main` branch.
    * Your app will be live at `https://oluakinG.github.io/Sucreapp/`.

## 📂 Project Structure
* `index.html`: The core application (UI, Logic, and Styles).
* `.github/workflows/`: Contains CI/CD configurations for Jekyll/GitHub Pages.

## 📜 License
MIT License - Feel free to use and modify for your logistics needs.
