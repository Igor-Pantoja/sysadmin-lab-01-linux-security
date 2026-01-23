# 🔐 Servidor Linux Seguro

Projeto prático de SysAdmin focado em segurança básica de servidores Linux,
simulando a entrega de um servidor para um cliente real.

## 🎯 Objetivo
Criar e proteger um servidor Linux aplicando boas práticas de segurança,
controle de acesso e firewall.

## 🛠️ Tecnologias Utilizadas
- Linux (Ubuntu Server)
- AWS EC2
- SSH com autenticação por chave
- Firewall UFW

## 🔒 Segurança Implementada
- Login root desativado
- Acesso SSH somente por chave
- Usuários com privilégios mínimos (sudo controlado)
- Firewall UFW ativo (deny incoming / allow outgoing)
- Testes de acesso após hardening

## 🧪 Testes Realizados
- Login SSH via chave (usuário sysadmin)
- Bloqueio de login root
- Validação de firewall ativo sem perda de acesso
- Controle de permissões sudo

## 📌 Cenário Real
Este projeto simula a configuração de um servidor Linux seguro para uma
pequena empresa ou profissional que precisa de acesso remoto confiável.

## 👨‍💻 Autor
Igor Cesar  
SysAdmin / Infraestrutura (em formação)

