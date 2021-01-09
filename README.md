# BooksAPI

[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

 <p align="center">
 <strong>API Web que pode gerenciar livros armazenados em um banco de dados mongodb.</strong>
    <br />
    <a href="https://github.com/renan2911?tab=repositories"><strong>Veja outros programas »</strong></a>
    <br />
    <br />
    <a href="https://github.com/renan2911/NOME_DESSE_REPOSITORIO/issues">Reporte um Bug</a>
  </p>
</p>


## Visão Geral
API	                       | Descrição                                               |	Corpo da solicitação     |	Corpo da resposta                  |
:-------:                  |:-------:                                                |:-------:                  | :-------:                           |
GET /api/books             | Obter todos os livros cadastrados                       | Nenhum                    | Matriz de livros                    |
GET /api/books/{id}	       | Obter um livro por ID                                   | Nenhum	                   | Item de livros                      |
POST /api/books            | Adicionar um novo livro	                               | Item de livros            | Item de livros                      |
PUT /api/books/{id}        | Atualizar um livro existente	                           | Nenhum                    | Nenhum                              |
DELETE /api/books/{id}     | Excluir um item                                         | Nenhum                    | Nenhum                              |




## Foi desenvolvido:
* Configuração do MongoDB
* Definição da coleção e um esquema do MongoDB
* Executar operações CRUD do MongoDB a partir de uma API Web.




## Pré-requisitos
* [Visual Studio 2019](https://visualstudio.microsoft.com/downloads/?utm_medium=microsoft&utm_source=docs.microsoft.com&utm_campaign=inline+link&utm_content=download+vs2019) - <strong>com a ASP.net e a carga de trabalho de desenvolvimento Web</strong>
* [SDK do .NET Core 3.0 ou Superior](https://dotnet.microsoft.com/download/dotnet/5.0)<strong></strong>
* [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)<strong></strong>


[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/renan2911/usuario.api/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/NICKNAME_DO_SEU_GITHUB/NOME_DESSE_REPOSITORIO/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/renan-alysson-f/
