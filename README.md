# 🍽️ Imersão Mobile Flutter - App de Restaurantes

Bem-vindo ao projeto desenvolvido durante a **Imersão Mobile Flutter**, onde construímos um app completo de restaurantes, com telas de navegação, exibição de dados, lógica de pedido e muito mais.

Este repositório contém o código-fonte desenvolvido ao longo das 3 aulas da Imersão, com foco na prática e no aprendizado das melhores práticas com Flutter e Provider.

## 🚀 Aulas e Funcionalidades

### Aula 01 - Seu app começa aqui! 📱

**Objetivo:** Criar a estrutura base do app com a tela de Splash e a Home inicial.

- Configuração inicial do projeto no [Flutter + IDX](https://idx.dev)
- Importação e organização dos **assets**
- Criação da tela de Splash (`SplashScreen`)
- Uso de widgets fundamentais:
  - `Scaffold`, `Stack`, `Column`, `Padding`
  - `Image.asset`, `Text`, `ElevatedButton`, `SizedBox`
- Personalização de temas:
  - `AppColor`: definição de paleta de cores
  - `AppTheme`: configuração global de estilo

🔗 [Link do projeto completo](https://github.com/alura-cursos/flutter_techtaste)  
🔗 [Link do Figma](www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imersão?node-id=7-47&p=f&t=TWIDMIpkK0jC2ChI-0)
🔗 [analysis_options.yaml]  
🔗 [Pasta de assets]

---

### Aula 02 - Transforme dados em experiência real! 🍔

**Objetivo:** Criar a **Home** com navegação entre telas e exibição de restaurantes.

- Navegação entre telas com `Navigator`
- Home com:
  - `AppBar`, `Drawer`, `TextFormField` (busca)
- Componentização:
  - `CategoryWidget` para categorias
  - `RestaurantWidget` para exibição de restaurantes
- Criação de **models** e leitura de dados:
  - `RestaurantModel` com `toMap()` e `fromMap()`
  - `RestaurantData` para carregar os dados do JSON
- Gerenciamento de estado com `Provider` para exibir os restaurantes dinamicamente

🔗 [Link do projeto completo](https://github.com/alura-cursos/flutter_techtaste)  
🔗 [Link do Figma](www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imersão?node-id=7-47&p=f&t=TWIDMIpkK0jC2ChI-0)

---

### Aula 03 - Finalize o fluxo do app! 🛍️

**Objetivo:** Criar a experiência completa de pedido com tela de detalhes e sacola.

- Tela de **detalhes do restaurante**, com listagem de pratos
- Criação do `DishModel` (prato)
- Integração dos pratos com o restaurante
- Funcionalidade de sacola com `BagProvider`:
  - Adicionar, remover e limpar itens
  - Cálculo de total do pedido com `.toStringAsFixed()`
- Modularização da `AppBar` com `Badge` de contagem
- Tela de **Checkout** com totalização e listagem dos itens

🔗 [Link do projeto completo](https://github.com/alura-cursos/flutter_techtaste)
🔗 [Link do Figma](www.figma.com/design/5WKjBnTvAKTraWTRqsjK02/TechTaste-%7C-Imersão?node-id=7-47&p=f&t=TWIDMIpkK0jC2ChI-0)

---

## 🛠️ Tecnologias Utilizadas

- [Flutter](https://flutter.dev) 💙
- [Provider](https://pub.dev/packages/provider) para gerenciamento de estado
- [Material Design](https://m3.material.io/) para componentes visuais
- [Google Fonts](https://pub.dev/packages/google_fonts)
- Assets customizados e ícones

---

## 📁 Estrutura de Pastas

```bash
lib/
├── models/
│   ├── restaurant_model.dart
│   └── dish_model.dart
├── providers/
│   ├── restaurant_provider.dart
│   └── bag_provider.dart
├── screens/
│   ├── splash_screen.dart
│   ├── home_screen.dart
│   ├── restaurant_detail_screen.dart
│   └── checkout_screen.dart
├── widgets/
│   ├── category_widget.dart
│   └── restaurant_widget.dart
├── theme/
│   ├── app_color.dart
│   └── app_theme.dart
└── main.dart

```
