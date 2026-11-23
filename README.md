## 🎯 Justificativa do Projeto

O crescimento e a complexidade da infraestrutura tecnológica da **Faculdade de Tecnologia de Barueri (Fatec Barueri)** demandam uma gestão de identidades e acessos (IAM) estruturada, segura e escalável. Anteriormente à concepção desta proposta, o ambiente enfrentava desafios operacionais críticos, tais como:

* **Uso de contas compartilhadas:** Docentes e discentes utilizavam credenciais genéricas ou compartilhadas nos computadores dos laboratórios, o que inviabilizava a rastreabilidade individual das ações e comprometia a segurança da informação.
* **Processos manuais e descentralizados:** O controle de inventário de máquinas, a nomenclatura de ativos e o atendimento de solicitações de acesso dependiam de controles manuais e trocas de e-mails, elevando o risco de falhas humanas e inconsistências cadastrais.
* **Falta de padronização e segregação de privilégios:** A ausência de políticas de grupo (GPOs) granulares e de separação clara entre ambientes acadêmicos e administrativos expunha os equipamentos a alterações indevidas e movimentação lateral de ameaças.

Diante desse cenário, este projeto justifica-se pela necessidade de estabelecer uma **arquitetura lógica, governança e automação** para o serviço de diretório (**Active Directory Domain Services - AD DS**) da unidade, alinhada às normativas do **Centro Paula Souza (CPS)**, à **Lei Geral de Proteção de Dados (LGPD)** e aos frameworks de boas práticas **ITIL**, **COBIT** e **ISO/IEC 27001**.

### Principais Benefícios Esperados
* **Segurança e Conformidade:** Implementação de credenciais individuais com políticas rigorosas de complexidade, bloqueio por inatividade e princípio do menor privilégio (segregação entre contas cotidianas e administrativas).
* **Eficiência Operacional:** Automação do provisionamento e ciclo de vida de contas (via scripts PowerShell integrados a fontes oficiais como o SIGA), reduzindo a carga manual da equipe de TI.
* **Padronização e Auditoria:** Criação de convenções claras de nomenclatura para usuários, grupos e computadores, além de trilhas de auditoria para rastreamento de alterações e incidentes.
* **Isolamento de Ambientes:** Separação lógica e de rede (VLANs e Unidades Organizacionais) entre os domínios **Acadêmico** e **Administrativo**, garantindo que cada perfil acesse estritamente os recursos necessários às suas atividades.
