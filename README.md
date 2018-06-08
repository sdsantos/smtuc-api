# SMTUC API

Baseada na aplicação web http://coimbra.move-me.mobi

## Linhas

### Obter todas as linhas

`GET http://coimbra.move-me.mobi/Lines/GetLines?providerName=SMTUC`

```
[{"Key":"SMTUC_2F","Value":"2F Manutenção - Sargento Mor"},{"Key":"SMTUC_2T","Value":"2T Manutenção - Vil de Matos"},{"Key":"SMTUC_4 ","Value":"4  Estação Nova - Sto Ant. dos Olivais( via Celas )"},{"Key":"SMTUC_5","Value":"5 Pedrulha - Estádio"},{"Key":"SMTUC_5F","Value":"5F Pedrulha - Parque"},{"Key":"SMTUC_5T","Value":"5T Pedrulha - Vale das Flores"},{"Key":"SMTUC_6","Value":"6 Cimo de Fala - Hospitais U.C."},{"Key":"SMTUC_6F","Value":"6F Fala - Hospitais U.C."},{"Key":"SMTUC_7","Value":"7 Arnado - Tovim"},{"Key":"SMTUC_7T","Value":"7T Palácio da Justiça - Tovim"},{"Key":"SMTUC_9","Value":"9 Parque - Casal da Misarela"},{"Key":"SMTUC_10","Value":"10 Parque - H. Sobral de Cid"},{"Key":"SMTUC_10A","Value":"10A Parque - H. Sobral de Cid"},{"Key":"SMTUC_10F","Value":"10F Beira Rio - H. Sobral de Cid"},{"Key":"SMTUC_11","Value":"11 Arnado - B. Norton de Matos(via Rua Verde Pinho)"},{"Key":"SMTUC_12","Value":"12 Beira Rio - Taveiro"},{"Key":"SMTUC_12A","Value":"12A Beira Rio - Taveiro"},{"Key":"SMTUC_12R","Value":"12R Beira Rio - Taveiro"},{"Key":"SMTUC_13","Value":"13 Beira Rio - Valongo( via Espirito St. Touregas)"},{"Key":"SMTUC_13P","Value":"13P Beira Rio - S. Martinho do Bispo (piscinas)(Piscinas )"},{"Key":"SMTUC_13T","Value":"13T Beira Rio - Valongo(por Coalhadas)"},{"Key":"SMTUC_14","Value":"14 Portagem - S. Martinho do Bispo(por Estação Velha)"},{"Key":"SMTUC_14T","Value":"14T Beira Rio - S. Martinho do Bispo( por Covões )"},{"Key":"SMTUC_16","Value":"16 Manutenção - Carapinheira da Serra"},{"Key":"SMTUC_16F","Value":"16F Manutenção - Carapinheira da Serra H.U.C."},{"Key":"SMTUC_16G","Value":"16G Manutenção - Rocha Velha"},{"Key":"SMTUC_17","Value":"17 Beira Rio - Coalhadas"},{"Key":"SMTUC_18","Value":"18 Portagem - H. Sobral de Cid( via Assafarge )"},{"Key":"SMTUC_18E","Value":"18E Portagem - Escola B. 2+3 de Ceira"},{"Key":"SMTUC_18F","Value":"18F Portagem - H. Sobral de Cid"},{"Key":"SMTUC_19","Value":"19 Praça da República - S. Paulo de Frades"},{"Key":"SMTUC_19A","Value":"19A Praça da República - Rocha Nova"},{"Key":"SMTUC_19R","Value":"19R Praça da República - S. Romão"},{"Key":"SMTUC_19T","Value":"19T Praça da República - Rocha Nova"},{"Key":"SMTUC_20","Value":"20 Portagem - Valongo( via Casais )"},{"Key":"SMTUC_20T","Value":"20T Portagem - Valongo(por Coalhadas)"},{"Key":"SMTUC_21","Value":"21 Beira Rio - Arzila"},{"Key":"SMTUC_21A","Value":"21A Beira Rio - Arzila"},{"Key":"SMTUC_21R","Value":"21R Beira Rio - Arzila"},{"Key":"SMTUC_21T","Value":"21T Beira Rio - Cruzam. R. Lameira (Arzila)"},{"Key":"SMTUC_22","Value":"22 Portagem - Escola Inês de Castro(por Fala)"},{"Key":"SMTUC_22F","Value":"22F Portagem - Escola Inês de Castro"},{"Key":"SMTUC_23","Value":"23 Portagem - Escola B. 2+3 de Ceira"},{"Key":"SMTUC_23C","Value":"23C Portagem - Ceira"},{"Key":"SMTUC_23F","Value":"23F Portagem - Hopital Sobral Cid"},{"Key":"SMTUC_24","Value":"24 Arnado - Quinta da Nora"},{"Key":"SMTUC_24T","Value":"24T Palácio da Justiça - Quinta da Nora"},{"Key":"SMTUC_25","Value":"25 Praça da República - Casal da Rosa(por Eiras)"},{"Key":"SMTUC_25T","Value":"25T Praça da República - Stª. Apolónia"},{"Key":"SMTUC_26","Value":"26 Praça da República - Chão do Bispo"},{"Key":"SMTUC_27","Value":"27 Praça da República - Bairro do Ingote(por B. Brinca)"},{"Key":"SMTUC_27F","Value":"27F Praça da República - Bairro do Ingote"},{"Key":"SMTUC_28","Value":"28 Universidade - Bairro do Ingote(por M. Formoso)"},{"Key":"SMTUC_28F","Value":"28F Praça da República - Bairro do Ingote"},{"Key":"SMTUC_29","Value":"29 Estação Nova - H.U.C."},{"Key":"SMTUC_30","Value":"30 Antero de Quental - Carapinheira da Serra"},{"Key":"SMTUC_30F","Value":"30F Praça da República - Lordemão"},{"Key":"SMTUC_30R","Value":"30R Antero de Quental - Redonda"},{"Key":"SMTUC_30T","Value":"30T Antero de Quental - Lordemão"},{"Key":"SMTUC_31","Value":"31 Largo do Arnado - Cruz dos Morouços"},{"Key":"SMTUC_32","Value":"32 Beira Rio - Vila Pouca do Campo"},{"Key":"SMTUC_32A","Value":"32A Beira Rio - Vila Pouca do Campo"},{"Key":"SMTUC_32R","Value":"32R Beira Rio - Vila Pouca do Campo"},{"Key":"SMTUC_33","Value":"33 Parque - Manutenção( via Casa Branca )"},{"Key":"SMTUC_33R","Value":"33R Parque - Manutenção"},{"Key":"SMTUC_34","Value":"34 Universidade - Polo II da Universidade"},{"Key":"SMTUC_34T","Value":"34T Universidade - Polo II da Universidade"},{"Key":"SMTUC_35","Value":"35 H.U.C. - Pedrulha"},{"Key":"SMTUC_36","Value":"36 Praça da República - Ponte de Eiras"},{"Key":"SMTUC_36F","Value":"36F H.U.C. - Ponte de Eiras"},{"Key":"SMTUC_36T","Value":"36T Praça da República - Ponte de Eiras"},{"Key":"SMTUC_37","Value":"37 Vale das Flores - H.U.C."},{"Key":"SMTUC_38","Value":"38 Stª. Clara - Polo II( via Forum )"},{"Key":"SMTUC_38F","Value":"38F Stª. Clara - Polo II"},{"Key":"SMTUC_38T","Value":"38T Parque - Polo II - Polo II - Portagem"},{"Key":"SMTUC_39","Value":"39 Palácio da Justiça - Ribeiro de Vilela"},{"Key":"SMTUC_41","Value":"41 Alqueves - Vale das Flores"},{"Key":"SMTUC_42C","Value":"42C Parque - Vale de Canas"},{"Key":"SMTUC_42M","Value":"42M Misarela - Esc. Eugénio de Castro"},{"Key":"SMTUC_42T","Value":"42T Portagem - Vale de Canas"},{"Key":"SMTUC_42V","Value":"42V Portagem - Vale de Canas"},{"Key":"SMTUC_43","Value":"43 Portagem - Almalaguês( via Vale das Flores )"},{"Key":"SMTUC_43T","Value":"43T Portagem - Almalaguês"},{"Key":"SMTUC_103","Value":"103 Estação Nova - Olivais - Sto Ant. dos Olivais( via Universidade )"},{"Key":"SMTUC_FEIRA DOS 7 E 23","Value":"FEIRA DOS 7 E 23 "},{"Key":"SMTUC_AZUL","Value":"AZUL "},{"Key":"SMTUC_BOTANICO","Value":"BOTANICO "}]
```

### Direcções de um linha

`GET http://coimbra.move-me.mobi/Lines/GetDirections?lineCode=SMTUC_2F`

```
["R§Volta§Sargento Mor - Manutenção","G§Ida§Manutenção - Sargento Mor"]
```

### Tipos de dia de uma linha

`GET http://coimbra.move-me.mobi/Scheds/GetDayTypes?lineCode=SMTUC_2F`

```
[{"Item1":["6099"],"Item2":"Seg, Ter, Qua, Qui, Sex"},{"Item1":["6101"],"Item2":"Sáb"},{"Item1":["6100"],"Item2":"Dom, Fer"}]
```

### Horário de linha

```
POST http://62.28.187.230/Scheds/Select
```

_Body: x-www-form-urlencoded_
```
dayType:6099
direction:R
directionDescription:Volta
line:SMTUC_2F
lineDescription:2F Manutenção - Sargento Mor
provider:SMTUC
```

Reposta em HTML com os horários numa tabela.


## Paragens

### Pesquisa paragem por keyword

`POST http://62.28.187.230/Find/SearchByStops?keyword=ctt`

```
SMTUC - Ctt [SMTUC_1473];SMTUC - S. Martinho (Ctt) [SMTUC_1240];SMTUC - S. Martinho (Ctt) [SMTUC_1241];
```

### Horário em tempo real da paragem

`GET http://coimbra.move-me.mobi/NextArrivals/GetScheds?providerName=SMTUC&stopCode=SMTUC_1473`

```
[{"Key":1,"Value":["7T","Tovim","-1*"]},{"Key":2,"Value":["21","Beira Rio ","1*"]},{"Key":3,"Value":["16","Beira Rio ","2*"]},{"Key":4,"Value":["FEIRA DOS 7 E 23","Beira Rio","2"]},{"Key":5,"Value":["24T","B. N. Matos","5*"]},{"Key":6,"Value":["4","Est. Nova","8*"]},{"Key":7,"Value":["4 ","Est. Nova","9"]},{"Key":8,"Value":["7T","Tovim","11*"]},{"Key":9,"Value":["29","Est. Nova","11*"]},{"Key":10,"Value":["14T","Beira Rio ","11*"]},{"Key":11,"Value":["24T","B. N. Matos","12*"]},{"Key":12,"Value":["25","Beira Rio","12"]},{"Key":13,"Value":["22","Portagem","14*"]},{"Key":14,"Value":["103","Est. Nova","15*"]},{"Key":15,"Value":["14T","Beira Rio","16"]},{"Key":16,"Value":["6","Bayer","19"]},{"Key":17,"Value":["32A","Beira Rio","21"]},{"Key":18,"Value":["4 ","Est. Nova","24"]},{"Key":19,"Value":["24T","B. Norton Matos","25"]},{"Key":20,"Value":["29","Est. Nova","25"]},{"Key":21,"Value":["103","Est. Nova","26"]},{"Key":22,"Value":["7T","Tovim","30"]},{"Key":23,"Value":["14T","Beira Rio","31"]},{"Key":24,"Value":["31","Cruz Morouços (C)","32"]},{"Key":25,"Value":["13T","Beira Rio","36"]},{"Key":26,"Value":["24T","B. Norton Matos","37"]},{"Key":27,"Value":["4 ","Est. Nova","39"]},{"Key":28,"Value":["21T","Beira Rio","39"]},{"Key":29,"Value":["29","Est. Nova","40"]},{"Key":30,"Value":["103","Est. Nova","41"]},{"Key":31,"Value":["6","Bayer","43"]},{"Key":32,"Value":["7T","Tovim","46"]},{"Key":33,"Value":["14T","Beira Rio","46"]},{"Key":34,"Value":["FEIRA DOS 7 E 23","Beira Rio","47"]},{"Key":35,"Value":["24T","B. Norton Matos","49"]},{"Key":36,"Value":["4 ","Est. Nova","54"]},{"Key":37,"Value":["29","Est. Nova","55"]},{"Key":38,"Value":["10","Parque 2","58"]}]
```
