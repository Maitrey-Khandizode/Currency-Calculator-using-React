# Currency Calculator (React)

A simple currency converter built with React. It uses a custom hook to fetch live exchange rates and a reusable input component to keep the UI clean. Styled with Tailwind CSS.

---

## ✨ Features

- Convert an amount from one currency to another using live rates
- Swap **From** ↔ **To** currencies with one click
- Reusable `CurrencyInput` component (controlled inputs)
- Custom hook `useCurrencyInfo(base)` that fetches rates for the current base currency

---

## 🧩 Tech Stack

- React (Vite or CRA)
- Tailwind CSS
- Fetch API
- Currency data from [`@fawazahmed0/currency-api`](https://github.com/fawazahmed0/currency-api) via jsDelivr

---

## 📂 Project Structure
src/
hooks/
useCurrencyInfo.js
components/
CurrencyInput.jsx
App.jsx
