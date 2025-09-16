# ikema_tts_evaluation
このリポジトリでは，池間西原方言テキスト音声合成の主観評価に用いた，方言特徴が反映されている評価文100文を提供しています．

## Dataset structure / データセット構成
```
- ikema_tts_evaluation_sentence.csv
```

#### `ikema_tts_evaluation_sentence.csv`

| ID   | sentence   | reason_for_choice      |
| ---       | ---   | ---           |
| ikmevl_0001    | さなう さす。    | 母音の無声化あり  |
| ...       | ...   | ...           |

- `ID`: 評価文のID．
- `sentence`: 評価文．
- `reason_for_choice`: なぜその文を評価文として選んだのか．
