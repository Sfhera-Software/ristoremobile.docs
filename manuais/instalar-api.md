---
title: Instalando a SfheraWebAPI
layout: single
permalink: /manuais/instalar-api/
sidebar:
  nav: "docs"
---

Veja o passo a passo de como realizar a instalação da SfheraWebAPI, responsável por fornecer os dados usados pelo aplicativo. 

### Pré-requisitos para a instalação da API:
- Sistemas operacionais Windows 10, 11, Windows Server 2019 ou posteriores.
- Recurso Gerenciador de Serviços de Informações da Internet(IIS) ativados no sistema operacional.
- Microsoft Hosting Bundle v8.x instalado.

> ℹ️ O Microsoft Hosting Bundle pode ser baixado [aqui](https://builds.dotnet.microsoft.com/dotnet/aspnetcore/Runtime/8.0.17/dotnet-hosting-8.0.17-win.exe). Também possuímos material de ajuda para [ativar o IIS no Windows](/ristoremobile.docs/manuais/ativar-iis/).

### 1. Faça o Download do Instalador

O instalador da API é um arquivo executável(.exe) e pode ser obtido clicando __<a href="https://sfhera.com.br/sistemas/sfherawebapi.exe">aqui</a>__.

Antes de prosseguir com a instalação, é importante já ter feito a instalação do Microsoft Hosting Bundle a ativação do IIS no Windows.

> ℹ️ Os pré-requisitos e a API devem ser configurados apenas em um computador da rede, esse computador funcionará como o servidor da API e deve ser preferencialmente o mesmo servidor do banco de dados do cliente.

### 2. Rode o Instalador

Execute como administrador o arquivo _sfherawebapi.exe_ e clique em avançar até o assistente concluir a extração de todos os arquivos.

<img src="/ristoremobile.docs/assets/images/manuais/instalar-api/2-rodar-o-instalador.gif" style="display:block; margin:auto;">
