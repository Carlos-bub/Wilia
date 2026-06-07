# Sistema Web para Gerenciamento de Objetos Perdidos no IFNMG

![Versão](https://img.shields.io/badge/version-v1.0.0-blue.svg)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow.svg)

**Sistema web para gestão de objetos perdidos e encontrados no IFNMG – Campus Salinas, centralizando informações e facilitando a devolução de pertences à comunidade acadêmica.**

---

## Sobre o Projeto

Este projeto nasceu de uma realidade observada no IFNMG – Campus Salinas: atualmente não existe um controle formal para objetos perdidos. O processo ocorre por meio de anotações informais em papel e mensagens em grupos de WhatsApp, o que dificulta a rastreabilidade dos itens e a comunicação com os proprietários.

Uma pesquisa de opinião com 82 alunos revelou que 61% já perderam algum objeto no campus e, desses, 73% não conseguiram recuperá-lo.

**O sistema proposto existe para resolver esse problema.** Ele centraliza o registro de objetos encontrados, permite consulta pública e garante devolução segura com validação de identidade.

## Funcionalidades Principais

- Cadastro de objetos encontrados com foto, descrição, local e data
- Consulta pública de itens perdidos
- Solicitação de devolução com validação do proprietário
- Painel administrativo para gestão dos objetos
- Controle de status dos itens (aguardando, devolvido, descartado)
- Geração de relatórios administrativos

## Tecnologias Utilizadas

- **Back-end:** Django (Python)
- **Front-end:** HTML, CSS
- **Banco de Dados:** MySQL
- **Prototipação:** Figma

## Estrutura do Repositório

```text
TCC-CHLN/
├── README.md
│   └── Documentação principal do projeto
│
├── pesquisa-opiniao/
│   └── dados-pesquisa-opiniao.csv
│       └── Dados brutos coletados na pesquisa com alunos
│
├── codigo/
│   └── Código-fonte do sistema
│
├── documentos/
│   └── Arquivos do TCC (.tex, .pdf e materiais auxiliares)
│
└── imagens/
    └── Imagens utilizadas na documentação e apresentação
```


## Pesquisa de Opinião

Os dados brutos da pesquisa realizada com 82 estudantes estão disponíveis na pasta [`/pesquisa-opiniao`](https://github.com/ifnmgsal-inf/TCC-CHLN/tree/main/pesquisa-opiniao). A pesquisa revelou que:

- **61%** dos entrevistados já perderam algum objeto no campus
- **73%** desses não conseguiram recuperar o pertencente

## Como Contribuir (Para o Orientador e Banca)

Este repositório é utilizado para acompanhamento do Trabalho de Conclusão de Curso. O Pull Request (PR) é a forma de entregar e validar cada etapa do projeto.

## Mentores do Projeto (Referências Teóricas)

- **PRESSMAN, R. S.** Engenharia de Software: uma abordagem profissional. 9. ed. Porto Alegre: AMGH, 2021.
- **SOMMERVILLE, I.** Engenharia de Software. 10. ed. São Paulo: Pearson, 2019.
- **DJANGO. Django Documentation.** Disponível em: https://docs.djangoproject.com/

## Licença

Este projeto está licenciado sob a **MIT License** - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

**Carlos Henrique Lima do Nascimento**  
Orientador: Arthur Faria Porto  
IFNMG – Campus Salinas, 2026
