# Průvodní listina k projektu SQL

**Autor:** Lucie Medvecka  
**Název souborů:** `Primary_table_vyzkumne_otazky.sql` a `Secondary_table.sql`  
**Období zpracování:** 2006–2018

---

## Úvod

Tato práce se zabývá analýzou vývoje vybraných ekonomických a sociálních ukazatelů v České republice a Evropě v období let **2006 až 2018**. Výchozími datovými zdroji byly předem zadané tabulky:

- `economies`
- `countries`
- `czechia_payroll`
- `czechia_price`
- `czechia_price_category`
- `czechia_payroll_industry_branch`

Zvolený časový úsek vychází z průniku dostupnosti dat napříč tabulkami a pokrývá roky 2006–2018.

---

## Cíle práce

Cílem bylo:

- sjednotit data z různých zdrojů do dvou výstupních tabulek (primární a sekundární),
- zodpovědět předem definované **výzkumné otázky** pomocí SQL dotazů.

---

## Vytvořené výstupní tabulky

### 1. `t_luc_medvecka_project_sql_primary_final`

Tato tabulka slouží jako hlavní zdroj dat pro analýzy vztahující se k České republice. Obsahuje:

- HDP (GDP) v ČR podle roku,
- průměrné mzdy v jednotlivých odvětvích a jejich názvy,
- průměrné roční ceny vybraných potravin a názvy těchto potravin,
- měřené množství a měrné jednotky k cenám.

### 2. `t_luc_medvecka_project_sql_secondary_final`

Sekundární tabulka obsahuje socioekonomické ukazatele pro **všechny evropské země**:

- HDP(GDP),
- populaci,
- koeficient Gini.

Tabulka slouží zejména pro srovnání mezi státy a pro doplňující analýzy evropského kontextu.

**Poznámka ke kvalitě dat:**
