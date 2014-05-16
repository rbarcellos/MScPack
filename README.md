README
========================================================

***2014-05-15***

```r
plot(rnorm(100))
```

![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1.png) 


Passos dados:
  - tentativa de acelerar o MCMC via remocao do loop. Resultado: nao houve ganho computacional. Ao contrario, aumentou-se o tempo computacional.

Passos futuros:
  - implementar funcao de calculo da verossimilhanca marginal. Para tanto, e' recomendavel integrar tanto os fatores quanto os parametros de estado do MCMC;
  - aplicar o modelo a dados artificiais e gerar relatorio dessa aplicacao, ilustrando as diferencas entre os valores verdadeiros e os estimados pelo modelo. Atentar para a relacao entre os parametros fixos e os dinamicos;
  - incorporar SV aos modelos ja implementados;
  - estudar modelos fatoriais dinamicos (*dynamic factor models*), pois me parece uma abordagem interessante para comparar a analise fatorial com o modelo de regressao pelo Brent. Nessa abordagem, reduzir-se-ia a complexidade do modelo por nao haver mais parametros dinamicos na relacao com o Brent e os niveis medio e sazonal seriam tratados constantes por simplificacao. O ganho dessa abordagem estaria na interpretacao que se poderia ter dos fatores globais, regionais e dos produtos.
