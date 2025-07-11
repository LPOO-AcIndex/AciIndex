# 🚗 Locadora de Veículos – Sistema de Gerenciamento

Projeto desenvolvido como parte da disciplina **Programação Orientada a Objetos II** (2025.1) no **IFPE – Campus Paulista**.

---

## 📌 Sobre o Projeto

O sistema **Locadora de Veículos** é uma aplicação desktop desenvolvida em **Java**, com uso da biblioteca **Swing** para interface gráfica e **MySQL** como sistema de banco de dados.  

O projeto segue a arquitetura de **três camadas** (interface gráfica, regras de negócio e acesso a dados), simulando o funcionamento completo de uma locadora: cadastro de clientes, busca e edição de funcionários, gerenciamento de veículos, entre outros.

---

## 💡 Funcionalidades

- ✅ **Cadastro de novos clientes** com validações básicas
- 🔍 **Busca de funcionários** com filtros por CPF, nome e cargo
- 📝 **Edição de dados** dos funcionários
- 🚘 Cadastro e controle de veículos
- 📄 Separação por camadas: `ui`, `regras_negocio`, `acesso_dados`
- 🗃️ Integração com banco de dados MySQL via JDBC
- 🎨 Interface gráfica com Java Swing
- 🧪 Mensagens de erro e validações de entrada

---

## 🚧 Tecnologias e Ferramentas

- **Java 8+**
- **Swing (AWT/Swing)**
- **JDBC**
- **MySQL**
- **Eclipse IDE** (ou similar)

---

## 📂 Estrutura de Pacotes

| Pacote           | Função |
|------------------|--------|
| `ui`             | Interface gráfica (Swing) |
| `regras_negocio` | Camada de lógica e validações |
| `acesso_dados`   | Conexão e operações no banco de dados |
| `modelo`       _ | Representação de entidades como `Funcionario`, `Cliente`, etc. |

---

## 🧠 Desenvolvedores

-Ana Clara
-Ana Luiza
-Adriel
-Maria Luiza
-Matheus

---

## 📎 Observações

- O projeto simula um sistema real de locadora, mas é voltado para fins educacionais.

- O foco está no uso correto de POO, integração com banco de dados e separação em camadas.

- A interface é feita com Swing para praticar manipulação de eventos e componentes gráficos.

- O código pode ser facilmente estendido para novos módulos (ex: reservas, relatórios, etc.)

---

## 📚 Licença

Este projeto foi desenvolvido exclusivamente para fins acadêmicos e não deve ser utilizado em ambientes de produção sem ajustes de segurança e escalabilidade.

---

## 💖 Agradecimentos

Agradecemos ao professor responsável pela disciplina, ao IFPE – Campus Paulista, e a todos os colegas e colegas de código que contribuíram com ideias e revisões.

---
