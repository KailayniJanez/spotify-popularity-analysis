# 🎵 Análise de Popularidade no Spotify

**Autores:**  
- Kailayni Rodrigues Janez  
- Lorenna Zaqui Oliveira  
- Julia Tavares dos Santos  

## 📌 Sobre o Projeto

Este projeto foi desenvolvido em equipe como parte do processo seletivo para o **Grupo de Extensão Panda - UFSCar**.

Analisamos o dataset **Spotify Tracks Genre Dataset** para responder à pergunta:

> **"O que torna uma música popular no Spotify?"**

Foram investigadas correlações entre popularidade e atributos como danceability, energy, loudness, instrumentalness, duração, e muito mais.

## 👥 Contribuições

- **Kailayni Rodrigues Janez** – Análise de dados, limpeza, visualizações e documentação
- **Lorenna Zaqui Oliveira** – Análise exploratória e tratamento de outliers
- **Julia Tavares dos Santos** – Estatísticas descritivas e validação dos resultados

## 🔍 Principais Descobertas

- **Danceability** e **loudness** são os atributos com maior correlação positiva com a popularidade
- **Instrumentalness** tem forte correlação negativa – músicas populares são majoritariamente vocais
- **Explicit** é 3x mais comum em músicas de alta popularidade
- **Duração média** do hit: ~3min30s
- **Velocidade (BPM)** não define dançabilidade – ritmo estável é mais importante

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- Pandas, NumPy
- Matplotlib, Seaborn
- KaggleHub (para download do dataset)

## 📊 Etapas da Análise

1. Importação e entendimento dos dados
2. Análise exploratória (EDA)
3. Limpeza e pré-processamento:
   - Remoção de duplicatas
   - Filtro de duração, loudness e speechiness
   - Remoção de popularidade zero
4. Engenharia de atributos
5. Análise de correlações e perguntas de negócio
6. Criação de perfil da música popular

## 🚀 Como Executar

1. Clone o repositório
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
