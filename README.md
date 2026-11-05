# Data-Cancer_RedesNeurais
Classificação de tumores de mama (benigno/maligno) com machine learning com Redes Neurais

Classificação de Câncer com Redes Neurais

Diagnóstico de Câncer de Mama

Este projeto é a continuação direta do desenvolvimento anterior focado na detecção de câncer de mama utilizando o dataset Breast Cancer Wisconsin. No estágio passado, exploramos a engenharia de recursos e tratamentos iniciais. Agora, avançamos para a aplicação de uma Rede Neural Artificial (MLP - Multi-Layer Perceptron) para maximizar a precisão dos diagnósticos.


 Evolução e Melhorias nesta Etapa

• Tratamento de Dados Cirúrgico: Correção de bugs de codificação e nulos na coluna alvo (diagnosis), mapeando os tumores de forma binária (0 para Maligno e 1 para Benigno).
• Ajuste de Escala Numérica: Eliminação do uso incorreto de encoders categóricos em dados contínuos. Aplicamos exclusivamente o StandardScaler para normalizar os 30 atributos numéricos das células.
• Arquitetura Oculta Otimizada: Implementação do modelo MLPClassifier estruturado com duas camadas ocultas de (16, 8) neurônios, função de ativação relu e otimizador adam.


Resultados Obtidos

A aplicação da Rede Neural superou as expectativas, demonstrando uma convergência rápida e estabilidade estatística:
• Acurácia Média de Treino: 100.00% (ajuste perfeito aos padrões históricos).
• Acurácia de Teste (Holdout): 97.66% (excelente capacidade de generalização).
• Acurácia Média na Validação Cruzada (10-Fold): 0.9771 (~97.71%), provando que o modelo é extremamente consistente e seguro contra variações nos dados.
A matriz de classificação final registrou apenas 4 erros em 171 pacientes de teste, consolidando este modelo como uma ferramenta de altíssima confiabilidade para apoio à decisão médica.
