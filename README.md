# Guia Prático: Configurando um Servidor de Arquivos SMB no Linux

**Compartilhamento de arquivos eficiente para redes locais e pequenas empresas**

---

## ⚠️ Aviso Legal

Este material é gratuito e de uso educacional.  
É proibida sua revenda ou redistribuição sem autorização.  
As instruções foram testadas em ambientes Linux baseados em Debian/Ubuntu. Podem variar em outras distribuições.

---

## 📑 Sumário

1. [Introdução](#1-introdução)  
2. [Pré-requisitos](#2-pré-requisitos)  
3. [Instalação do Samba](#3-instalação-do-samba)  
4. [Configuração Básica](#4-configuração-básica)  
5. [Testes e Validação](#5-testes-e-validação)  
6. [Configurações Avançadas](#6-configurações-avançadas)  
7. [Montagem Automática nos Clientes](#7-montagem-automática-nos-clientes)  
8. [Segurança](#8-segurança)  
9. [Erros Comuns e Soluções](#9-erros-comuns-e-soluções)  
10. [Conclusão](#10-conclusão)  
11. [Anexos](#11-anexos)  
12. [Sobre o Autor](#12-sobre-o-autor)

---

## 1. Introdução

- O que é SMB/Samba  
- Vantagens do servidor de arquivos  
- Para quem é este guia  

---

## 2. Pré-requisitos

- Conhecimentos básicos de terminal  
- Acesso root ou sudo  
- Sistema Linux (Ubuntu Server recomendado)  
- Conexão em rede  

---

## 3. Instalação do Samba

- Atualizando o sistema  
- Instalando o pacote `samba`  
- Verificando a instalação  

---

## 4. Configuração Básica

- Criando a pasta compartilhada  
- Definindo permissões  
- Editando o `smb.conf`  
- Adicionando usuários Samba  

---

## 5. Testes e Validação

- Reiniciando o serviço  
- Acessando o compartilhamento a partir de clientes  
- Análise de logs com `journalctl` e `log.smbd`  

---

## 6. Configurações Avançadas

- Permissões por grupo  
- Acesso somente leitura  
- Auditoria e log detalhado  
- Integração com Active Directory (opcional)  

---

## 7. Montagem Automática nos Clientes

- Windows: mapa de unidade de rede  
- Linux: montagem via terminal  
- Persistência com `/etc/fstab`  

---

## 8. Segurança

- Restringir acesso por IP  
- Controle por interface de rede  
- Uso de firewall (ufw ou iptables)  
- Recomendação: VPN para acessos externos  

---

## 9. Erros Comuns e Soluções

- Permissão negada  
- Compartilhamento visível, mas inacessível  
- Usuário inválido  
- Cliente não encontra o servidor  

---

## 10. Conclusão

- Resumo das etapas  
- Boas práticas de manutenção  
- Recomendações futuras  

---

## 11. Anexos

- Modelo de `smb.conf` comentado  
- Scripts de instalação automática  
- Tabela de comandos úteis  

---

## 12. Sobre o Autor

João Melo é profissional de TI com experiência em infraestrutura Linux e redes locais.  
Contato: [email@email.com] — GitHub: [@seuusuario](https://github.com/seuusuario)

---

