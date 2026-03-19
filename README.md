# Ecommerce-Logistics-Analysis
Analiza wpływu kosztów wysyłki na rentowność sprzedaży w brazylijskim sektorze e-commerce. Celem było zidentyfikowanie kategorii produktów, w których logistyka pochłania zbyt dużą część przychodu.

Wykorzystane technologie
Baza danych: PostgreSQL (Modelowanie relacyjne, import danych ETL)

Język zapytań: SQL (Joins, Aggregations, Case Statements, NULLIF)

Wizualizacja: Power BI (Native SQL Queries, DAX, Interactive Dashboards)

Zawartość folderu
Database_Setup.sql – Kod tworzący strukturę tabel i definiujący relacje (Primary/Foreign Keys).

margin_analysis.sql – Główny silnik analityczny łączący dane o zamówieniach, produktach i cenach.

Olist_Delivery_Analysis.pbix – Interaktywny raport Power BI.

Kluczowe wnioski
Zidentyfikowano kategorie (np. flores, moveis_casa), gdzie koszt wysyłki przekracza 25% wartości produktu.

Stworzono miarę Zysk Szacunkowy, pozwalającą na szybkie filtrowanie kategorii o ujemnej marży po uwzględnieniu logistyki.

Dashboard umożliwia dynamiczną segmentację produktów na "Tanie" i "Drogie" w wysyłce, co wspiera decyzje o zmianie polityki darmowych dostaw.
