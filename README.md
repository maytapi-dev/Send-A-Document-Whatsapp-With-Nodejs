## 📄 WhatsApp Document Messaging API

Easily send document messages via WhatsApp using Maytapi's robust API.

## 🚀 Features

- Send document messages via direct URL
- Send documents using Base64 encoded data
- Add optional captions
- Clean error handling and Axios-based requests

  ## 🔗 Navigation Links

Based on stakeholder feedback, the following key navigation links have been added:

- 🌐 [Home Page](https://maytapi.com/)  
- 🔐 [Login Page](https://console.maytapi.com/login)  
- 💰 [Pricing](https://maytapi.com/whatsapp-api-pricing)  
- 📄 [Documentation](https://maytapi.com/whatsapp-api-documentation#)
  

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
