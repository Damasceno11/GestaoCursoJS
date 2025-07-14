# Sistema de Gestão Escolar em Java

Este é um sistema simples de Gestão Escolar desenvolvido em **Java**, focado no cadastro e listagem de cursos, turmas e estudantes.

O projeto utiliza conceitos fundamentais de programação orientada a objetos, tratamento de exceções, enums e interação via console (terminal).

---

## Funcionalidades

- Cadastro de Cursos (código, nome, carga horária, nível)  
- Cadastro de Turmas vinculadas a Cursos (código, datas, período)  
- Cadastro de Estudantes (nome, CPF, email, telefone, endereço)  
- Listagem de Cursos, Turmas e Estudantes  
- Validação básica de dados (datas, enums, tipos)  
- Tratamento de exceções para entradas inválidas

---

## Tecnologias e Conceitos Utilizados

- Linguagem Java (versão 8 ou superior recomendada)  
- Programação Orientada a Objetos (POO)  
- Enums para níveis e períodos  
- Manipulação de datas com `java.time.LocalDate`  
- Entrada e saída via console (`Scanner`)  
- Tratamento de exceções (`try-catch`)  
- Organização modular com pacotes (`dominio`, `funcionalidades`)

---

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Damasceno11/GestaoCursoJS.git
````

2. Abra o projeto em sua IDE favorita (IntelliJ IDEA, Eclipse, NetBeans).

3. Compile e execute a classe `br.com.escola.gestaoescolar.Main`.

4. Use o menu exibido no console para interagir com o sistema.

---

## Estrutura do Projeto

```
src/
├── br/
│   └── com/
│       └── escola/
│           └── gestaoescolar/
│               ├── dominio/             # Classes do domínio (Curso, Estudante, Turma, Enums)
│               ├── funcionalidades/     # Classes para cadastro, listagem e manipulação
│               └── Main.java            # Classe principal com menu e interação
```

---

## Autor

Pedro Paulo Damasceno Muniz
Estudante de Análise e Desenvolvimento de Sistemas – Uniasselvi
Participante do curso intensivo +Devs2Blu – Blumenau

---

## Contato

GitHub: [https://github.com/Damasceno11](https://github.com/Damasceno11)

---
