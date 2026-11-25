# SUBDISPERSION

Modern basszus- és lead-szintetizátor plugin a GRASSPHONIC-tól: fázis-warpolt oszcillátor,
szaturáció, all-pass diszperziós lánc, dupla szűrő, két LFO, ciklikus burkoló, 8 soros
modulációs mátrix, chorus, phaser, delay, reverb és tape.

Ez a repó csak a kész telepítőket tartalmazza. **Letöltés: [Releases](../../releases/latest)**

## Telepítők

| | macOS | Windows |
|---|---|---|
| Fájl | `Subdispersion-<verzió>-macOS.pkg` | `Subdispersion-<verzió>-Windows-Setup.exe` |
| Formátumok | VST3, CLAP, AU (Audio Unit) | VST3, CLAP |
| Gép | macOS 11 vagy újabb, Apple Silicon és Intel | Windows 10/11, 64 bit |
| Hova települ | `/Library/Audio/Plug-Ins/VST3`, `/CLAP`, `/Components` | `C:\Program Files\Common Files\VST3`, `\CLAP` |

Az AU-t a Logic Pro, a GarageBand és a MainStage használja, a VST3-at például az Ableton Live,
a Cubase, az FL Studio és a Studio One, a CLAP-ot a Bitwig és a Reaper. A formátumok a
telepítőben egyenként kiválaszthatók.

A 132 gyári preset (Bass, Lead, Pad, Keys, Pluck, Fx) a pluginba van építve, a szerkesztő ▾
menüjében kategóriákba rendezve azonnal elérhető. A saját presetek a User kategóriába kerülnek.

Telepítés után indítsd újra a DAW-ot, vagy futtass benne plugin-keresést (rescan). A plugin
az *Instrument* kategóriában jelenik meg, gyártóként *GRASSPHONIC*.

## Figyelmeztetés az első megnyitáskor

A telepítők nincsenek fizetős tanúsítvánnyal aláírva, ezért a rendszer az első megnyitáskor
figyelmeztet:

- **macOS** („nem ellenőrizhető fejlesztő”): jobb klikk a `.pkg`-n → Megnyitás → Megnyitás,
  vagy Rendszerbeállítások → Adatvédelem és biztonság → „Megnyitás mégis”.
- **Windows** (SmartScreen, „A Windows megvédte a számítógépet”): „További információ” →
  „Futtatás mindenképp”. Ha hiányzik a WebView2 Runtime, a telepítő jelzi, és felajánlja a
  letöltési oldalt.

## Eltávolítás

- **macOS:** töröld a `Subdispersion.vst3`, `Subdispersion.clap` és `Subdispersion.component`
  bundle-t a fenti mappákból.
- **Windows:** Gépház → Alkalmazások (vagy Vezérlőpult → Programok). A saját presetek megmaradnak.

---

**English:** SUBDISPERSION is a bass/lead synthesizer plugin by GRASSPHONIC. This repository only
hosts the installers: see [Releases](../../releases/latest). macOS: VST3, CLAP and AU (macOS 11+,
Apple Silicon and Intel). Windows: VST3 and CLAP (64-bit). 132 factory presets are built in. The
installers are not signed with a paid certificate, so macOS and Windows show a warning the first
time: on macOS right-click the `.pkg` → Open; on Windows choose "More info" → "Run anyway".
