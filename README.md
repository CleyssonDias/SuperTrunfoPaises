# Super Trunfo de Cidades

Este é um programa em C que permite ao usuário cadastrar e exibir informações de duas cartas do jogo Super Trunfo, baseadas em cidades. O usuário insere dados como estado, código da carta, nome da cidade, população, área, PIB e número de pontos turísticos.

## 🛠️ Funcionalidades
- Cadastro de duas cartas com informações de cidades.
- Entrada de dados via teclado.
- Exibição formatada das informações inseridas.

## 🚀 Como Executar
### 1. Instale um compilador C
Se ainda não tiver um compilador instalado, siga as instruções:
- **Windows**: Instale o [MinGW-w64](https://www.mingw-w64.org/downloads/).
- **Linux (Ubuntu/Debian)**: Execute `sudo apt install build-essential -y`.
- **MacOS**: Execute `xcode-select --install`.

### 2. Compile o código
Abra o terminal no diretório onde está o arquivo `super_trunfo.c` e execute:
```sh
gcc super_trunfo.c -o super_trunfo
```

### 3. Execute o programa
- No Linux/macOS:
  ```sh
  ./super_trunfo
  ```
- No Windows:
  ```sh
  super_trunfo.exe
  ```

## 📌 Exemplo de Entrada e Saída
### Entrada do usuário:
```
Digite o estado da primeira cidade (A-H): A
Digite o código da carta (ex: A01): A01
Digite o nome da cidade: São Paulo
Digite a população da cidade: 12325000
Digite a área da cidade (km²): 1521.11
Digite o PIB da cidade (em bilhões de reais): 699.28
Digite o número de pontos turísticos: 50
```

### Saída esperada:
```
Carta 1:
Estado: A
Código: A01
Nome da Cidade: São Paulo
População: 12325000
Área: 1521.11 km²
PIB: 699.28 bilhões de reais
Número de Pontos Turísticos: 50
```

## 📜 Requisitos
- Entrada de dados correta e sem erros.
- Exibição organizada e legível.
- Código bem estruturado e comentado.

## 📂 Estrutura do Projeto
```
/
│── super_trunfo.c   # Código-fonte principal
│── README.md        # Instruções do projeto
```

## 📖 Licença
Este projeto está sob a licença MIT. Sinta-se à vontade para modificá-lo e compartilhá-lo! 🚀

