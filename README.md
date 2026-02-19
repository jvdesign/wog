Ez egy professzionális, látványos és informatív `README.md` tervezet a **Wrath of Gedeon (WogTD)** játékoz. Mivel a forráskód nem publikus, a dokumentáció a játékélményre, a technikai különlegességekre és a telepítésre fókuszál.

---

# Wrath of Gedeon (WogTD)

![Version](https://img.shields.io/badge/version-0.5.1--pre--alpha-orange)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Engine](https://img.shields.io/badge/engine-Pygame--ce%20%7C%20ModernGL-green)

A **Wrath of Gedeon** egy új generációs, 2D-s felülnézetes Tower Defense játék, amely az ARPG-k mélységét ötvözi a klasszikus stratégiai hadviseléssel. Ebben a világban nemcsak statikus védműveket építesz, hanem egy hadúr stratégiai zsenialitásával menedzeled a seregedet, fejleszted a képességeidet és gyűjtöd a mágikus zsákmányt.

---

## 🌟 Kiemelt Jellemzők

### Adatvezérelt Toronyrendszer
Minden torony egyedi karakterrel bír. A fejlesztési útvonalak nemcsak a statisztikákat növelik, hanem alapjaiban változtatják meg a tornyok működését. 
*   **Legénység (Crew):** Rendelj egységeket a tornyokhoz, akik tapasztalatot (XP) gyűjtenek és saját képességfával rendelkeznek.
*   **Testreszabhatóság:** Több tucat toronyfajta az íjászoktól a mágikus rezonátorokig.

### ARPG-stílusú Loot & Affix Rendszer
A legyőzött ellenségek kincseket hagynak maguk után. A tárgyrendszert a klasszikus ARPG-k (pl. Diablo) ihlették:
*   **Véletlenszerű Affixek:** Minden tárgy egyedi elő- és utótagokkal rendelkezhet, amelyek drasztikusan módosítják a torony vagy a játékos statisztikáit.
*   **Ritkasági szintek:** A Common tárgyaktól egészen az Ancient ereklyékig.

### Komplex Képességfa (Skill Tree)
Fejleszd saját stratégiai repertoárodat egy hatalmas, többágú képességfán keresztül:
*   **Passzív bónuszok:** Olcsóbb építkezés, nagyobb hatótáv vagy kamat a vagyonod után.
*   **Aktív képességek:** Pusztító meteoreső, globális fagyasztás vagy akár maga Gedeon megidézése a harcmezőre.

### Dinamikus Egységek & Kampány
*   **Szövetséges Egységek:** Irányíts mozgó csapatokat (íjászok, katapultok), adj nekik parancsokat, vagy állíts be őrjáratokat.
*   **Élő Világ:** Eseményvezérelt párbeszédrendszer és egy teljes kampánymód vár egyedi pályákkal és történetelemekkel.

---

## 🚀 Telepítés és Játék

Mivel a játék zárt forráskódú, a futtatható verziót a **Releases** menüpont alatt találod meg.

1.  Látogass el a [**Releases**](https://github.com/jvdesign/wog/releases/) oldalra.
2.  Töltsd le a legfrissebb `WoG.zip` csomagot.
3.  Csomagold ki egy tetszőleges mappába.
4.  Indítsd el a **`WoG.exe`** fájlt.

---

## 💻 Technikai Háttér

A játék a legmodernebb Python-alapú technológiákat használja a maximális teljesítmény érdekében:
*   **ModernGL Renderer:** GPU-gyorsított renderelés shaderekkel, valós idejű fényeffektekkel, bloom és torzítási (distortion) effektekkel.
*   **Spatial Grid Partitioning:** Optimalizált ütközésvizsgálat és célpontkeresés, amely lehetővé teszi több száz egység egyidejű kezelését.
*   **Data-Driven Architecture:** Szinte minden játékelem (hullámok, tornyok, tárgyak) JSON alapú, így a játék könnyen bővíthető és moddolható.

---

## 🎮 Irányítás

| Gomb | Funkció |
| :--- | :--- |
| **W, A, S, D / Nyilak** | Kamera mozgatása |
| **Egérgörgő** | Zoom (Közelítés/Távolítás) |
| **B** | Építési menü |
| **I** | Inventory (Felszerelés) |
| **T** | Képességfa |
| **V** | Kereskedő (Vendor) |
| **F** | Javító mód |
| **Esc** | Szünet / Menü |
| **Space** | Következő hullám indítása |

---

## 🛠️ Rendszerkövetelmények

*   **Op. rendszer:** Windows 10/11 (64-bit)
*   **Videókártya:** OpenGL 3.3+ támogatással rendelkező GPU
*   **Memória:** 4 GB RAM
*   **Tárhely:** kb. 200 MB szabad hely

---

## 📌 Megjegyzések

*   A játék jelenleg **Pre-Alpha (0.5.2)** fázisban van. Hibák előfordulhatnak.
*   **Felhő alapú mentés:** Jelentkezz be saját fiókoddal, hogy elmentsd az elért eredményeidet és az unlockolt achievementeket.
*   **Visszajelzés:** Ha hibát találsz vagy javaslatod van, kérlek jelezd a profilomon található elérhetőségeken!

---

© 2026 Valentin Jankai. Minden jog fenntartva.
[Hivatalos Weboldal & Encyclopedia](https://valentinjankai.com/apps/wog/)
