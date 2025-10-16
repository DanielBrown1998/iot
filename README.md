# IoT Flutter App

Uma aplicação Flutter focada em soluções para Internet das Coisas (IoT), oferecendo conectividade com dispositivos via MQTT, Bluetooth e APIs REST.

## 📱 Sobre o Projeto

Este projeto Flutter foi desenvolvido para facilitar a comunicação e controle de dispositivos IoT, proporcionando uma interface móvel intuitiva para gerenciar e monitorar dispositivos conectados.

## ✨ Funcionalidades

- 📡 **Comunicação MQTT**: Conectividade com brokers MQTT para troca de mensagens em tempo real
- 🔵 **Bluetooth**: Integração com dispositivos Bluetooth Low Energy (BLE)
- 🌐 **APIs REST**: Comunicação com serviços web via HTTP/HTTPS
- 📱 **Multiplataforma**: Suporte para Android, iOS, Web, Windows, macOS e Linux

## 🛠️ Tecnologias Utilizadas

### Dependências Principais
- **Flutter SDK**: ^3.9.2
- **mqtt_client** (^10.11.1): Cliente MQTT para comunicação com brokers IoT
- **flutter_blue_plus** (^2.0.0): Biblioteca para conectividade Bluetooth/BLE
- **dio** (^5.9.0): Cliente HTTP robusto para requisições REST
- **cupertino_icons** (^1.0.8): Ícones do iOS para interface consistente

### Dependências de Desenvolvimento
- **flutter_test**: Framework de testes do Flutter
- **flutter_lints** (^5.0.0): Conjunto de regras de lint recomendadas

## 🚀 Como Executar

### Pré-requisitos
- Flutter SDK ^3.9.2
- Dart SDK
- Android Studio / VS Code
- Emulador ou dispositivo físico

### Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd iot
```

2. Instale as dependências:
```bash
flutter pub get
```

3. Execute o projeto:
```bash
flutter run
```

## 📦 Estrutura do Projeto

```
lib/
├── main.dart          # Ponto de entrada da aplicação
├── models/            # Modelos de dados
├── services/          # Serviços (MQTT, Bluetooth, HTTP)
├── screens/           # Telas da aplicação
└── widgets/           # Componentes reutilizáveis
```

## 🔧 Configuração

### MQTT
Configure os parâmetros do broker MQTT no arquivo de configuração:
- Host do broker
- Porta (geralmente 1883 ou 8883 para SSL)
- Credenciais de autenticação
- Tópicos de inscrição

### Bluetooth
Certifique-se de que as permissões necessárias estão configuradas:
- **Android**: `BLUETOOTH`, `BLUETOOTH_ADMIN`, `ACCESS_FINE_LOCATION`
- **iOS**: `NSBluetoothAlwaysUsageDescription` no Info.plist

## 🌐 Plataformas Suportadas

- ✅ Android
- ✅ iOS
- ✅ Web
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 📖 Documentação

Para mais informações sobre desenvolvimento Flutter:
- [Documentação oficial do Flutter](https://docs.flutter.dev/)
- [Guia de MQTT](https://mqtt.org/)
- [Flutter Blue Plus Documentation](https://pub.dev/packages/flutter_blue_plus)
- [Dio HTTP Client](https://pub.dev/packages/dio)

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📞 Contato

Para dúvidas ou sugestões sobre o projeto, entre em contato através das issues do GitHub.
