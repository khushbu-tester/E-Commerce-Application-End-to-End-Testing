# Mobile App Testing Scenarios (Android & iOS)

Testing a mobile shopping app requires checking how the app behaves in real-world conditions. Below are the specialized scenarios I verified for this project.

### 1. Functional & UI Scenarios
- **Pinch-to-Zoom:** Verified that users can zoom into product images for better clarity.
- **Swipe-to-Delete:** Checked if swiping left on a cart item successfully removes it.
- **Screen Orientation:** Validated that the Checkout page layout doesn't break when switching from Portrait to Landscape mode.

### 2. Interrupt Testing (Critical)
- **Incoming Call/SMS:** Verified that the app maintains its state (e.g., doesn't log out or empty the cart) when the user receives a call.
- **Low Battery/Push Notifications:** Checked app stability when system popups appear.
- **App Backgrounding:** Verified that the app resumes from the same screen after being minimized.

### 3. Network & Performance
- **Network Switch:** Tested behavior when switching from Wi-Fi to 4G/5G during a payment process.
- **Slow Internet:** Verified that a proper "Loading" spinner or "Slow Connection" message is displayed.

### 4. Compatibility
- Tested on **Android 13 (Samsung/Pixel)** and **iOS 16 (iPhone)** to ensure font and button consistency.
