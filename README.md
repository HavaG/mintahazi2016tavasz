# Mintafeladat

**A k�vetkez� feladatok gyakorlaton oldjuk meg**

Egy c�gn�l sz�ks�g lenne egy eszk�z nyilv�ntart�ra, azaz
hogy melyik munkat�rsn�l melyik c�ges eszk�z van. Ehhez
a munkat�rsakat is kezelni kell tudni, meg az eszk�z�ket is,
meg az �sszerendez�st is.

**Fenntart�sokkal kezelj�k az ide beker�l� k�dot, elg�pel�sek, hib�k �s b�rmi egy�b huncuts�g is lehet benne.**

# A f�l�v feladatai

## 1. Feladat

Egy elk�pzelt megrendel� feladat�t specifik�ljuk:

- Legal�bb 2 entit�s t�pus (legal�bb egyikn�l az �sszes CRUD funkci� megval�s�t�sa)
- Legal�bb 3 n�zet (mindegyikhez mockup)
- R�szletes specifik�ci� kell

**Amit le kell adni:**

- specifik�ci� pdfben (Mi az oldal c�lja, az egyes oldalon milyen adatok jelennek meg, milyen kapcsolat van az oldalak k�z�tt) 
- mockup vagy a specifik�ci�ban, vagy k�pk�nt (pl. http://www.balsamiq.com/builds/mockups-web-demo/)

## 2. Feladat

Hozzon l�tre egy express alkalmaz�st a feladat megold�s�hoz, k�sz�tse el a mockup alapj�n a statikus oldalakat, ezeket tegye bej�rhat�v� linkeken kereszt�l.

## 3. Feladat

Hozza l�tre a sz�ks�ges middleware struktur�t �s routingot, commentek form�j�ban dokument�lja az egyes middlewarek m�k�d�s�t. Hozza l�tre a sz�ks�ges model �s seg�doszt�lyokat. A model oszt�lyok eset�ben az egyes f�ggv�nyek mockolt objektumokat adjanak vissza.

*A middlewarek implement�l�s�t ezen a ponton c�lszer� elkezdeni, az �sszes middlewert a 6. Feladat lead�s�nak idej�re kell elk�sz�teni!*

## 4. Feladat

M�dos�tsa a megl�v� n�zeteket �gy, hogy ne egyszer� HTML-t, hanem EJS-t haszn�ljanak. A n�zetek a middlewaret�l kapott adatokat jelen�ts�k meg.

## 5. Feladat

Hozza l�tre MongoDB seg�ts�g�vel a megfelel� adatstruktur�kat, haszn�lja ezeket a model oszt�lyaiban.

## 6. Feladat

Implement�lja az �sszes middlewaret, **ezen a ponton a teljes alkalmaz�snak m�k�d�k�pesnek kell lennie!**

## 7. Feladat

K�sz�tsen 2 szabadon v�lasztott, legal�bb egy el�gaz�st tartalmaz� middlewarehez teszteket. Ennek a 2 middlewarenek teljesen teszteltnek kell lennie.