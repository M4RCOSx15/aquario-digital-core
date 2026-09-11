# 🐠 Missão Aquário Digital: Protocolo de Versionamento e Gestão de Ecossistema

Este repositório contém o ecossistema principal do sistema **Aquário Digital**, focado em garantir o monitoramento e o controle de qualidade dos parâmetros essenciais do ambiente aquático.

---

## 🚀 Arquitetura de Ambientes e Branches

Para garantir a qualidade do software e a estabilidade das entregas, o projeto adota um fluxo de versionamento estruturado em três camadas principais:

| Ambiente | Branch | Descrição |
| :--- | :--- | :--- |
| **Produção** | `main` | Código estável, homologado e pronto para operação em ambiente real. |
| **Homologação / Testes** | `stage` | Ambiente para integração, testes de garantia de qualidade (QA) e validação antes da produção. |
| **Desenvolvimento** | `develop` | Branch base para integração de novas funcionalidades e correções contínuas. |

> **Nota:** As novas funcionalidades são desenvolvidas em branches curtas do tipo `feature/*` criadas a partir de `develop`.

---

## 🧪 Módulos do Sistema

### 💧 Controle de Qualidade da Água (`ControleQualidadeAgua.java`)
Módulo responsável por monitorar criticamente os parâmetros da água:
* **Faixa Ideal de pH:** `6.8` a `7.6`
* **Faixa Segura de Temperatura:** `22.0 °C` a `28.0 °C`

Se algum parâmetro estiver fora dos limites ideais, o sistema dispara alertas imediatos para intervenção da equipe.

---

## 🛠️ Como Executar o Projeto

1. Clone o repositório para sua máquina local:
   ```bash
   git clone [https://github.com/SEU-USUARIO/aquario-digital-core.git](https://github.com/M4RCOSx15/aquario-digital-core.git)