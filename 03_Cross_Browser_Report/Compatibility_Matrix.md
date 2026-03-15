# Cross-Browser & Compatibility Testing Report

I verified the E-commerce platform across different browsers and operating systems to ensure UI/UX consistency.

###  Desktop Browser Testing
| Browser | Operating System | Status | Observations |
| :--- | :--- | :--- | :--- |
| **Google Chrome** | Windows 11 |  Pass | Perfect rendering of fonts and buttons. |
| **Mozilla Firefox** | Windows 10 |  Pass | Checkout flow working smoothly. |
| **Microsoft Edge** | Windows 11 | Pass | All banners and sliders aligned. |

###  Mobile Browser Testing
| Browser | Device | Status | Observations |
| :--- | :--- | :--- | :--- |
| **Safari** | iPhone 14 (iOS) |  Pass | Sticky 'Add to Cart' bar is visible. |
| **Chrome Mobile** | Samsung S22 (Android) |  Pass | Mobile-responsive menu working fine. |

###  Issues Identified (Cross-Browser)
- **Safari Issue:** On older iPhone models, the 'Filter' sidebar was overlapping the product grid. (Reported & Fixed).
- **Firefox Issue:** Some custom icons were not loading due to font-face incompatibility. (Suggested CSS fix to Dev).
