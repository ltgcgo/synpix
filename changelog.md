# Changelog

## 2023m26a (2023/09/14)

* Add the glyph for the hiragana `を`, which are urgently needed for Octavia UIs.
* Add the following 2 CJKV ideographs: `丽邓`, which are urgently needed for Octavia UIs.
* Add the following 3 CJKV ideograph variant forms: `鄧麗麗`.
* SynPix was separated into its own repository.

*Changelogs between version 2023m05a and 2023m26a have not been completed yet.*

## 0.1 (2023m05a, 2023/02/13)

* Add Latin-9.
* Add basic Greek, Cyrillic and Hebrew.
* Add Bopomofo and half-width Hangul.
* Add some kanas, but with a very limited set. Kanas are completed by the next version.

A full list of glyphs newly added in this version (418 glyphs):

```
      ⏸︎÷◁◀︎♪♫↲↑↓→
 ♥●█¤⏫︎¦⏬︎ ≠≤≥↙︎↖︎↘︎↗︎
 ¡¢£€¥Š§š©ª«¬­®¯
°±²³Žµ¶·ž¹º»ŒœŸ¿
ÀÁÂÃÄÅÆÇÈÉÊËÌÍÎÏ
ÐÑÒÓÔÕÖ×ØÙÚÛÜÝÞß
àáâãäåæçèéêëìíîï
ðñòóôõö÷øùúûüýþÿ
ΆΈΉΊΌΎΏ
ΐΑΒΓΔΕΖΗΘΙΚΛΜΝΞΟ
ΠΡ΢ΣΤΥΦΧΨΩΪΫάέήί
ΰαβγδεζηθικλμνξο
πρςστυφχψωϊϋόύώ
ЁЄІЇ
АБВГДЕЖЗИЙКЛМНОП
РСТУФХЦЧШЩЪЫЬЭЮЯ
абвгдежзийклмноп
рстуфхцчшщъыьэюя
ёєіїҐґ
אבגדהוזחטיךכלםמן
נסעףפץצקרשת
いこのはぼりイォサズトフマルン
　　　　　ㄅㄆㄇㄈㄉㄊㄋㄌㄍㄎㄏ
ㄐㄑㄒㄓㄔㄕㄖㄗㄘㄙㄚㄛㄜㄝㄞㄟ
ㄠㄡㄢㄣㄤㄥㄦㄧㄨㄩㄪㄫㄬㄭㄮㄯ
ㆠㆡㆢㆣㆤㆥㆦㆧㆨㆩㆪㆫㆬㆭㆮㆯ
ㆰㆱㆲㆳㆴㆵㆶㆷㆸㆹㆺㆻㆼㆽㆾㆿ
ﾡﾢﾣﾤﾥﾦﾧﾨﾩﾪﾫﾬﾭﾮﾯﾰ
ﾱﾲﾳﾴﾵﾶﾷﾸﾹﾺﾻﾼﾽﾾￂￃ
ￄￅￆￇￊￋￌￍￎￏￒￓￔￕￖￗ
ￚￛￜ
```

* `Ϳ` (U+037F) is mistakenly mapped as an unused draft of `Ώ` (U+038F), this glyph will be removed in the version 0.3.
* Extended bopomofo was mapped wrongly, this was fixed when full-width Hangul components are added in the version.

| Unicode Block | New Glyphs |
| -- | -- |
| Latin-1 Supplement (Latin-9) | 122 |
| Greek | 69 |
| Cyrillic | 74 |
| Hebrew | 27 |
| Hiragana | 6 |
| Katakana | 9 |
| Bopomofo | 43 |
| Bopomofo Extended | 32 |
| Half-width Hangul | 51 |
| Total | 433 |

## 2022m35a (2022/12/11)

* Update the following glyphs in the libre font: `569jt`, as well as `0x85`.
* Update the following glyphs in the true font: `%&'()@&#96;jkmq~`.
* Glyph definitions for `0x7f` was briefly removed add `0x86` was briefly added at 2022-09-21 08:32:02, these changes are reverted in the version 2022m35a.

## 2022m33a (2022/11/21)

* Add a new typeface: True font, which covers ASCII only. Codepoints `0x7f` to `0x85` are assigned the same glyphs as the libre font.

## 2022m23a (2022/08/18)

* Add glyphs for ASCII.

A full list of glyphs newly added in this version (102 glyphs):

```
 !"#$%&'()*+,-./
0123456789:;<=>?
@ABCDEFGHIJKLMNO
PQRSTUVWXYZ[\\]^_
&#96;abcdefghijklmno
pqrstuvwxyz{|}~
▷▶︎♭♮𝄪𝄫
```

| Unicode Block | New Glyphs |
| -- | -- |
| Basic Latin (ASCII) | 95 |
| Non-Unicode standard shapes | 7 |
| Total | 102 |
