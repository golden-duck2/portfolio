# portfolio

## 経験業務・スキルなど

エンジニア歴：約15年

使用可能言語・ツール
- Unity
    - C#、HLSL(ShaderLab, ShaderGraph)
    - uGUI, imGUI, Editor拡張
    - Animation 等、Humanoid操作関連
    - 負荷軽減調整等
- VTuber関連開発 (ハードウェア：HTC Vive Tracker, Perception Neuron, Leap Motion、OpenCVなど)
- VB.net、VisualBasic、JavaScript
- DB
    - MSSQL, MySQL(AWS 構築経験あり)

## 製作物1 : 自作インディーズゲーム開発(開発中)
現在開発中のインディーズゲーム
ローグライトアクションゲーム
2023年6月あたりから着手開始。現在進行中。

### 環境
- Unity 2020.2.1f + URP

#### 開発中画面1
タイトル画面
![AbyssWalker1](https://github.com/golden-duck2/portfolio/blob/main/Picture/AbyssWalker.gif?raw=true)

#### 開発中画面2
キャラクターコントロール
![AbyssWalker3](https://github.com/golden-duck2/portfolio/blob/main/Picture/AbyssWalker3.gif?raw=true)

#### 開発中画面3
ボス行動ルーチン開発
![AbyssWalker2](https://github.com/golden-duck2/portfolio/blob/main/Picture/AbyssWalker2.gif?raw=true)


## 製作物2 : UnityRoom 1week GameJam
2020年12月ごろに開発。
一週間を期限とするゲームジャム

お題：あける

とあるESPの異界録(ラノベ感) - golden_duck2 https://unityroom.com/games/esp-wall-shot

![picture](https://github.com/golden-duck2/portfolio/blob/main/Picture/capture01.gif?raw=true)

### 環境
- Unity 2020.2.1f + URP

### 作成目標
- 期間内に完成させる
- シェーダープログラミングを生かし、3Dで、且つビジュアルにインパクトがあるものにする
- 操作感を大切にしたゲームを作る
- タイムラインを生かしカットシーン入れる
<p>

### 作業内容
- 使用アセット(キャラクター、箱の衝突時の分解エフェクト、音楽)以外のコンテンツ作成
<p>

### 製作期間
- 内訳：7日間（平日勤務時間後5日間、休日2日間）
    - 平日
        - 企画検討（随時）
        - アセット選定(1日 + 準備期間１～２日）
        - シェーダプログラミング(1.5日)
        - C# コーディング（2日）
        - WebGLビルド対応(0.5日)
    - 休日
        - C# コーディング（1日）
        - WebGLビルド対応(0.5日)
        - カットシーン作成・デバグ・レベルデザイン(0.5日)
   <p>     
### 未実装項目
- ボス戦の実装
- 各種エフェクト
- 効果音の実装
<p>
    
### 今後の対応・求められる機能
一定のクオリティにはまだ達していないが、GameJamのために考えた1発ネタな為、基本的には更新はしない予定。
<p>
今後の展開としては、

- ハイパーカジュアルに分類されるシンプルなランゲームとして修正する
- 取って投げる仕組みはそのまま
- ゲームオーバー判定を追加し、スコアアタック要素以外にレベル要素を持たせる
- 速度が乗った場合の爽快感をより強くするため、速度によるレベルデザインをより厳密にする
- CinemaChine がWebGLでエラーし、TimeLine活用に支障が発生していたため、エラーの回避を試みる。<br>
などが考えられる。

<p>
    
## 製作物2
    
- ProceduralGrass
    - プロシージャルに作られた草の実装テスト
    - 非ジオメトリシェーダーなため、機種依存無し (C# + URP + Shader Graph)
    
- パラメータ
  - 風の速さ : 0.2
  - 風の強さ : 0.5

![picture](https://github.com/golden-duck2/ProceduralGrass/blob/main/Force0.2Power0.5.gif)<br>

- パラメータ
  - 風の速さ : 0.8
  - 風の強さ : 0.8
  
![picture](https://github.com/golden-duck2/ProceduralGrass/blob/main/Force0.8Power0.8.gif)<br>

- 過去にテスト実装した物(今後整理予定)
    - 着せ替え機能の実装　： https://github.com/golden-duck2/ClothChange<br>
![picture](https://github.com/golden-duck2/ClothChange/blob/master/avater.gif?raw=true)<br>
    - プロシージャルな雨の実装　：　https://github.com/golden-duck2/VertexRain <br>
![result](https://github.com/golden-duck2/VertexRain/blob/master/VertexRain.gif?raw=true)<br>
    - 降雪シェーダーの実装　：　https://github.com/golden-duck2/DeepSnowSample <br>
![result](https://github.com/golden-duck2/DeepSnowSample/blob/master/DeepSnow.gif?raw=true)<br>
    - 草シェーダーサンプル　：　https://github.com/golden-duck2/UnityGrassGeometryShaderSample <br>
![picture](https://github.com/golden-duck2/UnityGrassGeometryShaderSample/blob/master/grass.gif?raw=true)<br>
    - プロシージャル岩地形サンプル <br>
![result](https://github.com/golden-duck2/voronoiGrand/blob/master/Voronoi.gif?raw=true)<br>
    

