# ♟️ Chess System (Java)

Repositório didático com uma implementação **completa** do jogo de **xadrez em Java**, ideal para estudo de **boas práticas de programação** orientada a objetos.

---

## 📌 Conteúdo

- [Sobre](#-sobre)  
- [Funcionalidades](#-funcionalidades)  
- [Requisitos](#-requisitos)  
- [Instalação](#-instalação)  
- [Estrutura do Projeto](#-estrutura-do-projeto)  
- [Boas Práticas Aplicadas](#-boas-práticas-aplicadas)  
- [Exemplo de Execução](#-exemplo-de-execução)  
- [Contribuição](#-contribuição)  
- [Licença](#-licença)  
- [Dicas para Estudo](#-dicas-para-estudo)  

---

## 📖 Sobre

Este projeto implementa **todas as regras oficiais do xadrez**, com foco em **legibilidade**, **organização** e **aprendizado de boas práticas em Java**.  
É um excelente exercício para quem está aprendendo **POO (Programação Orientada a Objetos)**, estruturação de projetos e design modular.

---

## ⚡ Funcionalidades

O sistema cobre as principais regras do xadrez:

- ✅ Representação do tabuleiro (8×8).  
- ✅ Movimento de todas as peças (peão, torre, cavalo, bispo, dama e rei).  
- ✅ Captura de peças adversárias.  
- ✅ Alternância de turnos entre as cores.  
- ✅ Validação de movimentos legais.  
- ✅ **Promoção de peão** (por padrão para dama, mas extensível).  
- ✅ **En Passant**.  
- ✅ **Roque pequeno e grande**.  
- ✅ **Xeque e Xeque-mate**.  
- ✅ **Partida completa** até vitória ou empate.  

---

## 🛠️ Requisitos

- **Java 11+**  
- IDE de sua preferência (Eclipse, IntelliJ IDEA, VS Code, etc.)  
- (Opcional) Maven ou Gradle para build automatizado  

---

## 🚀 Instalação

```bash
# Clone o repositório
git clone https://github.com/Marrafon91/chess-system-java.git
cd chess-system-java

# Compile e execute a classe principal
javac application/Program.java
java application.Program
