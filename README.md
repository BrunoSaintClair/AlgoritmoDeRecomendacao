# Algoritmo de recomendação

O objetivo desse repositório é desenvolver diferentes modelos de algoritmos para recomendação de filmes. Além de modelos diferentes, também pretendo testar métodos diferentes.


## Primeiro modelo

O primeiro modelo foi feito com o método de content based filtering. Que se baseia no conteúdo dos filmes para recomendar semelhantes que possam te interessar.

Para calcular a similaridade dos filmes, foi realizado o processo de embedding, que transforma as informações que estão presentes em formato de texto, para vetores numéricos. Após isso, foi feito o cálculo de similaridade de cossenos, que calcula o cosseno do ângulo entre vetores em um espaço multidimensional. Esse valor indica quão semelhantes são os vetores em termos de direção.
