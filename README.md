# App Os Inusitados

Aplicativo simples feito em flutter integrado com o [Google DialogFlow](https://dialogflow.cloud.google.com/) para interação com chatbot.

Este projeto foi desenvolvido para fins de estudo.
Curso [MBA em Atificial Intelligence](https://www.impacta.edu.br/mba/artificial-intelligence) da [Faculdade Impacta](https://www.impacta.edu.br/).

## Turma "Os Inusitados"

```
Ingrid Santos Rodrigues
Luan Oliveira Fernandez Rodrigues
Marcelo Almeida de Souza
Robson Jesus Nogueira de Paula
```

## Rodando o projeto

Segue abaixo algumas instruções simples para conseguir rodar o projeto

Primeiramente para rodar o app em Android, voce vai precisar gerar uma keystore (chave RSA), entre na pasta `assets`, e execute o comando abaixo

```
keytool -genkey -v -keystore keystore.jks -alias alias_name -keyalg RSA -keysize 2048 -validity 10000
```

### Para rodar o app no device

```
flutter run --no-sound-null-safety
```

### Para gerar o build Android (debug)

```
flutter build apk --no-sound-null-safety --debug
```

## Começando com Flutter

Conheça:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

Confira a [documentação](https://flutter.dev/docs).

## Referencias

[Criando um Chatbot com Flutter e DialogFlow](https://medium.com/flutter-comunidade-br/criando-um-chatbot-com-flutter-e-dialogflow-f828e5301101)
[chatbot-aulas-flutter](https://github.com/kleberandrade/chatbot-aulas-flutter)
