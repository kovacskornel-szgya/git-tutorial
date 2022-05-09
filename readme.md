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
git status #jelenlegi munkafolyamat állapota
git remote -v # ellenőrizzük a távoli repokat
git remote add origin https://github.com/kovacskornel-szgya/git-tutorial.git # origin néven hozzáadja a címben lévő repot
git remote remove origin # origin nevű távolio repo eltávolítása
git push -u origin master #új branch esetén használjuk
git push #az aktuális branch-et tölti fel 
