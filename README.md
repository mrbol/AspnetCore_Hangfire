# ⚙ Hangfire no ASP.NET Core 3.1

## Trabalhos em Segundo Plano no ASP.NET Core

Essencialmente, os trabalhos em segundo plano são aqueles métodos ou funções que podem levar muito tempo para serem executados (tempo desconhecido). Esses trabalhos, se executados no thread principal de nosso aplicativo, podem / não bloquear a interação do usuário e podem parecer que nosso aplicativo .NET Core travou e não está respondendo. Isso é bastante crítico para aplicativos voltados para o cliente. Portanto, temos trabalhos de segundo plano, semelhantes ao multithreading, esses trabalhos são executados em outro encadeamento, fazendo com que nosso aplicativo pareça bastante assíncrono.

Devemos também ter a possibilidade de agendá-los em um futuro próximo para que seja totalmente automatizado. A vida de um desenvolvedor seria muito difícil sem essas possibilidades incríveis.

Este repositório foi criado com proposito de implementar e testar o exemplo do artigo . Segue o link do artigo https://codewithmukesh.com/blog/hangfire-in-aspnet-core-3-1/
