# Sound source separation with Deep U-net

ボーカル抽出のために作った音源分離モデル。<br>
音楽音声音源分離だけでなく、ノイズ除去などにも利用可能です。

## 環境構築
macでしか動作確認していません。ターミナルで
```
git clone https://github.com/oozzZZZZ/unet-audiosep
cd unet-audiosep
sh setup.sh
```

## 使い方
GUIからボーカル抽出できます。<br>

*起動方法*<br>
`sh run.sh`

Epoch８０, Mask Rate85%くらいがおすすめですが，曲によって得手不得手あるようなのでいろいろ試してみてください。

# Reference
[Jansson, A., Humphrey, E., Montecchio, N., Bittner, R., Kumar, A., & Weyde, T. (2017). Singing voice separation with deep u-net convolutional networks.](https://openaccess.city.ac.uk/id/eprint/19289/)

# Datasets
- [MUSDB18](https://sigsep.github.io/datasets/musdb.html#musdb18-compressed-stems)<br>
- [MedleyDB 2.0 Audio](https://medleydb.weebly.com/)
