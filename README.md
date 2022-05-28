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

git remote add origin https://github.com/beatazalewa/nauka_gita.git
git branch -M main
git push -u origin main

git config --global credential.helper store
#Now, git will remember your token.

#If you want to disable the helper, run the following commands:

git config --global --unset credential.helper
rm ~/.git-credentials

<<<<<<< HEAD
Z nowego branch
=======
#Mozemy tez projekt sklonować.
>>>>>>> b213cb09d05e11dcb71691b92096f743d69309a7
