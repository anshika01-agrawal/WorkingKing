
## ROLE
You are a **senior React Native mobile application developer and UI/UX engineer**.
Your task is to build a **complete frontend-only React Native app** using **Expo**, strictly following the **provided UI reference images**.

The app should look **visually identical (same-to-same)** to the reference designs in layout, spacing, color usage, card styles, button shapes, and navigation behavior.

---

## 📸 UI REFERENCES (IMPORTANT)
Use the following images as **primary design reference**:

1. **Home Dashboard Screen**
   - Occupant card with purple header
   - "PAY RENT" pill button
   - Bills section (Electricity, Other Bills)
   - Services grid
   - Bottom Tab Navigation

2. **Add Complaint Bottom Sheet**
   - Modal-style bottom sheet
   - Input field
   - Category cards
   - Highlighted selected category
   - Submit button

3. **Payment / Wallet Screens**
   - Total rent display
   - Debit / History toggle
   - Bill selection list
   - Pay Now CTA

👉 These images are attached in the repository and must be treated as the **single source of truth** for UI design.

---

## 🎯 OBJECTIVE
Create a **fully navigable React Native frontend** with:
- Pixel-consistent UI
- Reusable components
- Clean folder structure
- Proper navigation between screens
- Ready for backend integration later

⚠️ Do NOT add backend logic, authentication, or APIs.
⚠️ Focus ONLY on frontend UI + navigation.

---

## 🧱 TECH STACK (MANDATORY)
- React Native (Expo)
- JavaScript (ES6+)
- React Navigation
  - Native Stack Navigator
  - Bottom Tab Navigator
- react-native-vector-icons
- StyleSheet API (no Tailwind)
- SafeAreaView + StatusBar

---

## 📁 REQUIRED PROJECT STRUCTURE

Generate the project using this structure **exactly**:


---

## 🎨 DESIGN SYSTEM (STRICT)

### Colors
- Primary Purple: `#B66DFF`
- Dark Background: `#2C1B3A`
- White: `#FFFFFF`
- Black: `#000000`
- Gray Text: `#888888`

### UI Rules
- Rounded corners (20–30px radius)
- Soft shadows
- Large cards
- Minimal text
- Clear hierarchy
- Mobile-first spacing
- No overcrowding

---

## 🧭 NAVIGATION REQUIREMENTS

### Bottom Tabs
Tabs must exist on all main screens:
- Home
- Wallet
- Complaints
- Profile

### Stack Navigation
- Home → Payment Screen
- Home → Add Complaint (Modal / Bottom Sheet)
- Wallet → Payment Confirmation

---

## 📱 SCREEN-BY-SCREEN REQUIREMENTS

### 1️⃣ HomeScreen
- Greeting text: "Hello, {User}"
- Notification bell icon (top right)
- Large **Occupant Card**:
  - Purple top section
  - “OCCUPANT” label
  - White pill button: "PAY RENT"
  - Name, DOB, Total Dues
- Bills section:
  - Two cards (Electricity, Other Bills)
- Services Grid:
  - Cleaning Service
  - Gate Pass
  - Add Complaints (black highlighted card)
  - Food Menu
  - Community Board
  - Deposit Money

---

### 2️⃣ ComplaintScreen (Bottom Sheet Style)
- Appears as modal from bottom
- Input field: "Write Your Complaint"
- Category cards (grid layout)
- Selected category highlighted in purple
- Internet Service card styled black + purple
- Submit button (full width, rounded, black)

---

### 3️⃣ PaymentScreen
- Purple header background
- Total Rent displayed prominently
- Debit / History toggle switch
- Bill selection list (radio-style)
- Bill breakdown section
- Large Pay Now button at bottom

---

### 4️⃣ WalletScreen
- Wallet balance
- Payment methods (Wallet / UPI)
- Radio button selection
- Confirm payment button

---

### 5️⃣ ProfileScreen
- User avatar
- Name
- ID
- Placeholder sections for future settings

---

## 🧩 COMPONENTIZATION RULES
- Each card must be a reusable component
- Buttons must be reusable
- Icons passed as props
- No hardcoded styles inside screens if reusable

---

## 🧠 CODING GUIDELINES
- Clean, readable code
- Use `StyleSheet.create`
- Descriptive variable names
- No inline styles unless necessary
- Comment important UI logic
- Export default components properly

---

## 🚫 DO NOT DO
- No backend
- No dummy APIs
- No authentication
- No random UI changes
- No deviation from reference design

---

## ✅ FINAL OUTPUT EXPECTATION
By following this prompt, generate:
- A fully working Expo React Native app
- All screens navigable
- UI closely matching provided images
- Clean, maintainable frontend codebase

This app should be **demo-ready**, **hackathon-ready**, and **internship-ready**.


