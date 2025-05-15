# 🧭 Testes Automatizados com Selenium WebDriver

Este repositório contém testes de interface (UI) automatizados utilizando o **Selenium WebDriver** com **Java** e **JUnit**.

---

## 📌 Objetivo

Automatizar testes funcionais em aplicações web, simulando o comportamento do usuário final para validar funcionalidades essenciais da aplicação.

---

## 🧰 Tecnologias Utilizadas

- Java 17  
- Selenium WebDriver  
- JUnit 5  
- Maven  
- IntelliJ IDEA  

---

## 📁 Estrutura do Projeto

```

selenium-tests/
├── src/
│   └── test/
│       └── java/
│           └── br/
│               └── com/
│                   └── seuusuario/
│                       ├── pages/
│                       ├── tests/
│                       └── utils/
├── pom.xml
└── README.md

````

- `pages/` → Page Objects (padrão de design para organizar os elementos das páginas)  
- `tests/` → Classes com os testes automatizados  
- `utils/` → Métodos auxiliares (ex: waits, screenshots, configs)  

---

## 🚀 Como Executar os Testes

1. **Clone o repositório:**

```bash
git clone https://github.com/seuusuario/selenium-tests.git
cd selenium-tests
````

2. **Execute os testes via Maven:**

```bash
mvn test
```

---

## ✔️ Casos de Teste Automatizados

* [x] Login com credenciais válidas
* [x] Login com credenciais inválidas
* [x] Cadastro de novo usuário
* [x] Navegação entre páginas
* [x] Validação de mensagens de erro e campos obrigatórios

---

## 🧪 Boas Práticas Aplicadas

* Page Object Model (POM)
* Testes independentes e reaproveitáveis
* Separação entre lógica de teste e lógica de navegação
* Uso de waits explícitos para estabilidade
* Organização por pacotes e nomes semânticos

---

## 📸 Extras (opcional)


* Integração futura com GitHub Actions

---

## 👨‍💻 Autor

**Kleber Barbosa**
Em transição para a área de QA | Pós-graduando em Engenharia de Software e Qualidade
[LinkedIn](https://www.linkedin.com/in/kleberkeki/) • 

---

## 📃 Licença

Este projeto está sob a licença MIT.

