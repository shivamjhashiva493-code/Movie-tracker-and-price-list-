# CinePrice - Cinema Ticket Comparison & Auto-Tracker Portal
(CONNPLEX, PVR, Cinepolis, BJP Multiplex - Muzaffarpur)

यह एक संपूर्ण, 100% फ्री ऑटोमेशन प्रोजेक्ट है जो बुकमायशो व सिनेमाघरों से टिकट दरों को ट्रैक और कम्पेयर करता है।

---

## 🚀 2 मिनट में वेबसाइट लाइव करने का तरीका:

### स्टेप 1: GitHub पर रिपॉजिटरी बनाएँ
1. [github.com](https://github.com) पर जाएं और लॉगिन करें।
2. **New Repository** पर क्लिक करें।
3. Repository का नाम रखें: `cinema-price-tracker`
4. इसे **Public** रखें और **Create Repository** दबाएं।

### स्टेप 2: फाइलें अपलोड करें
1. डाउनलोड किए गए ZIP को अनजिप करें।
2. अपनी GitHub रिपॉजिटरी में **Upload files** पर क्लिक करें।
3. इन सभी फाइलों को अपलोड करें:
   - `index.html`
   - `scraper.py`
   - `.github/workflows/update_rates.yml`
   - `live_movie_rates.json`
   - `README.md`
4. नीचे **Commit changes** दबाएं।

### स्टेप 3: GitHub Pages ऑन करें (वेबसाइट चालू)
1. अपनी रिपॉजिटरी की **Settings** ➔ **Pages** में जाएं।
2. **Branch** में `main` सेलेक्ट करें और **Save** दबाएं।
3. 60 सेकंड में आपकी लाइव वेबसाइट का लिंक ऊपर दिखेगा:
   👉 `https://<your-username>.github.io/cinema-price-tracker/`

---

## ⚡ 24/7 ऑटोमैटिक अपडेट कैसे काम करता है?
- **GitHub Actions** हर दिन सुबह 6:00 बजे और दोपहर 12:00 बजे `scraper.py` चलाता है।
- नया टिकट रेट `live_movie_rates.json` में सेव होता है।
- आपकी वेबसाइट बिना किसी रिफ्रेश या सर्वर के हमेशा ताज़ा रेट दिखाती है।
