# Projeto que calcula o IMC (índice de massa corporal), de acordo com a seguinte especificação: IMC = Peso / Altura²

## O resultado deve ser expresso, conforme os valores abaixo:

* Magreza, quando o resultado é menor que 18,5 kg/m2;
* Normal, quando o resultado está entre 18,5 e 24,9 kg/m2;
* Sobrepeso, quando o resultado está entre 24,9 e 30 kg/m2;
* Obesidade, quando o resultado é maior que 30 kg/m2;


## Como usar?

### Flask

```bash
flask run
```

### Docker

```bash
docker build -t imc_calculator .
docker run -p 5000:5000 imc_calculator
```

Acesse http://localhost:5000/ para ver a aplicação.