# Rime sync

1. All configurations are based on from Fcitx-Rime.
2. Schemas graph:
   1. wuwei_pinyin -> easy_en, emoji, wubi06 and terra_pinyin.dict;
   2. wubi06 -> pinyin_simp;
   3. pinyin_simp and terra_pinyin -> stroke;
   4. stroke -> luna_pinyin.
3. Check the following files before deployment:
   1. installation.yaml;
   2. default.custom.yaml;
   2. schemas with custom.yaml;
   3. Trime: essay.txt, opencc, trime.yaml
   4. Weasel: weasel.yaml
