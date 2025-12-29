# Hostel Management App

A complete React Native mobile application built with Expo for hostel management. This frontend-only app includes all the essential features for students living in hostels to manage their rent, bills, complaints, and services.

## 🎨 Features

### ✅ Implemented Screens

1. **Home Screen**
   - Greeting header with notification icon
   - Occupant card with purple header
   - "PAY RENT" button
   - Student details (Name, DOB, Total Dues)
   - Bills section (Electricity, Other Bills)
   - Services grid (6 service cards including Cleaning, Gate Pass, Add Complaints, Food Menu, Community Board, Deposit Money)

2. **Payment Screen**
   - Purple header with total rent display
   - Debit/History toggle switch
   - Bill selection with radio buttons
   - Bill breakdown card
   - Pay Now button

3. **Wallet Screen**
   - Wallet balance card
   - Payment method selection (Wallet, UPI, Card)
   - Recent transactions list
   - Confirm payment button

4. **Complaints Screen**
   - List of all complaints with status badges
   - Add complaint button
   - Complaint modal (bottom sheet style)

5. **Profile Screen**
   - User avatar and details
   - Menu options (Personal Info, Room Details, Documents, etc.)
   - Logout button
   - Version info

6. **Add Complaint Modal**
   - Bottom sheet style modal
   - Text input for complaint
   - Category selection grid
   - Submit button

## 🎨 Design System

### Colors Used
- **Primary Purple**: `#B66DFF`
- **Dark Background**: `#2C1B3A`
- **White**: `#FFFFFF`
- **Black**: `#000000`
- **Gray Text**: `#888888`
- **Light Gray**: `#F5F5F5`

### UI Features
- Rounded corners (20-25px radius)
- Soft shadows for depth
- Large, readable cards
- Clear visual hierarchy
- Mobile-first spacing
- Purple accent color throughout

## 🧭 Navigation

### Bottom Tabs
- **Home**: Main dashboard
- **Wallet**: Payment and transaction history
- **Complaints**: View and add complaints
- **Profile**: User profile and settings

### Stack Navigation
- Home → Payment Screen
- Payment → Wallet Screen
- Complaint Modal (from Home or Complaints tab)

## 📱 Tech Stack

- **Framework**: React Native with Expo
- **Language**: JavaScript (JSX/TSX)
- **Navigation**: Expo Router
- **Icons**: @expo/vector-icons (Ionicons)
- **Styling**: React Native StyleSheet API

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- Expo CLI

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Run on your device:
   - Scan QR code with Expo Go app (iOS/Android)
   - Press `a` for Android emulator
   - Press `i` for iOS simulator

## 📁 Project Structure

```
HostelApp/
├── app/
│   ├── (tabs)/
│   │   ├── _layout.tsx       # Bottom tab navigation
│   │   ├── index.tsx          # Home screen
│   │   ├── wallet.tsx         # Wallet screen
│   │   ├── complaints.tsx     # Complaints screen
│   │   └── explore.tsx        # Profile screen
│   ├── screens/
│   │   ├── HomeScreen.js
│   │   ├── ComplaintScreen.js
│   │   ├── PaymentScreen.js
│   │   ├── WalletScreen.js
│   │   └── ProfileScreen.js
│   ├── _layout.tsx            # Root layout
│   └── payment.tsx            # Payment route
├── assets/
├── components/
├── constants/
└── package.json
```

## ✨ Key Features

- ✅ Fully navigable UI
- ✅ Pixel-perfect design matching reference images
- ✅ Reusable components
- ✅ Clean code structure
- ✅ Modal bottom sheet for complaints
- ✅ Tab navigation with custom styling
- ✅ Stack navigation for payment flow
- ✅ Proper SafeAreaView implementation
- ✅ StatusBar styling

## 🎯 Design Highlights

1. **Occupant Card**: Eye-catching purple header with white pill button
2. **Service Cards**: Grid layout with highlighted "Add Complaints" card in black
3. **Complaint Modal**: Smooth bottom sheet animation with category selection
4. **Payment Screen**: Purple header section with toggle and bill breakdown
5. **Wallet**: Clean transaction history with color-coded amounts
6. **Profile**: Well-organized menu items with icons

## 📝 Notes

- This is a **frontend-only** application
- No backend integration or API calls
- No authentication implemented
- Ready for demo presentations
- Can be extended with backend services later

## 🔮 Future Enhancements

- Backend API integration
- User authentication
- Real payment gateway
- Push notifications
- Complaint tracking system
- Food menu ordering
- Community board features

## 📄 License

This project is created for educational and demonstration purposes.

---

**Version**: 1.0.0  
**Built with**: ❤️ using React Native & Expo
