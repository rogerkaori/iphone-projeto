# Projeto iPhone - Java & UML

Este projeto simula as funcionalidades básicas do iPhone apresentadas no vídeo de lançamento original do aparelho, demonstrando a aplicação de **interfaces** e **programação orientada a objetos** (POO). As funcionalidades são representadas através de interfaces em Java e implementadas na classe `IPhone`.

## Estrutura do Projeto

📁 **IPhoneProjeto**  
├── `AparelhoTelefonico.java`  
├── `ReprodutorMusical.java`  
├── `NavegadorInternet.java`  
├── `IPhone.java`  
└── `README.md`  

## Funcionalidades Representadas

✅ **Reprodutor Musical**  
Interface: `ReprodutorMusical`  
Métodos:  
- `tocarMusica()`  
- `pausarMusica()`  
- `selecionarMusica(String musica)`  

✅ **Aparelho Telefônico**  
Interface: `AparelhoTelefonico`  
Métodos:  
- `fazerChamada(String numero)`  
- `receberChamada(String numero)`  

✅ **Navegador de Internet**  
Interface: `NavegadorInternet`  
Métodos:  
- `exibirPagina(String url)`  
- `adicionarAba()`  
- `atualizarPagina()`  

A classe `IPhone` implementa as três interfaces, simulando o funcionamento real de um iPhone com essas três funcionalidades principais.

## Como Executar

1. Compile todos os arquivos:
   ```bash
   javac *.java
