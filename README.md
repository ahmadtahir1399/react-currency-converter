<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,55:1c1d20,100:0c63e7&height=170&section=header&text=Currency%20Converter&fontSize=46&fontColor=fcfaf8&fontAlignY=38&desc=Live%20exchange%20rates%20with%20React&descAlignY=60&descSize=16" width="100%" alt="Currency Converter" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
</p>

## ✨ About

A currency converter that gets live exchange rates from the free [fawazahmed0 currency API](https://github.com/fawazahmed0/exchange-api). The data fetching sits in a reusable **custom hook**, `useCurrencyInfo`, and the amount fields are a reusable `InputBox` component.

## 🔋 Features

- 🌍 Live rates for 150+ currencies
- 🔄 One-click **swap** between "from" and "to"
- 🪝 `useCurrencyInfo(currency)` custom hook that refetches when the currency changes
- ♻️ Reusable `InputBox` component with accessible labels (`useId`)

## 🛠️ Tech stack

React 18 · Vite · Tailwind CSS · Fetch API

## 🚀 Getting started

```bash
git clone https://github.com/ahmadtahir1399/react-currency-converter.git
cd react-currency-converter
npm install
npm run dev
```

## 📁 Project structure

```
src/
  hooks/useCurrencyInfo.js   fetches rates for the selected currency
  components/InputBox.jsx    amount + currency select
  App.jsx                    conversion + swap logic
```

## 👤 Author

**Muhammad Ahmad Tahir** · [Portfolio](https://ahmadverse.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/ahmad-ai-enginner/) · [GitHub](https://github.com/ahmadtahir1399)
