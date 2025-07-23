# 🎮 Jogo da Forca - Bootcamp Edition

Um jogo da forca completo desenvolvido em Java usando Programação Orientada a Objetos (POO) como parte do bootcamp.

## 📋 Descrição

Este projeto implementa um jogo da forca tradicional com interface console, incluindo:

- Sistema de categorias de palavras
- Desenho ASCII da forca
- Interface de menu interativa
- Controle de tentativas e erros
- Feedback visual em tempo real

## 🏗️ Arquitetura

O projeto segue uma arquitetura bem organizada em packages:

```
src/main/java/com/bootcamp/forca/
├── Main.java                 # Classe principal
├── controller/
│   └── JogoDaForca.java     # Lógica principal do jogo
├── model/
│   ├── Palavra.java         # Modelo da palavra
│   ├── Forca.java          # Modelo da forca
│   └── BancoPalavras.java  # Gerenciador de palavras
└── view/
    └── Menu.java           # Interface do usuário
```

## 🎯 Funcionalidades

### Categorias Disponíveis
- 🐾 **Animais**: Elefante, Girafa, Leão, etc.
- 🍎 **Frutas**: Banana, Maçã, Laranja, etc.
- 🌍 **Países**: Brasil, Argentina, França, etc.
- 👨‍⚕️ **Profissões**: Médico, Engenheiro, Professor, etc.
- 🎨 **Cores**: Vermelho, Azul, Verde, etc.

### Recursos do Jogo
- ✅ Seleção de categoria (específica ou aleatória)
- 🎨 Desenho ASCII da forca com 6 estágios
- 📊 Acompanhamento de letras corretas e erradas
- 🔄 Sistema de tentativas (máximo 6 erros)
- 🏆 Telas de vitória e derrota
- 📱 Interface intuitiva com menus

## 🚀 Como Executar

### Pré-requisitos
- Java 11 ou superior
- Gradle

### Compilação e Execução

1. **Clone ou baixe o projeto**
2. **Navegue até o diretório do projeto:**
   ```bash
   cd C:\Users\olive\Documents\GitHub\jogo-da-forca
   ```

3. **Compile o projeto com Gradle:**
   ```bash
   gradle build
   ```

4. **Execute o jogo:**
   ```bash
   gradle run
   ```

### Alternativa - Execução direta
```bash
# Compilar
gradle build

# Executar o JAR
java -jar build/libs/jogo-da-forca-1.0-SNAPSHOT.jar
```

## 🎮 Como Jogar

1. **Inicie o jogo** e escolha uma opção no menu principal
2. **Selecione uma categoria** ou jogue com categoria aleatória
3. **Digite uma letra** por vez para tentar descobrir a palavra
4. **Observe a forca** sendo desenhada a cada erro
5. **Ganhe** descobrindo todas as letras antes de 6 erros
6. **Perca** se a forca for completamente desenhada

### Regras
- 📝 Digite apenas uma letra por vez
- 🚫 Não é possível repetir letras já tentadas
- ⚠️ Máximo de 6 erros permitidos
- 🎯 Descubra todas as letras para ganhar

## 🏛️ Conceitos de POO Utilizados

- **Encapsulamento**: Dados privados com getters/setters apropriados
- **Abstração**: Classes representam conceitos do domínio do jogo
- **Organização**: Separação clara de responsabilidades em packages
- **Modularidade**: Cada classe tem uma responsabilidade específica

## 📁 Estrutura de Arquivos

```
jogo-da-forca/
├── build.gradle              # Configuração do Gradle
├── gradle.properties         # Propriedades do Gradle
├── README.md                # Documentação
└── src/main/java/com/bootcamp/forca/
    ├── Main.java            # Ponto de entrada
    ├── controller/
    │   └── JogoDaForca.java # Controlador principal
    ├── model/
    │   ├── BancoPalavras.java
    │   ├── Forca.java
    │   └── Palavra.java
    └── view/
        └── Menu.java        # Interface do usuário
```

## 🛠️ Tecnologias

- **Linguagem**: Java 11+
- **Build Tool**: Gradle
- **Paradigma**: Programação Orientada a Objetos
- **Interface**: Console/Terminal

## 📈 Versão

- **Versão Atual**: 1.0.0
- **Status**: Completo e funcional

## 🎓 Objetivos de Aprendizado

Este projeto foi desenvolvido para praticar:
- Estruturação de projetos Java
- Aplicação de conceitos de POO
- Organização de código em packages
- Uso do Gradle como build tool
- Desenvolvimento de aplicações console
- Implementação de lógica de jogos

---

**Desenvolvido como parte do bootcamp** 🎓