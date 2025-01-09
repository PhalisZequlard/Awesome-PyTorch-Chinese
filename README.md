
 
## 目錄：

* [PyTorch學習教程、手冊](#PyTorch學習教程手冊)
* [PyTorch影片教程](#PyTorch影片教程)
* [NLP&PyTorch實戰](#NLPPyTorch實戰)
* [CV&PyTorch實戰](#CVPyTorch實戰)
* [PyTorch論文推薦](#PyTorch論文推薦)
* [Pytorch書籍推薦](#PyTorch書籍推薦)

## PyTorch學習教程、手冊
 
* [PyTorch英文版官方手冊](https://pytorch.org/tutorials/)：對於英文比較好的同學，非常推薦該PyTorch官方文檔，一步步帶你從入門到精通。該文檔詳細的介紹了從基礎知識到如何使用PyTorch構建深層神經網絡，以及PyTorch語法和一些高質量的案例。
* [PyTorch中文官方文檔](https://github.com/fendouai/PyTorchDocs)：閱讀上述英文文檔比較困難的同學也不要緊，我們為大家準備了比較官方的PyTorch中文文檔，文檔非常詳細的介紹了各個函數，可作為一份PyTorch的速查寶典。
* [比較偏算法實戰的PyTorch代碼教程](https://github.com/yunjey/pytorch-tutorial)：在github上有很高的star。建議大家在閱讀本文檔之前，先學習上述兩個PyTorch基礎教程。
* [開源書籍](https://github.com/zergtant/pytorch-handbook)：這是一本開源的書籍，目標是幫助那些希望和使用PyTorch進行深度學習開發和研究的朋友快速入門。但本文檔不是內容不是很全，還在持續更新中。
* [簡單易上手的PyTorch中文文檔](https://github.com/fendouai/pytorch1.0-cn)：非常適合新手學習。該文檔從介紹什麼是PyTorch開始，到神經網絡、PyTorch的安裝，再到圖像分類器、數據並行處理，非常詳細的介紹了PyTorch的知識體系，適合新手的學習入門。該文檔的官網：[http://pytorchchina.com](http://pytorchchina.com) 。

## PyTorch影片教程
* [B站PyTorch影片教程](https://www.bilibili.com/video/av31914351/)：首推的是B站中近期點擊率非常高的一個PyTorch影片教程，雖然影片內容只有八集，但講的深入淺出，十分精彩。只是沒有中文字幕，小夥伴們是該練習一下英文了...
* [國外影片教程](https://www.youtube.com/watch?v=SKq-pmkekTk)：另外一個國外大佬的影片教程，在YouTube上有很高的點擊率，也是純英文的影片，有沒有覺得外國的教學影片不管是多麼複雜的問題都能講的很形象很簡單？
* [莫煩](https://morvanzhou.github.io/tutorials/machine-learning/torch/)：相信莫煩老師大家應該很熟了，他的Python、深度學習的系列影片在B站和YouTube上均有很高的點擊率，該PyTorch影片教程也是去年剛出不久，推薦給新手朋友。
* [101學院](https://www.bilibili.com/video/av49008640/)：人工智能101學院的PyTorch系列影片課程，講的比較詳細、覆蓋的知識點也比較廣，感興趣的朋友可以試聽一下。
* [七月在線](https://www.julyedu.com/course/getDetail/140/)：最後，向大家推薦的是國內領先的人工智能教育平台——七月在線的PyTorch入門與實戰系列課。課程雖然是收費課程，但課程包含PyTorch語法、深度學習基礎、詞向量基礎、NLP和CV的項目應用、實戰等，理論和實戰相結合，確實比其它課程講的更詳細，推薦給大家。
 

## NLP&PyTorch實戰
* [Pytorch text](https://github.com/pytorch/text)：Torchtext是一個非常好用的庫，可以幫助我們很好的解決文本的預處理問題。此github存儲庫包含兩部分：
    * torchText.data：文本的通用數據加載器、抽象和迭代器（包括詞彙和詞向量）
    * torchText.datasets：通用NLP數據集的預訓練加載程序
我們只需要通過pip install torchtext安裝好torchtext後，便可以開始體驗Torchtext 的種種便捷之處。
* [Pytorch-Seq2seq](https://github.com/IBM/pytorch-seq2seq)：Seq2seq是一個快速發展的領域，新技術和新框架經常在此發佈。這個庫是在PyTorch中實現的Seq2seq模型的框架，該框架為Seq2seq模型的訓練和預測等都提供了模塊化和可擴展的組件，此github項目是一個基礎版本，目標是促進這些技術和應用程序的開發。
* [BERT NER](https://github.com/kamalkraj/BERT-NER)：BERT是2018年google 提出來的預訓練語言模型，自其誕生後打破了一系列的NLP任務，所以其在nlp的領域一直具有很重要的影響力。該github庫是BERT的PyTorch版本，內置了很多強大的預訓練模型，使用時非常方便、易上手。
* [Fairseq](https://github.com/pytorch/fairseq)：Fairseq是一個序列建模工具包，允許研究人員和開發人員為翻譯、總結、語言建模和其他文本生成任務訓練自定義模型，它還提供了各種Seq2seq模型的參考實現。該github存儲庫包含有關入門、訓練新模型、使用新模型和任務擴展Fairseq的說明，對該模型感興趣的小夥伴可以點擊上方鏈接學習。
* [Quick-nlp](https://github.com/outcastofmusic/quick-nlp)：Quick-nlp是一個深受fast.ai庫啓發的深入學習Nlp庫。它遵循與Fastai相同的API，並對其進行了擴展，允許快速、輕鬆地運行NLP模型。
* [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py)：這是OpenNMT的一個PyTorch實現，一個開放源碼的神經網絡機器翻譯系統。它的設計是為了便於研究，嘗試新的想法，以及在翻譯，總結，圖像到文本，形態學等許多領域中嘗試新的想法。一些公司已經證明該代碼可以用於實際的工業項目中，更多關於這個github的詳細信息請參閱以上鏈接。
 
## CV&PyTorch實戰
* [pytorch vision](https://github.com/pytorch/vision)：Torchvision是獨立於pytorch的關於圖像操作的一些方便工具庫。主要包括：vision.datasets 、vision.models、vision.transforms、vision.utils 幾個包，安裝和使用都非常簡單，感興趣的小夥伴們可以參考以上鏈接。
* [OpenFacePytorch](https://github.com/thnkim/OpenFacePytorch)：此github庫是OpenFace在Pytorch中的實現，代碼要求輸入的圖像要與原始OpenFace相同的方式對齊和裁剪。
* [TorchCV](https://github.com/donnyyou/torchcv)：TorchCV是一個基於PyTorch的計算機視覺深度學習框架，支持大部分視覺任務訓練和部署，此github庫為大多數基於深度學習的CV問題提供源代碼，對CV方向感興趣的小夥伴還在等什麼？
* [Pytorch-cnn-finetune](https://github.com/creafz/pytorch-cnn-finetune)：該github庫是利用pytorch對預訓練卷積神經網絡進行微調，支持的架構和模型包括：ResNet 、DenseNet、Inception v3 、VGG、SqueezeNet 、AlexNet 等。
* [Pt-styletransfer](https://github.com/tymokvo/pt-styletransfer#pt-styletransfer)：這個github項目是Pytorch中的神經風格轉換，具體有以下幾個需要注意的地方：
    * StyleTransferNet作為可由其他腳本導入的類；
    * 支持VGG（這是在PyTorch中提供預訓練的VGG模型之前）
    * 可保存用於顯示的中間樣式和內容目標的功能
    * 可作為圖像檢查圖矩陣的函數
    * 自動樣式、內容和產品圖像保存
    * 一段時間內損失的Matplotlib圖和超參數記錄，以跟蹤有利的結果
* [Face-alignment](https://github.com/1adrianb/face-alignment#face-recognition)：Face-alignment是一個用 pytorch 實現的 2D 和 3D 人臉對齊庫，使用世界上最準確的面對齊網絡從 Python 檢測面部地標，能夠在2D和3D坐標中檢測點。該github庫詳細的介紹了使用Face-alignment進行人臉對齊的基本流程，歡迎感興趣的同學學習。
 

## PyTorch論文推薦
* [Google_evolution](https://github.com/neuralix/google_evolution)：該論文實現了實現了由Esteban Real等人提出的圖像分類器大規模演化的結果網絡。在實驗之前，需要我們安裝好PyTorch、 Scikit-learn以及下載好 [CIFAR10 dataset數據集](https://www.cs.toronto.edu/~kriz/cifar.html)。
* [PyTorch-value-iteration-networks](https://github.com/onlytailei/Value-Iteration-Networks-PyTorch)：該論文基於作者最初的Theano實現和Abhishek Kumar的Tensoflow實現，包含了在PyTorch中實現價值迭代網絡（VIN）。Vin在NIPS 2016年獲得最佳論文獎。
* [Pytorch Highway](https://github.com/kefirski/pytorch_Highway)：Highway Netowrks是允許信息高速無阻礙的通過各層，它是從Long Short Term Memory(LSTM) recurrent networks中的gate機制受到啓發，可以讓信息無阻礙的通過許多層，達到訓練深層神經網絡的效果，使深層神經網絡不在僅僅具有淺層神經網絡的效果。該論文是Highway network基於Pytorch的實現。
* [Pyscatwave](https://github.com/edouardoyallon/pyscatwave)：Cupy/Pythorn的散射實現。散射網絡是一種卷積網絡，它的濾波器被預先定義為子波，不需要學習，可以用於圖像分類等視覺任務。散射變換可以顯著降低輸入的空間分辨率（例如224x224->14x14），且雙關功率損失明顯為負。
* [Pytorch_NEG_loss](https://github.com/kefirski/pytorch_NEG_loss)：該論文是Negative Sampling Loss的Pytorch實現。Negative Sampling是一種求解word2vec模型的方法，它摒棄了霍夫曼樹，採用了Negative Sampling（負採樣）的方法來求解，本論文是對Negative Sampling的loss函數的研究，感興趣的小夥伴可點擊上方論文鏈接學習。
* [Pytorch_TDNN](https://github.com/kefirski/pytorch_TDNN)：該論文是對Time Delayed NN的Pytorch實現。論文詳細的講述了TDNN的原理以及實現過程。
 
## PyTorch書籍推薦
相較於目前Tensorflow類型的書籍已經爛大街的狀況，PyTorch類的書籍目前已出版的並沒有那麼多，筆者給大家推薦我認為還不錯的四本PyTorch書籍。
* **《深度學習入門之PyTorch》**，電子工業出版社，作者：廖星宇。這本《深度學習入門之PyTorch》是所有PyTorch書籍中出版的相對較早的一本，作者以自己的小白入門深度學習之路，深入淺出的講解了PyTorch的語法、原理以及實戰等內容，適合新手的入門學習。但不足的是，書中有很多不嚴謹以及生搬硬套的地方，需要讀者好好甄別。
推薦指數：★★★
* **《PyTorch深度學習》**，人民郵電出版社，作者：王海玲、劉江峰。該書是一本英譯書籍，原作者是兩位印度的大佬，該書除了PyTorch基本語法、函數外，還涵蓋了ResNET、Inception、DenseNet等在內的高級神經網絡架構以及它們的應用案例。該書適合數據分析師、數據科學家等相對有一些理論基礎和實戰經驗的讀者學習，不太建議作為新手的入門選擇。
推薦指數：★★★
* **《深度學習框架PyTorch入門與實踐》**，電子工業出版社，作者：陳雲。這是一本2018年上市的PyTorch書籍，包含理論入門和實戰項目兩大部分，相較於其它同類型書籍，該書案例非常的翔實，包括：Kaggle競賽中經典項目、GAN生成動漫頭像、AI濾鏡、RNN寫詩、圖像描述任務等。理論+實戰的內容設置也更適合深度學習入門者和從業者學習。
推薦指數：★★★★
* **《PyTorch機器學習從入門到實戰》**，機械工業出版社，作者：校寶在線、孫琳等。該書同樣是一本理論結合實戰的Pytorch教程，相較於前一本入門+實戰教程，本書的特色在於關於深度學習的理論部分講的非常詳細，後邊的實戰項目更加的綜合。總體而言，本書也是一本適合新手學習的不錯的PyTorch入門書籍。
推薦指數：★★★



