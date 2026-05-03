# 🧮 GATE Scientific Calculator

A fully-featured scientific calculator built in **Flutter** as part of the [iStudy – Syllabus & Papers](https://play.google.com/store/apps/details?id=com.istudy.app) app, available on both the **Google Play Store** and **Apple App Store**. The calculator is accessible within the app under the **GATE exam** feature.

> **Note:** This repository contains screenshots of the shipped feature. The source code is proprietary and lives in the company's private codebase.

---

## 📱 Try It Live

The calculator is live and available to real users inside the iStudy app:

- 🤖 [Download on Google Play] ([https://play.google.com/store/apps/details?id=com.istudy.app](https://play.google.com/store/apps/details?id=ini.istudy))
- 🍎 [Download on the App Store] ([https://apps.apple.com/app/istudy-syllabus-papers/id1527660428](https://apps.apple.com/ca/app/istudy-app-syllabus-papers/id6478500231))

After signup,

Navigate to: **GATE Exam → Calculator**

---

## 🛠️ My Contributions

Developed during my **Summer 2023 internship**. I was the primary developer responsible for:

### Backend — Calculator Engine
- Architected and implemented the **core calculation engine** in Dart/Flutter from the ground up
- Built a **BODMAS-compliant expression parser** to correctly handle operator precedence in complex, chained expressions
- Implemented the full scientific function suite:
  - **Trigonometric functions** — `sin`, `cos`, `tan` and their inverses
  - **Logarithmic & exponential operations** — `log`, `ln`, `eˣ`, `xʸ`
  - **Arithmetic operations** — with correct handling of edge cases (division by zero, undefined results, etc.)
- Ensured accuracy and consistency of results across all supported operation types

### Frontend — UI Components
- Built specific UI components for the calculator interface within the Flutter widget tree
- Collaborated with the existing frontend codebase to integrate the calculator engine cleanly into the app's design system

---

## 🧩 Tech Stack

| Layer | Technology |
|---|---|
| Framework | Flutter (Dart) |
| Platform | Android & iOS |
| Distribution | Google Play Store & Apple App Store |

---

## 📸 Screenshots

<p align="center">
  <img src="calc1.jpg" width="250"/>
  &nbsp;&nbsp;
  <img src="calc2.jpg" width="250"/>
  &nbsp;&nbsp;
  <img src="calc3.jpg" width="250"/>
</p>

---

## 💡 Key Challenges

- **Expression parsing** — correctly evaluating nested and chained expressions (e.g. `sin(log(2^3) + 4) × 5`) required careful parser design to handle precedence, parentheses, and function composition
- **Edge case handling** — ensuring the engine returned meaningful feedback for undefined operations rather than silently crashing or producing incorrect output
- **Integration** — fitting a from-scratch calculation engine into an existing production Flutter codebase without disrupting surrounding features

---

## 📄 License

Source code is proprietary and owned by the company. Screenshots are included for portfolio demonstration purposes only.
