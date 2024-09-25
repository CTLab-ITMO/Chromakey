# Классификация хромакея на видео
В настоящее время видеоигры, фильмы, реклама и телешоу повсеместно распространены в современном обществе.
Однако под поверхностью их визуального разнообразия скрывается сложная технология, которая может производить впечатляющие эффекты.
Одной из таких технологий является хромакей — метод, позволяющий менять фон на любое другое изображение или видео.
Распознавание технологии хромакей в видео играет ключевую роль в поиске поддельных материалов.
В этой статье мы рассматриваем подходы, основанные на моделях глубокого обучения, которые позволяют распознавать хромакей в видео на основе неестественных артефактов, возникающих при переходе между кадрами.
Видео состоит из последовательности кадров, и точность видео может быть определена разными способами.
Если рассматривать точность покадрово, наш метод достигает оценки $F_1$, равной $0,67$.
Если мы считаем все видео поддельным в случае, если в нем есть один или несколько поддельных сегментов, то оценка $F_1$ равна $0,76$.
Предложенные методы показали лучшие результаты на собранном нами наборе данных по сравнению с существующими методами обнаружения хромакея.

Более подробные readme для каждого подхода находятся в папках CNN-based Method и Transformer-based Method соответственно

# Chromakey
Currently, video games, movies, commercials, and television shows are ubiquitous in modern society. 
However, beneath the surface of their visual variety lies sophisticated technology, which can produce impressive effects. 
One such technology is chromakey --- a method that allows to change the background to any other image or video. 
Recognizing chromakey technology in video plays a key role in finding fake materials. 
In this paper, we consider approaches based on deep learning models that allows to recognize chromakey in video based on unnatural artifacts that arise during the transition between frames. 
The video consists of a sequence of frames, and the the video accuracy can be determined in different ways. 
If we consider the accuracy frame by frame, our method reaches an $F_1$ score equal to $0.67$. 
If we consider the entire video to be fake in case there is one or more fake segments, then the $F_1$ score equal to $0.76$. 
The proposed methods showed better results on the dataset we collected in comparison with existing methods for chromakey detection.

More detailed readme for each approach are in the folders CNN-based Method and Transformer-based Method respectively
