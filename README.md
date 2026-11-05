# LLM Council

Pytasz AI, czy podnieść stawkę. AI mówi, że świetny pomysł. Klasyczek.

Przy decyzji, która może Cię sporo kosztować, jedna odpowiedź to za mało. Więc ten skill robi z Twojego pytania naradę. Pięciu doradców patrzy na sprawę z pięciu stron. Potem ich odpowiedzi przechodzą ocenę. Na końcu dostajesz werdykt: co robić i od czego zacząć.

Działa w Claude Code i Claude Cowork.

## Co to w ogóle jest

Skill to zestaw instrukcji dla Claude'a do jednego konkretnego zadania. Wgrywasz go raz, a potem odpalasz jednym zdaniem.

GitHub to taki dysk Google, tylko na kod. Właśnie na nim jesteś.

## Jak to działa

Zanim doradcy ruszą, Claude zagląda do Twoich plików z kontekstem, na przykład CLAUDE.md. Dzięki temu doradcy wiedzą, o kim mówią.

Potem odpala całą piątkę naraz. Każdy pracuje osobno i myśli inaczej:

- **The Contrarian** szuka, co się wysypie.
- **The First Principles Thinker** sprawdza, czy w ogóle zadajesz dobre pytanie.
- **The Expansionist** patrzy, co może pójść lepiej, niż zakładasz.
- **The Outsider** nic o Tobie nie wie i ocenia tylko to, co widzi.
- **The Executor** pyta, co robisz w poniedziałek rano.

Odpowiedzi trafiają do oceny bez podpisów. Oceniający nie wie, kto co napisał, więc patrzy na samą treść. Wskazuje najmocniejszą odpowiedź, największą dziurę i to, co pominęli wszyscy.

Na końcu przewodniczący składa wszystko w jeden werdykt. Widzisz, gdzie doradcy się zgadzają, a gdzie kłócą. Dostajesz konkretną rekomendację i jeden krok do zrobienia na start.

## Kiedy to ma sens

Kiedy pomyłka drogo kosztuje, a dobrej odpowiedzi nie znasz.

Dobre pytania:

- „Warsztat za 400 zł czy kurs za 2000 zł?”
- „Który z tych 3 pomysłów na ofertę jest najmocniejszy?”
- „Chcę przejść z X na Y. Odbiło mi?”
- „Oto tekst z mojej strony. Co w nim nie działa?”
- „Zatrudnić asystenta czy najpierw zbudować automatyzację?”

Słabe pytania:

- „Jaka jest stolica Francji?” (jest jedna poprawna odpowiedź)
- „Napisz mi posta” (nie ma tu żadnej decyzji)
- „Streść ten artykuł” (tu też nie)

I szczerze? Jeśli decyzja już zapadła i chcesz tylko usłyszeć, że masz rację, możesz się zdziwić.

## Instalacja

Bez terminala. Masz dwie drogi i obie działają w Claude Code i Claude Cowork.

**Sposób 1: niech Claude zrobi to za Ciebie**

Otwórz nowy czat i wklej:

> Zainstaluj mi tego skilla. Plik SKILL.md jest w tym repo na GitHubie: https://github.com/krystianbefree/claude-skills-llm-council
>
> Ustaw wszystko tak, żeby działało od razu. Przeprowadź mnie przez to, czego będziesz ode mnie potrzebować.

Claude pobierze plik i wrzuci go w odpowiednie miejsce. Jeśli nie da rady zrobić tego sam, powie Ci, co kliknąć.

**Sposób 2: pobierz plik**

1. Kliknij [SKILL.md](./SKILL.md) na górze tego repo.
2. Pobierz plik przyciskiem po prawej stronie.
3. Otwórz Claude'a i wklej:

> Mam pobrany plik SKILL.md ze skillem LLM Council. Zainstaluj go i przeprowadź mnie przez to krok po kroku.

## Jak tego używać

Napisz w rozmowie jedną z tych fraz:

- `council this`
- `run the council on [Twoje pytanie]`
- `pressure-test this`
- `stress-test this`
- `war room this`

Frazy są wpisane w skilla po angielsku, więc tak je zostawiam. Samo pytanie zadajesz normalnie po polsku:

> council this: czy podnieść stawkę o 30%?

## Skąd to jest

Skill zbudował [Ole Lehmann](https://x.com/itsolelehmann), a metoda pochodzi z [LLM Council](https://github.com/karpathy/llm-council) Andreja Karpathy'ego. Ja dopisałem tylko polski opis, żeby łatwiej było się tym dzielić.
