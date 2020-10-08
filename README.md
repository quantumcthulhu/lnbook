# Освоєння Lightning Network. Український переклад

[![Build Status](https://travis-ci.com/lnbook/lnbook.svg?branch=develop)](https://travis-ci.com/lnbook/lnbook)

<img src="images/cover_thumb.png" width=200 alt="Mastering Lightning Cover">

## Про цю книгу
Освоєння Lightning Network - книга видання O'Reilly Media, що планується до видання в четвертому кварталі 2020 року, і була анонсована 28 Серпня 2019 авторами Andreas M. Antonopoulos ([@aantonop](https://twitter.com/aantonop)), Olaoluwa Osuntokun ([@roasbeef](https://twitter.com/roasbeef)), Rene Pickhardt ([@renepickhardt](https://twitter.com/renepickhardt)).

Книга описує peer-to-peer протокол Lightning Network (LN), що працює поверх Біткоїна та інших блокчейнів і забезпечує майже миттєві, безпечні мікроплатежі.

Книга підходить для технічно підкованих читачів, що володіють розумінням основ Біткоїна та інших відкритих блокчейнів.

## Стан

Поточний стан написання книги - "У ПРОЦЕСІ". Дивіться нижче стан написання конкретних розділів та прочитайте гід з контрибуцій, щоб дізнатись, як і де робити контрибуції.

### Легенда

* :arrows_clockwise:  LIVE EDITS - Continuously changing: Submit focused/small Issues and PRs
* :mag: REVIEW - Ready for review: Submit Issues and PRs as needed
* :lock_with_ink_pen: EARLY DRAFT - In progress, changing often: Submit issues only, NO PRs or fixes
* :bookmark_tabs: OUTLINE - Rough outline - Please contribute! PRs welcome.
* :thought_balloon: PLANNED - Planned section  - Do nothing yet.

| Секція | Довжина (Кількість Слів) |  Стан |  Перекладено |
|-------|------|:------:|:------:|
| [Preface and Acknowledgments](preface.asciidoc) | ### | :arrows_clockwise: |
| [Glossary](glossary.asciidoc) | ############## | :arrows_clockwise: |
| [Вступ](01_introduction.asciidoc) | ###### | :mag: | 100% |
| [Починаємо](02_getting_started.asciidoc) | ############ | :mag: | 100% |
| [Основи LN (Як працює LN)](03_how_ln_works.asciidoc) | ########################### | :mag: | 100% |
| [Nodes (LN Clients)](node_client.asciidoc) | #################### | :mag: |
| [Operating a Node](node_operations.asciidoc) | ############################ | :bookmark_tabs: |
| PART 2 | PART 2 | PART2 |
| [Intro to LN Routing (HTLCs)](routing.asciidoc) | ##################### | :lock_with_ink_pen: |
| [Channel Construction in Detail](channel-construction.asciidoc) | ########## | :lock_with_ink_pen: |
| [Channel operation with HTLCs and Statemachine](channel-operation.asciidoc) | ###### | :lock_with_ink_pen: |
| [Payment Path Finding](path-finding.asciidoc) | ############## | :bookmark_tabs: |
| [P2P Communication](p2p.asciidoc) | # | :bookmark_tabs: |
| [Channel Graph and Gossip Layer](channel-graph.asciidoc) | ### | :bookmark_tabs: |
| [End-to-End Payment Presentation Layer](e2e-presentation-layer.asciidoc) | ### | :bookmark_tabs: |
| [Lightning Applications (LApps)]() | # | :thought_balloon: |
| [LN's Future]() | # | :thought_balloon: |


Total Word Count: 81432

## Контрибуції

Автори вітають контрибуції до цієї книги! Читайте [Гід з Контрибуцій](CONTRIBUTING.md)

## Джерело та ліцензія

Освоєння Lightning Network випускається під ліцензією Creative Commons CC-BY-NC-ND, що дозволяє надавати вихідний код лише для особистого використання. Ви можете читати цю книгу безкоштовно. Ви не можете створювати похідні файли (наприклад, копії PDF) або поширювати книгу з комерційною метою. Повні умови ліцензії можна знайти тут:

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Mastering the Lightning Network</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://lnbook.info/" property="cc:attributionName" rel="cc:attributionURL">Andreas M. Antonopoulos, Olaoluwa Osuntokun, Rene Pickhardt</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

Очікується, що книга вийде під більш дозвільною ліцензією CC-BY-SA протягом року після публікації.