# README

## Informações Pessoais
**Nome Completo:** Lucas Garcia Costa  
**Matrícula:**  20210018356 (Bacharelado em Ciências e Tecnologia)

---

## Descrição da Tarefa
A tarefa realizada tinha como objetivo construir um grafo de co-ocorrência dos ingredientes presentes na culinária brasileira e analisar sua assortatividade . Para isso, utilizei o moodelo de linguagem ChatGPT para criar uma base de dados contendo o nome da receita de um prato típico, os ingredientes e os tipos dos ingredientes. Por questão de simplicidade, foram usadas apenas cinquenta receitas e os ingredientes foram classificados em oito categorias (Vegetal, Proteina, Carboidrato, Fruta, Condimento, Laticinio, Gordura e Outro). Depois construi um grafo utilizando a biblioteca NetwokX e a visualização com a biblioteca nxviz, utilizando esses para fazer a análise.
**Link para o vídeo de apresentação:** [Link do vídeo](https://www.loom.com/share/f96cc5a067cb4f3caa812338e67079c2?sid=77db09c9-0d54-4b83-b6d4-93ae654f0bfa)

---

## Discussão
Tive dificuldades de formatação e por isso tive um passo extra de código para concertar esse fato (Código presente na pasta ingredientes). Mas em relação aos resultados, eles expressam o esperado, uma assortatividade negativa, mas ainda próxima de zero. Esse fato demonstra a tendência a utilizar ingredientes de diferentes categorias, o que é intuitivo, mas devido a concentração de ingredientes classificados como vegetais, carboidratos e proteínas, há uma menor diversificação dos tipos de ingredientes nas receitas. Além de existir diversos pratos que concentram diversos ingredientes de um mesmo tipo, como feijoada para proteínas e vinagrete para vegetais, que aproximam a assortatividade ainda mais a zero.

---

## Grafo Gerado:  
![Grago gerado](https://github.com/L-Garcia-C/AED2-UFRN/blob/c09de103cf270c9922131ee459116f3788a6bdf4/UN1/U1T2/images/grafo.png)

---
