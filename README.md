# prog-sem9
Atividade do Hayashi da Semana 9 do módulo 7

**Introdução**

A manutenção de modelos de aprendizado de máquina é um desafio constante, especialmente quando se trata de modelos de linguagem que dependem de conhecimento do mundo real. À medida que o mundo muda, o conhecimento armazenado nesses modelos pode rapidamente se tornar desatualizado, o que pode levar a resultados imprecisos e até mesmo prejudiciais. Esse problema é conhecido como "concept drift", que se refere à mudança contínua nas relações entre as variáveis de entrada e saída de um modelo ao longo do tempo. O concept drift é um desafio significativo para a manutenção de modelos de linguagem, pois pode levar a uma perda de conhecimento anteriormente adquirido e a uma incapacidade de adquirir novos conhecimentos de forma confiável. Neste contexto, a Continual Knowledge Learning (CKL) surge como uma abordagem promissora para lidar com o concept drift e manter os modelos de linguagem atualizados e precisos.

**Solução proposta**

Para lidar com o problema de concept drift em modelos de linguagem, propomos uma abordagem de Continual Knowledge Learning (CKL) que consiste em três blocos principais: 

1. Bloco de Aquisição de Novo Conhecimento: Este bloco é responsável por adquirir novos conhecimentos do mundo real e integrá-los ao modelo de linguagem existente. Ele usa técnicas de aprendizado incremental para atualizar o modelo com novos dados sem afetar o conhecimento anteriormente adquirido. 

2. Bloco de Retenção de Conhecimento Invariante: Este bloco é responsável por reter o conhecimento invariante do mundo real que é relevante para o modelo de linguagem. Ele usa técnicas de regularização para evitar a perda de conhecimento anteriormente adquirido e garantir que o modelo permaneça preciso e confiável. 

3. Bloco de Atualização de Conhecimento Desatualizado: Este bloco é responsável por atualizar o conhecimento desatualizado no modelo de linguagem. Ele usa técnicas de aprendizado incremental para remover o conhecimento desatualizado e substituí-lo por novos dados relevantes. 

Diagrama de Blocos:

```
+------------------------------------+
|           Modelo de Linguagem       |
+------------------------------------+
                  |
                  |
+------------------------------------+
|   Bloco de Aquisição de Novo        |
|           Conhecimento             |
+------------------------------------+
                  |
                  |
+------------------------------------+
|   Bloco de Retenção de Conhecimento |
|            Invariante               |
+------------------------------------+
                  |
                  |
+------------------------------------+
|   Bloco de Atualização de           |
|      Conhecimento Desatualizado     |
+------------------------------------+
```

A solução proposta usa uma abordagem de aprendizado incremental para atualizar o modelo de linguagem com novos dados e evitar a perda de conhecimento anteriormente adquirido. O bloco de aquisição de novo conhecimento é responsável por adquirir novos dados relevantes do mundo real e integrá-los ao modelo de linguagem existente. O bloco de retenção de conhecimento invariante é responsável por garantir que o modelo retenha o conhecimento anteriormente adquirido que é relevante para o modelo de linguagem, usando técnicas de regularização para evitar a perda de conhecimento e garantir que o modelo permaneça preciso e confiável. O bloco de atualização de conhecimento desatualizado é responsável por remover o conhecimento desatualizado do modelo de linguagem e substituí-lo por novos dados relevantes, usando técnicas de aprendizado incremental. 

Em resumo, a abordagem proposta de CKL usa uma combinação de técnicas de aprendizado incremental e regularização para lidar com o problema de concept drift em modelos de linguagem. Cada bloco tem uma responsabilidade clara e trabalha em conjunto para garantir que o modelo de linguagem permaneça atualizado e preciso ao longo do tempo.

**Conclusão**
**Referências Bibliográficas**
