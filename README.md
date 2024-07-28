<p align="center">
  <img width="320" height="320" src="figures/U2Net_Logo.png">
  
  <h1 align="center">U<sup>2</sup>-Net: U Square Net</h1>
    
</p>

## ** Перевод.Сергей Дерябин.

## Это - официальный репозитарий(repo) для нашей статьи  **U<sup>2</sup>-Net(U square net)**, опубликованной в издании "Распознавание образов 2020"("Pattern Recognition 2020"):

## [U<sup>2</sup>-Net: Going Deeper with Nested U-Structure for Salient Object Detection](Углубленное движение с вложенной U-структурой для обнаружения выступающих объектов)(https://arxiv.org/pdf/2005.09007.pdf)
[Xuebin Qin](https://xuebinqin.github.io/), [Zichen Zhang](https://webdocs.cs.ualberta.ca/~zichen2/), [Chenyang Huang](https://chenyangh.com/), [Masood Dehghan](https://sites.google.com/view/masooddehghan), [Osmar R. Zaiane](http://webdocs.cs.ualberta.ca/~zaiane/) и[Martin Jagersand](https://webdocs.cs.ualberta.ca/~jag/)


__Contact__: xuebin[at]ualberta[dot]ca

## Обновления(Updates) !!!

** (2022-Aug.-24) ** Мы рады объявить что наш U<sup>2</sup>-Net , опубликованный в издании Распознавания образов Pattern Recognition был признан победителем 2020 года  the 2020 Pattern Recognition BEST PAPER AWARD !!!
![u2net-best-paper](figures/u2net-best-paper.jpg)

** (2022-Aug.-17) **
Наши U<sup>2</sup>-Net-модели теперь доступны на [PlayTorch](https://playtorch.dev/), где вы можете создать свой собственный демонстрационный пример и выполнить его на вашем Android/iOS-телефоне. Испытайте этот демонстрационный пример на [![PlayTorch Demo](https://github.com/facebookresearch/playtorch/blob/main/website/static/assets/playtorch_badge.svg)](https://playtorch.dev/snack/@playtorch/u2net/) и предложите свои идеи о U<sup>2</sup>-Net к истине в минутах!

** (2022-Jul.-5)** Наша новая работа   **Очень точная дихотомическая сегментация изображения** **Highly Accurate Dichotomous Image Segmentation (DIS) [**Project Page**](https://xuebinqin.github.io/dis/index.html), [**Github**](https://github.com/xuebinqin/DIS) принята на конференции ECCV 2022. До 17-го июля 2022 будут выпущены наш код и набор данных. Знайте о наших обновлениях. 
![ship-demo](figures/ship-demo.gif)
![bg-removal](figures/bg-removal.gif)
![view-move](figures/view-move.gif)
![motor-demo](figures/motor-demo.gif)

** (2022-Jun.-3)** Благодарим [**Adir Kol**](https://github.com/adirkol) за совместно используемое iOS-приложение Создатель 3D-фото [**3D Photo Creator**](https://apps.apple.com/us/app/3d-photo-creator/id1619676262), основанного на нашей U<sup>2</sup>-Net.
![portrait-ios-app](figures/3d-photo-re.jpg)

** (2022-Mar.-31)** Благодарим  [**Hikaru Tsuyumine**] за реализацию iOS-приложения Рисование эскиза портрета [**Portrait Drawing**](https://apps.apple.com/us/app/portrait-drawing/id1623269600) , основанного на U<sup>2</sup>-Net-модели генерации портрета.
![portrait-ios-app](figures/portrait-ios-app.jpg)

** (2022-Apr.-12)** Благодарим  [**Kevin Shah**](https://github.com/ioskevinshah)  за предоставление знакового iOS-приложения [**Lensto**](https://apps.apple.com/in/app/lensto-background-changer/id1574844033), ([**Demo Video**](https://www.youtube.com/shorts/jWwUiKZjfok)) , основанного на  U<sup>2</sup>-Net.
![lensto](figures/lensto.png)

** (2022-Mar.-31)** Наша U<sup>2</sup>-Net-модель также интегрирована [**Hotpot.ai**](https://hotpot.ai/) для художественного проекта.
![hotpot](figures/hotpot.png)

** (2022-Mar-19)** Благодарим  [**Kikedao**](https://github.com/Kikedao) за предоставление  фантастического веб-приложения Силуэт [**Silueta**](https://silueta.me/), основанного на сети U<sup>2</sup>-Net. Подробности смотрите на сайте по адресу [**https://github.com/xuebinqin/U-2-Net/issues/295**](https://github.com/xuebinqin/U-2-Net/issues/295).
![silueta](figures/silueta.png) 

** (2022-Mar-17)** Благодарим  [**Ezaldeen Sahb**](https://github.com/Ezaldeen99/BackgroundRemoval) за реализацию iOS-библиотеки для удаления фона изображения, основанной на сети U<sup>2</sup>-Net, которая значительно упростит разработку мобильных приложений.
![close-seg](figures/swift-u2net.jpeg) 

<!-- ** (2022-Mar-10)** Благодарим  [**Doron Adler**](https://github.com/Norod/U-2-Net-StyleTransfer) за обучение удивительной передачи стиля сетью U<sup>2</sup>-Net.
![style-trans](figures/style-trans.JPG)  -->

** (2022-Mar-8)** Благодарим  [**Levin Dabhi**](https://github.com/levindabhi/cloth-segmentation) за обучение удивительной сегментации одежды сетью U<sup>2</sup>-Net.
![close-seg](figures/close-seg.jpg) 

** (2022-Mar-3)** Благодарим  [**Renato Violin**](https://github.com/renatoviolin/bg-remove-augment) за предоставление  удивительного веб-приложения для удаления фона изображения и замены его, основанного на нашей сети U<sup>2</sup>-Net.
![bg-rm-aug](figures/bg-rm-aug.gif) 

**(2021-Dec-21)** Этот блог [**blog**](https://rockyshikoku.medium.com/u2net-to-coreml-machine-learning-segmentation-on-iphone-eac0c721d67b) четко описывает способ преобразовать U<sup>2</sup>-Net-модель в CoreML-модель  [**CoreML**](https://github.com/john-rocky/CoreML-Models) и выполнить ее на iPhone. 

**(2021-Nov-28)** Интересные модели Сегментации Неба(Sky Segmentation models), разработанные [**xiongzhu**](https://github.com/xiongzhu666/Sky-Segmentation-and-Post-processing) , используя сеть U<sup>2</sup>-Net. 

![im_sky_segmentation](figures/sky-seg.png)

**(2021-Nov-28)** Удивительное приложение редактирования изображения [**Pixelmator pro**](https://www.pixelmator.com/pro/) использует сеть U<sup>2</sup>-Net в качестве  одной из его  моделей удаления фона. 

![im_sky_segmentation](figures/pixelmator.jpg)

**(2021-Aug-24)** Мы поиграли немного больше о плавлении исходного изображения и сгенерированных портретов, чтобы составить различные стили. Вы можете <br/> 
(1) Загрузите этот репозитарий(repo) с помощью команды
```
git clone https://github.com/NathanUA/U-2-Net.git
```
(2) Загрузите предварительно обученную модель портрета(pre-trained portrait model) u2net_portrait.pth из Google-диска  [**GoogleDrive**](https://drive.google.com/file/d/1IG3HdpcRiDoWNookbncQjeaPN28t90yW/view?usp=sharing) или из  [**Baidu Pan(提取码：chgd)**](https://pan.baidu.com/s/1BYT5Ts6BxwpB8_l2sAyCkw) и поместите ее в каталог: ```./saved_models/u2net_portrait/```, <br/>
(3) выполните код с помощью команды 
```
python u2net_portrait_composite.py -s 20 -a 0.5
```
,где ``-s`` указывает сигму гауссовой функции для размывания(sigma of gaussian function for blurring) исходного изображения и ``-a`` обозначает альфа-веса(alpha weights) исходного изображения при плалении их. <br/>

![im_portrait_composite](figures/im_composite.jpg)

**(2021-July-16)** Новое веб-приложение удаления фона [background removal webapp](https://remove-background.net/) разработано Изатоп Василий. 

![rm_bg](figures/rm_bg.JPG)

**(2021-May-26)** Благодарим  [**Dang Quoc Quy**](https://github.com/quyvsquy) за его приложение передачи стиля художника [**Art Transfer APP**](https://play.google.com/store/apps/details?id=com.quyvsquy.arttransfer) построенного на сети U<sup>2</sup>-Net.

<!---![art_transfer](figures/art_transfer.JPG)--->

**(2021-May-5)** Благодарим [**AK391**](https://github.com/AK391) за совместный доступ к использованию его веб-демонстрационного примера Gradio [**Gradio Web Demo of U<sup>2</sup>-Net**](https://gradio.app/hub/AK391/U-2-Net).

![gradio_web_demo](figures/gradio_web_demo.jpg)


**(2021-Apr-29)** Благодарим [**Jonathan Benavides Vallejo**](https://www.linkedin.com/in/jonathanbv/) за выпуск его приложения LensOCR: Извлечение текста & изображения [**LensOCR: Extract Text & Image**](https://apps.apple.com/ch/app/lensocr-extract-text-image/id1549961729?l=en&mt=12), которое использует сеть U<sup>2</sup>-Net для извлечения переднего плана у изображения.

![LensOCR APP](figures/LensOCR.jpg)

**(2021-Apr-18)** Благодарим [**Andrea Scuderi**](https://www.linkedin.com/in/andreascuderi/) за выпуск его приложения Камера с обрезкой фото [**Clipping Camera**](https://apps.apple.com/us/app/clipping-camera/id1548192169?ign-mpt=uo%3D2), которое является U<sup>2</sup>-Net-сеть управляемым приложением камеры в реальном времени  и она "в состоянии обнаружить соответствующий объект нат сцене и отсечь его, чтобы применить необычные фильтры". 

![Clipping Camera APP](figures/clipping_camera.jpg)

**(2021-Mar-17)** [**Dennis Bappert**](https://github.com/dennisbappert) переобучил U<sup>2</sup>-Net-модель для покрытия портрета человека [**human portrait matting**](https://github.com/dennisbappert/u-2-net-portrait). Результаты выглядят очень обещающими, и он также предоставил подробности процесса обучения и стратегии генерации данных (и увеличение), которые являются вдохновляющими.

**(2021-Mar-11)** Dr. Tim разработал программу удаления фона в видео  [**video version rembg**](https://github.com/ecsplendid/rembg-greenscreen) с ипользованием сети U<sup>2</sup>-Net. Удивительные демонстрационные результаты могут быть найдены на  [**YouTube**](https://www.youtube.com/watch?v=4NjqR2vCV_k).

**(2021-Mar-02)** We found some other interesting applications of our U<sup>2</sup>-Net including [**MOJO CUT**](https://play.google.com/store/apps/details?id=com.innoria.magicut&hl=en_CA&gl=US), [**Real-Time Background Removal on Iphone**](https://www.linkedin.com/feed/update/urn:li:activity:6752303661705170944/?updateEntityUrn=urn%3Ali%3Afs_feedUpdate%3A%28V2%2Curn%3Ali%3Aactivity%3A6752303661705170944%29), [**Video Background Removal**](https://nisargkapkar.hashnode.dev/image-and-video-background-removal-using-deep-learning), [**Another Online Portrait Generation Demo on AWS**](http://s3-website-hosting-u2net.s3-website-eu-west-1.amazonaws.com/), [**AI Scissor**](https://qooba.net/2020/09/11/ai-scissors-sharp-cut-with-neural-networks/).

**(2021-Feb-15)** Мы только что выпустили онлайновый демонстрационный пример [**http://profu.ai**](http://profu.ai) для генерации портрета. Опробуйте его и давайте любые предложения или комментарии. <br/>
![Profuai](figures/profuai.png) <br/>

**(2021-Feb-06)** Недавно, некоторые люди указали на проблему использования сети U<sup>2</sup>-Net для сегментации человека, поэтому мы обучили другую модель в качестве примера для сегментации человека,  на основе Набора данных надзорного/контролируемой персоны [**Supervisely Person Dataset**](https://supervise.ly/explore/projects/supervisely-person-dataset-23304/datasets). <br/>

(1) Чтобы выполнить модель сегментации человека, сначала загрузите модель сегментации человека с весами [**u2net_human_seg.pth**](https://drive.google.com/file/d/1-Yg0cxgrNhHP-016FPdp902BR-kSsA4P/view?usp=sharing)  в каталог  ``` ./saved_models/u2net_human_seg/```. <br/>
(2) Подготовьте изображения, будущие  сегментированными, в соответствующий каталог, например. ```./test_data/test_human_images/```. <br/>
(3) Выполните вывод(inference)  командой: ```python u2net_human_seg_test.py``` и результаты будут выведены в соответствующий каталог, например. ```./test_data/u2net_test_human_images_results/```<br/>
[**Примечания: из-за точности маркировки Набора данных надзорного/контролируемой персоны(Supervisely Person Dataset), модель сегментации человека (u2net_human_seg.pth)  здесь не будет давать точность уровня волос. Но эта модель должна быть более устойчивой, чем u2net-модель, обученная с набором данных DUTS-TR на задаче сегментации  всего человека. Эта модель может использоваться для сегментации портрета человека, сегментации тела человека и т.д. **](https://github.com/NathanUA/U-2-Net)<br/>

![Human Image Segmentation](figures/human_seg.png) <br/>
![Human Video](figures/human_seg_video.gif)
![Human Video Results](figures/human_seg_results.gif)

**(2020-Dec-28)** Некоторые интересные приложения и полезные инструменты на основе U<sup>2</sup>-Net: <br/>
(1) [**Xiaolong Liu**](https://github.com/LiuXiaolong19920720) разработал несколько очень интересных приложений на основе  U<sup>2</sup>-Net , включая  рисование портрета человека [**Human Portrait Drawing**](https://www.cvpy.net/studio/cv/func/DeepLearning/sketch/sketch/page/)(Насколько я знаю, Xiaolong - первый, кто использует U<sup>2</sup>-Net для генерации портрета), [**image matting**](https://www.cvpy.net/studio/cv/func/DeepLearning/matting/matting/page/) и [**so on**](https://www.cvpy.net/). <br/>
(2) [**Владимир Серегин(Vladimir Seregin)**](https://github.com/peko/nn-lineart) разработал интересный инструмент,  штриховую графику на основе NN [**NN based lineart**](https://peko.github.io/nn-lineart/), для сравнения результатов портретирования на основе U<sup>2</sup>-Net и результатов портретирования на основе других популярных моделей, [**ArtLine**](https://github.com/vijishmadhavan/ArtLine), разработанный [**Vijish Madhavan**](https://github.com/vijishmadhavan). <br/>
(3) [**Daniel Gatis**](https://github.com/danielgatis/rembg) разработал python-инструмент, [**Rembg**](https://pypi.org/project/rembg/), для удаления фона в изображении на основе  U<sup>2</sup>-Net. Я думаю, что этот инструмент значительно упростит применение U<sup>2</sup>-Net в различных областях. <br/>
![REMBG](figures/rembg.png)

**(2020-Nov-21)** Недавно, мы нашли интересное приложение с U<sup>2</sup>-Net для рисования портрета человека [**human portrait drawing**](https://www.pythonf.cn/read/141098). Поэтому, мы обучали другую модель для этой задачи на основе набора данных  [**APDrawingGAN dataset**](https://github.com/yiranran/APDrawingGAN).

![Sample Results: Kids](figures/portrait_kids.png)

![Sample Results: Ladies](figures/portrait_ladies.png)

![Sample Results: Men](figures/portrait_men.png)

### Использование для генерации портрета(portrait generation)
1. Клонируйте этот репозитарий(repo) на локальный диск 
```
git clone https://github.com/NathanUA/U-2-Net.git
```

2. Загрузите предварительно обученную модель портрета(pre-trained portrait model) u2net_portrait.pth из Google-диска [**GoogleDrive**](https://drive.google.com/file/d/1IG3HdpcRiDoWNookbncQjeaPN28t90yW/view?usp=sharing) или [**Baidu Pan(提取码：chgd)**](https://pan.baidu.com/s/1BYT5Ts6BxwpB8_l2sAyCkw) и поместите модель в каталог: ```./saved_models/u2net_portrait/```.

3. Выполните набор тестирования(testing set). <br/>
(1) Загрузите набор данных обучения(train) и тестирования(test) из репозитария по адресу: [**APDrawingGAN**](https://github.com/yiranran/APDrawingGAN). Эти изображения и их истина основы сшиты бок о бок(These images and their ground truth are stitched side-by-side) (512x1024). Вы должны разделить(split) каждое из этих изображений на два изображения размером 512x512 и поместить их в каталог ```./test_data/test_portrait_images/portrait_im/```. Вы можете также загрузить набор тестирования разделения(split testing set) на Google-диск [GoogleDrive](https://drive.google.com/file/d/1NkTsDDN8VO-JVik6VxXyV-3l2eo29KCk/view?usp=sharing). <br/>
(2) Выполните команду вывода умозаключения(inference) ```python u2net_portrait_test.py```, которая выведет результаты(results) в каталог ```./test_data/test_portrait_images/portrait_results```. <br/>

4. Выполните на своем собственном наборе данных(your own dataset). <br/>
(1) Подготовьте свои изображения(images) и поместите их в каталог ```./test_data/test_portrait_images/your_portrait_im/```. [**Чтобы получить достаточно деталей портрета,  область головы человека во входном изображении должно иметь размер близкий или больше, чем размер 512x512. Фон головы должен быть относительно четким.**](https://github.com/NathanUA/U-2-Net) <br/>
(2) Выполните прогноз(prediction) командой  ```python u2net_portrait_demo.py```, которая выведет результаты(results) в каталог ```./test_data/test_portrait_images/your_portrait_results/```. <br/>
(3) Различие между командами ```python u2net_portrait_demo.py``` и ```python u2net_portrait_test.py``` состоит в том, что мы добавили простой [**face detection**](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_objdetect/py_face_detection/py_face_detection.html) шаг обнаружения лица, перед генерацией портрета(before the portrait generation) в команде ```u2net_portrait_demo.py```.  Поскольку набор тестирования(testing set) APDrawingGAN нормализован и обрезан(normalized and cropped) к размеру 512x512 для включения только голов людей, в то время как наш собственный набор данных может меняться в зависимости от различных разрешений и контентов. Поэтому, код ```python u2net_portrait_demo.py``` обнаружит самую большое лицо на данном изображении и затем обрежет, дополнит и изменит размеры(crop, pad and resize ) ROI к размеру 512x512 для передачи к сети. Следующие данные показывают, как сделать ваши собственные фотографии для генерации высококачественных портретов.

**(2020-Sep-13)** Наша U<sup>2</sup>-Net-модель является **6th** в [**MICCAI 2020 Thyroid Nodule Segmentation Challenge**](https://tn-scui2020.grand-challenge.org/Resultannouncement/).

**(2020-May-18)** Официальный доумент нашей сети **U<sup>2</sup>-Net (U square net)** ([**PDF in elsevier**(свободный до июля 5 2020)](https://www.sciencedirect.com/science/article/pii/S0031320320302077?dgcid=author), [**PDF in arxiv**](http://arxiv.org/abs/2005.09007)) доступен. Если вы не в состоянии получить доступ к архиву, не стесняйтесь известить меня по электронной почте.

**(2020-May-16)** Мы устранили проблему повышающей дискретизации(upsampling issue) сети. Теперь, модель должна быть в состоянии обработать произвольный входной размер **arbitrary input size**. (Советы: Эта модификация должна упростить переобучение/переквалификацию(retraining)   U<sup>2</sup>-Net модели на ваших собственных наборах данных. При использовании нашей предварительно-обученной модели(our pre-trained model ) на наборах данных SOD, сохраните входной размер как 320x320, чтобы гарантировать производительность.)

**(2020-May-16)** Мы высоко ценим **Cyril Diagne** за разработку этого фантастического AR-проекта(проекта дополненной реальности) [**AR Copy and Paste**](https://github.com/cyrildiagne/ar-cutpaste) , использующего **U<sup>2</sup>-Net** (Qin *et al*, PR 2020) и [**BASNet**](https://github.com/NathanUA/BASNet)(Qin *et al*, CVPR 2019). Демовидео  [**demo video**](https://twitter.com/cyrildiagne/status/1256916982764646402) в Твиттере достигло более **5M** просмотров, что феноменально и показывает нам большие  возможности применения SOD.

## U<sup>2</sup>-Net-результаты(Results) (176.3 MB)

![U<sup>2</sup>-Net Results](figures/u2netqual.png)


## Наша предыдущая работа: [BASNet (CVPR 2019)](https://github.com/NathanUA/BASNet)

## Требуемые библиотеки(Required libraries)

Python 3.6  
numpy 1.15.2  
scikit-image 0.14.0  
python-opencv
PIL 5.2.0  
PyTorch 0.4.0  
torchvision 0.2.1  
glob  

## Использование для обнаружения выступающих объектов (заметных объектов; salient object detection)
1. Клонируйте этот репозитарий(repo)
```
git clone https://github.com/NathanUA/U-2-Net.git
```
2. Загрузите предварительно-обученную модель(pre-trained model) u2net.pth (176.3 MB) из Google-диска [**GoogleDrive**](https://drive.google.com/file/d/1ao1ovG1Qtx4b7EoskHXmi2E9rp5CHLcZ/view?usp=sharing) или [**Baidu Pan 提取码: pf9k**](https://pan.baidu.com/s/1WjwyEwDiaUjBbx_QxcXBwQ) или предварительно-обученную модель(pre-trained model) u2netp.pth (4.7 MB) из Google-диска [**GoogleDrive**](https://drive.google.com/file/d/1rbSTGKAE-MTxBYHd-51l2hMOQPT_7EPy/view?usp=sharing) или [**Baidu Pan 提取码: 8xsi**](https://pan.baidu.com/s/10tW12OlecRpE696z8FxdNQ) и поместите модели в каталоги './saved_models/u2net/' и './saved_models/u2netp/'

3. Перейдите в каталог 'U-2-Net', запустите процесс обучения(train) или процесс вывода умозаключения(inference) с помощью соответствующей команды: ```python u2net_train.py```
или ```python u2net_test.py```. Для использования различных моделей, имя модели 'model_name' в обоих файлах может быть изменено на 'u2net' или на 'u2netp'.  

 Мы также предоставляем  карты  предсказанных выступов(predicted saliency maps) ([u2net results](https://drive.google.com/file/d/1mZFWlS4WygWh1eVI8vK2Ad9LrPq4Hp5v/view?usp=sharing),[u2netp results](https://drive.google.com/file/d/1j2pU7vyhOO30C2S_FJuRdmAmMt3-xmjD/view?usp=sharing)) для наборов данных(datasets) SOD, ECSSD, DUT-OMRON, PASCAL-S, HKU-IS и DUTS-TE.


## U<sup>2</sup>-Net.Архитектура(Architecture)

![U<sup>2</sup>-Net architecture](figures/U2NETPR.png)


## Сравнение качества(Qualitative Comparison)

![Quantitative Comparison](figures/quan_1.png)

![Quantitative Comparison](figures/quan_2.png)


## Сравнение качества(Qualitative Comparison)

![Qualitative Comparison](figures/qual.png?raw=true)

## Цитата(Citation)
```
@InProceedings{Qin_2020_PR,
title = {U2-Net: Going Deeper with Nested U-Structure for Salient Object Detection},
author = {Qin, Xuebin and Zhang, Zichen and Huang, Chenyang and Dehghan, Masood and Zaiane, Osmar and Jagersand, Martin},
journal = {Pattern Recognition},
volume = {106},
pages = {107404},
year = {2020}
}
```
