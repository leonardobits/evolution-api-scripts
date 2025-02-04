# Setup da Evolution API no Windows

Este repositório contém um script em **PowerShell** para configurar o ambiente da **Evolution API** no Windows utilizando o **Docker Compose**. O script realiza as seguintes tarefas:

- Verifica a existência dos pré-requisitos (Git e Docker Desktop com Docker Compose).
- Clona o repositório da Evolution API.
- Cria os arquivos de configuração `.env` e `docker-compose.yml`.
- Inicia os containers do Docker (Evolution API, PostgreSQL e Redis).

## Pré-requisitos

Antes de executar o script, certifique-se de que os seguintes componentes estejam instalados e configurados em seu sistema:

- **Sistema Operacional:** Windows 10 ou superior.
- **Git:** [Git para Windows](https://gitforwindows.org/) (versão 2.x ou superior).
- **Docker Desktop:** [Docker Desktop para Windows](https://www.docker.com/products/docker-desktop/) (versão 2.x ou superior).  
  > **Observação:** O Docker Desktop já inclui o Docker Compose.
- **PowerShell:** Versão 5.1 ou superior (padrão no Windows 10).

## Instruções de Uso

1. **Clone o Repositório ou Baixe os Arquivos**

   Clone este repositório ou baixe os arquivos manualmente para uma pasta de sua preferência:
   
   ```powershell
   git clone https://github.com/leonardobits/evolution-api-scripts
   cd evolution-api-scripts
