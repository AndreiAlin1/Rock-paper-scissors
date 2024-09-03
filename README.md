## Descrierea Proiectului
Acest proiect este o implementare simplă a jocului clasic "Piatra, Hârtie, Foarfecă" utilizând JavaScript, HTML și CSS. Scopul proiectului este de a oferi o experiență interactivă prin intermediul browser-ului, permițând jucătorului să se confrunte cu un calculator într-un joc de "Piatra, Hârtie, Foarfecă".

-**Caracteristici**:
Interacțiune User-Computer: Utilizatorul poate selecta una dintre cele trei mișcări (piatră, hârtie, foarfecă), iar calculatorul va selecta aleatoriu o mișcare ca răspuns.
Salvarea Scorului: Scorul curent al utilizatorului (numărul de victorii, înfrângeri și egaluri) este stocat local în browser folosind localStorage. Acest lucru permite păstrarea scorului chiar și după ce pagina este reîncărcată.
Afișarea Rezultatelor și Mișcărilor: Rezultatul fiecărui joc este afișat pe ecran, împreună cu mișcarea jucătorului și mișcarea aleasă de calculator.
Actualizarea dinamică a scorului: După fiecare rundă, scorul este actualizat și afișat pe ecran.

## Cum funcționează
Inițializarea Scorului: La încărcarea paginii, scorul este preluat din localStorage. Dacă nu există un scor salvat, este inițializat la zero pentru victorii, înfrângeri și egaluri.

-**Funcția playGame(playerMove)**:
Primește ca parametru mișcarea jucătorului.

Generează o mișcare aleatorie pentru calculator folosind funcția pickComputerMove().
Compară mișcarea jucătorului cu cea a calculatorului și determină rezultatul jocului (victorie, înfrângere sau egal).
Actualizează scorul în funcție de rezultat și îl salvează în localStorage.
Actualizează elementele din HTML pentru a afișa rezultatul jocului și scorul actualizat.

-**Funcția updateScoreElement()**:
Actualizează elementul HTML corespunzător pentru a afișa scorul curent al utilizatorului.

-**Funcția pickComputerMove()**:
Generează o mișcare aleatorie pentru calculator bazată pe o valoare aleatoare (piatră, hârtie sau foarfecă).

![image](https://github.com/user-attachments/assets/2348d553-0ece-4aa0-b19c-e524f3ca1c3d)


![image](https://github.com/user-attachments/assets/9df8cd8b-808a-42f1-a4ef-032881fd7cc9)


-**Prin apasarea butoul "Reset Score" -> scorul se va reseta la 0.

![image](https://github.com/user-attachments/assets/ccc2226f-f3c0-4791-887d-46a1bc7fa4ce)
