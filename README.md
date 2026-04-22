🚗 **România pe roți: ce tip de combustibil domină?**

<img width="674" height="375" alt="image" src="https://github.com/user-attachments/assets/300c13d5-04e9-454f-8f71-0c1a1ffdfc6e" />

Am analizat distribuția vehiculelor în funcție de tipul de combustibil, la nivel de județ, iar rezultatele sunt interesante 👇

🔍 **Ce ne arată datele?**

* **Benzina domină clar**, în special în județele mari (ex: București), cu volume semnificativ mai mari față de celelalte tipuri de combustibil.
* **Motorina rămâne puternică**, fiind a doua cea mai utilizată, mai ales în județele cu activitate economică intensă.
* **Vehiculele electrice și hibride** sunt încă într-o fază incipientă, dar încep să apară mai vizibil în județele dezvoltate.
* Combustibili alternativi precum **GNC, GPL sau GNL** au o prezență redusă și fragmentată.

📊 Dashboard-ul folosește o **scară logaritmică**, ceea ce ajută la compararea valorilor foarte diferite și evidențierea tiparelor la nivel național.

---

🧹 **Data Cleaning – un pas esențial în analiză**

Pentru a ajunge la aceste insight-uri, am acordat o atenție deosebită curățării datelor:

✔️ Am aplicat **`strip_chars`** pentru a elimina spațiile inutile din câmpuri
✔️ Am înlocuit valorile inconsistente din coloana *DESCRIERE_COMERCIALA* cu **"Unknown"**
✔️ Am gestionat valorile lipsă prin **replacement de nulls**
✔️ Am făcut **standardizare pe coloana MARCA**, unde aceleași branduri apăreau sub denumiri diferite (ex: variații de scriere, typo-uri etc.)

➡️ Fără acest proces, analiza ar fi fost fragmentată și mult mai puțin relevantă.

---

💡 **Concluzie:**
Piața auto din România este încă dominată de combustibili tradiționali, însă există semne clare de tranziție către alternative mai sustenabile. Evoluția acestui trend va depinde, cel mai probabil, de infrastructură și politici publice.

