
***

# Internet Diet Planner

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Size](https://img.shields.io/badge/size-%3C50kb-success)
![Status](https://img.shields.io/badge/status-stable-green)
![Privacy](https://img.shields.io/badge/privacy-offline--first-lightgrey)

**A philosophy-driven utility for conscious internet consumption.**

The Internet Diet Planner is not a site blocker. It is not surveillance software. It is a digital mindfulness dashboard designed to help you define boundaries, track urges, and move from reactive scrolling to intentional browsing.

It is a single-file, zero-dependency web application. It runs entirely in your browser. No data leaves your device.

---

## ⚡ Quick Start

You can use the tool immediately without installation, or download it for offline use.

| Method | Action |
| :--- | :--- |
| **Live App** | [**Launch Internet Diet Planner**](https://aliriyaj007.github.io/Internet-Diet-Planner/) |
| **Offline** | Download `index.html` and open it in any browser. |

---

## 🎯 The Problem

Most productivity tools treat the internet as an enemy to be blocked. This creates a cycle of restriction and relapse (the "binge/purge" cycle).

The **Internet Diet Planner** treats information consumption like food:
1.  **Menu:** What is nutritious? (Allowed Sites)
2.  **Windows:** When do we eat? (Time Constraints)
3.  **Mindfulness:** Are we actually hungry? (Urge Surfing)

### Before vs. After

| Scenario | Without Planning | With Internet Diet Planner |
| :--- | :--- | :--- |
| **The Urge** | "I'm bored, let's check Twitter." | "I'm bored. I'll log this urge in the tracker." |
| **The Result** | 45 minutes of doomscrolling. | 2 minutes of reflection; urge passes. |
| **The Feeling** | Brain fog, guilt, distraction. | Clarity, control, intentionality. |
| **The Data** | Sold to advertisers. | Stored locally in `localStorage`. |

---

## 🛠 Features

| Feature | Description |
| :--- | :--- |
| **The Menu** | Curate a specific whitelist of sites that add value to your life. |
| **Time Windows** | Define specific contexts for browsing (e.g., "Sunday Morning", "After Dinner"). |
| **Urge Surfing** | A dedicated log to delay gratification. Type out your impulse instead of acting on it. |
| **Print Mode** | CSS-optimized print layout. Print your rules and stick them on your wall. |
| **Themes** | 8 Built-in themes (Light, Dark, Sepia, OLED, etc.) and Density controls. |
| **Offline First** | Uses `localStorage`. Persists data between sessions without a server. |

---

## 💾 Installation & Usage

This project is built as a **Single File Application (SFA)**.

1.  **Clone or Download**
    ```bash
    git clone https://github.com/Aliriyaj007/Internet-Diet-Planner.git
    ```
    *Or just download the `index.html` file directly.*

2.  **Run**
    Double-click `index.html`. That's it.

3.  **Backup**
    Go to **Settings > Data Management** to export your rules as a `.json` file.

---

## 🔒 Privacy & Architecture

This tool was built with a strict "User Sovereignty" philosophy.

*   **No Backend:** There is no server.
*   **No Analytics:** No Google Analytics, no tracking pixels.
*   **No External Calls:** The app makes zero network requests. It works in Airplane Mode.
*   **Data Ownership:** Your diet plan lives in your browser's `localStorage`.

If GitHub disappears tomorrow, this tool will still work on your machine forever.

---

## 🤝 Contributing

This project is feature-complete for its intended purpose, but improvements are welcome.

**Guidelines:**
1.  **Keep it Single-File:** CSS and JS must remain embedded in the HTML.
2.  **No Dependencies:** No React, no Tailwind, no jQuery. Vanilla only.
3.  **No Complexity:** Features should simplify the user's life, not complicate the UI.

Fork the repo, make your change, and submit a PR.

---

## 👤 Author

**Riyajul Ali**

*   **GitHub:** [@Aliriyaj007](https://github.com/Aliriyaj007)
*   **LinkedIn:** [Aliriyaj007](https://linkedin.com/in/Aliriyaj007)
*   **Email:** [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)

---

> *"The goal is not to disconnect from the internet, but to reconnect with your intent."*
