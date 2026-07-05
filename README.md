[:gb: English version](README_ENG.md)

# Badanie metod wyjaśnialności sztucznej inteligencji na przykładzie analizy istotności cech

**Praca magisterska** — Politechnika Warszawska, Instytut Sterowania i Elektroniki Przemysłowej

- **Kierunek:** Informatyka Stosowana, specjalność Inżynieria Danych i Multimedia
- **Autor:** Daniel Ślusarczyk
- **Promotor:** dr inż. Grzegorz Sarwas
- **Miejsce i rok:** Warszawa 2025

Repozytorium pracy dyplomowej magisterskiej. Zawiera pracę dyplomową oraz pliki źródłowe wykorzystane do opracowania części eksperymentalnej projektu.

---

## Streszczenie

<div align="justify">

Dynamiczny rozwój sztucznej inteligencji obserwowany w ostatnich latach oraz rosnąca złożoność współczesnych modeli uczenia maszynowego doprowadziły do istotnego wyzwania w obszarze rozumienia dokładnego sposobu generowania wyników z ich pomocą. Wiele kluczowych decyzji w sektorach o wysokim ryzyku (medycyna, transport, administracja) jest podejmowanych przez systemy, których dokładne działanie jest niezrozumiałe nawet dla osób dysponujących wiedzą ekspercką. Takie modele, określane mianem tzw. czarnych skrzynek, stanowią rozwiązania, których wewnętrzna logika jest zbyt zaawansowana zarówno dla użytkowników końcowych, jak i projektantów algorytmów do bezpośredniego opisania skutków uzyskiwanych wyników. Taka okoliczność, w kontekście rosnących wymagań etycznych i regulacyjnych (np. prawa do wyjaśnienia decyzji), doprowadziła do powstania dziedziny wyjaśnialnej sztucznej inteligencji (XAI), której celem jest zwiększenie możliwości interpretacyjnych modeli. Nowo powstała gałąź sztucznej inteligencji stanowi zarówno filozofię projektowania przejrzystszych rozwiązań uczenia maszynowego, jak i dostarcza gotowych rozwiązań wykorzystujących złożoną strukturę popularnych algorytmów do opisu ich właściwości, w tym ważności cech wpływających na generowane predykcje.

Przedmiotem niniejszej pracy jest empiryczna ocena trzech popularnych technik wyjaśnialnej sztucznej inteligencji (LIME, PFI, SHAP) w badaniu różnych modeli uczenia maszynowego, obejmujących regresję liniową, drzewa decyzyjne, lasy losowe, XGBoost oraz perceptrony wielowarstwowe. W ramach części projektowej opracowano środowisko eksperymentalne, które miało za zadanie porównanie jakości, stabilności i zgodności wyników ważności cech w obrębie wariantów testowych. Uzyskane rezultaty wskazały, że wszystkie techniki mają zbliżony potencjał w identyfikacji najważniejszych predyktorów, lecz znacząco różnią się szczegółowym rozkładem ważności pozostałych cech. Największą stabilność uzyskano dla metod PFI i SHAP, natomiast LIME w wariancie globalnym wykazała się ograniczoną zasadnością stosowania. Praca podkreśla również wpływ współliniowości cech na interpretowalność modeli przy zastosowaniu wymienionych technik i wskazuje ich ograniczenia w tym zakresie. Zwieńczeniem pracy jest ocena praktycznej użyteczności omawianych metod oraz wskazanie dalszych kierunków badań.

</div>

## Słowa kluczowe

`wyjaśnialna sztuczna inteligencja` · `ważność cech` · `techniki XAI` · `SHAP` · `LIME` · `PFI`
