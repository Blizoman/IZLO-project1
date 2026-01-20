# IZLO – Projekt 1: SAT Solvery

Riešenie 1. projektu z predmetu IZLO (Logika a grafy) na FIT VUT.

## Obsah úlohy
- **SAT Solver** – riešenie problému splniteľnosti (Constraint Satisfaction Problem).
- **Výroková logika** – kódovanie logických podmienok do konjunktívnej normálnej formy (CNF).
- **Modelovanie problému** – optimalizácia distribúcie produktov v krajoch podľa prísnych pravidiel.
- **Implementácia** – generovanie klauzúl v jazyku C pre nástroj MiniSat.

Projekt bol vytvorený výlučne na vzdelávacie účely.

## Technológie
- **Jazyk:** C
- **Formát:** DIMACS (CNF)
- **Nástroje:** MiniSat, Make, GCC

## Hodnotenie
- Získané body: **8 / 8**

## Spustenie
Projekt využíva `make` na preklad a skript `run.sh` na overenie riešenia pomocou SAT solvera.

```bash
# Preklad
make

# Spustenie testu nad vstupným súborom
./run.sh tests/sat/assignment_example.in
