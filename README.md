# Projeto Integrador Fatec - 5º Semestre

Este é um projeto Flutter desenvolvido como parte do Projeto Integrador do 5º semestre da Fatec. O projeto utiliza a autenticação do Firebase e a API do Google Maps.

## Firebase Authentication

O Firebase Authentication é utilizado para fornecer recursos de autenticação no aplicativo. Ele permite que os usuários se cadastrem, façam login e gerenciem suas contas de usuário de forma segura.

### Funcionalidades

- **Registro de Usuário**: Os usuários podem se registrar no aplicativo fornecendo um endereço de e-mail e uma senha.
- **Login de Usuário**: Os usuários registrados podem fazer login no aplicativo usando suas credenciais.
- **Logout de Usuário**: Os usuários podem sair de suas contas, encerrando a sessão atual.

O código para a autenticação com o Firebase está disponível no arquivo `auth_service.dart`. Ele contém a lógica para registro, login e logout de usuários, além de tratamento de exceções.

Para mais informações, consulte a documentação da [Firebase Auth API](https://pub.dev/packages/firebase_auth).

## Google Maps API

A API do Google Maps é utilizada para integrar funcionalidades de mapas ao aplicativo. Ela permite exibir mapas interativos, adicionar marcadores, traçar rotas e muito mais.

Para integrar a API do Google Maps ao seu projeto Flutter, você pode utilizar o pacote `google_maps_flutter`. Consulte a documentação oficial para obter instruções de configuração e exemplos de uso.

Para mais informações, consulte a documentação do [Google Maps Flutter](https://pub.dev/packages/google_maps_flutter#android).

## Executando o Projeto

Para executar o projeto em seu ambiente local, siga estas etapas:

1. Clone este repositório:

```
git clone [https://github.com/seu-usuario/Projeto-Integrador-Fatec-5-semestre.git](https://github.com/Karllos26/Projeto-Integrador-Fatec-5-semestre.git)
```

2. Navegue até o diretório do projeto:

```
cd Projeto-Integrador-Fatec-5-semestre
```

3. Instale as dependências:

```
flutter pub get
```

4. Execute o aplicativo:

```
flutter run
```

Certifique-se de que um dispositivo ou emulador esteja conectado.

---

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
