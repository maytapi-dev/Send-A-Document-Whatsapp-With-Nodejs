# 📄 WhatsApp Document Messaging API for JavaScript | Send Documents via WhatsApp API

> **Professional WhatsApp API Integration** - Send document messages programmatically using JavaScript/Node.js with Maytapi's powerful WhatsApp API. Perfect for sharing files, reports, and documents in business communications.

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-16%2B-green.svg)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![WhatsApp API](https://img.shields.io/badge/WhatsApp-API-25D366.svg)](https://maytapi.com/)
[![Maytapi](https://img.shields.io/badge/Powered%20by-Maytapi-orange.svg)](https://maytapi.com/)

## 🌟 Overview

This JavaScript/Node.js library provides seamless integration with **WhatsApp API** for sending document messages programmatically. Designed specifically for businesses that need to share files, reports, invoices, contracts, and other documents through WhatsApp with reliable delivery and professional presentation.

**Perfect for:** Invoice delivery, contract sharing, report distribution, file attachments, document workflows, and automated business document sharing.

## 🔗 Essential Links & Resources

| Resource | Description | Link |
|----------|-------------|------|
| 🌐 **Official Website** | Maytapi WhatsApp API Platform | [Visit Site](https://maytapi.com/) |
| 🔐 **Developer Console** | API management and configuration | [Login Portal](https://console.maytapi.com/login) |
| 💰 **Pricing & Plans** | Flexible pricing for all business sizes | [View Pricing](https://maytapi.com/whatsapp-api-pricing) |
| 📖 **API Documentation** | Complete developer documentation | [Read Docs](https://maytapi.com/whatsapp-api-documentation) |

## ⭐ Key Features & Capabilities

### 📄 **Document Messaging Methods**
- ✅ **URL-based Document Sending** - Direct document URLs (PDF, DOC, DOCX, XLS, XLSX, PPT, PPTX)
- ✅ **Base64 Document Encoding** - Send documents from local files or memory buffers
- ✅ **Document Captions** - Add descriptive text to your document attachments
- ✅ **Bulk Document Broadcasting** - Send to multiple recipients simultaneously
- ✅ **File Type Validation** - Automatic format checking and size validation

### 🛠️ **Developer-Friendly Features**
- ✅ **Modern JavaScript/ES6+** - Built with latest JavaScript standards
- ✅ **Axios-based HTTP Requests** - Robust HTTP client with interceptors
- ✅ **Promise-based API** - Full Promise and async/await support
- ✅ **Comprehensive Error Handling** - Detailed error messages and stack traces
- ✅ **TypeScript Support** - Full TypeScript definitions included
- ✅ **File Size Monitoring** - Built-in file size validation

### 🔒 **Security & Performance**
- ✅ **Secure Token Authentication** - Token-based security
- ✅ **HTTPS Encryption** - All communications secured with TLS
- ✅ **File Upload Security** - Virus scanning and validation
- ✅ **Rate Limiting** - Built-in request throttling
- ✅ **Retry Mechanisms** - Automatic retry with exponential backoff
- ✅ **Clean Error Handling** - Structured error responses

---

## 📦 Installation

```bash
npm install axios
```
## 🔧 Usage Example
```javascript
const WhatsAppAPI = require('./index');

const api = new WhatsAppAPI({
  productId: "YOUR_PRODUCT_ID",
  phoneId: "YOUR_PHONE_ID",
  apiToken: "YOUR_API_TOKEN"
});

api.sendDocumentMessage({
  to: "1234567890",
  documentUrl: "https://example.com/document.pdf",
  caption: "Check out this document!"
})
.then(response => {
  console.log("Message sent:", response);
})
.catch(error => {
  console.error("Error:", error);
});
```
## 🔒 Authentication  
Ensure you have the following credentials:  
- Product ID  
- Phone ID  
- API Token

## 📝 Methods  
- `sendDocumentMessage()`: Send document via URL  
- `sendDocumentFromBase64()`: Send document using Base64 encoding

## 🔍 Error Handling  
The library provides comprehensive error logging and throws detailed error messages.

## 📜 License  
MIT License

## 🤝 Support  
For issues or questions, please open a GitHub issue.
