# Crypto Market Cap & Drawdown Analysis

## Descrição

Este projeto realiza uma análise profunda de criptomoedas com foco em **capitalização de mercado (market cap)** e **drawdown**. Ao invés de considerar apenas o preço, esta ferramenta oferece uma visão mais precisa do valor total de uma criptomoeda em circulação e seu risco relativo, permitindo uma melhor avaliação de oportunidades de investimento.

A solução utiliza dados coletados diretamente do [CoinMarketCap](https://coinmarketcap.com/), realizando cálculos automáticos para encontrar o **All-Time High (ATH)** e o drawdown percentual de cada criptomoeda, fornecendo insights sobre sua estabilidade e resiliência.

## Funcionalidades

- **Coleta automática de dados**: O projeto utiliza web scraping com BeautifulSoup para coletar os dados históricos de capitalização de mercado.
- **Análise de Drawdown**: Com base no maior valor de capitalização de mercado registrado anteriormente (ATH), o script calcula o drawdown para cada período, expressando o percentual de perda em relação ao ATH.
- **Visualização clara de dados**: Os dados processados podem ser facilmente visualizados em ferramentas como **pandas** ou exportados para análise em outros softwares.
- **Cálculo de indicadores de risco**: Através da análise de drawdown, é possível avaliar o risco de grandes quedas no valor de mercado de diferentes criptomoedas.

## Proposta de Valor

Ao focar na capitalização de mercado, a ferramenta oferece uma análise mais robusta e confiável do sucesso de uma criptomoeda. Além disso, o cálculo do drawdown ajuda investidores a entenderem a magnitude das perdas anteriores em relação ao maior valor já alcançado, permitindo uma avaliação mais completa de risco.

## Tecnologias Utilizadas

- **Python**: Linguagem principal para desenvolvimento da solução.
- **pandas**: Para manipulação e análise de dados.
- **BeautifulSoup**: Para web scraping e coleta de dados do CoinMarketCap.
- **SQLite**: Para armazenamento eficiente dos dados coletados.
- **Jupyter Notebook**: Para exploração e visualização interativa dos dados.

## Instalação

**1. Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/crypto-market-cap-drawdown.git

**2. Acesse o diretório do projeto:**
   cd crypto-market-cap-drawdown

**3. Crie um ambiente virtual e ative-o:**
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate      # Windows

**4. Instale as dependências:**
   pip install -r requirements.txt
   Como Usar
   Certifique-se de ter acesso à internet para realizar a coleta dos dados.

**5. Execute o script principal para iniciar a coleta e análise dos dados:**
   python main.py
   Os resultados da análise de market cap e drawdown estarão disponíveis no arquivo resultados.csv, ou podem ser visualizados diretamente no console.

##Contribuições
Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

##Licença
Este projeto está licenciado sob os termos da licença MIT. Consulte o arquivo LICENSE para mais informações.

---

### Pontos-Chave no README.md:

1. **Título**: O nome é direto e comunica claramente o propósito do projeto.
2. **Descrição**: Explica o contexto e a importância do projeto, abordando a análise de market cap e drawdown como diferencial.
3. **Funcionalidades**: Resume os principais componentes e o que o projeto oferece.
4. **Proposta de Valor**: Reforça como a abordagem baseada em market cap e drawdown é valiosa para investidores.
5. **Tecnologias**: Lista as ferramentas e linguagens utilizadas no desenvolvimento.
6. **Instruções de Instalação e Uso**: Ensina como clonar o repositório, configurar o ambiente e rodar o código.
7. **Contribuições**: Incentiva a comunidade a colaborar com o projeto.
8. **Licença**: Esclarece os direitos de uso e modificação do projeto.

Esse README e repositório estarão bem estruturados e prontos para que outros desenvolvedores possam testar, usar e contribuir com o projeto de análise de criptomoedas.








   
