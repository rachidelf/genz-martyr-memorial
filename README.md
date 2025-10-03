# 🇳🇵 The Voice of GenZ - Nepal Anti-Corruption Protest Memorial

[![Website](https://img.shields.io/badge/Website-Live-success)](https://thevoiceofgenz.globsoft.tech)
[![Martyrs](https://img.shields.io/badge/Confirmed-73%20Martyrs-red)]()
[![Contribute](https://img.shields.io/badge/PRs-Welcome-brightgreen)]()

> **In Loving Memory of the Brave Souls Who Sacrificed Their Lives for Justice**

This memorial website honors the martyrs of Nepal's GenZ Anti-Corruption Protest that took place on **Bhadra 24 & 25, 2082 B.S** (September 2025). These brave individuals, including children, gave their lives fighting against corruption and demanding justice.

🌐 **Live Website:** [thevoiceofgenz.globsoft.tech](https://thevoiceofgenz.globsoft.tech)

---

## 📊 Current Status

- **Confirmed Deaths:** 73 (as of October 3, 2025)
- **Total Records:** 73 martyrs documented
- **Missing Information:** Several martyrs still need photographs and verified details

---

## 🙏 How You Can Help

### **We Need Your Help!**

If you have information about:
- ✅ Additional martyrs not listed here
- 📸 Photographs of martyrs who don't have images
- ✏️ Corrections to existing information (name spelling, age, location)

**Please contribute by creating a Pull Request!**

---

## 🤝 Contributing Guide

### **Option 1: Add a New Martyr**

1. **Fork this repository**
   - Click the "Fork" button at the top right of this page

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
   cd REPO-NAME
   ```

3. **Edit `assets/js/martyrs.js`**
   
   Add a new entry to the `martyrsData` array:
   ```javascript
   const martyrsData = [
       // ... existing entries ...
       
       // Add your new entry here
       { 
           id: 74,                          // Next sequential number
           name: "Full Name in Nepali",     // Full name in Devanagari
           age: 25,                         // Age (number)
           place: "District Name",          // Place/District in Nepali
           image: "74.png",                 // Image filename (or "default.png" if no image)
           desc: "Bhadra 24"               // Date: "Bhadra 23", "Bhadra 24", or "Bhadra 25"
       },
   ];
   ```

4. **Add the photograph (if available)**
   - Place the image in `assets/img/sahid/` folder
   - Name it with the same ID number (e.g., `74.png`)
   - Recommended format: PNG or JPG
   - Recommended size: 300x300 pixels or similar ratio

5. **Commit your changes**
   ```bash
   git add assets/js/martyrs.js
   git add assets/img/sahid/74.png  # if you added an image
   git commit -m "Add martyr: [Name] from [Place]"
   ```

6. **Push to your fork**
   ```bash
   git push origin main
   ```

7. **Create a Pull Request**
   - Go to your fork on GitHub
   - Click "Contribute" → "Open Pull Request"
   - Describe what you added/changed
   - Submit!

---

### **Option 2: Add Missing Images**

If you have a photograph of a martyr who currently has no image:

1. **Identify the martyr** by checking `assets/js/martyrs.js`
   - Look for entries with generic images or placeholders

2. **Follow steps 1-2 from Option 1**

3. **Add the image**
   - Find the martyr's `id` number in `martyrs.js`
   - Name your image file with that ID (e.g., if id is 50, name it `50.png`)
   - Place it in `assets/img/sahid/` folder

4. **Update the entry** (if needed)
   ```javascript
   // Change from:
   { id: 50, name: "...", age: 25, place: "...", image: "default.png", desc: "..." },
   
   // To:
   { id: 50, name: "...", age: 25, place: "...", image: "50.png", desc: "..." },
   ```

5. **Follow steps 5-7 from Option 1**

---

### **Option 3: Correct Existing Information**

1. **Follow steps 1-2 from Option 1**

2. **Edit `assets/js/martyrs.js`**
   - Find the entry that needs correction
   - Update the information (name, age, place, etc.)

3. **Commit with a clear message**
   ```bash
   git add assets/js/martyrs.js
   git commit -m "Fix: Correct age/name/place for martyr ID [number]"
   ```

4. **Follow steps 6-7 from Option 1**

---

## 📝 Data Format Reference

```javascript
{
    id: 1,                           // Unique sequential number
    name: "नाम थर",                  // Full name in Nepali (Devanagari script)
    age: 21,                         // Age as number (not string)
    place: "जिल्ला/ठाउँ",             // District or place in Nepali
    image: "1.png",                  // Filename in assets/img/sahid/ folder
    desc: "Bhadra 24"               // Event date (Bhadra 23, 24, or 25)
}
```

### **Image Guidelines:**
- ✅ Format: PNG or JPG
- ✅ Size: Minimum 200x200px (square ratio preferred)
- ✅ Quality: Clear, respectful photographs
- ✅ Naming: Must match the `id` number (e.g., `73.png`)
- ✅ Location: `assets/img/sahid/` folder

---

## 🗂️ Project Structure

```
thevoiceofgenz/
├── assets/
│   ├── css/
│   │   └── styles.css          # Main stylesheet
│   ├── img/
│   │   ├── sahid/              # Martyr photographs (1.png, 2.png, etc.)
│   │   ├── about.webp          # About page image
│   │   ├── decoration1.png     # Decorative elements
│   │   ├── favicon.svg         # Site icon
│   │   └── WavingFlag.gif      # Animated Nepal flag
│   └── js/
│       ├── main.js             # Main JavaScript
│       └── martyrs.js          # ⭐ MARTYR DATA - EDIT THIS FILE
├── CNAME                        # Custom domain configuration
├── index.html                   # Main webpage
└── README.md                    # This file
```

---

## 🚨 Important Notes

- **As of October 3, 2025:** Only **73 deaths are officially confirmed**
- The actual number may be higher - we need community help to verify
- All information should be respectful and verified when possible
- This is a memorial - please maintain dignity and accuracy

---

## 💻 Development

### Local Development
```bash
# Clone the repository
git clone https://github.com/rajan-poudel/REPO-NAME.git

# Navigate to directory
cd REPO-NAME

# Open index.html in your browser
# Or use a local server:
python3 -m http.server 8000
# Then visit: http://localhost:8000
```

### Technologies Used
- Pure HTML5, CSS3, JavaScript
- No frameworks - lightweight and fast
- Responsive design for all devices
- Hosted on GitHub Pages

---

## 📞 Contact & Support

- **Maintainer:** [@rajan-poudel](https://github.com/rajan-poudel)
- **Issues:** [Create an issue](../../issues/new)
- **Website:** [thevoiceofgenz.globsoft.tech](https://thevoiceofgenz.globsoft.tech)

---

## 🕯️ In Memory

> **"Their sacrifice will not be forgotten. Their voices will echo through generations."**

This website serves as a digital memorial to ensure these brave souls are remembered forever. Every contribution helps preserve their legacy.

---

## 📜 License

This project is dedicated to the public domain. Use it freely to honor and remember the fallen heroes.

---

## 🙏 Acknowledgments

- All contributors who help maintain accurate records
- Families of the martyrs for their strength
- GenZ protesters who continue the fight for justice
- Everyone who keeps their memory alive

---

### ⭐ Star this repository to show your support and help spread awareness

**जय नेपाल! 🇳🇵**

---

*Last Updated: October 3, 2025*
