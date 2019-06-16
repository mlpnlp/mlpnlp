# 機械学習プロフェッショナルシリーズ 深層学習による自然言語処理
このページで正誤表を管理します。書籍の誤植等を見つけられた方は https://github.com/mlpnlp/mlpnlp/issues にIssueを作ってお知らせいただけると幸いです．

| issue | 報告者 | ページ | 修正前 | 修正後 | 修正済版　　|
| --- | ---- | ----  | ----| ----- | ------- |
| [#1](https://github.com/mlpnlp/mlpnlp/issues/1) | [shirayu様](https://github.com/shirayu) | p. 113 | noise contrasive estimation | noise contras**t**ive estimation | 第2刷 |
| [#2](https://github.com/mlpnlp/mlpnlp/issues/2) | [tam17aki様](https://github.com/tam17aki) | p. 40 | 「... この仮定**を**時間ごとに異なるパラメータを使うモデルに比べてパラメータ数が減り、...」 | 「... この仮定**により**時間ごとに異なるパラメータを使うモデルに比べてパラメータ数が減り、...」 | 第3刷  |
| [#3](https://github.com/mlpnlp/mlpnlp/issues/3) | [@stomohide様](https://twitter.com/stomohide/status/871979229310615552) | p. 36 式(2.62)| ![before](https://user-images.githubusercontent.com/1034551/26880097-4d804562-4bce-11e7-9702-6c1a5b48af6c.png)| ![after](https://user-images.githubusercontent.com/1034551/26879122-e2205080-4bca-11e7-8f99-b12af5b198be.png)| 第3刷 |
| [#4](https://github.com/mlpnlp/mlpnlp/issues/4) | [eiichiroi様](https://github.com/eiichiroi) | p. 109 式(4.35) |  ![softmax-eq-4 36-error](https://user-images.githubusercontent.com/1034551/26880211-a560831e-4bce-11e7-8df5-2de7ce99cc5c.png) | ![softmax-eq-4 36](https://user-images.githubusercontent.com/1034551/26879398-e4c9ed18-4bcb-11e7-8056-e7515e70d779.png)| 第3刷 |
| [#5](https://github.com/mlpnlp/mlpnlp/issues/5) | [tomohideshibat様](https://github.com/tomohideshibata) | p. 92 式(4.4) | ![eq4 4org](https://user-images.githubusercontent.com/1034551/27506122-f070e5ee-58ec-11e7-94fd-bd74d222b4e5.gif) | ![eq4 4new-bmatrix](https://user-images.githubusercontent.com/1034551/27506033-d27c0660-58ea-11e7-9c69-abd7e886717b.gif)  | 第4刷 |
| [#5](https://github.com/mlpnlp/mlpnlp/issues/5) | [tomohideshibat様](https://github.com/tomohideshibata) | p. 94 式(4.7) |  ![eq4 7org](https://user-images.githubusercontent.com/1034551/27506127-fcf22724-58ec-11e7-9846-1c09a394b9f6.gif) | ![eq4 7new-bmatrix](https://user-images.githubusercontent.com/1034551/27506036-dfa2d06c-58ea-11e7-90ce-4ce1b8b10cb9.gif) | 第4刷 |
| [#6](https://github.com/mlpnlp/mlpnlp/issues/6) | [tomohideshibat様](https://github.com/tomohideshibata) | P.92 最終段落 | ほとんど**最初の**3単語のみの情報 | ほとんど**3番目の入力**単語のみの情報 | 第4刷 |
| [#7](https://github.com/mlpnlp/mlpnlp/issues/7) | [shirayu様](https://github.com/shirayu) | P.24 最終段落 | 必ず微分係数が1以上になります | ![p24-fl](https://user-images.githubusercontent.com/1034551/27505982-5df26b64-58e9-11e7-9802-a9c5ea5e1028.gif)の微分の絶対値が小さくても全体の微分係数は1に近い値になります | 第4刷 |
| [#8](https://github.com/mlpnlp/mlpnlp/issues/8) | [himkt様](https://github.com/himkt) | P.10 式(2.5) | ![eq2 5org](https://user-images.githubusercontent.com/1034551/28116924-302dbccc-6746-11e7-83e8-59bd2fca1456.gif) | ![eq2 5new](https://user-images.githubusercontent.com/1034551/28116933-3484360c-6746-11e7-8911-4fd873f9c434.gif) | 第4刷 |
| [#9](https://github.com/mlpnlp/mlpnlp/issues/9) | [yuutat](https://github.com/yuutat) | P.146-148 図5.6, 図5.7, 図5.8 符号化器  | ![figure5 6-5 8org-small](https://user-images.githubusercontent.com/1034551/28145538-02895700-67ae-11e7-98bc-7cf3d99436e1.png) (緑の箱が実線)| ![figure5 6-5 8new-small](https://user-images.githubusercontent.com/1034551/28145539-0290396c-67ae-11e7-986f-32f40c478915.png)　（緑の箱は点線。ただし、入力の１つ目だけは実線） | 第4刷 |
| [#10](https://github.com/mlpnlp/mlpnlp/issues/10) | [yuutat](https://github.com/yuutat) | P.166 図 6.3 凡例| 「訓練データでの誤差」が青線、 「訓練データ以外での誤差」が黒線| 「開発データでの誤差」が青線、 「訓練データでの誤差」が黒線 | 第4刷 |
| [#11](https://github.com/mlpnlp/mlpnlp/issues/11) | [scapegoat06様](https://github.com/scapegoat06) | P.29 3段落目| 入力列全体 ![p29-inputseq-org](https://user-images.githubusercontent.com/1034551/28168766-1a22c3d4-681b-11e7-86c0-493fd41c9713.gif)| 入力列全体 ![p29-inputseq-new](https://user-images.githubusercontent.com/1034551/28168770-1ebaa290-681b-11e7-912f-849936df910c.gif) | 第4刷 |
| [#13](https://github.com/mlpnlp/mlpnlp/issues/13) | [arumtaunsaram様](https://github.com/arumtaunsaram) | P.79 (4) 復号化器再帰層| 復号化器**埋め込み**層の処理に対する入出力は　| 復号化器**再帰**層の処理に対する入出力は |  |
| [#14](https://github.com/mlpnlp/mlpnlp/issues/14) | [ysekky様](https://github.com/ysekky) | P.100 一般化 | gene**l**a**r**ization | gene**r**a**l**ization |  |
| [#16](https://github.com/mlpnlp/mlpnlp/issues/16) | [ysekky様](https://github.com/ysekky) | P.106 4.2.4節 | sem**e**ntic memory module | sem**a**ntic memory module |  |
| [#18](https://github.com/mlpnlp/mlpnlp/issues/18) | [ktphy様](https://github.com/ktphy) | P.68 式(3.22) |![eq3 22org](https://user-images.githubusercontent.com/1034551/30139340-404bc3cc-93a8-11e7-833d-cd68a7c0e1af.gif) | ![eq3 22new](https://user-images.githubusercontent.com/1034551/30139348-49905c40-93a8-11e7-9b95-a957f2226f3a.gif) (exp 抜け) |  |
| [#21](https://github.com/mlpnlp/mlpnlp/issues/21) | [dkawahara様](https://github.com/dkawahara) | P.32 4行目 |対処でき**る**ます | 対処できます|  |
| [#23](https://github.com/mlpnlp/mlpnlp/issues/23) | [murawaki様](https://github.com/murawaki) | p.137 下から10行目 |連結します関数concat | 連結します．　関数concat|  |
| [#24](https://github.com/mlpnlp/mlpnlp/issues/24) | [murawaki様](https://github.com/murawaki) | P.53 式(3.14) |![eq3 14org](https://user-images.githubusercontent.com/1034551/30139885-a4bba978-93ab-11e7-8110-10eced7b7063.gif)| ![eq3 14new](https://user-images.githubusercontent.com/1034551/30139887-a8226f20-93ab-11e7-83fb-2e93d2721351.gif)|  |
| [#24](https://github.com/mlpnlp/mlpnlp/issues/24) | [murawaki様](https://github.com/murawaki) | P.54冒頭 |![p54-pmodelorg](https://user-images.githubusercontent.com/1034551/30139895-bf926a48-93ab-11e7-93cf-77835b1d9c57.gif)| ![p54-pmodelnew](https://user-images.githubusercontent.com/1034551/30139901-c3d6b474-93ab-11e7-9f2f-20419abc18bf.gif)|  |
| [#24](https://github.com/mlpnlp/mlpnlp/issues/24) | [murawaki様](https://github.com/murawaki) | P.55 式(3.15) |![eq3 15org](https://user-images.githubusercontent.com/1034551/30139916-d47faede-93ab-11e7-9582-5addd3f13a54.gif)| ![eq3 15new](https://user-images.githubusercontent.com/1034551/30139920-d8fadbfa-93ab-11e7-9bca-ae9c5a136c93.gif)|  |
| [#26](https://github.com/mlpnlp/mlpnlp/issues/26) | [dkawahara様](https://github.com/dkawahara) | P.100 4.2.1節 2行目|モデル考えます| モデルを考えます|  |
| [#27](https://github.com/mlpnlp/mlpnlp/issues/27) | [dkawahara様](https://github.com/dkawahara) | P.103 式(4.25) の中央の項|![eq4.24org](https://user-images.githubusercontent.com/1034551/59075615-9e4d7500-890c-11e9-8cea-b30e068e7fd8.png)| ![eq4.24new](https://user-images.githubusercontent.com/1034551/59075608-8ece2c00-890c-11e9-9801-fb4b1d1d7ac8.png) （最後のxをboldに)|  |
| [#28](https://github.com/mlpnlp/mlpnlp/issues/28) | [dkawahara様](https://github.com/dkawahara) | P.104 4.2.3節 下から２行目|質問文 q| 質問文 **q**|  |
| [#29](https://github.com/mlpnlp/mlpnlp/issues/29) | [dkawahara様](https://github.com/dkawahara) | P.107 4.2.4節 下から２行目|ベクトル使って| ベクトルを使って|  |
| [#31](https://github.com/mlpnlp/mlpnlp/issues/31) | [dkawahara様](https://github.com/dkawahara) | P.154 5.4.1節 最下行|文のベクトルを単一のベクトルに符号化します| 文を単一のベクトルに符号化します|  |
| [#33](https://github.com/mlpnlp/mlpnlp/issues/33) | [tezoooka様](https://github.com/tezoooka)  | P.102 4.2.2節 上から２行目|内部情報とし扱います| 内部情報として扱います|  |
| [#35](https://github.com/mlpnlp/mlpnlp/issues/35) | [taku-buntu様](https://github.com/taku-buntu)| P.14 参考2.2 最下段|期待があるのだと思いますの| 期待があるのだと思います|  |
| [#38](https://github.com/mlpnlp/mlpnlp/issues/38) | [kamujun様](https://github.com/kamujun) | P.132 5.2.1節 |test summarization challenge (TSC)| text summarization challenge (TSC)|  |
