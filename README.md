# Criando a primeira API Web

**Requisitos mínimos**

1. .Net 8 ou superior

2. Ambiente de desenvolvimento integrado: Visual Studio 2022

3. SO: janelas

4. Modelo padrão: API Web ASP.NET Core

**Escopo do projeto**

1 - Criar APIs Web com Controladores

Observações:

Não usa mais a classe Startup
A configuração dos serviços e solicitação do pipeline é feita na classe Program
O Programa CLasse usa os seguintes recursos do C#:
Declarações de nível superior (Não use o método Main)
Global Usings - Uso de cláusulas using de forma implícita (sem declarações using)

**Estruitura do projeto**

- *Connected Services:* Contém qualquer serviço conectado ao seu projeto. Por exemplo, se você estiver usando o Azure, esta pasta conterá suas configurações de conexão ao Azure.
- *Dependencies:* Contém as propriedades do seu projeto. Isso inclui as configuraçõe e ferramentas de que seu projeto precisa para funcionar.
- *Properties:* Contém as propriedades do seu projeto. Isso inclui as configurações de compilação, as configurações de ambiente e as configurações de teste.
- *Controllers:* Contém os controladores do seu projeto. Os controladores são os métodos que respondem às solicitações do cliente.
- *appsettings.json:* Contém as configurações do seu projeto. Isso inclui as configurações de conexões ao banco de dados, as configuraçõe de autenticação e as configurações de autorização.
- *Program.cs:* Contém o ponto de entrada do seu projeto. É neste arquivo que o seu projeto é iniciado.
