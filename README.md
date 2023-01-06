# Excel-Py
<img src="https://img.shields.io/static/v1?label=Version&message=1.0.0&color=FF2102&style=for-the-badge&logo="/>

Projeto criado visando o funcionamento de uma interface gráfica onde é criado e editado uma planilha de medicamentos:

 - :white_check_mark: Planilha:
    - [x] Criação;
    - [x] Adição;
    - [ ] Atualização;
    - [ ] Remoção;
    - [x] Leitura;
    - [ ] Cadastro de usuário;
    - [ ] Autenticação de usuário;

---

# Sumário

- [Status](#status)
- [Habilidades desenvolvidas](#habilidades-desenvolvidas)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Organização e Estruturação do Projeto](#organização-e-estruturação-do-projeto)
- [Pré-requisitos](#pré-requisitos)
  - [Ferramentas necessárias](#ferramentas-necessárias)
  - [Executando localmente](#Executando-localmente)
  - [Quer contribuir com o projeto?](#quer-contribuir-com-o-projeto)
- [Orientações detalhadas de como utilizar](#orientações-detalhadas-de-como-utilizar)
  - [Planilha não existente](#Planilha-não-existente)
  - [Adicionar medicamento](#Adicionar-medicamento)
  - [Ver medicamento](#Ver-medicamento)
- [Contribuição](#contribuição)
- [Agradecimentos](#agradecimentos)
- [Autor](#autor)

---

# Status

Este projeto está em desenvolvimento, visando melhoras gráficas e adição de novas funcionalidades.

---

# Habilidades desenvolvidas

- Entender os conceitos básicos de interfaces gráficas;
- Entender sobre criação de aplicações;
- Entender sobre localização e edição de arquivos;
- Detectar e solucionar problemas no código de forma mais objetiva;
- Melhorar manutenibilidade e reusabilidade do seu código

---

# Tecnologias utilizadas

- [PySimpleGUI](https://www.pysimplegui.org/)
- [Openpyxl](https://foss.heptapod.net/openpyxl/openpyxl)

---

# Organização e Estruturação do Projeto

O projeto está organizado e estruturado da seguinte maneira:
```bash
├── app.py
├── README.md
├── .gitignore
└── dist
      ├── app.exe
      └── Planilha Remédios.xlsx
```
---

# Pré-requisitos

## Ferramentas necessárias

Para rodar o projeto, você vai precisar instalar as seguintes ferramentas:
 - [PySimpleGUI](https://www.pysimplegui.org/));
 - [Openpyxl](https://foss.heptapod.net/openpyxl/openpyxl);
 - Um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/) ou outro de sua preferência;

## Executando localmente

 - Clone do Projeto e instale as dependências

    ```bash
    # Clone este repositório
    $ git clone `https://github.com/AlexandreDinizVeloso/Excel-Py.git`

    # Acesse a pasta do projeto no terminal/cmd
    $ cd Excel-Py
    
    # Instale as dependencias
    $ pip install pysimplegui
    $ pip install openpyxl
    ```


## Quer contribuir com o projeto?

  - Crie uma branch e faça sua contribuição:

    ```bash
    # Crie uma branch a partir da branch main
    $ git checkout -b nome-da-nova-branch

    # Adicione as mudanças desejadas com os devidos commits
    $ git add . # adiciona as mudanças ao stage do Git
    $ git commit -m 'informação do conteúdo do commit' # salvando as alterações de cada pequena alteração em um commit
    $ git push -u origin nome-da-nova-branch # adiciona a nova branch no repositório remoto do Projeto
    ```
  - Crie um novo `Pull Request` (PR):
     - Vá até a página de `Pull Requests` do repositório no GitHub
     - Clique no botão verde `"New pull request"`
     - Clique na caixa de seleção `"Compare"` e escolha a sua branch com atenção
     - Clique no botão verde `"Create pull request"`
     - Adicione uma descrição para o Pull Request
     - Clique no botão verde `"Create pull request"`
     - Me marque para revisar. [Alexandre](https://github.com/AlexandreDinizVeloso)

---

# Orientações detalhadas de como utilizar

## Planilha não existente

 - Descrição: Responsável pela criação de uma planilha excel com as seguintes colunas: 'Medicamento', 'Data de Entrada', 'Gramatura', 'Quantidade'.
     
## Adicionar medicamento

- Descrição: Responsável pela adição de um medicamento e todas as suas especificações.


## Ver medicamento

- Descrição: Emite uma lista com todos os medicamentos adicionados na planilha. 

# Contribuição

Bora entrar para esta lista? `;)` [AQUI](#pré-requisitos) 

---

# Agradecimentos

Agradeço:
 - À minha família por me apoiar nos estudos;

---

# Autor

 <img src="https://avatars.githubusercontent.com/u/80282868" width="100px;" alt="Minha foto"/>
 <br />
  Alexandre Diniz Veloso
<br />
  Estudante do IFTM.

Entre em contato!

---
