# Calculadora de IMC

Aplicação web para calcular o Índice de Massa Corporal a partir do peso e da altura informados pelo usuário.

**Demo:** [imc-mocha.vercel.app](https://imc-mocha.vercel.app/)

## Funcionalidades

- Entrada de peso e altura;
- validação de valores numéricos;
- mensagem de erro para dados inválidos;
- cálculo do IMC;
- exibição do resultado em modal;
- fechamento do modal pelo botão ou teclado.

## Tecnologias

- HTML5
- CSS3
- JavaScript com módulos ES

## Como executar

Como o projeto utiliza módulos JavaScript, execute-o por um servidor local:

```bash
git clone https://github.com/felipeand-dev/imc.git
cd imc
python -m http.server 8000
```

Acesse `http://localhost:8000`.

## Cálculo

O valor é obtido pela fórmula:

```text
IMC = peso / altura²
```

O peso deve ser informado em quilogramas e a altura em metros.

> [!NOTE]
> O resultado tem finalidade demonstrativa e educacional. A aplicação não fornece diagnóstico ou orientação médica.

## Conceitos praticados

Manipulação do DOM, módulos JavaScript, formulários, validação, eventos e componentes visuais controlados por estado.

