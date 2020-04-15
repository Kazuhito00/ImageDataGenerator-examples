[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Kazuhito00/ImageDataGenerator-examples/master?filepath=ImageDataGenerator-examples.ipynb)

# ImageDataGenerator-examples
ImageDataGenerator-examplesはImageDataGeneratorによるデータ拡張のJupyter上での実行例です。

# Note
Random Erasing、RICAP、Mixup、Cutmixの手法はImageDataGeneratorに実装されていないため、別リポジトリからクローンしてきて実行しています。

それぞれのソースコードの権利は各作者様に帰属します。

Cutout/Random Erasing(yu4u様)

⇒https://github.com/yu4u/cutout-random-erasing

RICAP(koshian2様)

⇒https://github.com/koshian2/keras-ricap

Mixup

⇒https://github.com/Kazuhito00/mixup

Cutmix

⇒https://github.com/Kazuhito00/cutmix

# Requirement
 
* Tensorflow 2.x

# Usage
Jupyter上でImageDataGenerator-examples.ipynbを開いて実行してください。

# Examples
以下の実行例を実装しています。

* ランダム回転

* ランダム水平シフト

* ランダム垂直シフト

* ランダムシアー(せん断)

* ランダムズーム

* ランダムチャンネルシフト

* ランダム輝度変更

* ランダム水平反転

* ランダム垂直反転

* リスケール(各画素を等倍)

* 各サンプルの平均を0にする

* データセット全体で入力の平均を0にする

* Albumentationsを用いたデータ拡張(preprocessing_function経由)

* Cutout

* Random Erasing

* Mixup

* Cutmix

* RICAP


# ToDo
- [ ] ChangeBackground
- [ ] AugMix

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)

# License

ImageDataGenerator-examples is under [MIT license](LICENSE.md).

また、ハリネズミ、マンタ、犬、猫の画像は[フリー素材ぱくたそ](https://www.pakutaso.com)様の写真を利用しています。

