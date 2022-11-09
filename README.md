Json para cadastro de mulher

url : http://localhost:8080/api/mulher

```

{
    "nomeMulher" : "Julia Alves",
    "email" : "julia@gmail.com",
    "senha" : "senha123",
    "dtNascimento" : "01/01/2000",
    "cpf" : 123456,
    "cpfDigito" : 12,
    "telefone" : 123456789,
    "telefoneDDD" : 11
}


```

Json para cadastro de local escolhido

url : http://localhost:8080/api/localEscolhido

```

{
"codMulher" : 1,
    "incidente" : "tres caras numa moto",
    "dtOcorrencia" : "11/12/2022",
    "avaliacaoPerigo" : 5,
        "endereco" : {
        "numeroCep": 111222333,
        "nomeRua": "Bom retiro",
        "numeroRua": "25",
        "desComplemento": "Ao lado do shopping cidade sao paulo",
        "bairro" : {
            "nomeBairro" : "Paulista",
            "cidade" : {
                "nomeCidade" : "São Paulo",
                "siglaCidade" : "SP",
                "estado" : {
                    "nomeEstado" : "São paulo",
                    "siglaEstado" : "SP"
                }
            }
        }
    }
}

```
