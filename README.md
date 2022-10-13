# terbilang-php
Class PHP merubah number ke bahasa

## Penggunaan
require_once("NumberLang.php");

***untuk kebahasa Inggris***
echo NumberLang::toEnglish("1500");
*//Output: One Thousand, Five Hundred*

***untuk kebahasa Indonesia***
echo NumberLang::toBahasa("1500");

*//Output: Seribu Lima Ratus*

Class kebahasa Inggris Modifikasi dari [barokurniawan](https://gist.github.com/barokurniawan/45097f3d5595ea038cc30c1cdf7b90dc).
