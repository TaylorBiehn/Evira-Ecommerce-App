
[![Figma Design](screenshots/figma_thumbnail.png)](https://www.figma.com/community/file/1216043752712853958/evira-e-commerce-online-shop-app-ui-kit)

---

## ✨ Badges

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Android-blue.svg?style=for-the-badge)
![State Management: Bloc](https://img.shields.io/badge/State%20Management-Bloc-purple.svg?style=for-the-badge)
![Supabase](https://img.shields.io/badge/Backend-Supabase-green?style=for-the-badge&logo=supabase&logoColor=white)
![Sentry](https://img.shields.io/badge/Monitoring-Sentry-red?style=for-the-badge&logo=sentry&logoColor=white)


---


# 🛍️ Evira E-Commerce App

**Evira** is a premium **Flutter E-Commerce & Online Shopping app** built with **Bloc**, **Supabase**, and **Clean Architecture**.  
It delivers a complete and modern shopping experience — from product discovery and filtering to checkout, wallet payments, and order tracking — all with elegant light and dark themes.  

📱 Designed for performance, scalability, and beautiful UI across Android devices.  
⭐ Built with over **190+ responsive screens** and crafted for developers who want a ready-to-use, production-quality Flutter E-Commerce template.  


---

> ⚠️ **Project Status: In Development**  
>
> This project is still under active development.  
> Features, structure, and dependencies may change frequently until a stable release is published.  
> Contributions and feedback are always welcome!

---


## 🚀 Features

- 🎨 **Premium & Modern UI** with 190+ responsive screens  
- 🌗 **Light & Dark Theme** support  
- 🛒 **Complete Shopping Flow** – Wishlist, Cart, Checkout, and Order Tracking  
- 🔍 **Smart Product Search & Filters** with categories and reviews  
- 💳 **Secure Multiple Payment Methods** with promo & discount offers  
- 👛 **Integrated E-Wallet** – Top-Up, Transaction History & E-Receipts  
- 👤 **User Authentication** – Onboarding, Sign Up, Sign In, Forgot/Reset Password  
- 📦 **Shipping & Delivery Tracking** for orders  
- 🔔 **Notifications & Alerts** for updates and offers  
- ⚙️ **Profile & Settings Management** with account setup  
- 🛠️ **Fully Customizable Design System** with components, variants & auto layout  

---

## 📊 App Architecture

![App Architecture](screenshots/diagram.png)

```plaintext
lib
├───core
│   ├───constants
│   ├───di
│   ├───enums
│   ├───extensions
│   ├───gen
│   ├───l10n
│   ├───lang_generated
│   │   └───intl
│   ├───routes
│   │   └───args
│   ├───services
│   ├───theme
│   └───utils
├───features
│   ├───create_new_password
│   │   └───ui
│   │       ├───dialogs
│   │       ├───screen
│   │       └───widgets
│   ├───create_pin
│   │   ├───data
│   │   │   └───repos
│   │   ├───domain
│   │   │   ├───repos
│   │   │   └───usecases
│   │   └───ui
│   │       ├───cubit
│   │       └───screen
│   ├───error
│   │   └───ui
│   │       └───screen
│   ├───fill_profile
│   │   ├───data
│   │   │   ├───models
│   │   │   └───repos
│   │   ├───domain
│   │   │   ├───entities
│   │   │   ├───repos
│   │   │   └───usecases
│   │   └───ui
│   │       ├───cubit
│   │       ├───screen
│   │       └───widgets
│   ├───forget_password
│   │   └───ui
│   │       ├───screens
│   │       └───widgets
│   ├───home
│   │   └───ui
│   │       └───screen
│   ├───login
│   │   ├───data
│   │   │   ├───models
│   │   │   └───repos
│   │   ├───domain
│   │   │   ├───entities
│   │   │   ├───repos
│   │   │   └───usecases
│   │   └───ui
│   │       ├───cubit
│   │       ├───screen
│   │       └───widgets
│   ├───no_internet
│   │   └───ui
│   │       └───screen
│   ├───onboarding
│   │   ├───data
│   │   │   ├───models
│   │   │   └───repos
│   │   ├───domain
│   │   │   ├───entities
│   │   │   ├───repos
│   │   │   └───usecases
│   │   └───ui
│   │       ├───cubit
│   │       ├───screen
│   │       └───widgets
│   ├───set_fingerprint
│   │   ├───data
│   │   │   └───repos
│   │   ├───domain
│   │   │   ├───repos
│   │   │   └───usecases
│   │   └───ui
│   │       ├───cubit
│   │       ├───dialogs
│   │       └───screen
│   ├───signup
│   │   ├───data
│   │   │   ├───models
│   │   │   └───repos
│   │   ├───domain
│   │   │   ├───entities
│   │   │   ├───repos
│   │   │   └───usecases
│   │   └───ui
│   │       ├───cubit
│   │       ├───screen
│   │       └───widgets
│   └───social_auth
│       ├───data
│       │   └───repos
│       ├───domain
│       │   ├───repos
│       │   └───usecases
│       └───ui
│           ├───cubit
│           ├───screen
│           └───widgets
└───shared
    ├───cubits
    ├───data
    │   ├───models
    │   └───repos
    ├───domain
    │   ├───repos
    │   └───usecases
    ├───mixins
    └───widgets
```
---


## 🚀 Getting Started

To run this app locally:

```bash
git clone https://github.com/TaylorBiehn/Evira-E-Commerce.git
cd Evira-E-Commerce
flutter pub get
flutter run
```

### 🎨 UI

---

### 📸 Screenshots

<p float="left">
  <img src="screenshots/onboarding_screen.png" width="45%"/>
  <img src="screenshots/sign_up_screen.png" width="45%"/>
  <img src="screenshots/home_screen.png" width="45%"/>
  <img src="screenshots/details_screen.png" width="45%"/>
  <img src="screenshots/cart_screen.png" width="45%"/>
  <img src="screenshots/order_tracking_screen.png" width="45%"/>
  <img src="screenshots/my_orders_screen.png" width="45%"/>
  <img src="screenshots/wallet_screen.png" width="45%"/>
</p>


---

### 🛠️ Contributions

Feel free to fork the repo, open issues, or submit PRs to improve the app!
