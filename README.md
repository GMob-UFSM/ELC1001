


## Informações gerais

Disciplina: Sistemas de Computação Móvel (ELC1001)<br />
Professor: João Carlos Damasceno Lima (caio@inf.ufsm.br)

* [Servidor da disciplina no Discord](https://discord.gg/zZtYFqz)
* [Curso básico de React Native](https://drive.google.com/open?id=1K6gVlkE38LlOXJTrRygK1oYOj00WnpoH)

## Definição do trabalho

O trabalho consiste na implementação de algumas funcionalidades em um aplicativo. Cada grupo será responsável por implementar o frontend (React Native) ou backend (NodeJS) de **pelo menos** uma tela, conforme a documentação.

Dúvidas a respeito do trabalho podem ser esclarecidas no Discord da disciplina (link acima), ou via e-mail com o professor (e-mail acima) ou algum dos membros do GMob:

* Gustavo (gafantinel@inf.ufsm.br)
* João Vitor (jvbeltrame@inf.ufsm.br)
* Maurício (mvschmaedeck@inf.ufsm.br)
* Victor (vcmiranda@inf.ufsm.br)
* Talles (tsceolin@inf.ufsm.br)

## Desenvolvimento e entrega

Existem dois repositórios para esse trabalho:

* [ELC1001.Frontend](https://github.com/GMob-UFSM/ELC1001.Frontend): contém os arquivos do aplicativo em React Native
* [ELC1001.Backend](https://github.com/GMob-UFSM/ELC1001.Backend): contém os arquivos da API em NodeJS

Para desenvolver o trabalho você deve criar um `fork` público de um desses repositórios (conforme a tarefa que foi atribuída ao seu grupo) e compartilhá-lo com seu colega de grupo (caso haja um). 

Realize(m) as alterações nesse repositório conforme a tarefa que lhe(s) foi atribuída.

Para informações de como compilar e executar os projetos, consulte um dos seguintes links:

* [Informações de desenvolvimento do back-end](info-backend.md)
* [Informações de desenvolvimento do front-end](info-frontend.md)

## Grupos

| Índice | Grupo                                            | Integrantes                         |
| ------ | ------------------------------------------------ | ----------------------------------- |
| 1      | André                                            | André                               |
| 2      | Cristian e Alexsander                            | Cristian e Alexsander               |
| 3      | COVID-19                                         | Gabriel Righi e Bruno Alves         |
| 4      | Bruno                                            | Bruno Gottlieb                      |
| 5*     | Grupo da Goleadera                               | Frederico e William                 |
| 6      | Backteam                                         | Fernando Garcia e Felipe Mello      |
| 7*     | TeamName is Undefined                            | Fernando Paim e Mattheus Einloft    |
| 8      | DDVARGAS                                         | Daniel de Vargas                    |
| 9      | Dream Team                                       | Matheus Grisotti e Paulo Sarkis     |
| 10     | Débora Moreira da Silva e Lucas de Oliveira Dias | Débora e Lucas de Oliveira Dias     |
| 11*    | Grupo de Risco                                   | Alisson Machado e Eduardo Vedooto   |
| 12*    | Matheus Dalmolin                                 | Matheus Dalmolin                    |
| 13     | Grupo do João                                    | João Gonçalves Machado              |
| 14     | Daniel e Deivis                                  | Daniel B. Seitenfus e Deivis        |
| 15     | Zezed Camaro                                     | Pedro Leonel e Tiago Chagas         |
| 16     | Quarentena of Legends                            | Luigi Perotti e João Pedro da Silva |
| 17*    | Multitask                                        | Emilio                              |
| 18*    | Regex natives                                    | Júlia Acosta e Gabriel Gomes        |
| 19     | Joga y Joga                                      | Felipe Imhoff                       |
| 20     | Laurence                                         | Laurence                            |

## Trabalho de cada grupo

:warning: **ATENÇÃO**:
* Seu grupo pode ser responsável por mais de uma tela!
* Se mais de um grupo for atribuído para a mesma tela/rota os mesmos não devem realizar o trabalho juntos, **cada grupo deve implementar a sua versão e entregá-la separadamente**.
* Leia o README do repositório em que seu grupo for trabalhar.

### Telas (do App) a serem desenvolvidas

| Tela                              | Grupo responsável |
| --------------------------------- | ----------------- |
| [Menu principal][menu-f]          | 12 e 18           |
| [Meus looks][menu-looks-f]        | 7 e 13            |
| [Calendário][calendar-f]          | 1                 |
| [Compor look][compor-look-f]      | 5                 |
| [Perfil][perfil-f]                | 17 e 19           |
| [Visualizar peça][display-peca-f] | 10 e 11           |
| [Ajuda][ajuda-f]                  | 8 e 20            |
| [Sobre][sobre-f]                  | 8 e 20            |

### Controladores (da API) a serem desenvolvidos

| Controlador                            | Grupo responsável |
| -------------------------------------- | ----------------- |
| [`calendar.controller.js`][calendar-b] | 4 e 15            |
| [`look.controller.js`][look-b]         | 2 e 6             |
| [`user.controller.js`][user-b]         | 9 e 16            |
| [`wardrobe.controller.js`][wardrobe-b] | 3 e 14            |

[menu-f]: telas/menu.md
[menu-looks-f]: telas/menu-looks.md
[calendar-f]: telas/calendar.md
[compor-look-f]: telas/compor-look.md
[perfil-f]: telas/perfil.md
[display-peca-f]: telas/display-peca.md
[ajuda-f]: telas/ajuda.md
[sobre-f]: telas/sobre.md

[calendar-b]: https://github.com/GMob-UFSM/ELC1001.Backend/blob/master/api/controllers/calendar.controller.js
[look-b]: https://github.com/GMob-UFSM/ELC1001.Backend/blob/master/api/controllers/look.controller.js
[user-b]: https://github.com/GMob-UFSM/ELC1001.Backend/blob/master/api/controllers/user.controller.js
[wardrobe-b]: https://github.com/GMob-UFSM/ELC1001.Backend/blob/master/api/controllers/wardrobe.controller.js