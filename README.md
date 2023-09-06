# TodoXPress

This application is a helper to be more productive. It includes a calendar, a todo app (reminder) and a basic notes app.

It combines all apps in one to make it possible to link all elements of the apps to each other.

## Documentation repository

This repository contains documentations about the project. It includes architecture digrams, domain design in uml diagrams and informations.

## Techstack of the project

- .Net7 / C# 11
- Backend:
  - API: ASP.Net minimal api
  - Db: PostgreSQL
  - MessageQ: RabbitMQ
- Frontend:
  - Native: .Net Maui
  - Web: ASP.Net Blazor Web Assembly

## Code repository structure

- [TodoXpress.Domain](https://github.com/TodoXpress/TodoXpress.Domain)

  This repository contains the definition of the domains and all relevant
  domain entities, events, behaviors, etc.

- [TodoXpressBackend](https://github.com/TodoXpress/TodoXpressBackend)

  This repository includes the api project as an monolith, it represents the
  hole backend. It is designed vertically according to the Domain Driven Design and horizontal by feature or domain.

- [TodoXpress.UI.Native](https://github.com/TodoXpress/TodoXpress.Ui.Native)

  This repository contains the projekt for the nativ application. With .Net Maui Hybrid it provides the razor pages for the nativ clients.

- [TodoXpress.UI.Web](https://github.com/TodoXpress/TodoXpress.Ui.Web)

  This respoitory contains the project for the web application. With .Net Blazor Web Assembly it provides the razor pages for the website.

- [TodoXpress.UI.Components](https://github.com/TodoXpress/TodoXpress.Ui.Components)

  This repository contains all razor components and pages. It provides the views to the projects for the nativ and web.
