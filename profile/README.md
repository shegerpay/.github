<p align="center">
  <img src="https://raw.githubusercontent.com/shegerpay/sdk-python/main/logo.png" alt="ShegerPay" width="220" />
</p>

<h1 align="center">ShegerPay</h1>

<p align="center">
  <strong>Ethiopian Payment Infrastructure for Developers</strong><br/>
  Verify CBE · Telebirr · BOA · Awash payments in seconds — one API, all banks.
</p>

<p align="center">
  <a href="https://shegerpay.com"><img src="https://img.shields.io/badge/website-shegerpay.com-gold?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <a href="https://t.me/shegerpay_0"><img src="https://img.shields.io/badge/Telegram-@shegerpay__0-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="mailto:support@shegerpay.com"><img src="https://img.shields.io/badge/Email-support@shegerpay.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## ⚡ What We Do

ShegerPay is the **payment verification layer for Ethiopia**. We make it dead-simple for developers and businesses to confirm Ethiopian bank transfers automatically — no manual checking, no delays.

```python
from shegerpay import ShegerPay

client = ShegerPay("sk_live_...")
result = client.verify(transaction_id="FT26062K7WMY", amount=1000, provider="cbe")

print(result.verified)  # True ✅
```

---

## 🏦 Supported Banks

<p align="center">

| Bank | Provider Key |
|------|-------------|
| 🏦 Commercial Bank of Ethiopia | `cbe` |
| 📱 Telebirr (Ethio Telecom) | `telebirr` |
| 🏦 Bank of Abyssinia | `boa` |
| 🏦 Awash Bank | `awash` |
| 💳 eBirr Kaafi | `ebirr_kaafi` |
| 💳 eBirr Coop | `ebirr_coop` |

</p>

---

## 📦 Official SDKs

<p align="center">

| Language | Repository | Install |
|----------|-----------|---------|
| 🐍 Python | [sdk-python](https://github.com/shegerpay/sdk-python) | `pip install shegerpay` |
| 🟨 JavaScript / TypeScript | [sdk-js](https://github.com/shegerpay/sdk-js) | `npm install @shegerpay/sdk` |
| 🐘 PHP | [sdk-php](https://github.com/shegerpay/sdk-php) | `composer require shegerpay/sdk` |
| 🐹 Go | [sdk-go](https://github.com/shegerpay/sdk-go) | `go get github.com/shegerpay/sdk-go` |
| 💎 Ruby | [sdk-ruby](https://github.com/shegerpay/sdk-ruby) | `gem install shegerpay` |
| ☕ Java | [sdk-java](https://github.com/shegerpay/sdk-java) | Maven / Gradle |
| 🔷 C# / .NET | [sdk-csharp](https://github.com/shegerpay/sdk-csharp) | `dotnet add package ShegerPay.SDK` |
| 🎯 Kotlin | [sdk-kotlin](https://github.com/shegerpay/sdk-kotlin) | Gradle |
| 🍎 Swift / iOS | [sdk-swift](https://github.com/shegerpay/sdk-swift) | Swift Package Manager |
| 🤖 Android | [sdk-android](https://github.com/shegerpay/sdk-android) | Gradle |
| 🎯 Dart / Flutter | [sdk-dart](https://github.com/shegerpay/sdk-dart) | `dart pub add shegerpay` |
| 🔌 WordPress | [sdk-wordpress](https://github.com/shegerpay/sdk-wordpress) | Upload & activate plugin |

</p>

---

## 🚀 Quick Start

**1. Get your API key** — Sign up free at [shegerpay.com](https://shegerpay.com)

**2. Install your SDK**
```bash
pip install shegerpay          # Python
npm install @shegerpay/sdk     # Node.js
composer require shegerpay/sdk # PHP
```

**3. Verify a payment**
```javascript
import { ShegerPay } from '@shegerpay/sdk';

const client = new ShegerPay('sk_live_YOUR_KEY');
const result = await client.verify({ transactionId: 'FT26062K7WMY', provider: 'cbe' });

if (result.verified) {
  // ✅ Payment confirmed — fulfill the order
}
```

**4. Verify from a screenshot (OCR)**
```python
import base64
with open("receipt.png", "rb") as f:
    img = base64.b64encode(f.read()).decode()

result = client.verify_image(screenshot=img, provider="telebirr")
```

---

## 🔌 Integrations

- **WooCommerce** — Accept Ethiopian payments in your WordPress store. [→ Install plugin](https://github.com/shegerpay/sdk-wordpress)
- **Webhooks** — Get real-time notifications when payments are confirmed
- **Payment Links** — Create shareable payment links, no code needed
- **Telegram Bot** — Get verified in seconds via [@shegerpay_0_bot](https://t.me/shegerpay_0_bot)

---

## 📖 Documentation

| Resource | Link |
|----------|------|
| 📚 Full Docs | [shegerpay.com/docs](https://shegerpay.com/docs) |
| 🔌 API Reference | [shegerpay.com/docs/api](https://shegerpay.com/docs/api) |
| ⚡ Quick Start | [shegerpay.com/docs/quickstart](https://shegerpay.com/docs/quickstart) |
| 🪝 Webhooks Guide | [shegerpay.com/docs/webhooks](https://shegerpay.com/docs/webhooks) |

---

## 🤝 Connect With Us

<p align="center">
  <a href="https://shegerpay.com">
    <img src="https://img.shields.io/badge/🌐 Website-shegerpay.com-FFB800?style=for-the-badge" />
  </a>
  &nbsp;
  <a href="https://t.me/shegerpay_0">
    <img src="https://img.shields.io/badge/💬 Telegram-@shegerpay__0-2CA5E0?style=for-the-badge" />
  </a>
  &nbsp;
  <a href="mailto:support@shegerpay.com">
    <img src="https://img.shields.io/badge/📧 Email-support@shegerpay.com-EA4335?style=for-the-badge" />
  </a>
</p>

<p align="center">
  <sub>Built with ❤️ for Ethiopian developers and businesses · <a href="https://shegerpay.com">shegerpay.com</a></sub>
</p>
