# Third-Party Licenses

Скиллы и команды в каталогах `skills/` и `commands/` импортированы из
сторонних репозиториев. Все они распространяются под лицензией **MIT**,
полный текст которой приведён ниже. Уведомления об авторских правах
каждого источника указаны в соответствующих секциях.

## Полный текст лицензии MIT

> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.

## Источники

| Источник | Каталог | Скиллов | Команд | Copyright |
| -------- | ------- | ------: | -----: | --------- |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | `skills/emilkowalski/` | 12 | — | Copyright (c) 2026 Emil Kowalski |
| [ConardLi/garden-skills](https://github.com/ConardLi/garden-skills) | `skills/conardli/` | 5 | — | Copyright (c) 2026 ConardLi |
| [elayadesign/ai-design-skills](https://github.com/elayadesign/ai-design-skills) | `skills/elaya/` | 1 | — | Copyright (c) 2026 Elaya |
| [MengTo/Skills](https://github.com/MengTo/Skills) | `skills/mengto/` | 132 | — | Copyright (c) 2026 Meng To |
| [jakubkrehel/skills](https://github.com/jakubkrehel/skills) | `skills/jakubkrehel/` | 11 | — | Copyright (c) 2026 Jakub Krehel |
| [codeswithroh/tastemaker](https://github.com/codeswithroh/tastemaker) | `skills/tastemaker/` | 1 | — | Copyright (c) 2026 codeswithroh |
| [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills) | `skills/owl-listener/`, `commands/owl-listener/` | 107 | 32 | Copyright (c) 2026 MC Dean |

## Правило для новых импортов

Перед импортом стороннего материала руководствуйтесь чек-листом
«Проверка лицензии перед импортом» в [AGENTS.md](AGENTS.md) — он
определяет, какие лицензии допускаются в публичный репозиторий.
Затем:

При добавлении нового источника:

1. Проверьте файл `LICENSE` в исходном репозитории.
2. Добавьте строку в таблицу выше: ссылка на репозиторий, каталог,
   количество скиллов/команд, строка copyright из его LICENSE.
3. Если исходник распространяется не под MIT — уточните условия
   редистрибуции в этой секции перед импортом.
