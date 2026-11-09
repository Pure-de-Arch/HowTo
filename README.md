# HowTo
Hogyan készítsek új iso-t?

1. Telepíts egy Arch Linuxot natívan vagy virtuálsi gépben.. 
2. Frissítsd a csomagkezelőt: sudo pacman -Syu
3. Telepítsd az archiso csomagot: sudo pacman -S archiso
4. A Pure De Arch szervezetben keresd meg a számodra szinpatikus repositorit.
5. Töltsd le: git clone megfeleéő repo neve 
 pl. git clone https://github.com/Pure-de-Arch/ArchTrinity.git
6. Lépj be a letöltött könyvtárba: cd "könyvtárnév"
 pl: cd  cd ArchTrinity/
7. Lépj be az installation-script mappába:  cd installation-scripts/
8. Futtasd az iso készítéséhez a követkző parancsot: ./30-build-the-iso-the-first-time.sh 

GYIK.
 Mikor készítsek új iso-t?
  Amikor megjelenik egy új kiadás pl GNOME, akkor érdemes új iso-t készíteni.
