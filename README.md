# Elbinmon Edavazhickal | Epic Adcraft (Vercel Ready)

Luxury 9:16 digital business card web app configured for seamless 1-click deployment on **Vercel** with centralized configuration.

---

## 🛠️ വിവരങ്ങൾ എങ്ങനെ എഡിറ്റ് ചെയ്യാം? (How to Edit Content)
ഭാവിയിൽ പേരോ ഫോൺ നമ്പറോ ലിങ്കുകളോ മാറ്റാൻ [config.js](file:///Users/elbinmon/Downloads/Antigravity/16/config.js) ഫയൽ മാത്രം തുറന്ന് മാറ്റിയാൽ മതിയാകും:

```javascript
const CARD_CONFIG = {
  firstName: "Elbinmon",
  lastName: "Edavazhickal",
  title: "CEO and Founder of Epic Adcraft",
  agencyHeadline: "Digital Marketing Agency in<br>Kerala | Epic Adcraft, Kochi",
  agencyUrl: "https://epicadcraft.com",
  phone: "+919876543210",
  whatsapp: "+919876543210",
  email: "contact@epicadcraft.com",
  instagramUrl: "https://instagram.com",
  linkedinUrl: "https://linkedin.com",
  photoFile: "profile.jpg"
};
```
> [!TIP]
> ഇവിടെ മാറ്റം വരുത്തിയാൽ വെബ് പേജിലെ വിവരങ്ങൾ, സോഷ്യൽ ലിങ്കുകൾ, ഡയറക്റ്റ് കോളിംഗ്, ഫോണിലേക്ക് സേവ് ആകുന്ന vCard കോൺടാക്റ്റ് വിവരങ്ങൾ എന്നിവയെല്ലാം ഓട്ടോമാറ്റിക്കായി അപ്ഡേറ്റ് ആകും!

---

## 🚀 വേഴ്സലിൽ (Vercel) എങ്ങനെ ഡിപ്ലോയ് ചെയ്യാം? (How to Deploy to Vercel)

### ഓപ്ഷൻ 1: GitHub & Vercel Dashboard (ഏറ്റവും എളുപ്പമുള്ള വഴി)
1. ഈ ഫോൾഡറിലെ ഫയലുകൾ നിങ്ങളുടെ GitHub അക്കൗണ്ടിലേക്ക് ഒരു പുതിയ റിപ്പോസിറ്ററിയായി (Repository) അപ്‌ലോഡ് ചെയ്യുക.
2. [vercel.com](https://vercel.com) ലോഗിൻ ചെയ്ത് **"Add New Project"** ക്ലിക്ക് ചെയ്യുക.
3. നിങ്ങളുടെ GitHub റിപ്പോസിറ്ററി സെലക്ട് ചെയ്ത് **"Deploy"** അമർത്തുക.
4. ഒരൊറ്റ മിനിറ്റിനുള്ളിൽ നിങ്ങളുടെ ലൈവ് ലിങ്ക് (ഉദാ: `elbinmon.vercel.app`) ലഭിക്കും!

> **ഭാവിയിൽ എഡിറ്റ് ചെയ്യാൻ:** GitHub-ൽ കയറി `config.js` എഡിറ്റ് ചെയ്താൽ മതി, Vercel തനിയെ പുതിയ മാറ്റങ്ങൾ ലൈവാക്കി തരും!

---

### ഓപ്ഷൻ 2: Vercel CLI (കമാൻഡ് ലൈൻ വഴി)
ടെർമിനലിൽ ഈ ഫോൾഡറിൽ വെച്ച് താഴെ പറയുന്ന കമാൻഡ് റൺ ചെയ്യുക:
```bash
npx vercel
```
തുടർന്ന് സ്ക്രീനിൽ വരുന്ന ചോദ്യങ്ങൾക്ക് `Enter` അമർത്തിയാൽ ഉടൻ തന്നെ ലൈവ് URL ലഭിക്കും.

---

## 📁 പ്രോജക്ട് ഫയലുകൾ (Project Files)
- [index.html](file:///Users/elbinmon/Downloads/Antigravity/16/index.html) – 9:16 ഡിജിറ്റൽ കാർഡ് വെബ് പേജ്
- [style.css](file:///Users/elbinmon/Downloads/Antigravity/16/style.css) – സിനിമാറ്റിക് ഗ്രേഡിയന്റും 9:16 ആസ്പെക്ട് റേഷ്യോ സ്റ്റൈലിംഗും
- [app.js](file:///Users/elbinmon/Downloads/Antigravity/16/app.js) – ഓട്ടോമാറ്റിക് UI പോപ്പുലേഷനും ഫോൺ കോൺടാക്റ്റ് സേവിംഗ് ലോജിക്കും
- [config.js](file:///Users/elbinmon/Downloads/Antigravity/16/config.js) – വിവരങ്ങൾ എഡിറ്റ് ചെയ്യാനുള്ള പ്രധാന ഫയൽ
- [favicon.png](file:///Users/elbinmon/Downloads/Antigravity/16/favicon.png) – എപ്പിക് ആഡ്ക്രാഫ്റ്റ് ഒഫീഷ്യൽ ടാബ് ലോഗോ
- [profile.jpg](file:///Users/elbinmon/Downloads/Antigravity/16/profile.jpg) – ഹൈ-റെസലൂഷൻ പോർട്രെയിറ്റ് ചിത്രം
- [vercel.json](file:///Users/elbinmon/Downloads/Antigravity/16/vercel.json) – വേഴ്സൽ ഒപ്റ്റിമൈസേഷൻ കോൺഫിഗറേഷൻ
