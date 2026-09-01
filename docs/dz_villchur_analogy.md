# DZ – ICE analogija: Uždaro ciklo pneumatinės variklio logika

Ši analogija skirta padėti suprasti **„Dynamic Zero“ (DZ)** architektūrą tiems, kurie yra susipažinę su vidaus degimo varikliais (ICE) ar bendra mechanikos inžinerija.

**Pagrindinė idėja:** DZ nėra „dėžė su garsiakalbiu“. DZ yra **vidinis pneumatinis ciklas**, kuris nėra atvira sistema (jis neturi „išmetimo“). Energija cirkuliuoja uždaroje grandinėje, o jo komponentai atlieka funkcijas, analogiškas variklio ciklui.

---

## 1. Komponentų analogija (ICE ↔ DZ)

| ICE (Vidaus degimo variklis) | DZ (Vidaus ciklo variklis) | Fizinė funkcija |
| :--- | :--- | :--- |
| **1. Įsiurbimas** | **1. DMI (Dynamic Mass Interchanger)** | Energijos (oro/mišinio/slėgio) surinkimas į uždarą erdvę už diafragmos. |
| **2. Suspaudimas** | **2. DM Impulser** | Energijos suspaudimas ir pagreitinimas per siaurą inercinį kanalą. |
| **3. Darbas (Degimas)** | **3. DM Container** | Energijos atidavimas į darbinį ciklą. Laiko fazių (+0 / -0) simetriją. |
| **4. Išmetimas** | **❌ NĖRA** | DZ neturi atskiros išmetimo angos (nėra „bass-reflex“). „Išmetimo“ energija yra surenkama ir atiduodama atgal per reversyvią sąveiką tarp **DMI ir garsiakalbio galinės pusės**. |
| **→ EGR (Recirkuliacija)** | **4. DM Compensator** | **Fazės stabilizatorius**. Sugeria disbalansą ir užtikrina, kad energija grįžtų į ciklą, o ne būtų prarasta. |

---

## 2. Ką reiškia „Nėra išmetimo“ ir „Reversyvi DMI turbina“?

Tradicinis ICE veikia kaip **atviro ciklo** sistema: energija įvedama (degalai), atliekamas darbas, o likutinė energija **išmetama** kaip šiluma ir dujos. Dėl to ICE turi nuostolių (entropija didėja).

DZ atveju nėra atskiro „išmetimo kanalo“, nes **pati DMI (garsiakalbio galinė pusė) atlieka reversyvios turbinos funkciją**:

- Kai diafragma juda **atgal**, ji **surenka** energiją („įsiurbia“).
- Kai diafragma juda **pirmyn**, ji **atiduoda** tą pačią energiją atgal į ciklą.

Tai nėra „išmetimas“ – tai yra **energijos mainų taškas**, kuris veikia abiem kryptimis.

---

## 3. Reversyvumo skirtumas: Vienkryptis vs. Reversyvus

Tai yra pats esmingiausias skirtumas tarp ICE ir DZ:

| ICE | DZ |
| :--- | :--- |
| **Vienkryptis (vienakryptis)** srautas. Energija įeina, išsiplečia ir išmetama. Ji niekada negrįžta į šaltinį. | **Reversyvus (dvikryptis)** srautas. Energija juda pirmyn ir atgal, keisdama kryptį kas pusę ciklo (+0 / -0). |
| Sukamasis judesys (alkūninis velenas). | Grįžtamasis judesys (oro masės svyravimas). |
| Atviras termodinaminis ciklas (energija prarandama). | Uždaras regeneracinis ciklas (energija išlaikoma ir pakartotinai panaudojama). |

---

## 4. „Degimo kampas“ = Turnover Point (+0 / -0)

Abiejose sistemose svarbiausias parametras yra **laikas / fazė**.

| ICE | DZ |
| :--- | :--- |
| **Degimo kampas:** Kiek laipsnių prieš VMT (viršutinį mirusį tašką) uždegamas mišinys, kad būtų pasiektas maksimalus slėgis tinkamu momentu. | **Dalta Signum Point (+0 / -0):** Momentas, kai diafragma keičia kryptį. Kuo tiksliau šis taškas atpažįstamas, tuo tiksliau „pneumatinis uždegimas“ (Impulser) gali grąžinti energiją. |
| **Per anksti:** Detonacija, turbulencija. | **Per anksti:** Pneumatinė turbulencija, fazės praradimas. |
| **Per vėlai:** Galios praradimas, neefektyvus darbas. | **Per vėlai:** Prarandamas Reciprocal Inverted Push efektas. |
| **Optimalus kampas:** Maksimalus sukimo momentas, švarus darbas. | **Optimalus (+0 / -0):** Maksimalus fazinis grįžtamasis ryšys, sistema stabilizuojasi. |

---

## 5. „Pašildymo laikas“ (Compensator Time Constant)

> *DZ pastaba: „Uždarius DM Delta Compensator, DZ efektai išnyksta iškart. Vėl atidarius, reikia maždaug 4–5 sekundžių, kol sistema atsistato.“*

Tai nėra „elektroninis vėlavimas“. Tai yra **pneumatinės inercijos laikas** – būtent tiek reikia, kad DZ vidinė oro masė (Impulser / Container) surastų tinkamą **fazinį kampą** (Turnover Point) ir vėl pradėtų rezonuoti.

ICE analogijoje tai atitinka **variklio pašildymą** – kol grįžtamoji masė suranda savo stabilų darbo tašką.

---

## 6. Santrauka

| ICE | DZ |
| :--- | :--- |
| Atviro ciklo sistema (turi išmetimą) | Uždaro ciklo sistema (nėra išmetimo) |
| Vienkryptis (vienakryptis) procesas | Reversyvus (dvikryptis) procesas |
| Energija prarandama (šiluma, dujos) | Energija recirkuliuojama (fazinis grįžtamasis ryšys) |
| Varomas degalų | Varomas degalų (elektrinio signalo) ir pneumatinės inercijos ir grįžtamojo ryšio |
| Turi fiksuotą degimo kampą | Turi dinaminį Turnover Point (+0 / -0) |

---

## 7. Simbolinė tapatybė

> **Delta Signum = Degimo kampas = Turnover Point (+0 / -0)**

---

*Parengta pagal autentiškus DZ principus. Ši analogija skirta padėti suprasti sistemą tiems, kurie ateina iš mechanikos ar automobilių inžinerijos.*