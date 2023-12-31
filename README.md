# Data-Engineering

<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="80px" src="https://media.istockphoto.com/id/1080121484/vector/mvp-competition.jpg?s=612x612&w=0&k=20&c=4xBBrClOml2CWnrlMgLDU48RFFmRfqdA6zTbU_aB3Ik="></a>
    <span> Minimum Viable Product</span>
</h1>

Neste notebook será construído um pipeline de dados utilizando tecnologias na nuvem. O pipeline irá envolver a busca, coleta, modelagem, carga e análise dos dados. **Módulo - Engenharia de Dados** do Projeto de Pós Gradução em Ciência de Dados e Analytics da Puc Rio  [Pós-Graduação em Ciência de Dados e Analytics](https://especializacao.ccec.puc-rio.br/especializacao/ciencia-de-dados-e-analytics).



1. 🔍 [Objetivo](#objetivo)
2. 🔨 [Ferramentas Utilizadas](#versions)  
3. 🚀 [Percurso](#percurso)
4. ☑️ [Análise do Projeto - Cadeia de Suprimentos](#analysis-supply-chain)
5. 📈 [Análise - Banco de Dados: Cadeia de Suprimentos](#analysis-data)
6. 💬 [Contribuições](#contributors)    
7. 🔗 [Link](#link)  






## <a name="objetivo">🔍 Objetivo </a> 
Aprender e desenvolver projeto em banco de dados.



## <a name="percurso">🚀 Percurso</a>

| N°               | Etapas           |
| ----------------- | ----------------|
| 1    | Coleta de dados     |
| 2    | Tratamento de dados |
| 3    | Azure SQL Database  |
| 4    | Governança de dados |
| 5    | Análise exploratória de dados|

---


## <a name="versions">🔨 Ferramentas Utilizadas </a>

- [Microsoft Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal)
    * Data Factory
    * Azure SQL Database
    * Azure Purview
  
- [Google Colab:](https://colab.research.google.com/?utm_source=scs-index)
     ```bash
    # Importação das Bibliotecas:
    import numpy as np # Importação do Numpy
    import pandas as pd # Importação do Pandas
    import matplotlib.pyplot as plt # Importação do Matplotlib
    import seaborn as sns # Importação do Seaborn
    ```

## <a name="analysis-supply-chain">☑️ Análise do Projeto - Cadeia de Suprimentos</a>

Na plataforma Kaggle está um conjunto de dados que foi coletado de uma startup de Moda e Beleza. O conjunto de dados é baseado na cadeia de suprimentos de produtos de maquiagem.

Os insights gerados sobre as operações da cadeia de suprimentos é extremamente importante. É possível deduzir a partir das visualizações gráficas os produtos mais vendidos, geração de receita, modais de transporte, custos de envio, lead times e custos de fabricação, entre outras métricas.

A partir de uma análise, junto ao especialista de negócio, pode ser possível otimizar a gestão de estoques, evitar pertas de produtos, identificar clientes alvo, estudar melhores rotas para custo/benefício, estreitar relações comerciais com os fornecedores, entre outros.

Manter a integridade do banco de dados evita perdas ao negócio, pois aumenta performace dos dados para a geração de insights valiosos.

## <a name="analysis-data">📈 Análise - Banco de Dados: Cadeia de Suprimentos</a>

A partir da Entidade Supply-Chain podemos começar a construir novos relacionamentos para especilizar ainda mais nossa companhia, representando as associações entre as entidades.

O mapeamento de um esquema conceitual, definido pelo MER, em um esquema lógico do modelo relacional envolve transformar cada elemento de um esquema de entidades e relacionamentos (entidades, relacionamentos e atributos) em elementos equivalentes da modelagem relacional (tabelas, atributos e restrições estruturais).

Com a criação de uma chave estrangeira em uma das tabelas representam as entidades envolvidas no relacionamento. No caso apresentado abaixo, podemos especializar ainda mais nosso SKU e Fornecedores, criando a entidade produto e a entidade fornecedor, por exemplo.

 ## <a name="contributors"> 💬 Contribuições</a>

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir.
 
 Além disso, você também pode contribuir:
 
⚠️ Ajudando, respondendo ou compartilhando o seu trabalho comigo! 

⭐ Adicionando aos favoritos! 




## <a name="link">🔗 Link</a>


[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacqueline-ribeiro-743876247/)
---


<div align="center">Feito com muita dedicação por ❤️ <a href="https://github.com/jacquelinepalumbo">Jacqueline</a>.</div>
