# Tensorflow學習筆記

書言老師Lab的Uncle Angel為了跟小夥伴們一同進步，撐到畢業~於是小弟先開個頭把Tensorflow的學習筆記用jupyter整理出來。
希望大家能輕鬆把Tensorflow輕鬆上手，然後把自己論文的機器學習神經網路架起來。
把Model跑跑跑起來，寫出Masterpiece，順利畢業。

##### 歡迎大家把自己學到的神奇知識跟我分享，把這個Notebook的內容豐富起來~!

建議大家先學習機器學習的基本觀念再來閱讀這個筆記，不然讀到一半可能就會卡關，然後萌生放棄的念頭。(放心!Uncle Angel放棄好幾次了)

##### 機器學習學習流程：
基本觀念 -> 選擇機器學習框架(Tensorflow/PyTorch) -> 看論文 -> 架自己要用的神經網路

##### 推薦機器學習教材：
Google Machine Learning Crash Course:

https://developers.google.com/machine-learning/crash-course

Stanford CS229: Machine Learning 大神Andrew Ng的課 ////全英教材 當練聽力

https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU


###### 本筆記運用了"莫煩Python"的程式碼，但教學內容上傳於2016年。所以小弟有對程式碼加以修改，可用於新版本的Tensorflow

# ~

###### update: Example 9有點問題，不能跑出TensorBoard的Graph，不影響訓練。

### Uncle Angel的執行配置
本筆記使用以下配置執行程式碼並順利運行

| 配置 | 規格 |
| ------ | ------ |
| Python | 3.7 |
| Tensorflow | 1.14.0 |
| CUDA | 10.2 |
| Windows | 10 |
| CPU | Intel Core i7-9750H (8 cores) |
| RAM | 16GB |
| GPU | Nvidia RTX2070 8GB |


