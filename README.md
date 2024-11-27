# Previsão de Atrasos em Voos ✈️

Este repositório contém o desenvolvimento de um modelo de machine learning capaz de realizar previsões sobre atrasos em voos. O projeto envolve desde a análise exploratória de dados até a construção e otimização de um modelo preditivo utilizando o algoritmo **Random Forest Regressor**. Parabéns por concluir este projeto! 🎉

## 🛠️ Passos Realizados

1. **Análise Exploratória dos Dados**  
   - Extração de estatísticas descritivas.  
   - Construção de gráficos para melhor compreensão dos dados.

2. **Preparação dos Dados (Feature Engineering)**  
   - Limpeza e transformação dos dados para uso no modelo.

3. **Construção do Modelo Base**  
   - Treinamento inicial de um modelo preditivo para benchmarking.  

4. **Aprimoramento com Random Forest Regressor**  
   - Treinamento e validação do modelo utilizando **validação cruzada**.  
   - Seleção das **features mais importantes** para otimização do desempenho.

5. **Salvar o Modelo Treinado**  
   - O modelo final foi salvo como `model_producao.pkl`, permitindo reutilização futura.

## 🧪 Detalhes Técnicos

- **Modelo Utilizado:** Random Forest Regressor  
- **Técnica de Validação:** Validação cruzada  
- **Output:** Arquivo `model_producao.pkl`  

## 🚀 Como Utilizar

1. Clone o repositório:
   ```bash
   git clone https://github.com/monnikys/Analise_de_dados_voos.git
2. Instale as dependências necessárias (especifique as bibliotecas no arquivo `requirements.txt`):
   ```bash
   pip install -r requirements.txt
3. Utilize o modelo salvo (`model_producao.pkl`) para fazer previsões nos dados desejados.

## 📂 Estrutura do Repositório

- `exploratory_analysis/` - Scripts e gráficos de análise exploratória.  
- `feature_engineering/` - Processamento e preparação dos dados.  
- `model_training/` - Treinamento e validação do modelo.  
- `model_producao.pkl` - Modelo treinado para uso futuro.

## 📌 Observações

Este projeto serve como um ótimo ponto de partida para aprofundar seus conhecimentos em machine learning e manipulação de dados no contexto da previsão de atrasos em voos.
