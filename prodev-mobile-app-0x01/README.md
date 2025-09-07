# React Native Components and Styling - Task 2

## Project Information
- **GitHub Repository:** prodev-mobile-setup
- **Directory:** prodev-mobile-app-0x01
- **Developer:** Lewis Kimani (KiriManii)
- **Expo SDK Version:** 53

## Objective
Learn React Native core components (`<View>`, `<Text>`) and styling system using StyleSheet for cross-platform mobile development.

## Implementation Steps

### 1. Project Setup
```bash
cd prodev-mobile-setup
npx create-expo-app@latest prodev-mobile-app-0x01
cd prodev-mobile-app-0x01
npm run reset-project
```

### 2. Components Implemented
- **Root View:** Background container with blue styling
- **Main Text:** "Entry Screen - Awesome"
- **Text Group:** Three styled text components demonstrating different typography

### 3. Styling Features Applied
- **Container:** Light blue background (#90caf9)
- **Large Text:** Red, 30px, bold, small-caps variant
- **Medium Text:** Purple, 20px, right-aligned
- **Small Text:** Blue, 15px, center-aligned

### 4. Key Learnings
- `<View>` replaces HTML `<div>` elements
- `<Text>` replaces HTML `<p>` elements
- StyleSheet creates optimized styles vs inline styling
- fontVariant and textAlign work cross-platform

## File Structure
```
prodev-mobile-app-0x01/
├── app/
│   └── index.tsx
├── app-example/
└── README.md
```

## Testing Results
✅ App renders correctly on device  
✅ Styling displays as specified  
✅ Text alignment and colors working  
✅ Cross-platform compatibility verified  

---
*Task completed by Lewis Kimani*