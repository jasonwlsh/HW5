# AI HW5

以下我將講述如何使用colab復現我的實驗結果

## 先備作業

由於模型需要較大的VRAM空間，故需要使用colab中A100進行訓練，請助教先將必要csv檔下載至HW5資料夾中，並匯入雲端硬碟

請使用code cell放入以下內容並按下執行

掛載雲端硬碟：

```bash
from google.colab import drive
drive.mount('/content/drive')
```

下載必要套件：

```bash
!pip install -r /content/drive/MyDrive/HW5/requirements.txt
```
## 訓練模型

請複製我繳交至E3的main.py程式碼 並放進code cell中運行

訓練完成後就會生成112511188.pth和112511188.csv

