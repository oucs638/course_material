# course_material

上課教材的大集合！！！

## 條目

- [環境需求](#環境需求)
- [安裝](#安裝)
- [教材列表](#教材列表)

## 環境需求

1. 作業系統
    - 核心版本: `Linux version 4.15.0-54-generic`
    - 發行商版本: `Ubuntu 18.04.2 LTS (Bionic Beaver)`
2. python 執行環境
    - 版本: `3.6+`
    - `pip` 版本: `19+`

## 安裝

1. 下載程式碼

```sh
git clone https://github.com/IKMLab/course_material.git
```

2. 安裝**相關套件**

```sh
pip3 install -r requirements
```

3. 安裝 [**PyTorch**](https://pytorch.org/get-started/locally/#start-locally)

|選項|描述|選擇|
|-|-|-|
|PyTorch Build|請選**穩定版**避免未知錯誤|`Stable(1.4)`|
|Your OS|依照**作業系統**來選擇|`Linux`|
|Package|安裝 **PyTorch** 使用的方法|`Pip`|
|Language|當前執行 **Python** 版本|`Python 3.6`|
|CUDA|電腦上是否有 **GPU** 且支援 **CUDA 架構**|`10.1`|

```sh
pip install torch torchvision
```

如果沒有 GPU，可以考慮使用 [kaggle](https://www.kaggle.com/) 或 [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb) 等服務。

## 教材列表

- [python-入門語法](./python-入門語法.ipynb)
- [numpy-基本功能](./numpy-基本功能.ipynb)
- [pandas-基本功能](./pandas-基本功能.ipynb)
- [matplotlib-資料視覺化](./matplotlib-資料視覺化.ipynb)
- [scikit-learn-基本功能](./scikit-learn-基本功能.ipynb)
- [PyTorch-基本功能](./PyTorch-基本功能.ipynb)
- [CNN-手寫字辨識實作](./CNN-手寫字辨識實作.ipynb)
- [char-RNN-文本生成](./char-RNN-文本生成.ipynb)
