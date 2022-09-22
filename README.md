# Classificação de Expressões Faciais

Este projeto implementa um modelo CNN para a classificação de expressões faciais, baseada na arquitetura VGGNet, e utilizando a base de dados FER2013.
- No total, são consideradas 7 expressões: raiva, medo, nojo, felicidade, tristeza, surpresa e neutro;
- Bibliotecas principais: TensorFlow, Numpy, Matplotlib;
- Acurácia alcançada: 64%(o estado-da-arte não passa de 76%, e os autores da base de dados indicam que os humanos alcançam cerca de 65%);
- Utiliza Data Augmentation(rotação, deslocamento, alteração de brilho e de centro da imagem, "flip" horizontal, zoom, etc.);
