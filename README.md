### Solução do erro: ITMS-90117: Missing routing app coverage file: You must upload a routing app coverage file in App Store Connect if you register as a routing app.

- Caso você indique que seu aplicativo usa navegação, a apple vai pedir o arquivo de Coverage. Então você precisa gerar o arquivo para colocar, isso involve criar o poligono e depois formatá-lo.

- Para salvar sua vida hoje, pode usar o meu poligono que está pronto para todo o território Brasileiro.

# Covarage.geojson

    {
      "type": "MultiPolygon",
      "coordinates": [    [      [        [          -74.45042338526487,          -7.648001795952013        ],
            [          -71.55883389219483,          -12.270585428257533        ],
            [          -65.94815567232118,          -10.39993752011462        ],
            [          -64.84806321699492,          -13.17415985958641        ],
            [          -61.23117670672795,          -14.4986627920171        ],
            [          -60.52521867420623,          -16.585865021834806        ],
            [          -58.1818343863645,          -18.181086719323304        ],
            [          -58.42425328150088,          -21.865515514678947        ],
            [          -55.58785931151664,          -24.76885841160265        ],
            [          -54.454480141341136,          -26.32944407432892        ],
            [          -58.637187740369995,          -30.16549372068291        ],
            [          -53.48503805411269,          -34.394775665732986        ],
            [          -36.79185164860317,          -19.810427382198483        ],
            [          -34.0089201124413,          -4.027663476985069        ],
            [          -51.654123764816546,          5.510159690259016        ],
            [          -65.25195738618359,          4.797071850887363        ],
            [          -70.82740805280663,          1.560805619406608        ],
            [          -74.45042338526487,          -7.648001795952013        ]
          ]
        ]
      ]
    }

Esse código, gera o poligono cobrindo todo o território Brasileiro. Depois disso é só salvar o seu arquivo (ou baixar o que tem aqui no repo).
## Onde colocar o bendito arquivo
Eu tive uma certa dificuldade de encontrar o local para botar esse arquivo, segue o screenshot para ajudar na localização:

1. Clique em App Store
2. Perto da versão você vai encontrar o local para fazer o upload do arquivo de coverage

![](https://github.com/BrunoCCPires/Covarage-geojson-apple/blob/main/localizacao-do-campo.PNG?raw=true)

## Imagem do Poligono

![Geojson](https://github.com/BrunoCCPires/Covarage-geojson-apple/blob/main/geolocation.PNG?raw=true "Geojson")

## Referências 

1. Gerador: https://geojson.io/#new&map=3.5/-14.83/-54.23
2. Documentação apple: https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/LocationAwarenessPG/ProvidingDirections/ProvidingDirections.html
3. Arquivo [Covarage.geojson ](https://github.com/BrunoCCPires/Covarage-geojson-apple/blob/main/Coverage.geojson "Covarage.geojson ")do Brasil. 

#### Espero que ajude alguém perdido que bateu com o erro ITMS-90117

Se precisar de ajuda entre em contato. 
Boa sorte e abraço!
