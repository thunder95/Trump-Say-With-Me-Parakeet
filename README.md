# AI-Studio-川普, 来, 跟爷一起说 WeChaty + PaddleHub

## 项目描述
本项目有趣的地方在于可以使用自己说话的语音信息和其他人的照片, 逼真地生成一幅他人模仿你说话的影像。其原理是根据音频直接合成唇形动作。语音信息通过wechaty终端传入，再基于PaddleGAN的Wav2Lip模型直接端到端的生成。本项目以特朗普为例，我们说啥就让特朗普跟着说啥，不仅支持语音信息, 中英文本，还可以传入带有文字的图片。 功能上不仅能增加一定的趣味，给用户一种新的AI体验， 同时用户能基于此，扩展到其他应用，比如结合翻译模型识别图片上的外文，生成有声小说，创建点读笔应用，躺着听论文等等。

本项目是参加【AI ChatBot 创意赛】的作品，PaddleHub携手开源聊天机器人框架WeChaty带来 AI ChatBot创意赛，为AI算法工程师提供一个全新的应用场景：Chatbot （Conversational AI），同时也为Chatbot 开发者提供一个全新的AI能力平台，拓宽视野，为未来设计更加强大的 Chatbot 提供一扇门。

本项目主要难点是一方面要融合OCR， GAN， Parakeet三大模块，在兼容部署环境上和代码集成上有一定的挑战， 另一方面PaddlePaddle目前没有开源中文语音合成的模型，目前只能使用ZHTTS临时方案，后期若有时间可将此模型迁移至PaddlePaddle。

## 项目结构
```
-|data
-|work
-README.MD
-1905968.ipynb
```
## 使用方式
A：在AI Studio上[运行本项目](https://aistudio.baidu.com/aistudio/projectdetail/1905968)
B：此处由项目作者进行撰写使用方式。
