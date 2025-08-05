# Checkout-Coupon-Popup
Description: Displays a WooCommerce coupon code popup on the checkout page and applies it via AJAX. Improves user experience and conversion.

# 🧾 Checkout Coupon Popup for WooCommerce

A lightweight WordPress plugin that displays a popup on the WooCommerce checkout page, allowing users to apply a coupon code before completing their order. Designed for improved UX and better conversion.

## ✅ Features

- Automatically opens a coupon popup on checkout page load
- Input field for coupon code
- "Apply" button to submit via AJAX (no full page reload)
- "Close" button to dismiss the popup
- Prevents showing again once closed or submitted
- Mobile responsive layout
- No additional libraries required

## 📦 Installation

1. Download the ZIP file.
2. Go to your WordPress Admin Dashboard.
3. Navigate to **Plugins > Add New > Upload Plugin**.
4. Select the ZIP and click **Install Now**.
5. Activate the plugin.
6. Ensure WooCommerce is active on your site.

## 💻 Usage

Once the plugin is activated, the popup will appear automatically when a user lands on the WooCommerce checkout page. The coupon is applied using AJAX, and the popup won’t reappear after use or close (until browser storage is cleared).

## 📱 Mobile Friendly

The popup layout adapts to smaller screen sizes using responsive CSS.

## 🛠️ Developer Notes

- The plugin uses `localStorage` to track whether the popup has been shown.
- You can customize styling directly inside the plugin PHP file or extend it with an external stylesheet.

## 🧑‍💻 Author

**Abdul Rashid**  
Freelance WordPress Developer & Motion Graphics Designer  
[Portfolio](www.rashidverse.com) | [LinkedIn](https://www.linkedin.com/in/iamabdulrashid/) | [Email](rashedverse@gmail.com)

---

## 📄 License

This plugin is released under the [MIT License](LICENSE).

