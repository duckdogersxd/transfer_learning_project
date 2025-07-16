# Projeto: Transfer Learning com MobileNetV2

Este projeto utiliza Transfer Learning com a rede MobileNetV2 para classificar imagens entre duas classes: gatos e cachorros. O treinamento é feito com o dataset Cats vs Dogs da Microsoft.

## Etapas:
- Carregamento do dataset
- Pré-processamento e normalização das imagens
- Uso de MobileNetV2 pré-treinada como base
- Fine-tuning para melhorar a acurácia
- Predições com novas imagens

## Como testar:
1. Abra o notebook no Google Colab
2. Execute as células sequencialmente
3. Faça upload de uma imagem para teste

## Dataset
[Cats vs Dogs - Microsoft](https://www.microsoft.com/en-us/download/details.aspx?id=54765)

## Modelo
- Base: MobileNetV2
- Acurácia: ~99% após fine-tuning
