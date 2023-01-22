git clone  "url"
    -- távoli repositorybol lokális mappába másolja a projektet
    -- nem kell inicializálni

cd 
  -- mappa választás

git add .
   -- stagehez hozzá adja az összes mappában lévő fájl
   -- ami addolva van azt lehet commitolni

git commit -m  "megjegyzés"
    -- verzió létrehozása megjegyzéssel

git status
    -- megmuataja a változtatásokat amik még nincsenek addolva és commitolva
    -- kiírja azt is ha minden naprakész

clear
    -- törli a terminál sorait

git branch "name"
   -- létrehozza az ágat az adott névvel

git branch 
    -- listázza az ágakat

git checkout 
    -- átvált az adott ágra

git push "url"
    -- feltölti a távoli repositoryba a lokális mappát commitokkal brachekkel
