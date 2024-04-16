# LAB-AI-900-LANG
Neste LAB, exploramos o uso do Azure Language Studio e realizamos um teste de mineração de sentimento e opinião.

# Desenvolvimento do Lab
Ao iniciarmos o Lab, criamos um recurso de serviços de IA do Azure e utilizamos o Language Studio para análise de sentimentos, com as seguinte etapas:

### Conectar o recurso de serviço de IA do Azure ao Language Studio:
- Acessar o [Language Studio](https://language.cognitive.azure.com)
- Criar um recurso para realização da análise de sentimentos
- Configurar o recurso no Azure AI Language Studio

### Analisar avaliações no Language Studio:
- Selecionar a opção **nalyze sentiment and opinions**
- Selecionar o idioma do texto a ser analisado (**Português do Brasil**)
- Selecionar o recurso criado no **Azure AI Language Studio**
- Digitar o texto a ser analisado no campo: **Insira seu próprio texto, carregue um arquivo ou use um de nossos textos de exemplo**
- Marcar a caixa para confirmar a demosntração e selecionar **Executar**

# Resultados
Após execução das etapas supracitadas, foram obtidos os seguintes resultados a partir do Salmo 15:
- `Guardai-me, ó Deus, porque em vós me refugio!`
- `Guardai-me, ó Deus, porque em vós me refugio!`
- `Ó Senhor, sois minha herança e minha taça, meu destino está seguro em vossas mãos! Tenho sempre o Senhor ante meus olhos, pois se o tenho a meu lado não vacilo.`
- `Eis por que meu coração está em festa, minha alma rejubila de alegria, e até meu corpo no repouso está tranquilo; pois não haveis de me deixar entregue à morte, nem vosso amigo conhecer a corrupção.`
- `Vós me ensinais vosso caminho para a vida; junto a vós, felicidade sem limites, delícia eterna e alegria ao vosso lado!`

#### Sentimento do documento: Misturado (Confiança: 60,00%)

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 60,00% | 17,00% | 23,00% |

#### Frase 1: Positivo (Confiança: 50,00%)

`— Guardai-me, ó Deus, porque em vós me refugio!`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 50,00% | 33,00% | 17,00% |

#### Frase 2: Positivo (Confiança: 50,00%)

`— Guardai-me, ó Deus, porque em vós me refugio!`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 50,00% | 33,00% | 17,00% |

#### Frase 3: Neutro (Confiança: 30,00%)

`Ó Senhor, sois minha herança e minha taça, meu destino está seguro em vossas mãos! `

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 30,00% | 69,00% | 1,00% |

#### Frase 4: Positivo (Confiança: 64,00%)

`Tenho sempre o Senhor ante meus olhos, pois se o tenho a meu lado não vacilo.`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 64,00% | 33,00% | 3,00% |

#### Frase 5: Positivo (Confiança: 99,00%)

`Eis por que meu coração está em festa, minha alma rejubila de alegria, e até meu corpo no repouso está tranquilo;`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 99,00% | 1,00% | 0,00% |

#### Frase 6: Negativo (Confiança: 0,00%)

`pois não haveis de me deixar entregue à morte, nem vosso amigo conhecer a corrupção.`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 0,00% | 0,00% | 100,00% |

#### Frase 7: Neutro (Confiança: 16,00%)

`— Vós me ensinais vosso caminho para a vida;`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 16,00% | 84,00% | 1,00% |

#### Frase 8: Positivo (Confiança: 100,00%)

`junto a vós, felicidade sem limites, delícia eterna e alegria ao vosso lado!`

| Positivo   | Neutro       | Negativo                           |
| :---------- | :--------- | :---------------------------------- |
| 100,00% | 0,00% | 0,00% |
