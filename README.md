# 🫀 CardioVerse: AR ECG Training Application

[![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)](https://www.android.com/)
[![Engine](https://img.shields.io/badge/Engine-Unity-black?logo=unity)](https://unity.com/)
[![Tech](https://img.shields.io/badge/AR-ARCore-blue?logo=google-ar)](https://developers.google.com/ar)
[![Status](https://img.shields.io/badge/Release-v1.0-blue)]()

**CardioVerse** is an interactive educational mobile application designed to simplify the learning of heart physiology and Electrocardiogram (ECG) training through Augmented Reality (AR). By using a physical target marker, users can visualize 3D anatomical models to master lead placements and cardiac structures.

---

## 📥 Download & Install

**[📲 Download CardioVerse APK (v1.0)](PASTE_YOUR_APK_DOWNLOAD_LINK_HERE)**

> **Note:** Since this app is not on the Play Store, you may need to "Allow apps from unknown sources" in your Android settings to install it.

---

## ✨ Key Features

### 1. Augmented Reality (AR) Training Mode
The core feature of CardioVerse is the ability to project 3D models onto the real world using the device camera.
* **Chest Leads AR:** Visualizes a 3D heart model within the rib cage.
    * Shows precise placements for leads **V1 - V6**.
    * **Interactive Toggle:** Users can **"Hide Ribs"** to remove the skeletal view and see the heart clearly, or "Show Ribs" to understand anatomical landmarks.
* **Limb Leads AR:** Displays a full-body 3D model.
    * Demonstrates limb lead placements (**RA, LA, RL, LL**) and their connection to the heart.

### 2. Comprehensive Learning Modules
* **Physiology of the Heart:** Detailed breakdown of cardiac anatomy.
* **ECG Explorer:** Interactive guide to reading ECG waves.
* **ECG and Cardiac Cycle:** Visualizing the relationship between electrical activity and heartbeats.
* **Flashcards:** Built-in revision tool to test knowledge retention.

---

## 🔧 Technical Architecture

CardioVerse leverages industry-standard AR tools to ensure stable tracking and high-fidelity rendering.

* **Game Engine:** **Unity** (Scene management, UI logic, and 3D rendering).
* **AR SDK:** **Google ARCore** (Motion tracking and environmental understanding).
* **Language:** **C#**.
* **Interaction:** Raycasting for touch detection on specific 3D leads (V1-V6).
* **Pattern Recognition:** Vuforia/ARCore Image Target technology to anchor 3D content to the physical marker.

---

## 🚀 How to Use the AR Features

To use the AR mode, you must have the **Special AR Marker**.

### Step 1: Get the Marker
The app requires a specific image to recognize where to place the 3D model.
1.  **Download/View the Marker:** [**Click here to view the AR Marker**](./path/to/your/special-image.jpg](https://github.com/nabilashahirah/CardioVerseAR/blob/main/Special%20Image%20(MARKER).jpg) *(Replace this with your image link)*
2.  You can print this image out **OR** open it on a second screen (laptop/tablet).

### Step 2: Launch AR Mode
1.  Open **CardioVerse** and tap **"ECG Training: AR Mode"**.
2.  The app defaults to **Chest Lead AR**. Point your camera at the marker.
3.  Ensure the room is well-lit and the image is flat.

### Step 3: Interaction
* **Switch Views:** Tap the **"Limb Leads AR"** button to switch to the full-body view.
* **Learn:** Tap on any specific lead (e.g., V1, RA) to read its description.

---

## 🛠️ Troubleshooting

If the 3D model does not appear or behaves incorrectly:
* **Lighting:** Ensure the area is bright. Avoid glare on the marker image.
* **Distance:** Move your camera slightly closer or further from the marker.
* **Reset:** If buttons become unresponsive, restart the application.

---

## 👤 Author

Developed by **Nur Nabila Shahirah**.
*Final Year Project / Independent Development*
