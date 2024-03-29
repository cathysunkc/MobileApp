CPRG-303B - Assignment: Architectural Decisions - Cathy Sun (Student ID: 909611)

# Architectural Decision Record for Developing a Mobile App for a Retail Company

## Status

Proposed

## Context

The purpose of this ADR is to review the existing requirements for developing a mobile app for a retail company; to provide architectural decisions on varies technical aspects include the app type, UI framework, backend language, payment gateway, data storage, required app permissions and data collections.

## Decision

After analysis, the following are the proposed architectural decisions for the retail app:

- **App Type** -
  It is proposed to develop a **Hybrid App** for the retail company. The reason is a hybrid app could run on varies operation systems and devices, include laptops, tablets, and mobile phones, in both online and offline mode, which would help the retail app to expand the customer base and user types.
- **UI Framework** -
  It is suggested to use **React Native** as the UI framework because the libraries of React Native are compatible and reusable for cross-platform devices (such as iOS and Android), which could save development time for building the hybrid app. Besides, React Native has existing images resize and compression packages which capable to load and show only particular images on the app screen, either from local or remote sources, which could help the retail app to display product images with optimized performance.
- **Backend Language** -
  The main reason to choose **Express/Node.js** as backend language is it is highly compatible with React Native, which could save development time. Another reason is, React Native could make HTTP requests to server through APIs of Node.js. This would enable the retail app to synchronize customer data, handle concurrent requests and integrate with push notifications efficiently.
- **Payment Gateway** -
  **PayPal** is a secure payment gateway which support end-to-end encryption to protect customer financial and personal data. PayPal is also a popular payment gateway which commonly used in over 200 countries and support over 100 currencies. Therefore, it is a good choice for the retail app to handle orders and transactions for international customer.
- **Data Storage** -
  **MongoDB** is a database platform which could be seamlessly execute with React Native and Node.js. MongoDB could also handle massive data and has build-in libraries to generate visualize dashboard. Its Realm Sync feature could support both offline data sync or online cloud storage, which matches the app requirements.
- **Permissions** -
  The following are the required permissions to use the retail app:
  1. **Location** - enable the app to show different languages and cultural preferences according to user's location.
  2. **Notification** - enable the app to push notification to customer about new products and special offers.
  3. **SMS** - enable the app to send SMS to customer about order and delivery status.
- **Data Collection** -
  The following is the app and user data to be collected by the retail app:
  1. **App Activity** - the customer browsing history, order history and app interactions data would be collected by the retail app for data analysis, marketing, and personalization use.
  2. **App Info and Performance** - any crash logs, diagnostics and performance data would be collected for improving the app performance and user experiences.
  3. **Personal Info** - the customer’s name, email account, phone number and address would be collected for sending notification about order and delivery updates.
  4. **Financial Info** - the customer purchase and transaction data would be collected for personalization, redeem points for discounts and marketing purposes.

## Consequences

Based on above proposed architectural decisions, we believe the use of M.E.R.N. stack (MongoDB, Express.js, React, and Node.js), PayPal, and with the predefined data collection and permission policies would help to develop a scalable and robust mobile app for the retail company. The app would support both online and offline mode; enable push notifications; integrate with secure payment method; capable to track user behavior; with optimize performance; and be expandable and scalable to international customer base.
