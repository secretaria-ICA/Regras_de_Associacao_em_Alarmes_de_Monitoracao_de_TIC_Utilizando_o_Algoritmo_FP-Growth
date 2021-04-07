# Regras de Associação em Alarmes de Monitoração de TIC Utilizando o Algoritmo FP-Growth

#### Aluno: [Tiago Santos](https://github.com/TiagoSantosVidal).
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

Esta monografia visa apresentar o uso de técnicas de mineração de dados através de regras de associação aplicada ao gerenciamento de alarmes de monitoração de serviços de TIC em uma grande empresa nacional. O uso de associações automáticas neste processo tem por objetivo tornar o diagnóstico de alarmes mais assertivo e a recuperação de falhas mais efetiva e em um menor tempo. 
Dentre as vantagens da aplicação desta técnica podemos citar a redução da quantidade de notificação de alarmes transferidos aos operadores de gerenciamento de redes, aumentando a relevância dos alarmes recebidos e assim aprimorando a análise técnica realizada reduzindo o tempo de recuperação à normalidade das falhas. Com isso, temos como resultados esperados a melhoria na qualidade dos serviços, diante do aumento da disponibilidade para os usuários, redução dos custos de operação e manutenção dos serviços de TIC. 
Para o estudo de caso apresentado foi utilizado o algoritmo FP-Growth, com testes em diferentes parâmetros e cenários, considerando a busca pela melhor eficiência no resultado das regras de associação. Para tanto, foram utilizados dados históricos de ocorrência de alarmes e considerados cada transação como um agrupamento de alarmes identificados e ocorridos em uma certa janela de tempo. Cada alarme foi caracterizado de acordo com um identificador montado por um par (elemento, tipo de alarme). Foram testados diversos valores nesta janela de tempo, observando a qualidade da saída e a validação dos resultados das associações. Durante o trabalho vários processos de ETL foram utilizados para a limpeza dos dados. O desenvolvimento da programação foi feito em Python, aplicando a biblioteca pyfpgrowth. 
Para analisar a eficácia das regras apresentadas como resultado, foi elaborado um ambiente para que tais regras fossem verificadas como listas de recomendações onde, após análise criteriosa feita pela equipe técnica especializada, esta possa ser aplicada como uma associação aceita para ser aplicada em definitivo. Utilizando o método de entrevista para a validação, obtivemos como medição de eficácia do algoritmo, a aceitação de 82,7% das recomendações. A partir destes resultados obtidos, considerando condições típicas de operação, estima-se que a implementação desta técnica possua o potencial para redução do quantitativo de alarmes tratados em torno de 45,5%, validando assim o potencial de utilização no problema apresentado.

---

Matrícula: 183.477.001

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
