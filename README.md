# 💳 Payment Methods System - Object-Oriented Programming (OOP)

Este projeto simula um sistema de processamento de pagamentos robusto, utilizando os conceitos fundamentais da **POO** em JavaScript. Ele permite gerenciar diferentes modalidades de transações (Cartão de Crédito, Débito e Pix) a partir de uma estrutura centralizada e reutilizável.

---

# 📝 Resumo (Resume)
A aplicação utiliza **Herança funcional** através do método `.call()`, permitindo que classes filhas herdem atributos e métodos de uma classe pai (`MeiosDePagamento`). Implementei o **Encapsulamento** com métodos *getters* e *setters* para proteger a integridade dos dados (como o valor do pagamento) e utilizei **Polimorfismo** para que cada meio de pagamento execute ações específicas (como parcelamento ou confirmação de chave) mantendo uma base comum.



## 🚀 Tecnologias e Conceitos (Tech Stack)

[![JavaScript](https://img.shields.io/badge/JavaScript-POO-000?style=for-the-badge&logo=javascript&logoColor=4F0199)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Details_of_the_Object_Model)
[![OOP](https://img.shields.io/badge/Conceitos-Herança%20|%20Encapsulamento-000?style=for-the-badge&logo=codeschool&logoColor=4F0199)](https://pt.wikipedia.org/wiki/Programação_orientada_a_objetos)
[![Node.js](https://img.shields.io/badge/Ambiente-Console.log-000?style=for-the-badge&logo=node.js&logoColor=4F0199)](https://nodejs.org/)

## 📋 Funcionalidades em Destaque
* **Abstração de Pagamentos:** Uma classe base que controla `status`, `valor` e `dataPagamento` para qualquer transação.
* **Lógica de Parcelamento:** Cálculo automático de parcelas específico para a modalidade de Cartão de Crédito.
* **Tratamento de Datas:** Uso do `toLocaleString` para formatar a confirmação do pagamento no fuso horário `America/Sao_Paulo`.
* **Validação de Dados:** Uso de *setters* para garantir que valores de pagamento sejam apenas números positivos.
* **Interatividade via Console:** Logs detalhados que simulam o fluxo de autorização de operadoras e envio de transferências instantâneas.



---

# 👨‍💻 Sobre mim (About Me)
Olá, meu nome é **Kaio**, tenho 22 anos. Como meu objetivo é o **Back-End com Python**, este projeto foi crucial para eu entender como estruturar classes e objetos. No Python, os conceitos de Herança e Encapsulamento são a base de frameworks como **Django** e **Flask**, e este exercício de lógica me preparou para construir arquiteturas de software mais profissionais.

### Entre em contato (Contact me)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=4F0199)](https://linkedin.com/in/kaio-grativol-baldo-071a74150/)
[![Instagram](https://img.shields.io/badge/Instagram-000?style=for-the-badge&logo=instagram&logoColor=4F0199)](https://www.instagram.com/kaiull__/)
[![GitHub](https://img.shields.io/badge/Github-000?style=for-the-badge&logo=github&logoColor=4F0199)](https://github.com/SeuUsuarioAqui)

---
*Projeto desenvolvido para aplicar padrões de projeto e lógica de herança em sistemas financeiros.*
