# Detecção e Reconhecimento Facial

O presente projeto tem como objetivo desenvolver um sistema automatizado de detecção e reconhecimento de faces, aplicando-o especificamente para identificar os personagens principais da série *The Big Bang Theory*. A solução combina técnicas modernas de visão computacional e aprendizado profundo para realizar duas tarefas principais: detecção de faces em imagens ou vídeos e reconhecimento de identidades específicas.

### 1. Metodologia

**Detecção de faces:**
Para localizar rostos nas imagens, foi utilizada a rede MTCNN (Multi-task Cascaded Convolutional Networks). 

**Reconhecimento facial:** FaceNet e um classificador leve (KNN ou SVM).

### 2. Base de Dados

Para o reconhecimento dos personagens, foi construída uma base de 12 imagens por personagem, contendo apenas o rosto, garantindo um treinamento eficiente mesmo com um número reduzido de exemplos. Técnicas de *data augmentation* (giro, flip, ajustes de brilho) foram aplicadas para aumentar virtualmente o conjunto de dados e melhorar a robustez do modelo.


### 3. Tecnologias e Ferramentas

* **Python** com bibliotecas: OpenCV, MTCNN, keras-facenet, scikit-learn.
* **Redes neurais profundas**: MTCNN para detecção e FaceNet para reconhecimento.
* **Classificador leve**: KNN, para mapear embeddings em identidades de personagens.
* **Data augmentation**: aumento de base para robustez.



