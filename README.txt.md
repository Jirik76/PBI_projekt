# Power BI projekt – Vývoj mezd, cen potravin a kupní síly v ČR

Cílem tohoto projektu je vizualizovat vývoj průměrných mezd a cen vybraných potravin v České republice v čase a analyzovat jejich vzájemný vztah, včetně dopadu na kupní sílu obyvatel. Projekt navazuje na analytickou část předchozího SQL projektu a zaměřuje se na srozumitelnou a interaktivní prezentaci dat v prostředí Power BI.
---

## Struktura reportu

Power BI report je rozdělen do čtyř tematických stránek:

| Stránka                  | Popis                                                                                   |
|--------------------------|-----------------------------------------------------------------------------------------|
| **Mzdy**                 | Vývoj průměrné mzdy v čase, možnost filtrování podle odvětví.                           |
| **Ceny potravin**        | Vývoj cen vybraných potravin, filtrování podle konkrétní potraviny.                     |
| **Porovnání mezd a cen** | Meziroční růst mezd a cen potravin.                                                     |
| **Kupní síla**           | Vývoj kupní síly průměrné mzdy ve vztahu k cenám vybraných potravin.                    |

---

## Interaktivita a filtrace

Report využívá průřezy (slicery) pro:

- výběr roku
- výběr odvětví
- výběr konkrétní potraviny

Všechny vizuály se dynamicky přepočítávají na základě zvolených filtrů. Navigace mezi jednotlivými stránkami je řešena pomocí interaktivních tlačítek.

---

## Datový model

Součástí projektu je:

- kalendářová (dimenzionální) tabulka pro správné vazby 1:N
- dimenzionální tabulka odvětví
- dimenzionální tabulka potravin
- odstranění M:N vazeb v datovém modelu

Datové tabulky jsou propojeny pomocí relací v Power BI modelu.

---

## Použité vizualizace a metriky

V reportu je použito více typů vizualizací:

| Typ vizualizace  | Popis                                       |
|------------------|---------------------------------------------|
| Karty            | Zobrazení klíčových hodnot                  |
| Spojnicové grafy | Vývojové trendy v čase                      |
| Sloupcové grafy  | Porovnání hodnot mezi kategoriemi           |
| Kombinované grafy| Srovnání více metrik v jednom grafu         |
| Tabulky          | Detailní zobrazení dat                      |

Byly vytvořeny vlastní míry v jazyce DAX, například:

- průměrná mzda
- průměrná cena potravin
- meziroční růst mezd a cen
- kupní síla (počet jednotek vybrané potraviny, které lze zakoupit za průměrnou mzdu)

---

## Výsledek

Výsledkem je přehledný a interaktivní Power BI report, který umožňuje:

- sledovat dlouhodobé trendy mezd a cen potravin
- porovnávat jejich meziroční vývoj
- analyzovat kupní sílu podle odvětví a konkrétních potravin

Projekt splňuje požadavky zadání a demonstruje práci s datovým modelem, DAX výpočty a pokročilou vizualizací v Power BI.

> Projekt byl vytvořen v rámci Datové akademie ENGETO.



