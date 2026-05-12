<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25&height=200&section=header&text=ShegerPay&fontSize=72&fontColor=fff&fontAlignY=38&desc=Ethiopian%20Payment%20Infrastructure%20for%20Developers&descSize=18&descAlignY=62&descColor=FFB800&animation=fadeIn)

<img src="https://raw.githubusercontent.com/shegerpay/sdk-python/main/logo.png" width="130" alt="ShegerPay Logo" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=FFB800&center=true&vCenter=true&width=600&lines=Verify+CBE+payments+in+milliseconds;Telebirr+%7C+BOA+%7C+Awash+%7C+CBE;One+API+for+all+Ethiopian+banks;SDKs+for+12+languages+%26+frameworks)](https://git.io/typing-svg)

<br/>

[![Website](https://img.shields.io/badge/🌐%20shegerpay.com-FFB800?style=for-the-badge&logoColor=white)](https://shegerpay.com)
[![Telegram](https://img.shields.io/badge/Telegram-@shegerpay__0-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/shegerpay_0)
[![Email](https://img.shields.io/badge/Email-support@shegerpay.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:support@shegerpay.com)
[![Docs](https://img.shields.io/badge/Docs-shegerpay.com/docs-4285F4?style=for-the-badge&logo=gitbook&logoColor=white)](https://shegerpay.com/docs)

</div>

---

<div align="center">

## ⚡ What is ShegerPay?

</div>

<table>
<tr>
<td width="50%" valign="top">

### 🏦 Auto-verify Ethiopian payments
No more manual checking. One API call confirms any bank transfer instantly — CBE, Telebirr, BOA, Awash and more.

```python
result = client.verify(
  transaction_id="FT26062K7WMY",
  amount=1000,
  provider="cbe"
)
# ✅ verified in < 2 seconds
```

</td>
<td width="50%" valign="top">

### 📸 Verify from receipt screenshot
Send us a photo of any payment receipt — our OCR engine reads and verifies it automatically.

```python
result = client.verify_image(
  screenshot=image_base64,
  provider="telebirr"
)
# ✅ works on any receipt photo
```

</td>
</tr>
</table>

---

<div align="center">

## 🏦 Supported Banks

<img src="https://skillicons.dev/icons?i=&theme=light" />

| &nbsp; | Bank | Provider Key | Status |
|--------|------|-------------|--------|
| 🏦 | Commercial Bank of Ethiopia (CBE) | `cbe` | ![](https://img.shields.io/badge/-Live-22c55e?style=flat-square) |
| 📱 | Telebirr — Ethio Telecom | `telebirr` | ![](https://img.shields.io/badge/-Live-22c55e?style=flat-square) |
| 🏦 | Bank of Abyssinia (BOA) | `boa` | ![](https://img.shields.io/badge/-Live-22c55e?style=flat-square) |
| 🏦 | Awash Bank | `awash` | ![](https://img.shields.io/badge/-Live-22c55e?style=flat-square) |
| 💳 | eBirr Kaafi | `ebirr_kaafi` | ![](https://img.shields.io/badge/-Live-22c55e?style=flat-square) |
| 💳 | eBirr Coop | `ebirr_coop` | ![](https://img.shields.io/badge/-Live-22c55e?style=flat-square) |

</div>

---

<div align="center">

## 📦 Official SDKs — v2.2.0

</div>

<table>
<tr>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-python">
    <img src="https://skillicons.dev/icons?i=python" width="48"/><br/>
    <b>Python</b><br/>
    <img src="https://img.shields.io/badge/pip%20install%20shegerpay-3776AB?style=flat-square&logo=python&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-js">
    <img src="https://skillicons.dev/icons?i=ts" width="48"/><br/>
    <b>TypeScript / JS</b><br/>
    <img src="https://img.shields.io/badge/npm%20install-CB3837?style=flat-square&logo=npm&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-php">
    <img src="https://skillicons.dev/icons?i=php" width="48"/><br/>
    <b>PHP</b><br/>
    <img src="https://img.shields.io/badge/composer%20require-8892BE?style=flat-square&logo=composer&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-go">
    <img src="https://skillicons.dev/icons?i=go" width="48"/><br/>
    <b>Go</b><br/>
    <img src="https://img.shields.io/badge/go%20get-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-ruby">
    <img src="https://skillicons.dev/icons?i=ruby" width="48"/><br/>
    <b>Ruby</b><br/>
    <img src="https://img.shields.io/badge/gem%20install-CC342D?style=flat-square&logo=rubygems&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-java">
    <img src="https://skillicons.dev/icons?i=java" width="48"/><br/>
    <b>Java</b><br/>
    <img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white"/>
  </a>
</td>
</tr>
<tr>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-csharp">
    <img src="https://skillicons.dev/icons?i=cs" width="48"/><br/>
    <b>C# / .NET</b><br/>
    <img src="https://img.shields.io/badge/NuGet-004880?style=flat-square&logo=nuget&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-kotlin">
    <img src="https://skillicons.dev/icons?i=kotlin" width="48"/><br/>
    <b>Kotlin</b><br/>
    <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-swift">
    <img src="https://skillicons.dev/icons?i=swift" width="48"/><br/>
    <b>Swift / iOS</b><br/>
    <img src="https://img.shields.io/badge/SPM-FA7343?style=flat-square&logo=swift&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-android">
    <img src="https://skillicons.dev/icons?i=androidstudio" width="48"/><br/>
    <b>Android</b><br/>
    <img src="https://img.shields.io/badge/Gradle-3DDC84?style=flat-square&logo=android&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-dart">
    <img src="https://skillicons.dev/icons?i=flutter" width="48"/><br/>
    <b>Flutter / Dart</b><br/>
    <img src="https://img.shields.io/badge/pub%20add-02569B?style=flat-square&logo=dart&logoColor=white"/>
  </a>
</td>
<td align="center" width="16%">
  <a href="https://github.com/shegerpay/sdk-wordpress">
    <img src="https://skillicons.dev/icons?i=wordpress" width="48"/><br/>
    <b>WordPress</b><br/>
    <img src="https://img.shields.io/badge/WooCommerce-7F54B3?style=flat-square&logo=woocommerce&logoColor=white"/>
  </a>
</td>
</tr>
</table>

---

<div align="center">

## 🔌 Integrations & Features

</div>

<table>
<tr>
<td align="center" width="25%">

### 🪝 Webhooks
Real-time notifications when payments land. HMAC-signed payloads.

</td>
<td align="center" width="25%">

### 🔗 Payment Links
Create shareable payment pages. No code needed — share the link.

</td>
<td align="center" width="25%">

### 🤖 Telegram Bot
Customers verify payments directly via [@shegerpay_0_bot](https://t.me/shegerpay_0_bot)

</td>
<td align="center" width="25%">

### 🛒 WooCommerce
WordPress plugin — accept Ethiopian payments at checkout instantly.

</td>
</tr>
</table>

---

<div align="center">

## 🚀 Get Started in 60 Seconds

</div>

```bash
# 1. Install
pip install shegerpay

# 2. Verify a payment
python3 -c "
from shegerpay import ShegerPay
client = ShegerPay('sk_test_YOUR_KEY')
result = client.verify(transaction_id='FT26062K7WMY', provider='cbe')
print('✅ Verified!' if result.verified else '❌ Not verified')
"
```

> Get your free API key at **[shegerpay.com](https://shegerpay.com)** — no credit card required.

---

<div align="center">

## 📊 Platform Stats

![](https://img.shields.io/badge/SDKs-12%20languages-FFB800?style=for-the-badge)
![](https://img.shields.io/badge/Banks-6%20supported-22c55e?style=for-the-badge)
![](https://img.shields.io/badge/API%20Version-v2.2.0-4285F4?style=for-the-badge)
![](https://img.shields.io/badge/Uptime-99.9%25-22c55e?style=for-the-badge)

<br/>

**Built for Ethiopian developers. Trusted by businesses.**

<br/>

[![Website](https://img.shields.io/badge/🌐%20shegerpay.com-FFB800?style=for-the-badge)](https://shegerpay.com)
[![Telegram](https://img.shields.io/badge/💬%20@shegerpay__0-2CA5E0?style=for-the-badge)](https://t.me/shegerpay_0)
[![Email](https://img.shields.io/badge/📧%20support@shegerpay.com-EA4335?style=for-the-badge)](mailto:support@shegerpay.com)

![footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,25&height=100&section=footer)

</div>
