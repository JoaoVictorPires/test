# Points of Interest

Aplicativo Flutter para cadastro e visualização de pontos de interesse, com persistência local e uso de localização.

## Tecnologias Utilizadas

- **Flutter**: Framework principal para desenvolvimento multiplataforma (Android, iOS, Web, Desktop)
- **Dart**: Linguagem de programação
- **GetX**: Gerenciamento de estado e rotas
- **Geolocator**: Obtenção da localização do dispositivo
- **Sqflite**: Persistência de dados local (SQLite)
- **Path**: Manipulação de caminhos de arquivos

## Estrutura de Pastas

```
lib/
  main.dart                  # Ponto de entrada do app
  domain/
    point_of_interest.dart   # Entidade principal
  screens/
    home/
      home.dart             # Tela principal
      home_controller.dart  # Lógica da tela principal
  shared/
    infrastructure/
      database/
        database.dart       # Configuração do banco de dados
        repositories/
          point_of_interest.dart # Repositório de dados
  use_cases/
    create_point_of_interest.dart # Caso de uso para criar ponto
    read_point_of_interest.dart   # Caso de uso para ler pontos
```

## Como rodar o projeto

1. Instale o [Flutter](https://flutter.dev/docs/get-started/install)
2. Execute `flutter pub get` para instalar as dependências
3. Rode o projeto com `flutter run`
