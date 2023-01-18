#include <Arduino.h>

#define STR_SIZE 54
#define CHAR_SIZE 200

const char str[STR_SIZE][CHAR_SIZE] PROGMEM= {
"    `  `  `  `  `  `  `  `     `  `                                                                                                                                                                `\n", "                                     `\n", "                            `           `                                                                                                                                                       `    `\n", "   `                                       `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `\n", "      `  `  `  `  `  `  `       `  `                                                                                                                                                          `\n", "                           `          `                                                                                                                                                           `\n", "   `                          `         `                                                             `.                                                                                   `         `\n", "               `        `                  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `    ...  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `\n", "      `  `  `      `        `    `  `                                                               ` ..~  ._                                                                            `    `  `\n", "   `                  `                 `                                                            ~.._._.~                                                                                       `\n", "               `                                                             ~                      ..._<.._`.\n", "                   `     `  `  `           `  `  `  `  `  `  `  `  `  `  ` ..`  `..Jdqqkqkqkqkqqka,..(+--__~_    `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `   `  `\n", "   `   `  `                       `  `  `                                 .._ .+kHHqHHkkkkkqHHHqkqqhdHHm+1,`                                                                                    `  `\n", "             `  `     `                                                   ._(kkkHkkkkkkkkkkkkkkkkkkHNkHHHkx-\n", "                           `               `                             _(6uKUHkkkkkkkkHHkkkkkHHH3?HHkkHHkk>                                                                          `    `        `\n", "   `  `            `          `  `     `       `  `  `  `  `  `  `  ` .WHJzdK>JK+zTUUUWHHHHpHHY1>?HuHHHkkHHbHo.  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `             `\n", "         `  `  `       `            `                               .1HgH1XWC>db>>;>;>>;dm>?HpHs<+&WHkHHkkHkkHci.                                                                        `\n", "                          `             `   `                       (dggCdHK>>Xb<>>;>+111HNJ?dkWHkkkHHHHNkkkkkkmxI.                                                                   `      `      `\n", "   `              `         `    `                                  <WgHbHWHQgHMg&gagAQmkk6-Y1dHfHkkkHHkgNkkkkkkgHHkh,.                                                                         `\n", "      `       `      `                         `  `  `  `  `  `     .HgkkHWHkkgHHkkkkkkHHH_jmWg@MHHkkkHHHHgHkkkkHggHkkkW..  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `  `\n", "                               `        `  `                     `   4MkkHg@HH@<HgHkHbbpHHHHqm, ?HWkkkkHkkkHHkkkkHggHkkkkkh,\n", "                                                                      HkkHHggHX_JqqqWHfWWWHMvUC ,HHkkkHK(WkkHMkkkHgggHkkkHHkH+\n", "                  `         `                                         HkkkKHHgHHgMHppffVW/v<~_!..qqkkkHH_(kkkD,WkkHgggHkkkkHHHka.\n", "      `                                 `            `  `             WkkHHY?WHWVH$?f4XXXV>...` .WHbkkHHeJHkkD  TkHg@ggHkkkkHHHHkn.\n", "                                                                `     ,kkkH- .?<~<!``__````````  JHbkkkHHgHWpR   ,Hgggg@HkkkkkHgHkHn.\n", "                 `            `            `                       `   HkkkN-  ..```` `` ``     `(HkkkkHgmf(4W,    4gggg@HkkkkkHgHHkHa.\n", "                                        `          `                   (kkkHb `````` ` .(<;< `  ` vHbbbHB=```.?1=z<<THgggHkkkkkkHggHkH@o\n", "     `                      `                         `  `     `       .WbbbN_``      .<<<!` `    (HHfWW[```````.4I;;;;;<zUHHHkkkHggkkHHH,\n", "                 `                                                     dHHfWWh. ` ` ` `  `  ` ` ._.(4MkXXl.   `  (<;;;;;;;?HWWBHkkHgHkkHHgN,\n", "                               `        `          `        ...........TTTTWXWHh.. `````` ` ..g#_-!.<dM,_~!     (<;;;;;;;;:Xp6dHkkHggHkkH,4@L\n", "                            `              `              ?&dAX>:;;;;;;;+uzzWWXWUY7'<<((ugH$:dMQ/```.MWd,` ` ` (>;;;;;;;;;;J6dgkkkkggHkkkb -Wv,\n", "      `          `                             _.     ..--..dkD:;;;;;;;;;;1--    ` ``  (MM1..MMB5.`.dW@MMo`   .J;;;;;+&?+;;+MHHkkkkggHkkkk,  ?z,\n", "                                        `      _`.- .,pW@@@HHgHJ;;;;/(vwx;;;?- `       dHLJ+J:,.+xJH@BTM@@p ..(>;;;;jvrzIJdggMHkkkkggHkkkk]    j.\n", "                            `              !-`_`~`.HHpfpWM@@@MHgHe+zJzOI<;;;;;+, ``  `_HHWMM@@HMHHY4b_`-W@@N,.+;;;;;c(V>jH$HHHHHHHHgHkkkkkD     1\n", "                 `             `           .~~ `!`JHHfppppM@@@@MNHNHNx+1>;;;;;;;1_ `  (!.H%`` J ```,@-``.?M@@NI;;;;;;+(7H1WHpffWMHggHHkkkkP     ,.\n", "                                           .?` `` XNpffpfppWMM@@@@@MMN&+;;;;;;;;;?,---/ dM!```]````,Y\\``` <?WM>;;;;;;jWgkHfpfppffpHMHggHHk%     c{\n", "      `                     `               .!` `.XNppffpffppfpHHHWHggggHx<;;;;;;;?Xzz:.<>````]````_ .```` <:(;;;;;;jWgHpfpfpfppfppfkvWggH`    (w`\n", "                 `                                ?$ZWppfpffpfpppppppHHggggHa+;;;;;<Xw_  `````]``````_``` ``~(;;;;;jHHHfpfpfpffpffppppk+?F   .XbP\n", "                               `        `          .1?XWpfppfpffffffpfpWHggMgggmx<;;<X)     ``(`  `` ``    ..N;;;;jgMHpffpfpfppfpffffpfWxz .dkbf\n", "                            `                         ?<OWpfpfppfppffpfWgggMHggNHMR<;?X,..     {     ` ...HY=.+;;j@MgHHppfpfpffpppfppfppfXHHkk=\n", "                 `                                         ?''TTTTUYY'TWHMHQH@@@MM3I;JzznJ<;:::?I:<+j+gMf!````I;;vH@@HHHpfpfppfffppffpfpWbdY'~.\n", "      `                                 `                            ...d@@@@@MMH$<<JzzzzYWMMHYYW9'T1+#^````` <1<<?W@@@MM@HHWWppffpfpfpWMW\\  ..~`\n", "                            `              `                ....JxTWMe?W@@@MMMHH3;<Jzzzzzt`(?TBQJe+d5: `````` <+U+;<WMMMM@M5;jMNkpfpfpWHH$   .,~`\n", "                 `             `                           I?1pHfWm>?MNJ?WMHHpWC;+wzzzzzzua-J(JXY=?7TYBBWUUVT""<Ozo;;UHHHHNgjH@@;?HfpWMH3_ ...~`\n", "                                        `              `   I?dfWppWWA<dMMHppfK>;jXzzzzzzw!~~``...       ` ````` <4zG+;?HWfpHHM#;;JpWWHf~` {\n", "                            `                              IjWWWHHHHHHWHppfpf<;jXzzzzzzz%````` __~<<::_-..  ````_:?Two;<TWpfWHHN&HHMHHgY. :\n", "      `          `                         `        `      IdHppfpfpfWppfpp6;;JzzzzzzzzZ `` ``````    _`` ``````` `_~?71<;?WHkfpWHpWHf`\n", "                               `        `                  (fWpfpfpWWW9UYY3;+wzzzzzzzzzr` `  ``````````````````````````` ?i;?WHkfpWH9{\n", "                            `                          `   .kpHWWUYC;;;;;;++uwwwwuzzzzu:`    ```````` ``````` ` `````   __..1:?4HY4K+~\n", "                 `                                 `        jpV=~~::::;;<!.WkHmmHqmggHf` ._`  ````````` ```` _~.`````    (?-`(-~(wHD+_\n", "                                        `                    >~~~~~::<?`  dX\\(WWHWUWWW(``.(``   ``` ````` ```..?-``` `  ` (+akHJWZUr:}\n", "      `                     `              `                  <~~~:(!    ,jr  UvSXvzV!.` .<;`     ````````````1:<>``   ` .gHHWBV(wvI:(.\n", "                 `             `                   `  `        <~(!     .>J`   kXwrv` .` `>+    `      ``` ``.Hx:<<` ..XbHY(WUv  (rw_~<.\n"};

//二次元配列を扱うための配列テーブル
const char* const str_table[] PROGMEM = {
  str[0], str[1], str[2], str[3], str[4], str[5], str[6], str[7],
  str[8], str[9], str[10], str[11], str[12], str[13], str[14],
  str[15], str[16], str[17], str[18], str[19], str[20], str[21],
  str[22], str[23], str[24], str[25], str[26], str[27], str[28],
  str[29], str[30], str[31], str[32], str[33], str[34], str[35],
  str[36], str[37], str[38], str[39], str[40], str[41], str[42],
  str[43], str[44], str[45], str[46], str[47], str[48], str[49],
  str[50], str[51], str[52], str[53]
};

void setup() {
  Serial.begin(9600);
  Serial.println("SerialBegin");
  Serial.println("Charactors from PROGMEM");
}
 
void loop() {
  for (byte i = 0 ; i < STR_SIZE ; i++){
    char buf[200];
    /*
    フラッシュメモリの読み出し
    1byte)pgm_read_byte(フラッシュメモリ上アドレス)
    2byte)pgm_read_word(フラッシュメモリ上アドレス)
    引数は変数名を記述
    strcpy_P(結果を代入する変数、フラッシュメモリ上アドレス)
    */
    strcpy_P(buf, (char*)pgm_read_word(&str_table[i]));
    Serial.println(buf);
  }
  delay(2000);

  /*
  byte data_size = Serial.available();

  if (data_size > 0)
  {
    delay(20);
    data_size = Serial.available();
    byte buf[data_size];
    Serial.print(F("data_size "));
    Serial.println(data_size);
    for (byte i = 0; i < data_size; i++){
      buf[i] = Serial.read();
      Serial.print((char)buf[i]);
    }
    
    Serial.println();
  }
  //*/
}


/*
https://jumbleat.com/2017/10/26/send_value_from_serial_monitor/
Serial.avilable();
シリアル通信を受信したらキャッシュするタスクを常時行う。
受け取ったバイトデータの個数を返す。最大で64バイトまでキャッシュする。
受信がなければ0を返す。

Serial.read();
受信してキャッシュしているデータを1バイトずつ吐き出す。
呼び出すごとにキャッシュはクリアされるのでSerial.availableの返り値も減っていく。
*/
