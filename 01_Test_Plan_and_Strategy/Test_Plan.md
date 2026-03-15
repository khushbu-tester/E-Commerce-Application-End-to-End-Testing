# Test Plan - E-Commerce Application (Web & Mobile)

## 1. Introduction
The purpose of this document is to define the testing strategy and scope for the E-commerce platform. The goal is to ensure a bug-free experience for users during product search, cart management, and checkout.

## 2. Test Strategy
- **Manual Testing:** Functional testing of all modules.
- **UI/UX Testing:** Checking the interface on different screen sizes (Responsive Testing).
- **Regression Testing:** Ensuring new updates don't break existing features like 'Add to Cart'.
- **Compatibility Testing:** Testing across Chrome, Safari, and Firefox.

## 3. Scope of Testing (What we will test)
- **User Authentication:** Login, Signup, and Password Reset.
- **Product Journey:** Search filters, Category browsing, and Product details.
- **Checkout Flow:** Guest checkout, Coupon codes, and Payment status validation.
- **Mobile Specific:** App behavior during interrupts (calls/notifications).

## 4. Tools & Environment
- **Bug Tracking:** JIRA
- **API Testing:** Postman
- **Database:** MySQL (for data integrity)
- **Devices:** Windows Laptop, Android (v13), iOS (v16)

## 5. Exit Criteria (When to stop testing)
- 100% of 'Critical' and 'High' priority bugs are fixed and closed.
- All planned test cases have been executed.
- No major UI alignment issues remain.
