### Case Serviço de Atendimento ao Cliente - Power BI | Análise de dados

Link de acesso ao pbix publicado:

https://app.powerbi.com/view?r=eyJrIjoiOTBiNThiZmYtYWUyNS00YTkxLTg1YmMtZmEwOWZlOTQ5MTQwIiwidCI6ImI1NTBlNzA3LTEwY2MtNDc2ZC05NDExLWJkOGM5ZGU3ZWNjNCJ9

### Objetivo 

Considere uma empresa do segmento de tecnologia, essa empresa desenvolve uma ferramenta de gerenciamento de usuários online, ministrando até treinamentos na área. 
No setor de suporte, há uma grande quantidade de chamados registrados pelos clientes.

O principal objetivo deste projeto é analisar como o suporte está lidando com esses chamados, avaliando aspectos como tempo de resposta, avaliações de desempenho e quantidade de chamados. A empresa valoriza a agilidade no atendimento, já que cada demanda exige uma resposta rápida e eficiente.
Outro ponto importante é a sazonalidade dos chamados, especialmente durante as atualizações no servidor, que ocorrem duas vezes ao ano. Assim, é essencial monitorar a quantidade de chamados (respondidos e pendentes) em diferentes períodos do ano.

Além disso, busca-se identificar os principais motivos pelos quais os clientes entram em contato, categorizando-os por tipo de problema.Também é fundamental destacar os funcionários com um alto número de chamados em aberto, para direcionar ações específicas de melhoria.

### Organização do Projeto

```
├── .gitignore    <- Arquivos e diretórios a serem ignorados pelo Git  
├── LICENSE       <- Licença de código aberto (MIT)  
├── README.md     <- README principal para desenvolvedores que utilizam este projeto  
├── arquivos     <- Arquivos pbix
        ├── BI SAC Fd.pbix
```

### Detalhes das métricas utilizadas e resumo dos resultados

Este relatório foi desenvolvido com o objetivo de abordar todas essas questões identificadas anteriormente. Inicialmente, como boa prática, a seleção dos parâmetros é obrigatória e amplia o leque de possibilidades, tornando os tipos de análises significativamente mais abrangentes.

![image](https://github.com/user-attachments/assets/91e52698-a865-4247-bece-98805dc0f1f7)

Com algumas seleções é possível pré-estabelecer uma visualização,por exemplo, de os tipos de problemas por chamados encerrados. Com esse visual, é simples definir os motivos que levaram os clientes a contatarem o suporte.

![image](https://github.com/user-attachments/assets/e02f031b-61d4-497a-a0de-14a603c68011)

As análises temporais também são de suma importância, pois, a cada semestre, ocorrem atualizações que modificam o sistema, o que pode aumentar o contato com o SAC.

![image](https://github.com/user-attachments/assets/86d9fc34-737e-44c6-b7cd-73ef2a0262ca)

 Ambas possuem interatividade com parâmetros e apresentam dicas de ferramentas para uma visão no detalhe.
 
![image](https://github.com/user-attachments/assets/e69579e4-adc3-404c-beb1-e499d0e36bee)

![image](https://github.com/user-attachments/assets/2e9412b4-f19e-4604-ba0c-4ec1c2d12a3f)

Além disso, como em todo projeto de BI, é indispensável alguns indicadores agrupados, o que nesse relatório consta com cards superiores.

![image](https://github.com/user-attachments/assets/2f653849-2097-432b-82c6-acd575065f8c)


### Ferramentas e Metodologia
   - Ferramenta Utilizada: Power BI.
  
   - Conexão de Dados: A base de dados foi importada de um arquivo Excel.
  
   - Processo ETL: Todo o processo de transformação e limpeza dos dados foi realizado no Power Query, garantindo consistência e qualidade na análise.
  
### Características do Painel

  O projeto inclui um painel interativo a critério do usuário, com os seguintes recursos:

   - Botões de Navegação: Guias intuitivas, como "Home" e "Limpar Filtros", para facilitar a usabilidade.
  
   - Segmentações de Data: Permite filtrar os dados por períodos específicos, garantindo flexibilidade nas análises.
  
   - Indicadores Dinâmicos: Dois parâmetros principais foram configurados para apresentar métricas de forma totalmente dinâmica e personalizável.

### Como Reproduzir o Projeto

- O link no início do README contém a publicação do BI de forma pública.

- Baixar o arquivo .pbix, dessa forma, tem acesso a todo o projeto, como: bases, cálculos, imagens, modelagem e ícones. (É necessário ter o Power BI Desktop instalado)
 
