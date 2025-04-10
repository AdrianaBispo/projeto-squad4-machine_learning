# 🌊 Flood Area Segmentation - Bootcamp de Machine Learning | Atlântico Avanti

Projeto desenvolvido em equipe durante o **Bootcamp de Machine Learning** promovido pela **Atlântico Avanti**. Nosso desafio consiste em aplicar técnicas de Visão Computacional e Aprendizado de Máquina para **segmentar áreas afetadas por inundações** a partir de imagens de satélite.

## 📁 Dataset

Utilizamos o dataset disponível no Kaggle:  
🔗 [Flood Area Segmentation Dataset](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation/data)

O conjunto de dados contém:
- Imagens das areas inundadas
- Máscaras de segmentação que identificam áreas inundadas

## 🎯 Objetivo

Construir um modelo de **segmentação semântica** capaz de identificar com precisão as regiões alagadas em imagens de satélite.  
Esse tipo de solução pode ser aplicada para monitoramento ambiental, resposta a desastres naturais e planejamento urbano.

## 🛠️ Tecnologias e Ferramentas

- **Linguagem:** Python 3.9+
- **Bibliotecas principais:**  
  - NumPy / Pandas    
- **Modelos testados:** 
- **Ambiente:** Google Colab / Jupyter Notebook

## 🧪 Etapas do Projeto

1. **Análise Exploratória dos Dados (EDA)**  
   - Visualização de imagens e máscaras  
   - Verificação de balanceamento de classes  
   - Estatísticas básicas dos dados  

2. **Pré-processamento**  
   - Redimensionamento das imagens  
   - Normalização dos pixels  
   - Augmentations (data augmentation) para aumentar a robustez do modelo  

3. **Treinamento dos Modelos**  
   - Arquitetura base: UNet  
   - Funções de perda customizadas (como Dice Loss)  
   - Métricas: IoU (Intersection over Union), F1 Score  

4. **Avaliação**  
   - Análise quantitativa e qualitativa  
   - Visualização das predições versus máscaras reais  

## 📊 Resultados (parciais)


## 🤝 Integrantes da Equipe

- [Nome 1] –   
- [Nome 2] –   
- [Nome 3] –  
- [Nome 4] –   

## 🚀 Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/AdrianaBispo/projeto-squad4-machine_learning.git
   cd flood-segmentation-avanti
   ```

2. Execute o notebook principal:
   ```bash
   jupyter notebook notebooks/.ipynb
   ```
