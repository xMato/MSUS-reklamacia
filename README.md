# MSUS Reklamacia

Vypracovali: Matej Lovász, Martin Martiška, Tomáš Pudiš, Maté Habán

Úlohou projektu bolo namodelovanie systému pre vytvárenie objednávok a reklamácií. 
Namodelované procesy:
* Objednávka
* Tovar
* Zákazník
* Obchod
* Reklamácia

Jednotlivé procesy predstavujú tabuľky v databáze.

Vytvorili sme systém, v ktorom je najprv potrebné vytvoriť tovar,obchod a zakaznika. Tieto tri triedy sú následne spojené v objednávke pomocou ich ID-éčok. Pri vytvorenej objednávke je zákazník schopný podať reklamáciu, ale nie je schopný ju ukončiť. Reklamácia je ukončená systémom až ked celý process reklamácie prebehne.
V projekte sme sa nesnažili o vytvorenie úplného procesu reklamácie, ale len o systém na spracovávanie informácií o reklamácii a o priebehu konkrétnej reklamácie.
