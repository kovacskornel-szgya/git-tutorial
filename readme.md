Git segédlet
VSC-ben terminál nyitása, git bash #ha nincs, akkor git scm telepítése
mkdir git-tutorial #munkakönyvtár létrhozása (make directory)
cd git-tutorial #mappa választás
echo "git segédlet" >> readm.md #"git segédlet" szöveg belírása a readme.md fájlba
ls #list mappa listázása
git init #könyvtár inicializálása git mappává
git config --global --list #a globális beállítások listázása
git add readme.md #readme.md változtatásainak staging-elése
git commit -m "first commit" #összes staging commitolása "first commit" üzenettel