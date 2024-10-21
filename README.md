# Raport Proiect Tic-Tac-Toe

## Introducere
Proiectul Tic-Tac-Toe a fost realizat pentru a implementa jocul clasic de pe tabla 3x3 utilizând limbajul de programare C++. Scopul principal a fost de a dezvolta o aplicație care să permită interacțiunea între doi jucători, respectând regulile standard ale jocului.

## Obiective
- Implementarea unei table de joc (3x3) care să permită plasarea markerilor (X și O).
- Crearea unei logici de joc pentru a verifica dacă un jucător a câștigat sau dacă jocul s-a încheiat cu un egal.
- Definirea pentru fiecare structură de date care reprezintă date de joc a următoarelor:
  - constructor implicit
  - constructor de copiere
  - constructor cu parametri
  - operator de copiere
  - operator de comparație
  - operator de citire
  - operator de afișare
- Utilizarea conceptelor de programare orientată pe obiect pentru a organiza codul în clase și a promova reutilizarea acestuia.

## Structura Proiectului
Proiectul este organizat în următoarele fișiere:

- **main.cpp**: Punctul de intrare al aplicației, unde se inițiază jocul.
- **board.hpp / board.cpp**: Conține definiția și implementarea clasei `Board`, care gestionează tabla de joc și logica de plasare a markerilor.
- **game.hpp / game.cpp**: Conține definiția și implementarea clasei `Game`, care se ocupă cu fluxul jocului și interacțiunea dintre jucători.
- **Makefile**: Script pentru a compila proiectul cu ușurință.

## Detalii Tehnice
1. **Constructori și Operatori**:
   - Am implementat constructori impliciți, de copiere și cu parametri pentru clasa `Board`.
   - Suprascrierea operatorului de asignare (`operator=`), operatorului de comparare (`operator==`), și operatorilor de input/output (`operator>>`, `operator<<`).
  
2. **Logica Jocului**:
   - Tabla de joc este reprezentată printr-o matrice 2D de caractere.
   - Jucătorii introduc sloturile în care doresc să plaseze markerii lor.
   - Jocul verifică dacă un jucător a câștigat după fiecare mutare și anunță jucătorul câștigător sau dacă jocul s-a încheiat cu un egal.

## Concluzii
Acest proiect a reprezentat o oportunitate excelentă de a aplica conceptele de programare orientată pe obiect și de a învăța despre gestionarea input-ului și output-ului în C++. Am reușit să dezvolt un joc simplu, dar funcțional, care poate fi extins cu ușurință pentru a adăuga caracteristici suplimentare în viitor, cum ar fi un mod de joc împotriva unui AI.

## Pașii Următori
- Posibilitatea de a adăuga un mod de joc single-player.
- Implementarea unor caracteristici vizuale mai atractive prin utilizarea unei biblioteci grafice.
- Optimizarea codului și adăugarea de teste unitare pentru a verifica corectitudinea funcționalităților.
