# 1131-DL-Tensor
1. 在 PPT p.17 提到「為什麼在 img_gray_naive = img_t.mean( -3 ) 指令裡不用索引值 0 去使用 -3，兩者做的結果一樣，為什麼要用 -3?」請提供您的看法

2. 請開啟一張彩色影像 (影像自備)，分別用 PyTorch 與 TensorFlow 讀入彩色影像放在 3維的 Tensor 裡，使用 「einsum」指令搭配用下列公式分別將彩色影像轉成灰階影像

$$Y = 0.299\times R + 0.587 \times G + 0.114\times B$$

$$z = 0.2126\times R+0.7152\times G+0.0722\times B$$

3. 延續第 2 題，準備3張影像彩色影像 (3張影像的 width 與 height 要一樣)讀入彩色影像放在 Tensor 裡，使用 「einsum」指令搭配用題2所列公式分別將彩色影像轉成灰階影像，最後用 matplotlib 將結果顯示出來

![Screenshot 2024-10-02 at 9 19 11 AM](https://github.com/user-attachments/assets/54e33d29-fa3b-4664-946b-8cfdc37d14c8)
