# 📑 Professional Invoice Generator

A high-fidelity, client-side invoice creation tool built with **React**, **Tailwind CSS v4**, and **jsPDF**. This application allows users to generate professional-grade business invoices with custom logos and instant PDF downloads.

## 🚀 Live Demo
[Will update soon]

## ✨ Features
- **Dynamic Line Items**: Add, update, and remove invoice rows with automatic subtotal and tax calculations.
- **Custom Branding**: Upload your company logo via `FileReader` API for personalized documents.
- **Modern UI**: A clean, responsive dashboard styled with Tailwind CSS v4's latest configuration.
- **Pixel-Perfect PDF**: Uses an off-screen rendering technique to ensure A4 PDF exports match professional corporate templates exactly.
- **Real-time Totals**: Automatic calculation of Sales Tax (5%) and grand totals as you type.

## 🛠️ Technical Implementation
- **React Hooks**: Managed complex state transitions using `useState` and `useRef`.
- **DOM to Canvas**: Implemented `html2canvas` to capture DOM elements even when positioned off-screen to avoid display errors.
- **PDF Generation**: Utilized `jsPDF` to convert image data into standard A4 document formats.
- **Tailwind v4 Pipeline**: Configured the project to work with the new PostCSS plugin structure and `@import` syntax.
