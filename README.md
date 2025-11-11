# sistema-gerenciamento-veiculos
# 🚗 Sistema de Gerenciamento de Veículos (Java)

Este projeto foi desenvolvido como parte de uma atividade prática sobre **Programação Orientada a Objetos** (POO) em Java.  
O objetivo é aplicar conceitos como **herança**, **encapsulamento**, **métodos abstratos** e **polimorfismo**.

---

## 🧠 Estrutura do Projeto

O sistema é composto pelas seguintes classes:

- **Veiculo** (classe abstrata)
  - Atributos: `marca`, `modelo`, `ano`
  - Métodos: `getAno()`, `setAno()`, `informacoesVeiculo()`
- **Carro** (herda de Veiculo)
  - Atributo adicional: `numeroPortas`
- **Moto** (herda de Veiculo)
  - Atributo adicional: `cilindrada`
- **Main**
  - Classe principal para testar o sistema.
