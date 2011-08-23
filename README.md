=Farewell, gem russian

Совершенно понятно, почему Ярослав перестал его подерживать.
После `I18n v.0.3.0`, когда появлился модуль Pluralization в этом джеме отпала необходимость.

Этот маленький проект содержит всего три файла, которые достаточно добавить в рельсовый проект, чтобы получпть полноценнвую поддрежку русского языка.

If you do not read Russian, here is the explenation.

After the version 0.3.0 of the gem I18n has appeared the full pluralization support is implemented for every language.

For use of this possibility you need to add to your project the following files.

1. config/initializers/locale.rb that adds the module Pluralization;
2. the pluralizarion rules, here there is the file config/locales/ru.rb
for Russian languages; yuo can easyly add the rules for other languages
just looking at http://unicode.org/repos/cldr-tmp/trunk/diff/supplemental/language_plural_rules.html;
3. the standard rails translations; here are ones for Russian language in the file config/locales/ru.yml that I recoomend to rename and keep unchaged.
