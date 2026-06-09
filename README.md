# සිංහල ලිපිගොනු (Legacy Sinhala Fonts)

මෙම ගබඩාවේ (repository) අඩංගු වන්නේ **සිංහල ලිපිගොනු** (Legacy/Non-Unicode Sinhala Fonts) එකතුවකි. මෙම අකුරු මුද්‍රණ 798ක් පමණ මෙහි ඇතුළත් වේ.

---

## ⚠️ වැදගත් දැනුම්දීමක්

මෙම අකුරු මුද්‍රණ **යුනිකේත (Unicode) සමග අනුකූල නොවේ**. ඒවා **ලිගසි (Legacy)** හෙවත් **පැරණි ක්‍රමයේ** සිංහල අකුරු මුද්‍රණ වේ.

### Legacy Fonts යනු කුමක්ද?

Legacy සිංහල අකුරු මුද්‍රණ යනු යුනිකේත ප්‍රමිතියට පෙර නිර්මාණය කරන ලද අකුරු මුද්‍රණ වේ. මේවා:
- සම්මත යුනිකේත කේතීකරණය භාවිතා නොකරයි
- එක් එක් අකුරු මුද්‍රණයටම ආවේණික වූ අකුරු සිතියම්ගත කිරීමක් (character mapping) ඇත
- සාමාන්‍යයෙන් **විජේරත්න හෝඩිය** (Wijerathna Hodiya) වැනි කේතීකරණ ක්‍රම භාවිතා කරයි
- නවීන යුනිකේත-අනුකූල යෙදුම්වල මේවා නිවැරදිව පෙන්වීමට විශේෂ පරිවර්තක (converters) අවශ්‍ය වේ

---

## 🎯 මෙම අකුරු භාවිතා කළ හැක්කේ කෙසේද?

### 1. පැරණි මෘදුකාංගවල
- **Adobe PageMaker**, **Adobe Photoshop (පැරණි සංස්කරණ)**, **CorelDraw** වැනි පැරණි මෘදුකාංග
- මෙම මෘදුකාංගවල Font dropdown එකෙන් මෙම අකුරු තෝරා ගත හැක

### 2. Font Converter භාවිතයෙන්
යුනිකේත බවට පරිවර්තනය කිරීමට පහත මෙවලම් භාවිතා කරන්න:
- **Sinhala Unicode Converter** (Online)
- **Google Input Tools** - Sinhala
- **Sinhala Typing Tools**

### 3. Legacy Font Input Methods
- **Singlish** / **Sinhala Phonetic** ටයිප් කිරීමේ ක්‍රම
- **Wijerathna Keyboard Layout**
- **FM (FM Abhaya, FM Basuru, FM Derana)** පවුලේ අකුරු සඳහා විශේ‍ෂ යතුරු පුවරු පිරිසැලසුම්

---

## 📂 අකුරු මුද්‍රණ වර්ගීකරණය

මෙම එකතුවේ ඇති ප්‍රධාන අකුරු මුද්‍රණ පවුල්:

| පවුල | උදාහරණ | භාවිතය |
|--------|---------|---------|
| **FM පවුල** | fm-abhaya, fm-basuru, fm-derana, fm-gemunu, fm-samantha | පුවත්පත්, පොත් |
| **DL පවුල** | dl-araliya, dl-manel, dl-ridhma, dl-lihini, dl-nelum | සඟරා, වාණිජ මුද්‍රණ |
| **NPW පවුල** | npw-araliya, npw-manel, npw-ridhma, npw-sawana | පොත්, ලේඛන |
| **AMS පවුල** | amsajith, amsbindu, amsmanahara, amsshilpa | විවිධ |
| **Sara පවුල** | sara-baron, sara-chithra, sara-siri, sara-mahee | අලංකාර මුද්‍රණ |
| **Apex පවුල** | apex001-apex050 | ඩිජිටල් මුද්‍රණ |
| **Ridi පවුල** | ridi1-ridi19 | පැරණි පද්ධති |
| **Tharu Digital පවුල** | TharuDigitalMahasen, TharuDigitalMaya, TharuDigitalNikini | නවීන මුද්‍රණ |
| **Wije පවුල** | wije1-wije8 | විජේරත්න හෝඩිය පාදක කරගත් |
| **අනෙකුත්** | 0kdmanel, 4u-nisansala, aa-anurada, Aloka, Aragalaya, WARNA | විශේෂිත |

---

## 💻 ස්ථාපනය කරන ආකාරය

### Windows:
1. `.ttf` ගොනුවක් මත Right-click කරන්න
2. **Install** තෝරන්න
3. හෝ `C:\Windows\Fonts\` ෆෝල්ඩරයට ගොනු පිටපත් කරන්න

### macOS:
1. Font Book යෙදුම විවෘත කරන්න
2. File > Add Fonts වෙත ගොස් `.ttf` ගොනු තෝරන්න
3. හෝ `~/Library/Fonts/` ෆෝල්ඩරයට ගොනු පිටපත් කරන්න

### Linux:
```bash
# සියලුම fonts පද්ධති font ඩිරෙක්ටරියට පිටපත් කරන්න
mkdir -p ~/.fonts
cp *.ttf ~/.fonts/
fc-cache -fv
```

---

## 🔄 යුනිකේත බවට පරිවර්තනය

මෙම ලිගසි අකුරු වලින් ලියැවුණු පෙළ යුනිකේත බවට පරිවර්තනය කිරීමට:

1. **Online Converters:** Google සිංහල යුනිකේත පරිවර්තක
2. **Sinhala Unicode Converter** යෙදුම්
3. **FM Font Converter** - FM පවුලේ අකුරු සඳහා

---

## 📜 බලපත්‍රය (License)

මෙම අකුරු මුද්‍රණ එකතුව විවිධ නිර්මාපකයින් විසින් නිර්මාණය කරන ලද ඒවා වේ. එක් එක් අකුරු මුද්‍රණයට අදාළ බලපත්‍ර කොන්දේසි පිළිපැදීමට වග බලා ගන්න.

---

## 👨‍💻 ප්‍රධාන නිර්මාපකයින් සහ ආයතන

- **FM Fonts** - FM පවුලේ අකුරු
- **DL Fonts** - DL පවුලේ අකුරු
- **NPW Fonts** - NPW පවුලේ අකුරු
- **AMS Fonts** - AMS පවුලේ අකුරු
- **Sara Fonts** - Sara පවුලේ අකුරු
- **Tharu Digital** - Tharu Digital පවුලේ අකුරු
- **විවිධ ස්වාධීන නිර්මාපකයින්** - අනෙකුත් අකුරු

---

## 🤝 දායකත්වය

නව අකුරු මුද්‍රණ එක් කිරීමට හෝ දෝෂ වාර්තා කිරීමට:
1. Fork කරන්න
2. වෙනස්කම් සිදු කරන්න
3. Pull Request එකක් විවෘත කරන්න

---

**සටහන:** මෙම අකුරු මුද්‍රණ බොහොමයක් 2000-2015 කාලය තුළ නිර්මාණය කරන ලද අතර, යුනිකේත ප්‍රමිතිය සිංහල බසට හඳුන්වා දීමට පෙර සිංහල ඩිජිටල් මුද්‍රණ ක්ෂේත්‍රයේ වැදගත් කාර්යභාරයක් ඉටු කළේය. යුනිකේත සිංහල දැන් පුළුල් ලෙස භාවිත වුවද, බොහෝ පැරණි ලේඛන, පොත්පත් සහ මුද්‍රණ කටයුතු සඳහා මෙම අකුරු තවමත් අවශ්‍ය වේ.