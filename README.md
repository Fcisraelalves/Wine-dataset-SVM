
# Classificação do Dataset Wine com SVM

Este projeto utiliza o algoritmo **Support Vector Machine (SVM)** para classificação do dataset **Wine**. O objetivo é prever a categoria do vinho com base em atributos químicos da amostra.

## 📌 Descrição
O dataset Wine contém 178 amostras de vinho divididas em 3 classes:
- **Classe 0**
- **Classe 1**
- **Classe 2**

Cada amostra possui 13 atributos químicos, como:
- **Álcool**
- **Ácido málico**
- **Cinzas**
- **Fenóis totais**
- **Flavonoides**
- **Entre outros**

O modelo SVM é treinado para classificar corretamente cada amostra com base nesses atributos.

## 🛠 Tecnologias Utilizadas
- **Python**
- **Scikit-learn** (para implementação do SVM)
- **Pandas** (para manipulação do dataset)
- **Matplotlib & Seaborn** (para visualização de dados)
- **Jupyter Notebook** (para desenvolvimento e testes)

## 📂 Estrutura do Projeto
```
/
|-- Wine.ipynb  # Notebook contendo o código do projeto
|-- README.md   # Documentação do projeto
|-- requirements.txt  # Lista de dependências
```

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/svm-wine.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd svm-wine
   ```

3. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```

4. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

5. Execute o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

6. Abra o arquivo `Wine.ipynb` e execute as células passo a passo.

## 📊 Resultados
- Visualização das distribuições das classes.
- Treinamento e avaliação do modelo SVM.
- Testes de previsão com novos dados.

## 📝 Contribuição
Se quiser contribuir com melhorias, sinta-se à vontade para:
1. Fazer um fork do repositório.
2. Criar uma branch para suas modificações:
   ```bash
   git checkout -b minha-modificacao
   ```
3. Commitar suas mudanças:
   ```bash
   git commit -m "Melhoria no modelo SVM"
   ```
4. Enviar suas alterações para o repositório remoto:
   ```bash
   git push origin minha-modificacao
   ```
5. Abrir um Pull Request.

## 📜 Licença
Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e modificá-lo como desejar.

---
Desenvolvido por Israel Alves 🚀

---

