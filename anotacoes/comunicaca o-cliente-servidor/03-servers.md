# 03 — Sobre Servidores

## 🖥️ Conceito de Servidor

O **servidor** usa a **conexão com a internet** para fazer a conexão entre os dispositivos. Mas servidor **não quer dizer necessariamente** que aquele computador só é acessível pela internet — ele pode ser um servidor **dentro de uma rede local**.

- O servidor tende a ser um **computador mais robusto**, pois exige **processamento**.
- Existem **diversos tipos de servidores**.

## 🗂️ Tipos de servidores (por função)

| Tipo | Função |
|------|--------|
| **Servidor de arquivos** | Centraliza imagens, áudios e arquivos que todos podem acessar |
| **Servidor de segurança** | Cuida da segurança das informações |
| **Servidor de streaming** | Transmite vídeos e áudios |
| **Servidor de email** | Armazena e gerencia e-mails |
| **Servidor web** | Hospeda sites e os entrega aos clientes |

Os servidores podem ser **um computador simples** ou **enormes** — exemplo: os **data centers**.

## ⚙️ Diferença entre hardware e software em servidores

- **Software:** o servidor tem o **sistema operacional** e, instalado nele, o **servidor web**. É ele que faz o processamento das **requisições HTTP** (quando um cliente pede alguma informação).
- **Hardware:** é a **parte física** do computador.

## 🔀 Tipos específicos de servidores

### 🛡️ Servidor Proxy

Imagine uma empresa com **10 funcionários**, e você quer **bloquear o acesso** a certos sites. O **proxy** é um servidor **no meio** do caminho:

1. O funcionário tenta acessar a internet.
2. Antes de chegar à internet, ele passa pelo **proxy**.
3. O proxy **analisa** se aquele site pode ser acessado.
4. Se sim, ele busca na internet e devolve a resposta.

O proxy também pode servir como **servidor de autenticação**: ele guarda usuário e senha e valida no servidor central.

### 🧱 Servidor Firewall

Parecido com o proxy, mas cuida de **acessos externos** — por exemplo, de um cliente ou de alguém malicioso.

### 🌐 Servidor Web

Tem um **site hospedado** que está disponível na internet e é entregue ao cliente.

### 📧 Servidor de Email

Voltado para **emails** — armazenar e enviar mensagens.

### 🗄️ Database Server

O **banco de dados** fica separado: a aplicação web está instalada no servidor, e essa aplicação se conecta ao banco de dados (que pode estar em **outro servidor**) para armazenar as informações dos usuários.

## 🏢 Intranet

**Intranet** é um **servidor web que não precisa de internet**. É um site acessível **apenas na rede local** — não pela internet, onde qualquer um poderia entrar.

## 📇 Servidor DNS

**DNS** = *Domain Name Service* (Serviço de Nomes de Domínio).

- É um servidor que detém uma **lista de nomes e IPs**.
- Cada máquina tem um **IP** — é como se fosse a **identidade** dela.
- O DNS **traduz o nome** (ex.: `google.com`) para o **IP** correspondente.
- Ele consulta a lista, vê qual máquina tem aquele IP e **direciona** o nome para o IP específico.

> 💡 **Analogia:** o DNS é como a **agenda de contatos** da internet — você digita o nome, ele encontra o número (IP).

## 🌍 Hospedagem de Site

**Hospedagem** é colocar os **arquivos do site** em um **servidor na internet** para que os clientes possam acessar.

### Protocolos importantes

- **HTTP:** requisição comum (não segura).
- **HTTPS:** requisição **segura** — a informação é **criptografada de ponta a ponta**.
- **FTP:** conexão usada para **enviar arquivos** ao servidor.

> Com isso, você tem seu próprio **website disponível para todos na internet**.

## 🔗 Navegação

[⬅️ Anterior: Clients](02-clients.md) | [Voltar ao índice](README.md) | [Próximo: Linguagens de Programação ➡️](04-linguagens-programacao.md)
