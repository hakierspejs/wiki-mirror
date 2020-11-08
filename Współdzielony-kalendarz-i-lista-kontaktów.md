Hakierspejs Łódź posiada serwer CalDAV/CardDAV ([Radicale](https://radicale.org/)) pozwalający informować się wzajemnie o dacie nadchodzącej wizyty w HSie i przekazywać sobie dane kontaktowe.

### Założenie konta
Serwer wymaga uwierzytelnienia.

Jeśli masz dostęp ssh, do naszej VM, to wykonaj jako root komendę:

`# htpasswd /etc/radicale/htpasswd nazwa_użytkownika`

Jeśli nie masz, poproś o założenie konta kogoś, kto ten dostęp ma np. [@ksiezak](https://github.com/ksiezak) (Matrix: [@ksiezak:matrix.org](https://matrix.to/#/@ksiezak:matrix.org) Telegram: [@ksiezak](https://t.me/ksiezak))

### Wspierane klienty

Android: 
- [DAVx⁵](https://www.davx5.com/) także na [F-Droid](https://f-droid.org/en/packages/at.bitfire.davdroid/)

Linux:
- [Thunderbird](https://www.thunderbird.net/pl/) z wtyczkami [CardBook](https://addons.thunderbird.net/pl/thunderbird/addon/cardbook/) i [Lightning](https://addons.thunderbird.net/pl/thunderbird/addon/lightning/)
- GNOME [Calendar](https://wiki.gnome.org/Apps/Calendar), [Contacts](https://wiki.gnome.org/Apps/Contacts) i [Evolution](https://wiki.gnome.org/Apps/Evolution)
- [MineTime](https://minetime.ai/) (niestety closed-source :( )

### Używanie

W kliencie dodaj dwa konta, w obu przypadkach podaj swoją nazwę użytkownika i hasło, a jako adresy URL użyj:
- dla książki adresowej: [https://cal.hs-ldz.pl:5232/addressbook/61bb92bb-6ea9-0366-22f5-9fdcd5c53e02/](https://cal.hs-ldz.pl:5232/addressbook/61bb92bb-6ea9-0366-22f5-9fdcd5c53e02/)
- dla kalendarza: [https://cal.hs-ldz.pl:5232/cal/fcbca4e6-3adb-6d08-2b8b-64c4d7e3e4a9/](https://cal.hs-ldz.pl:5232/cal/fcbca4e6-3adb-6d08-2b8b-64c4d7e3e4a9/) 


### TODO
- [ ] Konteneryzacja serwera
- [ ] Dołożenie WebUI np. [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/)
- [ ] Ustawienie prawilnego certyfikatu np. Let'sEncrypt
- [ ] Napisanie jakiegoś WebUI do rejestracji nowych użytkowników
- [ ] Rozbudowa dokumentacji, opis jak ustawiać klienty, więcej klientów