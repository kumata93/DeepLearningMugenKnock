
<img src="icons/dl_icon_trans.png" width=300>

# ディープラーニング∞CheatSheet

DeepLearningの実装Tips (WiP) **たぶんしばらくモチベないので更新しません**

**ノック作るのが大変になってきたのでTips集に変更しました**

- 【注意】このページを利用して、または関して生じた事に関しては、**私は一切責任を負いません。** すべて **自己責任** でお願い致します。
- あくまで個人の趣味で作成しているものです　**PRは受け付けてますが、実装の依頼などは一切受け付けていませんので、そこをご理解頂けた方のみご利用下さい**


もしこれがみなさんのお役に立ったらGithub Sponsorになってください！

## Related

- ***Study-AI株式会社様 http://kentei.ai/ のAI実装検定のシラバスに使用していただくことになりました！(画像処理100本ノックも）Study-AI株式会社様ではAIスキルを学ぶためのコンテンツを作成されており、AIを学ぶ上でとても参考になります！
検定も実施されてるので、興味ある方はぜひ受けることをお勧めします！***

- ***画像処理100本ノック!! https://github.com/yoyoyo-yo/Gasyori100knock)***


## Codes

### Model

| Method | Code | |
|:---:|:---:|:---:|
| VGG 16, 19| [pytorch](notes_pytorch/ImgRec/VGG_cifar10_pytorch.ipynb)  | 2014
| GoogLeNet-v1 | [pytorch](pytorch/googletnetv1_pytorch.ipynb) 
| ResNet | [pytorch](notes_pytorch/ImgRec/ResNet_cifar10_pytorch.ipynb) | 2015
| ResNeXt | [pytorch](notes_pytorch/ImgRec/ResNeXt_cifar10_pytorch.ipynb) | 2016
| Xception| [pytorch](notes_pytorch/ImgRec/Xception_cifar10_pytorch.ipynb)  | 2016
| DenseNet121, 169, 201, 264| [pytorch](notes_pytorch/ImgRec/DenseNet_cifar10_pytorch.ipynb) | 2016
| MobileNet-v1 | [pytorch](notes_pytorch/ImgRec/MobileNet_v1_cifar10_pytorch.ipynb) | 2017
| SEResNeXt | [pytorch](notes_pytorch/ImgRec/SEResNeXt_cifar10_pytorch.ipynb) | 2017 
| MobileNet-v2 | [pytorch](notes_pytorch/ImgRec/MobileNet_v2_cifar10_pytorch.ipynb) | 2018
| EfficientNet | [pytorch](notes_pytorch/ImgRec/EfficientNet_cifar10_pytorch.ipynb) | 2019

###  Interpretation

| Method |  Code |
|:---:|:---:|
| Grad-CAM | [pytorch](notes_pytorch/Interpretation/GradCAM_STL10_pytorch.ipynb)


### Segmentation

| Method | Code | |
|:---:|:---:|:---:|
| U-Net|  [pytorch](notes_pytorch/ImgSeg/UNet_VOC2012_pytorch.ipynb) | 2015

### Object Detection

| Method | Code |
|:---:|:---:|
| MaskRCNN (torchvision)| [pytorch](pytorch/MaskRCNN_torchvision_sample.ipynb) 


### AE
| Method | Code |
|:---:|:---:|
| AE |  [pytorch](notes_pytorch/AE/AE_MNIST_pytorch.ipynb)
| AEによる異常検知 | [pytorch](notes_pytorch/AE/AE_AnormalyDetection_MNIST_pytorch.ipynb)
| VAE (+ clustering)|  [pytorch](notes_pytorch/AE/VAE_MNIST_pytorch.ipynb)

### GAN
| Method | Code | 
|:---:|:---:|
| GAN | [pytorch](notes_pytorch/GAN/GAN_Cifar10_pytorch.ipynb) 
| DCGAN | [pytorch](notes_pytorch/GAN/DCGAN_Cifar10_pytorch.ipynb) 
| CGAN | [pytorch](notes_pytorch/GAN/CGAN_pytorch.ipynb) 
| pix2pix Seg | [ pytorch](pytorch/Pix2pix_Seg_pytorch.ipynb) [ tf.keras](scripts_tf_keras/pix2pix_tf2.1_keras.py)
| WGAN | [pytorch](notes_pytorch/GAN/WGAN_Cifar10_pytorch.ipynb)
| WGAN-GP | [pytorch](notes_pytorch/GAN/WGANGP_Cifar10_pytorch.ipynb) 
| alphaGAN MNIST | [ pytorch](pytorch/alphaGAN_mnist_pytorch.py)
| alphaGAN cifar10 | [ pytorch](pytorch/alphaGAN_cifar10_pytorch.py)
| CycleGAN | [ pytorch](pytorch/CycleGAN_pytorch.ipynb) 

### Other
| Method | Code |
|:---:|:---:|
| Style Transfer|  [tf.keras](tf/StyleTransfer_tf2.1_keras.py) |


### NLP
| Method | Code | 
|:---:|:---:|
| seq2seq | [ pytorch](pytorch/Seq2seq_pytorch.ipynb)
| Transformer | [ pytorch](pytorch/Transformer_pytorch.ipynb)
| HRED | [ pytorch](pytorch/HRED_pytorch_sand.ipynb) 
| Word2Vec (Skip-gram)| [ pytorch](pytorch/Word2vec_pytorch.ipynb) |


- 2020.5.3 Sun [pytorch] CycleGANを追加
- 2020.4.3 Fri [tf.keras] pix2pixを追加
- 2020.3.27 Thu [tf.keras] Style Transferを追加
- 2020.2.25 Tue [Pytorch] WGAN-GPを修正
- 2020.1.1 [Pytorch] EfficientNetB1~B7を追加
- 2019.12.30 [Pytorch] EfficientNetB0を追加
- 2019.12.23 Chainerのサポートが終了したらしいので、PytorchとTensorflowに絞っていきます
- 2019.12.23 [Pytorch] 可視化 Grad-CAMを追加
- 2019.11.23 [Pytorch] 言語処理・会話生成のHREDを追加
- 2019.11.19 [Pytorch] 画像生成のWGAN-GPを追加
- 2019.11.8 [Pytorch]　画像生成のVAEとalphaGANを追加
- 2019.10.28 [Pytorch] 画像生成のWGANを追加
- 2019.10.21 [PyTorch] Semantic SegmentationでSegNetを追加
- 2019.10.16 [PyTorch] Seq2Seq Hard Attentionを追加
- 2019.10.10 [PyTorch] Seq2Seq Attention(Step別)を追加
- 2019.9.30 [Pytorch] MobileNet v2 を追加
- 2019.9.19 [TensorFlow] Xception, MobileNet_v1 を追加
- 2019.9.16 [TensorFlow] ResNet 18, 34, 50, 101, 152 を追加
- 2019.8.19 [Pytorch] NLP: Seq2seq+Attention, word2vecを追加
- 2019.8.15 [Pytorch] pix2pixを追加
- 2019.8.4 [Pytorch] DenseNet121, 169, 201, 264を追加
- 2019.7.30 [PyTorch, Keras] Xceptionを追加
- 2019.7.28 [Keras] ResNeXt-50, 101を追加
- 2019.7.23 [Pytorch] ResNeXt-50, 101を追加
- 2019.7.17 [Pytorch] VAEを追加  [keras, tensorflow, chainer] CGAN(MNIST)を追加
- 2019.7.5 [pytorch, keras]ResNet18, 34, 101, 152を追加
- 2019.6.16 [pytorch, tensorflow, keras, chainer] ResNet50を追加
- 2019.6.9 [tensorflow] DCGANを追加
- 2019.6.7 [Pytorch, tensorflow, keras, chainer]GoogleNet-v1(Inception)を追加
- 2019.5.26 [tensorflow] DCGAN, Conditional GANを追加
- 2019.5.19 [Keras, Chainer] ConditionalGANを追加
- 2019.5.18 [データセット準備] MNIST, [Pytorch]ConditionalGANを追加
- 2019.5.2 [データセット準備] Cifar10、[AutoEncoder, ConvAutoEncoder, GAN, DCGAN]Cifar10を追加
- 2019.3.31 [画像認識モデル] APIを追加
- 2019.3.19 [Pytorch][Chainer] GAN, DCGANを追加
- 2019.3.17 Pooling layerを追加したけど、あとからクラス化と学習を追加する予定
- 2019.3.17 seq2seq, convolutional layer を追加
- 2019.3.16 ニューラルネットをクラス化　を追加
- 2019.3.13 パーセプトロン系を追加
- 2019.3.12 AutoEncoder, ConvAutoEncoder, パーセプトロンを追加
- 2019.3.9 GAN, DCGANを追加
- 2019.3.6 RNN, LSTM, BDLSTMを追加
- 2019.3.5 AutoEncoder, RNNを追加　
- 2019.3.4 データ拡張・回転を追加
- 2019.3.3 UNetを追加

## Citation

```bash
@article{yoyoyo-yoDeepLearningMugenKnock,
    Author = {yoyoyo-yo},
    Title = {DeepLearningMugenKnock},
    Journal = {https://github.com/yoyoyo-yo/DeepLearningMugenKnock},
    Year = {2019}
}
```

## License

&copy; Curry yoshi All Rights Reserved.

This is under MIT License.
