# Projeto Centuriões — Active Directory

## 📌 Visão Geral
Este projeto tem como objetivo organizar e documentar o ambiente **Active Directory (AD)** já existente da Faculdade de Tecnologia Padre Danilo José.  
O repositório centraliza documentação, diagramas UML, scripts e evidências de testes, garantindo rastreabilidade e colaboração entre os integrantes.

---

## 📂 Estrutura de Pastas
- `src/` → Código-fonte e scripts principais  
  - `src/modules/` → módulos específicos  
  - `src/utils/` → funções auxiliares  

- `docs/` → Documentação e artefatos  
  - `docs/backlogs/` → arquivos de backlog  
  - `docs/uml/` → diagramas UML (casos de uso, atividades, sequência, classes, estados)  
  - `docs/architecture/` → diagramas de arquitetura e OUs  

- `tests/` → Scripts e evidências de testes  
  - `tests/unit/` → testes unitários  
  - `tests/integration/` → testes de integração  

- `assets/` → Recursos estáticos (imagens, ícones, diagramas exportados)  

- `config/` → Arquivos de configuração (`.env.example`, `settings.json`, políticas)  

- `scripts/` → Scripts auxiliares para manutenção e automação  


---

## 🌱 Estratégia de Branches

- **main** → versão estável e homologada.  
- **develop** → integração de funcionalidades antes do merge final.  
- **feature/** → desenvolvimento de tarefas específicas.  
  - Exemplo: `feature/cadastro-usuarios`  

### Regras
- Nenhum commit direto em `main` ou `develop`.  
- Todo merge deve ser feito via Pull Request.  

### Tipos permitidos
- **feat**: nova funcionalidade
- **fix**: correção de bug
- **docs**: alterações na documentação
- **style**: ajustes de formatação (sem impacto no código)
- **refactor**: refatoração de código sem mudança de comportamento
- **test**: inclusão ou ajuste de testes
- **chore**: tarefas auxiliares (build, configs, dependências)


---

## 🚀 Como usar
1. **Clonar o repositório**
   ```bash
   git clone https://github.com/guirlima/centurioes.git
   cd centurioes

---
##Confirmação de versionamento
- Guilherme Rodrigues de Lima
- Gabriel Tavares Bento
- Miguel Santana Matos
- Roger Ferreira Cardoso
