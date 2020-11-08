Hakierspejs Łódź posiada serwer CalDAV/CardDAV ([Radicale](https://radicale.org/)) pozwalający informować się wzajemnie o dacie nadchodzącej wizyty w HSie i przekazywać sobie dane kontaktowe.

### Założenie konta
Serwer wymaga uwierzytelnienia.

Jeśli masz dostęp ssh, do naszej VM, to wykonaj jako root komendę:

`# htpasswd /etc/radicale/htpasswd nazwa_użytkownika`

Jeśli nie masz, poproś o założenie konta kogoś, kto ten dostęp ma np. [@ksiezak](https://github.com/ksiezak) (Matrix: [@ksiezak:matrix.org](https://matrix.to/#/@ksiezak:matrix.org) Telegram: [@ksiezak](https://t.me/ksiezak))

### Wspierane klienty

Android: [DAVx⁵](https://www.davx5.com/) także na [F-Droid](https://f-droid.org/en/packages/at.bitfire.davdroid/)

### TODO
- [ ] Konteneryzacja serwera
- [ ] Dołożenie WebUI np. [InfCloud](https://www.inf-it.com/open-source/clients/infcloud/)
- [ ] Ustawienie prawilnego certyfikatu np. Let'sEncrypt
- [ ] Napisanie jakiegoś WebUI do rejestracji nowych użytkowników
- [ ] Rozbudowa dokumentacji