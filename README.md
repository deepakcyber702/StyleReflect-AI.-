# StyleReflect-AI.-
AI-based smart fashion mirror
# StyleReflect AI 👗🤖

StyleReflect AI is an AI-powered smart fashion mirror application that analyzes
face shape and skin tone to recommend outfits, accessories, and styles in real time.

## 🚀 Features
- Face detection
- Skin tone analysis
- Face shape analysis
- Outfit & accessory recommendations
- Android TV / Display mode
- Offline AI support
- Shop subscription model

## 🛠 Tech Stack
- Frontend: React Native
- Backend: Node.js (Express)
- AI Engine: Python (OpenCV, PIL)
- Database & Storage: Firebase
- Payments: Razorpay (UPI)

## 📁 Project Structure
StyleReflectApp/
│
├── App.js
├── package.json
└── src/
    ├── navigation/
    │   └── AppNavigator.js
    └── screens/
        ├── HomeScreen.js
        ├── CategoryScreen.js
        ├── PhotoUploadScreen.js
        ├── ProcessingScreen.js
        ├── ResultScreen.js

ai-engine/
├── face_detection.py
├── skin_tone.py
├── face_shape.py
├── rules_engine.py
├── image_styler.py
└── main.py


backend/
├── routes/
│   ├── upload.js
│   ├── analyze.js
│   └── result.js
└── server.jsai-engine/assets/
├── shirts/
│   ├── black_shirt.png
│   ├── white_shirt.png
├── goggles/
│   └── black_goggles.png
├── beard/
│   └── medium_beard.pngMobile App
   ↓ (image upload)
Node Backend
   ↓ (call python)
Python AI Engine
   ↓ (JSON + image)
Node Backend
   ↓
Mobile Appadmin-panel/
├── dashboard
├── styles
├── users
├── payments