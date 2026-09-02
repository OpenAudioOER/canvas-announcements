# Canvas Announcement Builder

A lightweight web application designed for generating rich, responsive, and 100% Canvas LMS sanitizer-compliant announcements across multiple course shells.

Hosted live at: **[OpenAudioOER Canvas Announcement Builder](https://openaudiooer.github.io/canvas-announcements/)**

---

## 🌟 Key Features

- **Side-by-Side Live Preview:** Real-time visual preview alongside generated Canvas HTML code.
- **Canvas RCE Sanitizer Compliant:** Uses standard HTML5 inline styles and elements that Instructure Canvas will not strip or alter.
- **GitHub Image Asset Browser:** Dynamically browse, thumbnail preview, and select raw banner images hosted in this repository (`OpenAudioOER/canvas-announcements`).
- **Cohesive Color Palettes:** Select from Primary Blue, Alert Red, Warning Amber, Success Green, Purple Accent, or Neutral Slate themes.
- **Customizable Task & Due Dates Boxes:** Flexible group deadlines, customizable container borders, custom icons (`📝`, `🧠`, `📖`), and optional task notes/times.
- **16:9 Responsive Video Embed Wrapper:** Prevents YouTube, Vimeo, and Canvas Studio iframe videos from distorting or shrinking on mobile devices.
- **1-Click Copy:** Instant copy-to-clipboard button formatted for Canvas HTML view (`</>`).
- **LocalStorage Defaults:** Saves instructor profile details, default department, signature image, and GitHub settings across browser sessions.

---

## 📂 Repository Structure

```
├── index.html        # Main Builder Web Application (GitHub Pages)
├── README.md         # Documentation & Usage Guide
└── banners/          # Folder for course banner images (.png, .jpg, .svg)
```

---

## 🚀 How to Use

1. **Open the Tool:** Open [`index.html`](https://openaudiooer.github.io/canvas-announcements/) in your browser.
2. **Fill in Weekly Details:** Select a banner image, customize section titles, text, colors, video embeds, and due date lists.
3. **Copy HTML:** Click **"Copy Canvas HTML"** in the top right.
4. **Paste in Canvas:** In your Canvas course shell, create a new Announcement, click the **HTML Editor button (`</>`)**, and paste your code.
