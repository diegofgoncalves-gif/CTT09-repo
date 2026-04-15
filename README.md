1-A mensagem foi um AssertionError. No log do GitHub Actions, ela aparece destacada com um E vermelho, indicando que uma condição esperada não foi atendida.

2-O Pytest esperava receber {"resultado": 30} (considerando um teste de soma de 10 + 20).
Porém, ele recebeu de fato {"resultado": -10}, porque a função foi alterada para subtrair (10 - 20 = -10).
