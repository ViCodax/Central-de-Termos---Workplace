<div align="center">

# 📄 Central de Termos Workplace

### Automação para criação e preenchimento de termos de equipamentos, reduzindo atividades manuais e padronizando a documentação de TI.

<img src="https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge&labelColor=0b241c" />
<img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-22C55E?style=for-the-badge&labelColor=0b241c" />
<img src="https://img.shields.io/badge/Copilot_Studio-Powered-22C55E?style=for-the-badge&logo=microsoft&logoColor=white&labelColor=0b241c" />

</div>

<br/>

## 📑 Sumário

- [Sobre o projeto](#sobre-projeto)
- [Funcionalidades](#funcionalidades)
- [Tipos de termo](#tipos-termo)
- [Tecnologias](#tecnologias)
- [Fluxo de funcionamento](#fluxo)
- [Estrutura do repositório](#estrutura)
- [Objetivo](#objetivo)
- [Status do projeto](#status)
- [Roadmap](#roadmap)
- [Licença](#licenca)
- [Autor](#autor)

<br/>

<a id="sobre-projeto"></a>
## 📌 Sobre o projeto

A **Central de Termos Workplace** automatiza a geração de documentos de **Entrega** e **Entrega/Devolução** de equipamentos utilizados pela equipe de TI.

A solução é um **agente de IA construído em Microsoft Copilot Studio**, que utiliza informações corporativas e dados dos ativos para preencher automaticamente os documentos — reduzindo erros de digitação, tempo operacional e tarefas repetitivas que antes exigiam preenchimento manual.

<br/>

<a id="funcionalidades"></a>
## ⚡ Funcionalidades

- ✅ Identificação automática do tipo de termo solicitado
- ✅ Seleção do modelo adequado para cada cenário
- ✅ Consulta automática de dados corporativos (matrícula, cargo, e-mail, gestor)
- ✅ Consulta à base oficial de ativos (fabricante, modelo, serial, hostname)
- ✅ Busca de equipamentos pelo número do ativo
- ✅ Padronização completa dos documentos gerados

<br/>

<a id="tipos-termo"></a>
## 📋 Tipos de termo

| Tipo | Descrição |
|---|---|
| 📥 Termo de Entrega | Gerado na entrega de um equipamento ao colaborador |
| 🔄 Termo de Entrega e Devolução | Gerado em cenários de troca simultânea de equipamento |

> 📌 **Observação:** também é possível utilizar o Termo de Devolução, porém ele não é necessário no ambiente atual.

<br/>

<a id="tecnologias"></a>
## 🧰 Tecnologias

<div align="left">

<img src="https://img.shields.io/badge/Microsoft_Copilot_Studio-22C55E?style=for-the-badge&logo=microsoft&logoColor=white&labelColor=0b241c" />
<img src="https://img.shields.io/badge/Windows-22C55E?style=for-the-badge&logo=windows&logoColor=white&labelColor=0b241c" />
<img src="https://img.shields.io/badge/Integração_Corporativa-22C55E?style=for-the-badge&logo=microsoftazure&logoColor=white&labelColor=0b241c" />

</div>

- Microsoft Copilot Studio (motor do agente de IA)
- Integração com serviços e bases corporativas de ativos e colaboradores (Work IQ)
- Automação de processos de documentação

<br/>

<a id="fluxo"></a>
## 🔄 Fluxo de funcionamento

```
Solicitação
    ↓
Identificação do tipo de termo
    ↓
Consulta de dados do analista
    ↓
Consulta de dados do colaborador
    ↓
Consulta do ativo
    ↓
Preenchimento automático
    ↓
Geração do documento
```

<br/>

<!---
<a id="estrutura"></a>
## 📂 Estrutura do repositório

```
Central-de-Termos---Workplace/
├── assets/
│   └── screenshots/
├── docs/
│   └── fluxo-agente.md
├── LICENSE
└── README.md
```

> 📌 Estrutura de referência recomendada para próximas atualizações do repositório — screenshots do agente em ação e documentação detalhada do fluxo ajudam bastante quem visita o projeto pela primeira vez.
-->
<br/>

<a id="objetivo"></a>
## 🎯 Objetivo

Transformar um processo operacional e repetitivo em um fluxo automatizado, confiável e escalável, permitindo que a equipe de Workplace concentre seus esforços em atividades de maior valor.

<br/>

<a id="status"></a>
## 📊 Status do projeto

Em **desenvolvimento contínuo**, com evolução das automações, integrações e possibilidades de aplicação direta na plataforma de gestão de ativos (no caso atual, TOPdesk).

<br/>

<a id="roadmap"></a>
## 🗺️ Roadmap

- [ ] Adicionar screenshots do agente em funcionamento
- [ ] Documentar fluxo técnico de integração (Copilot Studio ↔ bases corporativas)
- [ ] Expandir para integração de API para plataforma de chamados
- [ ] Publicar métricas de adoção via Power BI

<br/>

<a id="licenca"></a>
## 📄 Licença

Este projeto está licenciado sob os termos da **Licença MIT** — veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

<br/>

<a id="autor"></a>
## 👤 Autor

<div align="center">

**Vinicius Correia**
<br/>
Workplace Automation Specialist

<a href="https://www.linkedin.com/in/viniciuscdantas"><img src="https://img.shields.io/badge/LinkedIn-viniciuscdantas-22C55E?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b241c" /></a>
<a href="https://github.com/ViCodax"><img src="https://img.shields.io/badge/GitHub-ViCodax-22C55E?style=for-the-badge&logo=github&logoColor=white&labelColor=0b241c" /></a>

</div>
