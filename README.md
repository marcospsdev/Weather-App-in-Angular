# Weather App em Angular

App de clima feito em **2024** com **Angular 15** e a API pública do **OpenWeatherMap**.

## O que tem

- Busca do clima atual por cidade
- Card com temperatura, mínima, máxima, umidade e vento
- Imagem de fundo que muda conforme a temperatura
- Ícones com Font Awesome e serviço HTTP com RxJS

## Como rodar

1. Crie uma chave gratuita em [openweathermap.org](https://openweathermap.org/api)
2. Copie `src/environments/environment.example.ts` para `src/environments/environment.ts` e coloque a sua chave
3. Instale e rode:

```bash
npm install
npm start
```

O arquivo `environment.ts` está no `.gitignore` para a chave não ir para o repositório.
