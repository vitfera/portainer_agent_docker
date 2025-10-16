# Portainer Agent Docker

Este repositório contém um arquivo `docker-compose.yml` para facilitar a implantação do Portainer Agent utilizando Docker Compose.

## Como usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/vitfera/portainer_agent_docker.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd portainer_agent_docker
   ```
3. Suba o ambiente com Docker Compose:
   ```bash
   docker compose up -d
   ```

## Sobre

Portainer Agent é um componente que permite ao servidor Portainer gerenciar ambientes Docker remotos. O agente expõe a API Docker na porta 9001 para comunicação segura com o servidor Portainer principal.

**Nota**: Este agente deve ser conectado a um servidor Portainer principal. Configure o endpoint no servidor Portainer usando o endereço `<IP_DO_HOST>:9001`.

---

Desenvolvido por [vitfera](https://github.com/vitfera)