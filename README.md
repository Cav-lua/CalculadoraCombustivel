# **FuelSaver - Calculadora de Consumo de Combustível**

> Um aplicativo Android para calcular o consumo de combustível e o custo de viagens baseado nas especificações do veículo.

## 📱 Descrição

O **FuelSaver - Calculadora de Consumo de Combustível** permite que os usuários calculem a quantidade de combustível necessária e o custo total de uma viagem.
O app solicita informações sobre o veículo e o percurso e exibe os resultados com base no consumo médio do veículo e no preço do combustível por litro.

## 🔧 Funcionalidades

- [x] Cadastro de informações do veículo (nome, placa)
- [x] Entrada de dados para distância, consumo médio e preço do combustível
- [x] Cálculo de combustível necessário para a distância informada
- [x] Cálculo do custo total da viagem
- [x] Exibição dos resultados em uma tela clara e intuitiva

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio**
- [x] **Java** para desenvolvimento
- [x] **LinearLayout** para organização da interface
- [x] **TextView** e **EditText** para entrada e exibição de dados
- [x] **Button** para acionar o cálculo

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:

    ```bash
    git clone https://github.com/Cav-lua/consumocombustivel.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/consumocombustivel
│   │   │   │   └── MainActivity.java      # Atividade principal com cálculo de combustível
│   │   │   ├── res
│   │   │   │   ├── layout
│   │   │   │   │   └── activity_main.xml   # Layout da tela principal
│   │   │   │   ├── values
│   │   │   │   │   ├── strings.xml         # Strings usadas no app
│   │   │   │   │   └── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
````
🎨 Design e Prototipagem
A interface do app foi criada usando LinearLayout para manter a simplicidade e usabilidade, com um design escuro voltado para visualização confortável.

🖥️ Telas do Aplicativo
Tela Principal
Na tela principal, o usuário insere os dados do veículo e da viagem, e o app calcula e exibe a quantidade de combustível necessária e o custo da viagem.

![TelaPrincipal](https://github.com/user-attachments/assets/988aded1-1343-4543-aaed-a06d571ba196)


👨‍💻 Desenvolvedores
Cav-lua - Desenvolvedor - GitHub

📄 Licença
Este projeto está licenciado sob os termos da licença MIT. 
