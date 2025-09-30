# 🔐 Experimento de Quebra de Senhas com Medusa no Kali Linux

Este projeto documenta um experimento de cibersegurança utilizando a ferramenta **Medusa** em um ambiente controlado com **Kali Linux bootável**. O objetivo é demonstrar como ataques de força bruta funcionam na prática, reforçando o entendimento sobre segurança de autenticação.

---

## 🧪 Objetivo

Realizar testes de quebra de senha em serviços como SSH ou FTP utilizando a ferramenta Medusa, em um ambiente seguro e isolado, com o propósito educacional.

---

## ⚙️ Ferramentas Utilizadas

- [Kali Linux](https://www.kali.org/)
- Medusa
- Pendrive bootável (crtcher)
- Serviço alvo local (ex: servidor SSH ou FTP em máquina virtual)

---

## 📁 Estrutura do Projeto


medusa-password-cracking/
├── README.md
├── setup/
│   └── kali-boot.md
├── medusa/
│   ├── medusa-test.md
│   └── comandos-utilizados.txt
├── resultados/
│   └── logs.txt
└── imagens/

✅ Etapas do projeto

1. Preparar o Kali Linux Bootável
Criar um pendrive bootável com Kali Linux usando ferramentas como Rufus ou balenaEtcher.
Documentar esse processo no arquivo setup/kali-boot.md.

2. Instalar e configurar Medusa
Medusa já vem no Kali, mas você pode garantir com:
sudo apt update
sudo apt install medusa

3. Realizar o teste de quebra de senha
Escolha um serviço alvo em ambiente controlado (ex: SSH local, FTP local).
Exemplo de comando:
medusa -h 192.168.0.10 -u admin -P senhas.txt -M ssh










