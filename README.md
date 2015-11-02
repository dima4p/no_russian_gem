Farewell, gem russian!
======================

Совершенно понятно, почему Ярослав перестал его подерживать.
После `I18n v.0.3.0`, когда появлился модуль Pluralization в этом джеме отпала необходимость.

Этот маленький проект содержит всего три файла, которые достаточно добавить в рельсовый проект, чтобы получить полноценную поддрежку русского языка, в том числе и транслитерацию:

1. `app/config/initializers/locale.rb` — добавляет модуль Pluralization;
2. `app/config/locales/core_ru.rb` — правила плюрализации для русского языка и хэши для транслитерации; можно добавлять свои [правила](http://unicode.org/repos/cldr-tmp/trunk/diff/supplemental/language_plural_rules.html)
3. `app/config/locales/core_ru.yml` — стандартный файл с переводом; приведены значения по-умолчанию для русского языка.


If you do not read Russian, here is the explanation
---------------------------------------------------

With the `I18n v0.3.0+`, full pluralization support made possible for every language.

To use this possibility you need to add the following three files to your project:

1. `app/config/initializers/locale.rb` — adds the Pluralization module;
2. `app/config/locales/core_ru.rb` — pluralization rules and transliteration hashes for Russian; you can easily add your own rules for other languages (look [here](http://unicode.org/repos/cldr-tmp/trunk/diff/supplemental/language_plural_rules.html) for more examples)
3. `app/config/locales/core_ru.yml` — standard rails translations; these are the defaults for Russian language, that I recommend to rename and keep unchanged.
