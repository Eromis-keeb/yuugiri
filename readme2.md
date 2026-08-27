# 夕霧、桐壺 共通 ケース・組込みビルドガイド
夕霧は以下の特徴を備えるキーボードです。
- ４２キーオーソリニア配列（直交配列、サムクラスタ変則）
- １つのロータリーエンコーダー（プッシュボタン付き）
- ２つのトグルスイッチによる機能変更（レイヤー変更）
- LEDによるライティング（インジケーターの役割もある）
- 自由に柄など（0.5mm以下の紙など）をあしらえる額縁（夕霧は裏側のみ）プレート
- - ※作例では千代切り紙（バックストリートファクトリー製）を使用した例です。キットには同梱されません。  

ファームウェアはVial対応です。  <br/>
<br/>



## 組み立てにあたって

<img width="1024" height="768" alt="EC1B3D02-78BA-4D1A-BB50-DE724829FE93_1_105_c" src="https://github.com/user-attachments/assets/cd09a239-61b9-4ed0-9807-34ba85106b81" /> <br/>

<br/>
<br/>
本キットには基板完成済みの通常版と基板の組み立てが必要なチャレンジキットがあります。<br/>
→こちら<br/>
https://github.com/Eromis-keeb/yuugiri/blob/2217565ba8053d60883e2770c6a3af40b1092aee/readme.md <br/>
通常版の場合も最初から最後まで読むことである程度仕組みが解るので読んで頂いたほうが良いと思います。<br/>
カスタムプレートを使用する場合もチャレンジキット用のビルドガイドの最後にカスタムガイドがあります。<br/>



## 必要な物

### キット付属のもの

部品|個数
--|--
夕霧 基板(完成)|x1
トッププレート（アクリル）|x1
ミドルプレート上|x1
ミドルプレート下|x1
カスタムミドルプレート下|x1
ボトムプレート（アクリル）|x1
ミドルフレーム（アクリル）|x1
取っ手用ミドルフレーム（3DP製）|x1
取っ手|x1
スペーサー（10mm）|x9
トップ用ネジ（5mm）|x9
ボトム用ネジ（8mm）|x9
脚用ネオジムマグネット(穴あき)|x2
脚用マグネットカバー|x2
脚|x2




### 各自用意するもの
部品|個数
--|--
MXキースイッチ |x10
MXキーキャップ |x10
ロータリーエンコーダーノブ（直径17mmくらいまで）|x3



部品はTALPKEYBOARDさん、遊舎工房さん、秋月電子通商さん、マルツオンラインさんで調達しています。<br/>
<br/>
<br/>
## 組み立て
基板部分は夕霧基板を使用して解説していきますが、どのモデルでも内容は同じなので適宜読み替えてください。<br/>
ところどころ別基板の写真が使われいる箇所がありますが、こちらも適宜読み替えて眼の前の基板と照らし合わせて組み立てを行ってください。
<br/>

### 1.ボトムプレートの組み立て
#### 1-1.脚の組み立て<br/>
<br/>
ボトムプレートを組み立てていきます。<br/>
<img width="2048" height="1536" alt="35ECBC9F-395A-4E59-8E8E-3F31BEBFCB89_1_102_o" src="https://github.com/user-attachments/assets/3203a6d2-b6d9-499d-8b5e-b940077a9e27" /> <br/>

<br/>
<br/>

まず初めにマグネット脚を組み立てます。<br/>
<img width="1536" height="2048" alt="889E0885-E68E-4170-BEFA-8FDCB5975300_1_102_a" src="https://github.com/user-attachments/assets/5d22e5fc-ba1c-447f-b41f-28bb78c2481a" /> <br/>
ネオジムマグネット（穴あき）2つ、マグネット脚用カバー2つ、通常脚２つ、ボトム用ネジ（８mm）４つ用意します。<br/>
<br/>
<br/>

マグネット脚用カバーの表裏を確認します。<br/>
<img width="4032" height="3024" alt="3D85E10E-7033-4DA5-844B-C60AE2930741_1_201_a" src="https://github.com/user-attachments/assets/5bbe2c71-aa01-46a5-9705-5eb852528da1" /> <br/>
でこぼこした面が底面、若干穴が広くなっている方が上面です。<br/>
<br/>
<br/>

ネオジムマグネット（穴あき）をカバーに嵌め込みます。<br/>
<img width="3024" height="4032" alt="7386E9FB-65FB-4E94-9F0C-DC86050F54E5_1_201_a" src="https://github.com/user-attachments/assets/12fde933-7fd9-48ba-992e-bc86391891bb" /> <br/>
上面（穴の広い方）を上に穴あきマグネットの窪んでいる方が上になるように嵌め込みます。<br>
<br/>
<br/>

持ち上げた時にマグネットが落下しないのが正解の向きです。<br/>
<img width="768" height="1024" alt="89FED13F-75E0-4C19-8C53-208BA437D89F_1_105_c" src="https://github.com/user-attachments/assets/63d47d40-c4c0-43c9-8848-d719e3885b3a" /> <br/>
<br/>
<br/>

カバーに嵌め込んだマグネット脚にネジを入れます。<br/>
<img width="768" height="1024" alt="1E1E7649-2C07-46B9-9E78-ABA967FD5426_1_105_c" src="https://github.com/user-attachments/assets/f0f2959b-1438-411e-9f47-ddf04c2cad5e" /> <br/>
<br/>
<br/>

<img width="3024" height="4032" alt="1E1E7649-2C07-46B9-9E78-ABA967FD5426_1_201_a" src="https://github.com/user-attachments/assets/67a77d89-b6a7-4ed2-907b-5e2d0e8b20aa" /> <br/>
<br/>
<br/>

マグネットの窪みにネジ頭がはまるように差し込みます。<br/>
<img width="768" height="1024" alt="22C73C22-2449-4EC3-9B27-5FEA223553B6_1_105_c" src="https://github.com/user-attachments/assets/0c04971e-b00a-4a38-a797-aad67548f0a9" /> <br/>
持ち上げた際にネジが落下しなければ正解の向きです。<br/>
<br/>
<br/>

同様にもう一つを作成します。<br/>
<img width="1536" height="2048" alt="F2C116EB-2769-41E2-AF0A-8AFA8A0E0C27_1_102_a" src="https://github.com/user-attachments/assets/af686d70-5377-4ff8-9d03-b27811f68c4e" /><br/>
マグネット脚のできあがり。<br/>
<br/>
<br/>

続いて通常脚を作成します。<br/>
<img width="3024" height="4032" alt="23E4F986-0A1D-4181-ADE3-903D26D304FD_1_201_a" src="https://github.com/user-attachments/assets/bcccdda1-bfdc-4481-8607-5d9ff5652c26" /> <br/>
赤枠内の穴の小さい部品を使います。<br/>
<br/>

8mmネジをドライバーを使ってねじ込んでいきます。<br/>
<img width="3024" height="4032" alt="7580F283-7379-47BA-BB3C-0030A2CBF134_1_201_a" src="https://github.com/user-attachments/assets/b094eddd-c30f-45c6-918a-4cabb8ab332d" /> <br/>
<img width="1536" height="2048" alt="EA0AA4E5-E3F8-4E1A-89D9-8F03FD29EA79_1_102_o" src="https://github.com/user-attachments/assets/ce823ba8-5b95-4cfd-aa41-5142af6d4aee" /> <br/>
<img width="1536" height="2048" alt="23C7815B-66A1-4136-8DFF-0967704618F5_1_102_o" src="https://github.com/user-attachments/assets/ad579330-13bb-4c8a-b1ee-4cb25452fcd7" /> <br/>
このように平らになるまで捻じ込めばOK <br/>
<br/>







#### 1-2.スペーサー取り付け<br/>
<br/>

<img width="2048" height="1536" alt="7C98727F-9FBD-485A-A90A-8EDAA6325B6F_1_102_o" src="https://github.com/user-attachments/assets/6d29a13c-be6e-40c0-8ecb-69eed15918cd" /> <br/>
ボトムプレートと１−１で作成したマグネット脚、通常脚、スペーサー、ボトム用ネジを用意します。<br/>
<br/>
<br/>

ボトムプレートのシートを剥がします。<br/>
<img width="2048" height="1536" alt="E5ACC21F-AF40-4758-B8E5-7311C72D2A7D_1_102_o" src="https://github.com/user-attachments/assets/c8d4eacc-c105-458f-b9c6-4fad29d5f2e9" /> <br/>
裏表があるので気をつけてください。トッププレート（アクリル）を重ねるなどして穴の位置を合わせておくとよいでしょう。<br/>
<br/>
<br/>


９箇所にスペーサーを取り付けていきます。<br/>
<img width="4032" height="3024" alt="475AF272-3C8F-4894-ABC7-BE4B44F7E26F_1_201_a" src="https://github.com/user-attachments/assets/52403b43-817c-48e6-98aa-bfedf36c9f2b" /> <br/>

青枠部分の９箇所にスペーサーをネジで取り付けます。<br/>
四隅はすでにネジが付いているので、その内側の５本を先に付けていきます。<br>
ボトム用ネジ（8mm）を５本用意します。 <br/>
<br/>
<br/>

内側５箇所にスペーサーを取り付けます。<br/>
<img width="4032" height="3024" alt="9517394F-3090-4132-8F9F-15F21A87896E_1_201_a" src="https://github.com/user-attachments/assets/717dec13-5d60-483e-a841-37add4d50a7c" /> <br/>
<br/>
<br/>

上面側にスペーサー、底面側からネジを差し込みます。<br/>
<img width="3024" height="4032" alt="73D179DD-903A-45F3-9622-4AB4DF6DA667_1_201_a" src="https://github.com/user-attachments/assets/fd69f4e4-6a0d-499a-8f7e-024bbc2786bc" /> <br/>
<br/>
<img width="768" height="1024" alt="A90B3763-A033-40C1-B452-C1A9FFA496CD_1_105_c" src="https://github.com/user-attachments/assets/9a87e66a-9697-4e07-94cb-d3c4db4b1ee8" /> <br/>
裏面側からドライバーでネジ止めします。しっかり締めてください。<br/>
<br/>
<br/>

スペーサーを取り付けた所 <br/>
<img width="2048" height="1536" alt="27321502-02C0-4ABC-B115-A97F3F0970F5_1_102_a" src="https://github.com/user-attachments/assets/18d3289a-53d2-4e3e-9f42-c43cad399270" />
 <br/>
１つ出来たら残り４箇所にもにもスペーサーを取り付けます。<br/>
<br/>
<br/>

１−１で作成したマグネット脚を同じ要領で上部に２つ取り付けます。<br/>
<img width="4032" height="3024" alt="DB5C9089-646D-40F0-92C1-330C861E22EE_1_201_a" src="https://github.com/user-attachments/assets/6e41d454-7d46-4bb5-a19c-06b0e8b57c88" /> <br/>
裏表を間違えないように気をつけましょう。 <br/>
切り欠きのある上部にマグネット脚x２ <br/>
切り欠きのない下部に通常脚x２ <br/>
<br/>
<br/>


<img width="768" height="1024" alt="11F68660-5C6A-451B-9645-E2E7F07E6B88_1_105_c" src="https://github.com/user-attachments/assets/764f96f7-0917-48d6-914f-b040d91bc28a" /> <br/>
<br/>
<br/>

取り付け完了状態（上面） <br/>
<img width="4032" height="3024" alt="E1AC9AAD-BF29-4419-B776-5B809F75F651_1_201_a" src="https://github.com/user-attachments/assets/5c4c6894-370b-4892-bc8e-e1bc8e93a9cf" /> <br/>
<br/>
<br/>

取り付け完了状態（底面） <br/>
<img width="4032" height="3024" alt="8E98EA5A-AE4C-4555-AA88-74AAB9F2E1D2_1_201_a" src="https://github.com/user-attachments/assets/15c835d0-5c73-4412-9c7c-5e79e75ccb33" /> <br/>
これでボトムプレートは完成です。<br/>
<br/>
<br/>






### 2.基板の組み付け
#### ２-1.ミドルフレームの取り付け<br/>
<br/>

1ー2までに作ったボトムプレートにミドルフレームを組み付けていきます。<br/>
ここでは取っ手付きミドルフレーム（３DP製）を使用した場合の説明をしますが、アクリルフレームを使った場合も同じ手順です。<br/>
<img width="2048" height="1536" alt="54F3929C-294C-4995-B580-9CCCAD9A0910_1_102_o" src="https://github.com/user-attachments/assets/299c1f70-6c44-4f5f-a22c-df8a85a8e284" />
 <br/>
ミドルフレームを用意します。<br/>
このとき必要であれば取っ手なしのアクリルフレームなどを使用することもできます。<br/>
<br/>
<br/>

ミドルフレームをボトムプレートに乗せてスペーサーを差し込む形で組み付けます。 <br/>
<img width="4032" height="3024" alt="7300A725-0CA0-428C-958C-B7F567D4165B_1_201_a" src="https://github.com/user-attachments/assets/d05d9998-33dc-4150-9ce2-81c9435a1c71" /> <br/>
隙間がないように差し込んでください。 <br/>
![IMG_7154](https://github.com/user-attachments/assets/aa1b5fc9-c2e2-4aa2-a70f-e9af4f91dc79)<br/>
<br/>
<br/>

※上記の差し込みを行う際、固くて差し込みにくい場合は無理せず以下の写真のように
ミドルフレームの各スペーサ穴をボトムプレートを使って予め差し込みやすくしてから
全体を差し込むとすんなり入ると思います。<br/>
無理に強行するとアクリルが割れます。<br/>
注意して差し込んでください。 <br/>
![IMG_7155](https://github.com/user-attachments/assets/d451e68c-95c6-4c60-9c7d-0b79141ccdcf) <br/>
<br/>
<br/>

ミドルフレームの取り付け完了 <br/>
<img width="2048" height="1536" alt="8B4AD7B8-D081-4701-9CCD-7F9F0B2AB30D_1_102_o" src="https://github.com/user-attachments/assets/a44cddc5-c9ef-48d6-8fdb-6f232ad3809c" />
 <br/>
<br/>
<br/>

#### ２-2.ミドルプレート下の取り付け<br/>
<br/>
次にミドルプレート下を取り付けていきます。 <br/>
<img width="2048" height="1536" alt="51B8BEA7-F039-43BF-956D-10179ED3399F_1_102_o" src="https://github.com/user-attachments/assets/cd853bfa-4173-4511-8bc4-5a22b8c0e32f" /> <br/>
<br/>

ミドルプレート下をミドルフレームを取り付けたボトムプレートに乗せます。　<br/>
<img width="4032" height="3024" alt="CF9B7D5E-2952-41AB-91F5-22DFB1FC4131_1_201_a" src="https://github.com/user-attachments/assets/05d22eee-90ef-4696-888e-51a92e46ecc6" /> <br/>
ミドルプレート下は左右で分かれているので一つづつ取り付けます。<br/>
向きが間違っていなければすんなり嵌るはずです。<br/>
<br/>
<br/>

ミドルプレートの取り付け完了<br/>
<img width="2048" height="1536" alt="B125D95D-5921-47A5-B742-1F589FA89B28_1_102_o" src="https://github.com/user-attachments/assets/d55e980f-72af-4752-b1cc-54c085b518a9" />
　<br/>
<br/>
<br/>

#### ２-3.基板の取り付け<br/>
<br/>
次に基板を取り付けます。 <br/>
<img width="2048" height="1536" alt="C6A5A08D-60B7-46A7-8876-698A04C69382_1_102_o" src="https://github.com/user-attachments/assets/7bbf9524-a14b-4e0a-b3dc-4b9f747f6b8e" />
 <br/>
<br/>
<br/>

２ー２までに作ったものの上に基板をはめ込む形で取り付けます。<br/>
<img width="4032" height="3024" alt="C4506477-46A3-4796-B332-4B338A239EC6_1_201_a" src="https://github.com/user-attachments/assets/e4c15f46-8cba-4d7c-bf9a-7f01af5175e9" /> <br/>
カポッと軽く嵌まらなければ組み付けの向きが間違っている可能性があります。無理やりやらずに戻って確認してください。<br/>
<br/>


基板組み付け完了。<br/>
<img width="2048" height="1536" alt="6E0D8904-27C4-45CD-B204-92110665A4BB_1_102_o" src="https://github.com/user-attachments/assets/1e5996af-c62c-4d7c-a4a2-1b3a56693c66" /> <br/>
正しく組み付けられていれば基板とミドルプレート下の高さが同じになっているはずです。<br/>
なっていない場合ははめ込み不足ですのでしっかり確認してください。<br/>
この部分があまい場合、のちのキースイッチの取り付けで問題が出る場合があります。<br/>
<br/>
<br/>


#### 2-4.ミドルプレート上の取り付け
2-3までに作った本体にミドルプレート上を取り付けていきます。<br/>
<img width="2048" height="1536" alt="A036699B-0451-461A-958C-4E231EA188A2_1_102_o" src="https://github.com/user-attachments/assets/4eba65a0-f884-47f2-aa8b-f1e6838accef" /> <br/>

<img width="4032" height="3024" alt="13C1A582-3570-464F-B350-C30F1B1ABE01_1_201_a" src="https://github.com/user-attachments/assets/47304b08-fc7b-4161-aa06-56f5ba49186f" /> <br/>
ミドルプレート上もミドルプレート下と同様に左右で分かれているので一つづつ乗せる形で取り付けます。<br/>
<img width="2048" height="1536" alt="DD4A03FF-2534-4C7F-ACED-91FA95F87CA3_1_102_o" src="https://github.com/user-attachments/assets/ee7a0a0e-1778-4298-b979-6a6f6b4773a9" /> <br/>
正しく取り付けられていれば、ミドルフレームとミドルプレートの高さが同じになっているはずです。 <br/>
そうでない場合はこれまでの手順にミスがあるので見直してください。<br/>
<img width="2048" height="1536" alt="C85A05D4-AF0C-4029-AF0E-095D8ECE9182_1_102_o" src="https://github.com/user-attachments/assets/b78cd266-2595-4597-9910-56a784c83900" /> <br/>
ミドルプレート上取り付け完了<br/>
<br/>
<br/>


### 3.トッププレートの取り付け<br/>
トッププレートを取り付けていきます。<br/>
<img width="2048" height="1536" alt="6ABC7785-00CC-48D6-BAA3-ED3078C4DF02_1_102_o" src="https://github.com/user-attachments/assets/4044bec1-0053-4979-870b-2114a9207cb5" /> <br/>
トップ用ネジ（5mm）を9本用意します。<br/>
トッププレートのフィルムを剥がします。<br/>
<br/>
<br/> 

<img width="2048" height="1536" alt="FC227CDE-E50E-4C0B-B249-CDD26495B2C6_1_102_o" src="https://github.com/user-attachments/assets/97422cb6-dc7c-404b-8271-11fcd2dd9786" /> <br/>


裏表に注意してトッププレートを本体に乗せます。<br/>
<img width="4032" height="3024" alt="AB16673B-51A5-4EE5-9B4F-0CE3B1468421_1_201_a" src="https://github.com/user-attachments/assets/edba315f-67d1-45ad-be5b-21dbaff8b655" /> <br/>
※裏表が違うとネジ穴が合いません。<br/>
<br/>
<br/>

トッププレートを載せたらネジ止めしていきます。<br/>
<img width="2048" height="1536" alt="56FB2710-B26E-427A-BF59-D276A27607E2_1_102_o" src="https://github.com/user-attachments/assets/355b6bd9-cf95-4f2a-bc97-77099d5a38bb" />
 <br/>
<br/>
<br/>

スペーサーの穴が見えている部分にネジ止めします。<br/>
<img width="1536" height="2048" alt="713B5107-C2AD-4E29-A48B-966814B1D23C_1_102_o" src="https://github.com/user-attachments/assets/2a39adf0-8c29-4aa5-b9b3-0af60502a77c" /> <br/>

<img width="4032" height="3024" alt="4DA502C2-B3EC-49EA-B71E-31B873971517_1_201_a" src="https://github.com/user-attachments/assets/a08a5d5f-1463-4e86-b6af-b74ff0f32eb8" />

赤枠内の９箇所に5mmネジで止めます。<br/>
最初は軽く締めて対角を少しずつ絞めるのがポイントです。<br/>
<br/>
<br/>


これで本体は完成です！<br/>

 <br/>
<br/>
<br/>


### 4.仕上げ
仕上げは好きなキースイッチやキーキャップを付けて使えるようにしていきます。<br/>
<br/>

<img width="768" height="1024" alt="4ABEA8D3-D12D-487E-83DD-62AB7FAC8BA8_1_105_c" src="https://github.com/user-attachments/assets/60d685e7-58c0-4c60-8ff6-bdd2687e076b" /> <br/>
<br/>
<br/>

キースイッチを付けます。<br/>
<img width="768" height="1024" alt="2E28995F-BBE6-456D-83DE-04B62DA539C6_1_105_c" src="https://github.com/user-attachments/assets/ba5b681c-5fd6-497e-8c6d-447db5fa36f6" /> <br/>
キースイッチによっては嵌め込みが硬い場合もあります。<br/>
多くはそれほど力をかけずとも付くはずなので、無理に力を入れすぎてピンを折ったり曲げたりしないように注意してください。<br/>
万一、曲がってしまった場合はラジオペンチなどで挟んでまっすぐ矯正すれば再び使えることが殆どです。<br/>
また特定のキーだけ反応しない場合はピン曲りが濃厚なので、故障を疑う前にキースイッチを外して曲りがないか確認しましょう。<br/>
<br/>
<br/>

キースイッチが付いたらキーキャップを取り付けます。<br/>
<img width="768" height="1024" alt="9D435325-2163-40D6-9ADD-80D30E544996_1_105_c" src="https://github.com/user-attachments/assets/78eef0c9-9f59-4085-8a33-2dff70bfe6c4" /> <br/>
<br/>

お好みのデザイン、カラーのキーキャップを取り付けることでいろいろな見た目を楽しめます。<br/>
<img width="768" height="1024" alt="2566B36B-CC7B-4F48-9C30-3C5D00551BCD_1_105_c" src="https://github.com/user-attachments/assets/439b71fa-962a-4cbc-b543-69fca6e8f9cf" /> <br/>
自作キーボードのカスタマイズの肝の部分ですね。<br/>
<br/>
<br/>

最後にロータリーエンコーダーノブを取り付けて完成！<br/>
<img width="768" height="1024" alt="0CDAD361-1CCC-4EC1-B44F-A45255D15710_1_105_c" src="https://github.com/user-attachments/assets/f0bb8e99-21f5-4ad1-a014-c286bb35c9f1" /> <br/>
付属の標準ノブでも良いですし様々な作家さんの作るアルチザンエンコーダーノブもオススメです。<br/>
ビルドガイド上は直径17mmくらいまでとなってますが、作者の確認する限りでは22mm位までは一応付きます。（使いやすいかどうかは別）<br/>

<br/>

お疲れ様でした！以上でキーボードは完成です。<br/>
PCに繋ぎ動作確認を取ってください。<br/>
予めファームウェアは書き込んであるので動作はしますが、<br/>
キーマップを弄ったりする場合は、Vialソフトウェアが必要です。<br/>
自分好みに動作させるにはほぼ必須なので是非インストールして使ってください。<br/>
詳しくは夕霧用のHOW to Guidを書いているのでそちらを参照のこと。<br/>
→こちら<br/>
https://note.com/eromis_sumomorry/n/nb64a1454d9ee?sub_rt=share_pb <br/>
<br/>
<br/>
