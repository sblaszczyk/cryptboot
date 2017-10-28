# Cryptboot

Program wspomaga zaszyfrowanie systemu Ubuntu podczas jego instalacji na dysku wraz z utworzeniem zaszyfrowanego pendrive USB służącego do uruchamiania tego systemu.
Tak skonfigurowany system podnosi bezpieczeństwo danych, ponieważ zarówno nagłówek LUKS jak i klucz są umieszczone na zaszyfrowanym pendrive.

Przetestowano na instalatorze mini Ubuntu 17.04.

## Jak zacząć

Zalecane jest wykonanie instalacji systemu Ubuntu 17.04 na maszynie wirtualnej, np. Oracle VirtualBox jako ćwiczenie procedury instalacji przed wykonaniem jej na rzeczywistej maszynie.
Instalcję systemu należy przeprowadzić w trybie ekspert.

### Wymagania wstępne

W celu przeprowadzenia instalacji należy pobrać obraz instalatora mini Ubuntu.

```
wget http://archive.ubuntu.com/ubuntu/dists/zesty/main/installer-amd64/current/images/netboot/mini.iso
```

### Instalacja

Przebieg instalacji jest zaprezentowany w filmie instruktażowym @link.

## Autorzy

* **Sławomir Błaszczyk** - *Zanicjował pracę* - [sblaszczyk](https://github.com/sblaszczyk)

## Licencja

Ten projekt jest objęty licencją MIT - szczegóły [LICENSE](LICENSE)

## Podziękowania

* Motywacją, inspiracją do przygotowania tego narzędzia jest prelekcja Krzysztofa Leszczyńskiego pod tytułem: Szyfrowanie, zabezpiecz się przed złodziejem, prokuratorem, sądem. https://www.youtube.com/watch?v=S7qy5-tS1Q4

