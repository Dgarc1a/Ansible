## Hi there 👋

# 🔐 Ansible Security Automation

**Automação de Segurança para Ambientes Windows, Linux e Active Directory**

Este repositório contém um conjunto crescente de playbooks Ansible
focados exclusivamente em **automação de segurança**

## incluindo

| playbooks                                  
|-----------------------------------------------|
| Hardening de sistemas Windows e Linux         |
| Aplicação de patches de segurança             |
| Atualização de software vulnerável            | 
| Configuração do Microsoft Defender            | 
| Auditoria e segurança de Active Directory     | 
| Inventário, descoberta e compliance           |

## 📌 Objetivo do Projeto

Criar uma base sólida, modular e reutilizável de **playbooks de
segurança** para uso em ambientes corporativos, ajudando a:

✔ Reduzir riscos\
✔ Aumentar a consistência operacional\
✔ Automatizar tarefas repetitivas\
✔ Eliminar vulnerabilidades comuns\
✔ Padronizar boas práticas de segurança

------------------------------------------------------------------------

## 📁 Estrutura do Repositório

    ├── playbooks/
    │   ├── windows/
    │   │   ├── apply_windows_updates.yml
    │   │   ├── windows_defender_config.yml
    │   │   
    │   ├── linux/
    │   │   ├── hardening_linux.yml
    │   │   ├── patch_linux.yml
    │   │   
    │   ├── software/
    │   │   ├── update_firefox.yml
    │   │   └── update_thirdparty.yml
    │   └── compliance/
    │       ├── cis_check.yml
    │       └── baseline.yml
    │
    ├── roles/
    │   └── (em expansão)
    |
    ├── Config/
    |   ├── ansible_cfg.txt
    |   ├── requirement.txt
    |   ├── winrm_config.ps1
    |
    ├── Commands.txt
    ├── inventory.txt
    |
    ├── docs/
    │   ├── guia_windows.md
    │   ├── guia_linux.md
    │   └── guia_ad.md
    │
    └── README.md

------------------------------------------------------------------------

Este projeto serve como uma base prática e escalável para automatizar tarefas de segurança em ambientes corporativos, reduzindo riscos, aumentando consistência e diminuindo trabalho manual.


![GitHub issues](https://img.shields.io/github/issues/Dgarc1a/BlueTricks)
![GitHub stars](https://img.shields.io/github/stars/Dgarc1a/BlueTricks)
![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)

Made with 💙 by [m0m0n0suk3](https://github.com/Dgarc1a/)

- 🔭 I’m currently working on it ...
- 🌱 I’m currently learning more about it ...
- 👯 I’m looking to collaborate on ...
