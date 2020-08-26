Napisać:

**Opis**

**Koszty:**

**Migracja:** __rozumiana zarówno jako zmiana providera jak i admina, jeśli zniknie__

**Kto kontroluje:**

# Domeny

**Opis/zastosowanie**: domeny [hakierspejs.pl](https://whois.domaintools.com/hakierspejs.pl) oraz [hs-ldz.pl](https://whois.domaintools.com/hs-ldz.pl). Informacje o aktualnym hostingu i czasie ważności można sprawdzić w WHOIS. Stan na 16 marca 2020:

```
DOMAIN NAME:           hakierspejs.pl 
registrant type:       individual 
nameservers:           dns1.microhost.pl. [46.248.186.63] 
                       dns2.microhost.pl. [46.248.186.63] 
created:               2020.03.02 11:11:22 
last modified:         2020.03.02 11:14:11 
renewal date:          2021.03.02 11:11:22 
```

```
DOMAIN NAME:           hs-ldz.pl 
registrant type:       individual 
nameservers:           dns111.ovh.net.  
                       ns111.ovh.net.  
created:               2020.03.14 21:17:12 
last modified:         2020.03.14 21:23:50 
renewal date:          2021.03.14 21:17:12 
```

Domenę hakierspejs.pl zarejestrował d33tah, żeby nikt jej nam nie zasiedział (@q3k wolałby żebyśmy jej nie używali jako głównej, co by się nie myliło z hackerspace.pl). hs-ldz.pl jest ustawiony na wildcard kierujący do VMki PC d33taha.

**Kto kontroluje:** @d33tah, @cytP450

**Koszty:** 2x13zł, +/- 5zł. Zarówno w OVH jak i w MicroHost za przedłużenie wezmą jakieś 50zł licząc VAT.

**Migracja:** w OVH migracja .pl nie jest płatna. MicroHost wg swojego cennika też nie bierze nic za taką usługę nic. Źródła:

https://www.ovh.pl/domeny/cennik/

https://microhost.pl/domeny/cennik/ ("pl" jest poniżej "work")

# Infrastruktura do lokalu - plan szkieletowy, żeby wdrożenie było łatwiejsze

Przeniesione do [hakierspejs-netzwerk/wiki](http://www.github.com/hakierspejs/hakierspejs-netzwerk/wiki)

# Github

**Opis/zastosowanie:** Repozytorium gita na projekty, które rozwijają członkowie hakierspejsu i nie tylko. Rozważaliśmy hostowanie własnego serwisu (Gogs, Gitea), ale korzystanie z Githuba otwiera nasze repozytoria na kontrybucje z zewnątrz.

**Koszty:** null.

**Migracja:** W każdej chwili repozytoria można sklonować na inny serwis, ale przydałoby się zautomatyzować backupy. Gogs ma nawet możliwość automatycznej migracji repozytoriów.

**Kto kontroluje:** Każdy członek Hakierspejsu może zostać dodany do grupy na GitHubie. Pull requesty może słać dosłownie każdy, na takiej samej zasadzie jak na każdym innym repozytorium na GitHubie. Patche mergujemy po pozytywnym code review (każdy członek HS'u może takie przeprowadzić). Członków może dodawać @d33tah i @Martti25.

# Meetup

**Opis:** konto na meetup.com, stronie na której ogłasza się tzw. meetupy, czyli spotkania o różnej tematyce. Jesteśmy tam, bo nie chcieliśmy zaczynać od Facebooka i sam meetup ogarnia nam promocję naszej grupy w ramach zainteresowań. Ma też społeczność użytkowników w Łodzi.

**Koszty:** [Opis na ich stronie](https://help.meetup.com/hc/en-us/articles/360001620472-Organizer-subscription-pricing) ; pierwsze 6 miesięcy kosztowało w ramach promocji 164zł.

**Migracja:** stracimy historię meetupów oraz przestaniemy przyciągać ludzi, którzy stamtąd się o nas dowiedzieli. Also, żeby boty działały, trzeba będzie przepisać/przemigrować z [meetupscrapera](https://github.com/hakierspejs/meetupscraper).

**Kto kontroluje:** @d33tah (organizer), @Martti25 (co-organizer), @biniu (co-organizer) @kszmigiel (co-organizer), @nikolaad (co-organizer), @Keij0 (co-organizer)

# Lista mailingowa
* [https://lists.hackerspace.pl/pipermail/lodz/](https://lists.hackerspace.pl/pipermail/lodz/)

**Opis/zastosowanie:** dzielenie się informacjami o bieżących planach/wydarzeniach/co się dzieje

**Koszty:** 0

**Migracja:** stoi na Pipermail 0.09 hostowane przez Hackerspace Warszawa. W razie czego można zrobić dumpy .txt całych archiwów, ale adres listy musiałby się zmienić. Możliwy eksport listy osób zasubskrybowanych.

**Kto kontroluje:** @d33tah, @q3k

# Telegram - kanały

## t.me/hakierspejs

**Opis/zastosowanie:** Podstawowe narzędzie komunikacji. Dołączyć do grupy może każdy pod tym [linkiem](https://t.me/hakierspejs). Telegram to dobry kompromis jako narzędzie do komunikacji dla hackerów (aplikacje dla klientów mają otwarty kod źródłowy). Jednocześnie, jeżeli ktoś czuje się bardziej komfortowo z IRC, to może dalej z niego korzystać. Bramka, która wymienia wiadomości między IRC a grupą na Telegramie, zadba o reszte.

**Koszty:** 0 zł / miesiąc, każdy może założyć swoją własną grupę na serwerach Telegrama i zapraszać do niej ludzi.

**Migracja:** Niemożliwa, wszystko na własnościowych serwerach Telegrama. Zmieniając główne narzędzie do komunikacji, tracimy jednocześnie sporo ludzi, którzy tylko lurkują. Na szczęście można przynajmniej wyeksportować historię kanału.

**Kto kontroluje:** @d33tah, @kszmigiel, @BluRaf

## t.me/hakierspejs_spam

**Opis/zastosowanie:** Pierwotnie do shitpostowania, spamowania i gadania na tematy mało związane z IT, elektroniką i wolną kulturą (w tym na będący bardzo na czasie temat pewnego biologicznego bytu, który opanował cały świat i przewrócił życie milionów ludzi do góry nogami) używaliśmy kanału, który stworzyliśmy na jednym ze spotkań w Opusie w celu testowania botów do Telegrama. Z uwagi jednak na to, że wiadomości diagnostyczne od botów przeszkadzały w użytkowaniu kanału do komunikacji human-to-human, 18 kwietnia 2020 stworzyliśmy [nowy kanał do shitpostów](https://t.me/hakierspejs_spam). **Uwaga**: tematy około-techniczno-hakerskie, nawet jeżeli zahaczają o shitpost (typu: rant na *wstaw dowolne distro*), lepiej kierować na główny kanał, żeby nam po prostu nie umarł. Więcej informacji na ten temat [tutaj](https://lists.hackerspace.pl/pipermail/lodz/2020-March/000026.html).

**Koszty:** 0 zł / miesiąc, kolejny kolejny czat na telegramie.

**Migracja:** To tylko kanał na shitposty.

**Kto kontroluje:** @BluRaf, @d33tah

## t.me/hslodzbot

**Opis/zastosowanie:** Dołączyć można [tutaj](https://t.me/hslodzbot). Początkowo był to kanał do testowania botów, potem robił też za spamiarnię i kanał do shitpostów. Z praktycznych względów shitposty zostały jednak wydzielone do osobnego kanału. Obecnie na kanale znaleźć można głównie wiadomości diagnostyczne od botów i innego rodzaju automatyczne powiadomienia (np. o aktualizacji Wiki, pojawieniu się kogoś na Mumble'u). Oczywiście nic nie stoi na przeszkodzie, by użyć go jako trzeciego kanału do dyskusji, gdyby chwilowo zaszła taka potrzeba.

**Koszty:** 0 zł / miesiąc, kolejny czat na telegramie.

**Migracja:** To tylko kanał do testowania botów.

**Kto kontroluje:** Każdy kto poprosi o admina.

# Matrix - kanały
## hs-ldz:hackerspace.pl

**Opis/zastosowanie:** Kanał Matrix zmostkowany z kanałem t.me/hakierspejs na Telegramie. Dołączyć można [tutaj](https://matrix.to/#/#hs-ldz:hackerspace.pl)

**Koszty:** 0 zł / miesiąc

**Migracja:** -

**Kto kontroluje:** @BluRaf

## hs-ldz-offtopic:hackerspace.pl

**Opis/zastosowanie:** Kanał Matrix zmostkowany z kanałem t.me/hakierspejs_spam na Telegramie. Dołączyć można [tutaj](https://matrix.to/#/#hs-ldz-offtopic:hackerspace.pl)

**Koszty:** 0 zł / miesiąc

**Migracja:** -

**Kto kontroluje:** @BluRaf

# IRC

**Opis/zastosowanie:** Kanał IRC #hakierspejs dostępny w sieci Freenode (`chat.freenode.net`) zmostkowany z czatem na Telegramie.

**Koszty:** 0 zł / miesiąc

**Migracja:** -

**Kto kontroluje:** @BluRaf, @d33tah (operatorzy)

# Mumble

**Opis/zastosowanie:** Serwer do rozmów głosowych dostępny pod domeną `junkcc.net`

**Koszty:** 0 zł / miesiąc, jako iż obecny serwer jest wykorzystywany przez właściciela również do innych celów

**Migracja:** Kwestia przeniesienia konfiguracji (o ile jest co przenosić)

**Kto kontroluje:** @BluRaf

# Boty
## Mariusz

**Opis/zastosowanie:** śmieszkowanie, update tematu na kanale, straszenie koronawirusem, integrowanie poprzez wspólne programowanie.

## Konfident

**Opis/zastosowanie:** transport między Telegramem a IRC-em

**Migracja:** hostowanie tego jest już rozgryzione, więc kwestia poświęcić 2-4h na odpalenie kontenera Dockera na innym serwerze z tym samym lub innym kluczem API.

**Kto kontroluje:** @BluRaf

# Hosting

**Opis/zastosowanie**: maszyna wirtualna hostowana przez Hackerspace Warszawa. Hostujemy na niej nasze projekty i usługi różnego typu, m.in.: Grafanę, CodiMD czy Discourse.

**Koszty**: dzięki uprzejmości Hackerspace Warszawa, na ten moment jest gratis. W momencie gdy zostaniemy przemigrowani na fizycznego hosta, pojawią się koszty za prąd (poniżej 50zł/mies).

**Migracja:** zakładając, że robimy regularnie backupy, jest to kwestia wynajęcia gdzieś innej VMki i przepięcia domeny na nowy adres IP.

**Kto kontroluje:** roota mają: @d33tah, @kpc, @Keij0, @thinkofher i @cytP450. Fizycznie maszynę kontroluje Hackerspace Warszawa, w szczególności q3k.

# Pad

**Opis:** spejsowy notatnik https://pad.hs-ldz.pl; zastosowanie np. notatki ze spotkań

**Koszty:** 0 (musi być gdzieś hostowany; aktualnie jest to nasza VMka od HSWAW)

**Migracja:** self-hosted, więc gdzieś przenieść nie problem, przeniesienie samych treści może być bardziej problematyczne, ale notatki opierają się na kodzie źródłowym a'la Markdown, więc jest to rabialne

**Kto kontroluje:** @d33tah

# Forum

**Opis:** nasze forum Discourse https://forum.hs-ldz.pl; służy do dłuższych dyskusji, w odróżnieniu od listy mailingowej gdzie zwykle raczej idą powiadomienia

**Koszty:** 0 (musi być gdzieś hostowane; aktualnie jest to nasza VMka od HSWAW)

**Migracja:** self-hosted w Dockerze, więc raczej da radę to przenieść. Aleksy [udokumentował](https://github.com/hakierspejs/forumhsldz) proces żenienia tego z Traefikiem.

**Kto kontroluje:** @d33tah, @thinkofher, @cytP450

# Grafana

**Opis:** [https://grafana.hs-ldz.pl/](https://grafana.hs-ldz.pl/)

**Koszty:** 0 (musi być hostowany)

**Migracja:** self-hosted

**Kto kontroluje:** #deetah

# Naklejki

**Opis/zastosowanie:** promocja HSŁ

**Migracja:** nie dotyczy

**Kto kontroluje:** są dostępne na CC0 jako SVG, każdy może robić co chce. W wersji wydrukowanej kilka osób w HSŁ ma parę nadmiarowych sztuk. Wydruk ogarniał @kszmigiel. Firma która tym się zajęła to: http://www.magmedia.pl/naklejki_samoprzylepne.php - wychodziło 50-100gr za naklejkę ~4x3cm z wycięciem (20 na arkusz). W razie czego q3k ogarnia inną firmę, którą poleca. 
***

# Konto na Fejsie

**Opis/zastosowanie:** promocja HSŁ

**Koszty:** 0

**Migracja:** nie dotyczy

**Kto kontroluje**: @Martti25, @nikolaad, @BluRaf