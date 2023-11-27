# Changelog

## 0.3 (2023m33a, 2023/11/29)

* Complete (basic) coverage for the following languages:
* * Ainu (Katakana)
* * Armenian
* * Belarusian
* * Coptic
* * Croatian (no tone marks yet)
* * Czech
* * Tai Nüa (a.k.a. Tai Le / Dehong Dai)
* * Esperanto
* * Full-width ASCII
* * Georgian
* * Kazakh (Cyrillic)
* * Kyrgyz
* * Lisu (Fraser alphabet)
* * Macedonian
* * Mongolian (Cyrillic)
* * Polish
* * Runes
* * Serbo – Croatian (Latin & Cyrillic, no tone marks yet)
* * Slovak
* * Slovene (no tone marks yet)
* * Tajik
* * Tuvan
* * Uzbek (Cyrillic)
* Add support for IPA glyphs within the range of U+0250 - U+029F.
* Add bagua and astronomical symbols.
* Add the following kanas: `ぎヷヸヹヺ`.
* Modify the glyphs for `Æ` (U+00C6), `Œ` (U+0152), `Ѳ` (U+0472) and `つ` (U+3064).
* Modify the glyph for `卯` (U+536F), `細` (U+7D30) and the related variants.
* Add the following 16 CJKV ideographs: `乌宗岛当敏明泉男礻福純衤裕郎郭鈴`, 9 of which (`敏明泉男福純裕郎鈴`) are urgently needed for Octavia UIs.
* Add the following 11 CJKV ideograph variant forms: `島嶋嶌烏當纯铃郎鈴福敏`.
* Remove the glyph for `Ϳ` (U+037F), which was mistakenly mapped as an unused draft of `Ώ` (U+038F) in the past versions all the way from v0.1 (2023m05a).
* Remove 34 empty glyphs, scattered around the Greek block and the half-width Hangul block.
* Add two new typefaces: HD44780U-A00 and A02 font, which both have ASCII, EASCII and remapped Unicode characters.

A full list of glyphs newly added in this version, excluding CJKV variant forms (484 glyphs):

```
ĀāĄąĆćĈĉČčĎďĐđĒē
ĘęĚěĜĝĤĥĪīĲĳĴĵĹĺ
ĽľŁłŃńŇňŊŋŌōŔŕŘř
ŚśŜŝŤťŪūŬŭŮůŹźŻż
ǍǎǏǐǑǒǓǔǕǖǗǘǙǚǛǜ
ǝǾǿ
ɐɑɒɓɔɕɖɗɘəɚɛɜɝɞɟ
ɠɡɢɣɤɥɦɧɨɩɪɫɬɭɮɯ
ɰɱɲɳɴɵɶɷɸɹɺɻɼɽɾɿ
ʀʁʂʃʄʅʆʇʈʉʊʋʌʍʎʏ
ʐʑʒʓʔʕʖʗʘʙʚʛʜʝʞʟ
ʠʡʢʬʭʮʯ˂˃˄˅ː˜˥˦˧˨˩
ϢϣϤϥϦϧϨϩϪϫϬϭϮϯ
ЀЂЃЅЈЉЊЋЌЍЎЏ
ѐђѓѕјљњћќѝўџ
ҒғҚқҢңҮүҰұҲҳҶҷҺһ
ӘәӢӣӨөӮӯ
 ԱԲԳԴԵԶԷԸԹԺԻԼԽԾԿ
ՀՁՂՃՄՅՆՇՈՉՊՋՌՍՎՏ
ՐՑՒՓՔՕՖ
 աբգդեզէըթժիլխծկ
հձղճմյնշոչպջռսվտ
րցւփքօֆև
ႠႡႢႣႤႥႦႧႨႩႪႫႬႭႮႯ
ႰႱႲႳႴႵႶႷႸႹႺႻႼႽႾႿ
ჀჁჂჃჄჅ Ⴧ     Ⴭ
აბგდევზთიკლმნოპჟ
რსტუფქღყშჩცძწჭხჯ
ჰჱჲჳჴჵჶჷჸჹჺ჻ჼჽჾჿ
ᚠᚡᚢᚣᚤᚥᚦᚧᚨᚩᚪᚫᚬᚭᚮᚯ
ᚰᚱᚲᚳᚴᚵᚶᚷᚸᚹᚺᚻᚼᚽᚾᚿ
ᛀᛁᛂᛃᛄᛅᛆᛇᛈᛉᛊᛋᛌᛍᛎᛏ
ᛐᛑᛒᛓᛔᛕᛖᛗᛘᛙᛚᛛᛜᛝᛞᛟ
ᛠᛡᛢᛣᛤᛥᛦᛧᛨᛩᛪ᛫᛬᛭ᛮᛯ
ᛰᛱᛲᛳᛴᛵᛶᛷᛸ
ᥐᥑᥒᥓᥔᥕᥖᥗᥘᥙᥚᥛᥜᥝᥞᥟ
ᥠᥡᥢᥣᥤᥥᥦᥧᥨᥩᥪᥫᥬᥭ
ᥰᥱᥲᥳᥴ
ᲐᲑᲒᲓᲔᲕᲖᲗᲘᲙᲚᲛᲜᲝᲞᲟ
ᲠᲡᲢᲣᲤᲥᲦᲧᲨᲩᲪᲫᲬᲭᲮᲯ
ᲰᲱᲲᲳᲴᲵᲶᲷᲸᲹᲺ  ᲽᲾᲿ
ẞ
₀₁₂₃₄₅₆₇₈₉
☰☱☲☳☴☵☶☷
♀♁♂♃♄♅♆♇
ⲀⲁⲂⲃⲄⲅⲆⲇⲈⲉⲊⲋⲌⲍⲎⲏ
ⲐⲑⲒⲓⲔⲕⲖⲗⲘⲙⲚⲛⲜⲝⲞⲟ
ⲠⲡⲢⲣⲤⲥⲦⲧⲨⲩⲪⲫⲬⲭⲮⲯ
ⲰⲱⲲⲳⲴⲵⲶⲷⲸⲹⲺⲻⲼⲽⲾⲿ
ⳀⳁⳂⳃⳄⳅⳆⳇⳈⳉⳊⳋⳌⳍⳎⳏ
ⳐⳑⳒⳓⳔⳕⳖⳗⳘⳙⳚⳛⳜⳝⳞⳟ
ⳠⳡⳢⳣⳤ⳥⳦⳧⳨⳩⳪ⳫⳬⳭⳮ
ぎヷヸヹヺ
ㇰㇱㇲㇳㇴㇵㇶㇷㇸㇹㇺㇻㇼㇽㇾㇿ
乌宗岛当敏明泉男礻福純衤裕郎郭鈴
ꓐꓑꓒꓓꓔꓕꓖꓗꓘꓙꓚꓛꓜꓝꓞꓟ
ꓠꓡꓢꓣꓤꓥꓦꓧꓨꓩꓪꓫꓬꓭꓮꓯ
ꓰꓱꓲꓳꓴꓵꓶꓷꓸꓹꓺꓻꓼꓽ꓾꓿
｟｠
```

A list of new characters that are remapped onto existing glyphs (105 glyphs):

```
ŒœŠšŸŽž€
↑→↓↖↗↘↙↲≠≤≥⏫︎⏬︎⏸︎█◀︎
◁●♥♪♫♭♮♯
　！＂＃＄％＆＇（）＊＋，－．／
０１２３４５６７８９：；＜＝＞？
＠ＡＢＣＤＥＦＧＨＩＪＫＬＭＮＯ
ＰＱＲＳＴＵＶＷＸＹＺ［＼］＾＿
｀ａｂｃｄｅｆｇｈｉｊｋｌｍｎｏ
ｐｑｒｓｔｕｖｗｘｙｚ｛｜｝～
￠￡￥
```

Libre font:

| Unicode Block | New Glyphs |
| -- | -- |
| Latin Extended-A | 64 |
| Latin Extended-B | 19 |
| IPA | 87 |
| Spacing Modifier Letters | 11 |
| Coptic (Old block) | 14 |
| Cyrillic | 48 |
| Armenian | 77 |
| Georgian | 88 |
| Runes | 89 |
| Tai Le | 35 |
| Georgian Extended | 46 |
| Latin Extended Additional | 1 |
| Superscripts and Subscripts | 10 |
| Miscellaneous Symbols | 16 |
| Coptic (New block) | 111 |
| Hiragana | 1 |
| Katakana | 4 |
| Katakana Phonetic Extensions | 16 |
| CJKV Ideographs | 16 |
| CJKV Ideographs (Repeated) | 7 |
| Lisu | 48 |
| CJK Compatibility Ideographs | 4 |
| Full-width ASCII | 94 (old glyphs) |
| Full-width Brackets | 2 |
| Total | 814 |

## 2023m27a (2023/09/26)

* Update `<` and `>` for true font.

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
* Update the following glyphs in the true font: `%&'()@jkmq~`, as well as `0x60`.
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
PQRSTUVWXYZ[\]^_
`abcdefghijklmno
pqrstuvwxyz{|}~
▷▶︎♭♮𝄪𝄫
```

| Unicode Block | New Glyphs |
| -- | -- |
| Basic Latin (ASCII) | 95 |
| Non-Unicode standard shapes | 7 |
| Total | 102 |
