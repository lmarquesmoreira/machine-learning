Questão 4:

1. Descreva os passos que você tomou para implementar o modelo de estimativa final para que tenha uma precisão de 80%.

   - Escolha um atributos
   - Adicione condições
   - Valide o nivel de sobrevivencia é maior que o da não sobrevivencia.
      -  Se Sim, teste a eficacia da precisão.
      -  Se não, adicione mais condições e reinicie os passos.

2. Quais atributos você investigou? 

    Atributos: Sex, Age, Fare, SibSp, Parch e Pclass.

3. Alguns atributos eram mais informativos do que os outros? 

    Sim, alguns atributos eram mais informativos(ex: Ticket e Cabin) e por conta disso preferi não utilizá-los, pois precisaria de mais condições para gerar a precisão esperada.

4. Quais condições você utilizou para separar os resultados de sobrevivência nos dados?

    Condições utilizadas:

    - se passenger['Sex'] for igual a 'female';
    - se passenger['Age'] for menor que 10;
    - se passenger['Age'] for menor que 75;
    - se passenger['Fare'] for maior que 40 e passenger['Fare'] for menor que 60 e passenger['SibSp'] for igual a 1:
    - se passenger['Fare'] for maior que 20 e passenger['Fare'] for menor que 40 e passenger['Age'] for menor que 40 e passenger['Parch'] for igual a 0 e passenger['Pclass'] for menor que 1 :

5. Quão precisas são suas estimativas?

    Nivel de precisão: 80.47%.
     
Questão 5: Pense em uma situação do mundo real em que a aprendizagem supervisionada pode ser aplicada. O que seria o resultado variável que você está tentando estimar? Nomeie dois atributos sobre os dados utilizados nessa situação que possam ser úteis para fazer as estimativas.

Resposta:

    - Situação: Suspeita de fraude na compra com cartão de crédito.

        . 

    - Resultado variável: 1 para Fraude, 0 para não fraude

    - Atributos: Numero do Cartao, Data e Hora de uso do cartão 