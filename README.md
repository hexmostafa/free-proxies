# Free Auto-Updated Proxy Lists / لیست پروکسی‌های رایگان با به‌روزرسانی خودکار

## Language / زبان
- [English](#english)
- [فارسی](#فارسی)

---

## English

[![Last Commit](https://img.shields.io/github/last-commit/hexmostafa/free-proxies?style=for-the-badge&logo=github)](https://github.com/hexmostafa/free-proxies/commits/main)
[![Workflow Status](https://img.shields.io/github/actions/workflow/status/hexmostafa/free-proxies/update-proxies.yml?style=for-the-badge)](https://github.com/hexmostafa/free-proxies/actions)
[![Repo Size](https://img.shields.io/github/repo-size/hexmostafa/free-proxies?style=for-the-badge&logo=github)](https://github.com/hexmostafa/free-proxies)
[![License: MIT](https://img.shields.io/github/license/hexmostafa/free-proxies?style=for-the-badge)](https://github.com/hexmostafa/free-proxies/blob/main/LICENSE)

A repository containing free proxy lists that are automatically updated every few minutes via GitHub Actions.

### 📋 Proxy Lists

Here are the direct links to the proxy lists. Use the "Raw" links for programmatic access.

| Protocol  | Link to File                                    | Raw Link (for code)                                    |
|:----------|:-----------------------------------------------|:-----------------------------------------------------|
| **HTTP**  | [http.txt](https://github.com/hexmostafa/free-proxies/blob/main/http.txt) | [Raw](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/http.txt) |
| **HTTPS** | [https.txt](https://github.com/hexmostafa/free-proxies/blob/main/https.txt) | [Raw](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/https.txt) |
| **SOCKS4**| [socks4.txt](https://github.com/hexmostafa/free-proxies/blob/main/socks4.txt) | [Raw](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/socks4.txt) |
| **SOCKS5**| [socks5.txt](https://github.com/hexmostafa/free-proxies/blob/main/socks5.txt) | [Raw](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/socks5.txt) |

### ⚙️ How It Works

This repository uses a GitHub Actions workflow that runs on a schedule (every 5 minutes). The workflow executes a script that:
1. Fetches fresh proxies from an external API for different protocols (HTTP, HTTPS, SOCKS4, SOCKS5).
2. Formats the proxy lists into `.txt` files.
3. Commits and pushes the updated files back to this repository.

### 🚀 Usage

You can use these lists directly in your applications. Here are examples using `curl`:

```bash
# Get HTTP proxies
curl -o http_proxies.txt https://raw.githubusercontent.com/hexmostafa/free-proxies/main/http.txt

# Get HTTPS proxies
curl -o https_proxies.txt https://raw.githubusercontent.com/hexmostafa/free-proxies/main/https.txt
```

### ⚠️ Disclaimer

These proxies are sourced from public providers and are provided as-is.
- **Reliability**: They may be slow, unreliable, or short-lived.
- **Security**: As public proxies, they should not be used for sensitive activities. Use at your own risk.

### 🤝 Contributing

Feel free to open an issue to report problems or suggest improvements. Pull requests are also welcome.

### 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/hexmostafa/free-proxies/blob/main/LICENSE) file for details.

---

## فارسی

[![Last Commit](https://img.shields.io/github/last-commit/hexmostafa/free-proxies?style=for-the-badge&logo=github)](https://github.com/hexmostafa/free-proxies/commits/main)
[![Workflow Status](https://img.shields.io/github/actions/workflow/status/hexmostafa/free-proxies/update-proxies.yml?style=for-the-badge)](https://github.com/hexmostafa/free-proxies/actions)
[![Repo Size](https://img.shields.io/github/repo-size/hexmostafa/free-proxies?style=for-the-badge&logo=github)](https://github.com/hexmostafa/free-proxies)
[![License: MIT](https://img.shields.io/github/license/hexmostafa/free-proxies?style=for-the-badge)](https://github.com/hexmostafa/free-proxies/blob/main/LICENSE)

این ریپازیتوری شامل لیست پروکسی‌های رایگان است که به صورت خودکار هر چند دقیقه یک بار توسط GitHub Actions به‌روزرسانی می‌شوند.

### 📋 لیست پروکسی‌ها

در جدول زیر لینک‌های مستقیم به لیست پروکسی‌ها قرار دارد. برای استفاده در برنامه‌ها و اسکریپت‌ها از «لینک خام» استفاده کنید.

| پروتکل   | لینک فایل                                       | لینک خام (برای برنامه‌نویسان)                         |
|:---------|:-----------------------------------------------|:-----------------------------------------------------|
| **HTTP**  | [http.txt](https://github.com/hexmostafa/free-proxies/blob/main/http.txt) | [خام](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/http.txt) |
| **HTTPS** | [https.txt](https://github.com/hexmostafa/free-proxies/blob/main/https.txt) | [خام](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/https.txt) |
| **SOCKS4**| [socks4.txt](https://github.com/hexmostafa/free-proxies/blob/main/socks4.txt) | [خام](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/socks4.txt) |
| **SOCKS5**| [socks5.txt](https://github.com/hexmostafa/free-proxies/blob/main/socks5.txt) | [خام](https://raw.githubusercontent.com/hexmostafa/free-proxies/main/socks5.txt) |

### ⚙️ نحوه عملکرد

این پروژه از یک workflow در GitHub Actions استفاده می‌کند که طبق یک زمان‌بندی مشخص (هر ۵ دقیقه) اجرا می‌شود. این workflow اسکریپتی را اجرا می‌کند که:
۱. پروکسی‌های جدید را برای پروتکل‌های مختلف (HTTP, HTTPS, SOCKS4, SOCKS5) از یک API خارجی دریافت می‌کند.
۲. لیست پروکسی‌ها را در فایل‌های `.txt` فرمت‌بندی می‌کند.
۳. فایل‌های به‌روز شده را به همین ریپازیتوری کامیت و پوش می‌کند.

### 🚀 نحوه استفاده

شما می‌توانید از این لیست‌ها مستقیماً در برنامه‌های خود استفاده کنید. در زیر نمونه استفاده با `curl` آمده است:

```bash
# دریافت پروکسی‌های HTTP
curl -o http_proxies.txt https://raw.githubusercontent.com/hexmostafa/free-proxies/main/http.txt

# دریافت پروکسی‌های HTTPS
curl -o https_proxies.txt https://raw.githubusercontent.com/hexmostafa/free-proxies/main/https.txt
```

### ⚠️ سلب مسئولیت

این پروکسی‌ها از منابع عمومی جمع‌آوری شده و به همان صورت ارائه می‌شوند.
- **پایداری**: ممکن است کند، ناپایدار یا کوتاه‌مدت باشند.
- **امنیت**: به عنوان پروکسی‌های عمومی، نباید برای فعالیت‌های حساس استفاده شوند. مسئولیت استفاده از آن‌ها با خود شماست.

### 🤝 مشارکت

برای گزارش مشکل یا ارائه پیشنهاد می‌توانید یک Issue باز کنید. Pull Requestها نیز پذیرفته می‌شوند.

### 📄 مجوز (لایسنس)

این پروژه تحت مجوز MIT منتشر شده است. برای جزئیات بیشتر فایل [LICENSE](https://github.com/hexmostafa/free-proxies/blob/main/LICENSE) را مشاهده کنید.
