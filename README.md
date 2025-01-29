# 📧 Spam Mail Detection with Machine Learning

Este repositório apresenta um modelo de **detecção de spam** usando **Random Forest** e a técnica de **Bag of Words (CountVectorizer)** para transformar textos de e-mails em dados estruturados.

---

## 📌 Tecnologias Utilizadas

- **Python 3**
- **Pandas** (para manipulação de dados)
- **NumPy** (para operações matemáticas)
- **NLTK** (para processamento de linguagem natural)
- **Scikit-Learn** (para modelagem e Machine Learning)

---

## ⚙️ Como Instalar as Dependências

Antes de executar o projeto, instale as bibliotecas necessárias com o seguinte comando:

```bash
pip3 install pandas numpy nltk scikit-learn scipy
```

---

## ⚙️ Como Funciona?

1. **Pré-processamento dos textos**

   - Conversão para letras minúsculas
   - Remoção de pontuação
   - Remoção de stopwords (palavras comuns)
   - Aplicação de **Stemming** (reduzir palavras à sua raiz)

2. **Transformação em Vetores**

   - Uso do **CountVectorizer** para converter os textos em uma matriz numérica

3. **Treinamento do Modelo**

   - Modelo de **Random Forest** para classificar os e-mails como **spam** ou **não spam**

4. **Teste e Avaliação**

   - O modelo é testado com um conjunto de dados de validação
   - Classificação de novos e-mails

---

## 📊 Resultados Esperados

O modelo irá treinar e exibir a **acurácia** do classificador. Em seguida, ele classificará um e-mail de teste, retornando se ele é **Spam** ou **Ham (não spam)**.

---

## 📌 Melhorias Futuras

- Testar outros algoritmos de machine learning
- Usar técnicas avançadas como **TF-IDF** e **Word Embeddings**
- Implementar uma API para classificação de e-mails em tempo real

---

## 📜 Licença

Este projeto é de **uso livre** para fins educacionais e pode ser modificado conforme necessário. 🚀

