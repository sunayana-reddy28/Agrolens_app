# 🌱 **AgroLens - Smart Agriculture App**

## 🚀 **Getting Started**

### 🛠️ **Step-by-Step Instructions**

1. 📥 **Download & Extract the Project**

   - Download the ZIP file from this GitHub repository.
   - Extract it to your preferred location (e.g., `C:\Users\YourName\Projects\AgroLens`).

2. 🖥️ **Open Command Prompt**

   - Press **Windows + R**, type `cmd`, and hit **Enter**.

3. 📂 **Navigate to the Project Folder**

   - Run the following command (adjust the path if needed):
     ```bash
     cd C:\Users\YourName\Projects\AgroLens\AgroLens
     ```

4. 🚀 **Start the React Native App**

   - Run this command in the project root folder:
     ```bash
     npx expo start
     ```
   - This will open an Expo DevTools window in your browser.
   - Use **Expo Go** on your phone to scan the QR code and launch the app.

5. 🌾 **Run the Crop Recommendation Model**

   - Open a new command prompt window.
   - Navigate to the `crop_recommendation_model` folder:
     ```bash
     cd C:\Users\YourName\Projects\AgroLens\AgroLens\flask_server\crop_recommendation_model
     ```
   - Run the server:
     ```bash
     python app.py
     ```

6. 🍃 **Run the Leaf Disease Detection Model**

   - Open another command prompt window.
   - Navigate to the `leaf_disease_model` folder:
     ```bash
     cd C:\Users\YourName\Projects\AgroLens\AgroLens\flask_server\leaf_disease_model
     ```
   - Run the server:
     ```bash
     python app.py
     ```

7. 📱 **Test the App**

   - Download **Expo Go** App on your phone.
   - Open **Expo** **Go** on your phone.
   - Scan the QR code displayed after running `npx expo start`.
   - Input soil and weather data for crop recommendations.
   - Upload a leaf image for disease detection.

---

## ⚠️ **Important Notes**

- 🔄 **Simultaneous Server Execution**: Both servers must be running simultaneously for predictions to work.
- 🌐 **Network Connection**: Ensure your phone and PC are connected to the same Wi-Fi network.
- ⚙️ **Dependencies**: If running for the first time, install necessary dependencies:
  ```bash
  npm install
  pip install -r requirements.txt
  ```
- ⚡ **Live Server Requirement**: The app works only when both servers are live.

---

🌾 **Happy Farming!** 🌿
