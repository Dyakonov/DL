# «Глубокое обучение» (Deep Learning)
* Курс на факультете ВМК, МГУ имени М.В. Ломоносова
* для бакалавров 317 группа
* лектор: [Александр Дьяконов](https://dyakonov.org/ag/)


### страница курса
важная информация по курсу будет размещаться здесь, канал в телеграмме для общения уже сообщён группе

Взаимодействие (слайды лекций + задания и тесты) будет проводиться через https://classroom.google.com
* нужно иметь Google-аккаунт 
* Важно: чтобы в нём были Ваши настойщие ФИО
* Для входа в курс надо использовать код XXXXX

**Очень важно** за первые 2 недели зарегистрироваться! На все задания будет дедлайн.

## темы 2020 года



| тема | программа |
| :-- | :-- |
| [**Введение**](2020/DL2020_010intro_03n.pdf) | Обзор достижений DL |
| [**Нейронные сети**](2020/DL2020_021nn_03n.pdf) | Простейшая нейросеть – 1 нейрон. Функции активации (линейная, пороговая, сигмоида, гиперболический тангенс, softmax, LeakyReLU, ELU, Maxout). Функциональная выразимость нейрона. Теорема об универсальной аппроксимации. Сеть прямого распространения. Обучение. Функции ошибки. Производные на компьютере. Проблема затухания градиента. Обратное распространение градиента.|
| [**Борьба с переобучением в нейронных сетях**](2020/DL2020_022learning_03n.pdf) | Борьба с переобучением в нейронных сетях. Нормировки (Normalization of Data). Инициализация весов (Xavier initialization). Верификация – ранний останов (Early Stopping). Мини-батчи (mini-batches) / Batch-обучение. Продвинутая оптимизация (стохастический градиент с моментом (momentum), метод Нестерова, Adagrad, RMSprop, Adam, AdaDelta). Зашумление. Регуляризация + Weight Decay. Max-norm-регуляризация. Оптимизаторы. Dropout. Inverted Dropout. DropConnect. Обрезка градиентов (Gradient clipping). Батч-нормализация (Batch normalization). Расширение обучающего множества (Data Augmentation). Аугментация: Mixup. Ансамбль нейросетей. Диагностика проблем с НС. Кривые ошибок. Настройка темпа обучения. Transfer Learning. Упрощение НС (Pruning). Layer Normalization. Оптимизация гиперпараметров. Практические советы. |
| **Нейронные сети: трюки** | Проблема калибровки. Непараметрические методы калибровки. Решение проблемы дисбаланса классов. Взвешивание. В случайных нейронных сетях есть хорошие подсети. |
| [**Свёрточные нейронные сети**](2020/DL2020_031cnn_05n.pdf) | Что такое изображение. Линейный подход к классификации на несколько классов. Свёрточные нейронные сети (ConvNet, CNN). Что такое свёртка (Convolution). Отступ (Padding). Шаг (stride). Реализация свёртки. Разреженные взаимодействия (sparse interactions). Pooling (агрегация, субдискретизация / subsampling). Устройство слоя свёрточной НС, мотивация. Перевод тензора в тензор. Смысл свёрток 1×1. Какие бывают свёртки: Group Convolutions. Какие бывают свёртки: Depth-wise separable convolution. |
| [**Архитектуры свёрточных нейронных сетей**](2020/DL2020_032archi_08n.pdf) | Основные архитектуры свёрточных сетей: LeNet, AlexNet, VGG, GoogLeNet, ResNet, Inception-v4,SENet, Network in Network (NiN),  Deep Networks with Stochastic Depth, FractalNet, Fractal of FractalNet DenseNets, SqueezeNet, ResNeXt, HyperNets, MobileNet, EfficientNet, SqueezeNet, ShuffleNet, WideResNets. Применение CNN. ResNet: почему работает. |
| [**Детектирование объектов на изображениях**](2020/DL2020_033objectdetection_06n.pdf) | Задачи с изображениями: Классификация, Локализация, Детектирование, Сегментация, Преобразование изображений, Восстановление объектов. Классификация изображений – почему нетривиальная задача, решение, проблемы. Детектирование объектов: R-CNN, Spatial Pyramid Pooling (SPP-net), Fast R-CNN, Faster R-CNN, YOLO, SSD. Selective Search. Метрики качества. Non Maximum Suppression (NMS). Сегментация объектов: Mask R-CNN. Feature Pyramid Networks (FPN). Детектирование объектов: R-FCN. FCOS: Fully Convolutional One-Stage Object Detection. |
| [**Сегментация и поиск  изображений**](2020/DL2020_034segmentation_06n.pdf) | Семантическая сегментация. Elastic Transform. Классические методы сегментации. Полностью свёрточная сеть – Fully Convolutional Network (FCN). FCN: восстановление изображения, обратные операции. U-Net. «Тирамису» = DenseNet + U-Net. TernausNet. PSP-Net = Pyramid Scene Parsing Network. Расширенные свёртки (Dilated convolutions / Atrous Convolutions), DeepLabv1/2/3. SharpMask: Top to Down Refinement. Сегментация объектов (Instance segmentation). Mask R-CNN. Panoptic Feature Pyramid Networks. RetinaNet. V-Net. Модели для сегментации. UNet + FPN. BlendMask: SOTA 2020. Поиск изображений: Сиамские сети, Triplet Loss. Сиамские сети: Person Re-Identification. Сиамские сети: Street-View to Overhead-View Image Matching. Сиамские сети: Intermediate merging. Сиамские сети: for viewpoint invariance. Сиамские сети:  for cross-modal embedding. FaceNet. |
| [**Визуализация нейронных сетей и генерация изображений**](2020/DL2020_035visualgeneration_04n.pdf) | Зачем наблюдать? За чем можно наблюдать в NN? Стандартные средства в признаковых пространствах. Анализ активации нейронов. Чувствительность к удалению (Occlusion sensitivity). «Saliency maps» – градиенты по входу. «guided back-propagation» ~ градиенты по входу.Анализ отдельных нейронов. Анализ отдельных нейронов: оптимизационный подход. Генерация изображений: восстановление из признаков. Генерация текстур. Генерация пейзажей. Стилизация изображений. Быстрая стилизация. Причина шахматных сеток на изображениях. Дистилляция данных. Мягкая дистилляция данных. |
| **Атаки на сети** |  |
| [**CNN: дополнение**](2020/DL2020_037priorcolor_03n.pdf) | Deep Image Prior. Раскраска изображений. |
| [**Рекуррентные нейросети**](2020/DL2020_041rnn_04n.pdf) | RNN (базовый блок). RNN: обучение. RNN: как решать задачи классификации. LSTM. Забывающий гейт (Forget Gate). Входной гейт (Input Gate). Обновление состояния (Cell update). Выходной гейт (Output Gate). Gated Recurrent Unit (GRU). Метод форсирования учителя (teacher forcing). Scheduled sampling. Двунаправленные (Bidirectional) RNN. Глубокие (Deep) RNN. Глубокие двунаправленные RNN. Многонаправленные RNN. Пиксельные RNN. Рекурсивные (Recursive Neural Networks) НС. Exploding / Vanishing gradients. Особенности регуляризации в RNN: Dropout. Особенности регуляризации в RNN: Batchnorm. MI (Multiplicative Integration). Интерпретация LSTM: Sentiment neuron. Применение RNN.  |
| [**Анализ текстов**](2020/DL2020_042texts_08n.pdf) | Задачи с текстами. Данные. Понимания языка (Language Understanding). Свёрточные модели для текста. Dynamic Convolutional Neural Network. Very Deep Convolutional Networks for Text Classification. Сравнение CNN vs RNN. CNN + LSTM = C-LSTM. CNN + LSTM = LSTM-CNNs-CRF. Модель seq2seq. Обобщения seq2seq. Механизм внимания. Виды внимания. Дифференцируемые структуры памяти. Neural Turing Machines. Pointer Network. Discrete Read/Write: Reinforcement L.earning Neural Turing Machines. Memory Network «MemN2N». KV-MemNN. |
| [**Векторные представления слов и текстов**](2020/DL2020_043embeddings_08n.pdf) | Способы представления слов: классические: OHE, counts, LSA, кластеризация, LDA. Вложение слов в непрерывное пространство (embedding). word2vec: CBOW, skip-gram. Negative Sampling. Ближайшие соседи. Операции над представлениями слов. Fasttext. Glove: Global Vectors for Word Representation. Contextualized Word Embeddings. Embeddings in Tag LM. CoVe = Contextual Word Vectors. ELMo: Embeddings from Language Models. FLAIR: Contextual String Embeddings for Sequence Labelling. Представление текстов. Distributed Memory Model of Paragraph Vectors (Doc2Vec / paragraph2vec). The skip-thoughts model. Предтренировка автокодировщика (Autoencoder pretraining). Supervised sentence embeddings. StarSpace. Deep Averaging Network (DAN). Universal Sentence Encoder. DSSM. Случайный кодировщик. |
| [**Трансформер**](2020/DL2020_044transformer_10n.pdf) | attention / self- attention – матричная запись. Transformer: Основная идея «Parallelized Attention». Transformer: виды внимания. Особенности обучения трансформера. BERT = Bidirectional Encoder Representations from Transformers. RoBERTa: A Robustly Optimized BERT Pretraining Approach. SpanBERT. ALBERT = A Lite BERT. T5: Text-To-Text Transfer Transformer. ELECTRA = Efficiently Learning an Encoder that Classifies Token Re-placements  Accurately. |
| [**Языковые модели**](2020/DL2020_045languagemodel_10n.pdf) | Моделирование языка (Language Modeling). Параметрическое оценивание. Немарковские модели. RNN-моделирование языка. Подходы к генерированию. Beam Search (метод луча). ERNIE (Enhanced Representation through kNowledge IntEgration). GPT. GPT2. Нейронная дегенерация текстов. |
| [**Генерация текстов (NLG)**](2020/DL2020_046tokenNLG_09n.pdf) | Представление слов: - токенизация на подслова (byte-pair encoding (BPE), wordpiece, unigram language model, sentencepiece), - посимвольный подход (представления слов из анализа символов, Compositional Character Model, Character-Aware NLM), - гибридный подход (действуем на уровне слов, если надо – на уровне символов, Compositional Character Model, 	Character-Aware NLM). С(у/а)ммаризация текста: - seq2seq-подход / + attention, - Pointer-Generator Networks, - Bottom-up summarization, - NLG + RL, - simplification: DRESS (Deep REinforcement Sentence Simplification). Extractive summarization: SummaRuNNer. Abstractive Summarization: TCONVS2S. Суммаризация с BERT: BertSum. Диалоги. Рассказ историй: Storytelling. Рассказ историй по тексту: Hierarchical Neural Story Generation. Генерация поэзии: Hafez, Deep-speare. Проблемы метрики качества для саммаризации / диалогов / описания. Coreference Resolution. Coreference Resolution: Clustering-Based. |
| [**Машинный перевод с помощью НС (Neural Machine Translation)**](2020/DL2020_047NMT_09n.pdf) | Особенности нейросетевого перевода. Метрика качества в переводе и саммаризации: BLEU (Bilingual Evaluation Understudy), GLEU (Google-BLEU), ROUGE: Recall-Oriented Understudy for Gisting Evaluation, METEOR: Metric for Evaluation of Translation with Explicit ORdering, TER (Translation Edit Rate), SARI: System output against references and against the input sentence. Подходы к NMT: Seq2seq, Attention, The Transformer model, Ансамблирование. Convolutional Sequence to Sequence Learning (ConvS2S). GNMT (Google’s Neural Machine Translation System). RNMT+. Языковая модель в NMT. Использование нескольких языков. Редкие пары языков. Проблемы переводчика. |
| [**Обучение без учителя**](2020/DL2020_051unsup_08n.pdf) |  Автокодировщики (Auto-encoders). Глубокие автокодировщики. Denoising Autoencoder. Сокращающие автокодировщики – Contractive Autoencoders (CAE). Предобучение с помощью автокодировщика (раньше так делали). Sparse Coding. Context Encoders. Использование RBM. Глубокие RBM (Deep Boltzmann Machines). SOM – Самоорганизующиеся карты Кохонена. Сжатие. Генеративная модель. Проблема оценки плотности. Решения для оценки плотности. Авторегрессионные модели. Masked Autoencoder for Distribution Estimation (MADE). Masked Temporal (1D) Convolution. Masked Spatial (2D) Convolution: PixelCNN, PIXELCNN++, PixelSNAIL, PixelRNN. Masked Attention + Convolution. Поток (Glow): real NVP, Glow. Авторегрессионные потоки (Autoregressive Flows) |
| [**Вариационный автокодировщик**](2020/DL2020_052vae_06n.pdf) |  Генеративная модель. Variational Autoencoders (VAE). Variational Bayesian Inference. Reparametrizaton trick. Векторная арифметика. Conditional VAE (CVAE). Ladder Variational Autoencoders. Bidirectional-Inference Variational Autoencoder (BIVA). Vector Quantised-Variational AutoEncoder (VQ-VAE). VQ-VAE-2. VAE: Image Colorization. VAE: Forecasting from Static Images. Adversarial Autoencoder. |
| [**Генеративные состязательные сети**](2020/DL2020_053gan_13n.pdf) |   Generative Adversarial Networks (GAN). Генератор и дискриминатор. Что могут GAN. GAN: обучение – min-max-игра. Настройка GAN. Least Square GAN. Wasserstein GAN (WGAN). WGAN-GP. Energy-Based GAN (EBGAN). Deep Convolutional Generative Adversarial Networks (DCGAN). Условные состязательные сети (сGAN). Pix2pix c условными состязательными сетями (сGAN). Проблема отсутствия выборки - CycleGAN. BiGAN (Bidirectional). BigGAN: Генерация изображений / интерполяция. SAGAN (Self-Attention Generative Adversarial Networks). CAN: Creative Adversarial Networks. ProGAN (NVIDIA).  InfoGAN. Условные GANы (Conditional GANs). Coupled GANs. Как оценивать качество (сгенерированные картинки).|
| [**Самообучение**](2020/DL2020_055selfSV_20n.pdf) |  Self-Supervised Learning: pretext task, downstream task. Predicting  (spatial) context. Predicting image  rotation. Exemplar. Головоломка (Jigsaw). Кластеризация (DeepCluster). Контекстные кодировщики (Context Encoder) / image inpainting. Раскраска изображений (image colorization). Расщеплённые автокодировщики (Split-brain  autoencoders). Сегментация, порождённая движением (motion segmentation prediction). Разметка окружающими звуками (ambient sounds). Подсчёт примитивов (counting visual primitives). Multi-task Self-Supervised Visual Learning. Augmented Multiscale Deep InfoMax (AMDIM). Deep InfoMax (DIM). Invariant Information Clustering (IIC). Contrastive Predictive Coding. CPCv2 - Large Scale CPC on ImageNet. Momentum Contrast (MoCo). SimCLR. Исследование архитектур для самообучения.|
| **Звук и речь** |  |
| **Распознавание речи: классический подход** |  |
| **Распознавание речи: end2end-подход** |  |
| **Синтез речи** |  |



# конец