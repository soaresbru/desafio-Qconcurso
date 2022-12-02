# O Desafio de Aprendizagem Adaptativa - Qconcurso - SigmaGeek

## Introdução
Esta é a minha primeira participação em competição. Resolvi o case em apenas 2 dias e fiquei entre os 28% melhores.

Eu sabia que tinha pouco tempo para fazer então tentei entregar um produto rápido e que já serviria de alguma forma, tentando implementar o conceito de MVP (Produto mínimo viável)

Este é um desafio do SigmaGeek, caso queira ver este e mais desafios entre no meu link:
https://sigmageek.com/?ref=04QS0KSQ7V8J9VH

o conjunto de dados pode ser encontrado no link:
https://drive.google.com/drive/folders/1VtFkocuaNB8oo3bqF0VCx6ctnJwXitx_


## O Desafio


Os participantes deverão criar um modelo para classificar a resposta à 101ª questão, dado um conjunto de 100 respostas a questões feitas na sequência por 20.000 usuários.

O banco de dados Dataset_Model contém as respostas de 100 questões respondidas sequencialmente por  20.000 usuários e deverá ser usado para treinar o modelo.

O arquivo subjects_question  contém informações adicionais sobre as perguntas, mapeando as perguntas com assuntos. É importante notar que cada pergunta pode conter mais do que um assunto.

O arquivo Submit.csv é o arquivo que contém os dados sobre a 101ª questão para cada usuário. Seu modelo deverá fazer o score para a coluna "Acertou", contendo "0" se não acertou ou "1" se acertou.

Você deverá submeter um arquivo .csv contendo 20.000 linhas e apenas uma coluna contendo 0's e 1's que o seu modelo calculou.


## Método de avaliação

Para esse desafio de classificação vamos adotar o "F1-Score" como método de avaliação. Essa métrica pode ser interpretada como uma ponderação entre o “precision" e o "recall".

## Conteúdo do meu notebook:
1. Leitura das bases consumidas
2. Análise dos dados
3. Engenharia de Variáveis
4. Treinando o modelo
5. Criando o modelo para submissão
