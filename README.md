To jest plik README.md o nauce gita.

Tutaj będą wpisywane komendy dotyczące podstaw gita:

# utworzenie nowego folderu
mkdir -p workspace/nauka_gita
cd workspace/nauka_gita

# konfiguracja gita
git config -l
git config --global user.name "beatazalewa"

# nie lubimy spamerów
# (email jest dołączony do zapisów w git/githubie)
git config --global user.email "beatazalewa@users.noreply.github.com"

# cała globalna konfiguracja jest w następującym pliku
cat ~/.gitconfig

# sprawdzamy, czy jesteśmy we właściwej ścieżce
pwd

# powinnismy zobaczyc
# sciezke konczaco sie nauka_gita

# tworzymy repozytorium (inicjalizujemy gita)
git init

# repozytorium jest w .git/
ls .git/

# repozytorium ma swoj
# plik konfiguracyjny
cat .git/config

# tworzymy plik README.md
touch README.md

# otwieramy edytor np. atom lu nano w katalogu glownym
# repozytorium
atom .
nano README.md
