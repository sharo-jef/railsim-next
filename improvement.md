# 現在の RailSim 2 の要改善点

- クラッシュ
    - `.txt` なファイルの文法エラー
        - 起動時のクラッシュはまあ良い
        - ゲーム中に選択した際にクラッシュするのは許容し難い
- オートセーブ
    - 2k のオートセーブみたいなやつ
- FPS
    - ゲームのシミュレーション速度に依存している
- 設定ファイルの文法
    - 独自の文法なので扱いづらい
        - 候補
            - yml
                - 条件式とか書きづらい？
            - 何かしらのプログラミング言語
                - JavaScript (Node.js)
                - Ruby
                - Python3
                - C# (.csx)
- 3D モデルの形式
    - `.x` 以外も読み込めるようにしたいかも？ (優先度低)
- Unity 等のエンジンを使って作れるならそちらのほうが良い
    - とにかく影や煙が重すぎる
    - クラッシュも減らせそう
    - (実装によっては) FPS 問題も解決しそう
- ゲーム機能
    - マルチプレイ
        - 2, 2k のマルチプレイは眺めるだけ
            - 同時編集できるようにしたい
            - 自動運転も
    - 自動運転での連結、切り離しがない
    - 曲線駅
    - ダイヤを組みづらい
        - A 列車をパクると良いかも？
