# Documentação Técnica: Kizuna Sys
**Versão:** 0.0.1 (Pre-Alpha)  
**Equipa:** Lucas Silva, Filipe Venturinha, Beatriz Figuereido 
**Estado:** Em Planeamento / Conceção

2. Definição do Conceito & Requisitos
*O que o sistema TEM de fazer. Vai adicionando itens à medida que surgem ideias.*
Desenvolver uma plataforma robusta que permite gerir diferentes módulos empresariais (como logística e frotas) através de um núcleo centralizado e colaborativo.
Além de desenvolver um ambiente que permite facilitar e fortaler a colaboração entre pessoas dentro de uma organização.

### Requisitos Funcionais (O que o software faz)
- [ ] **RF01 - Gestão Multi-Tenant:** O sistema deve isolar dados de diferentes empresas.
- [ ] **RF02 - Módulos (plug-in) :** Deve permitir a adicição configuração e remoção de modulos de forma simples.

### Requisitos Não-Funcionais (Qualidade técnica)
- [x] **RNF01 - Licenciamento:** O projeto deve utilizar Apache License 2.0.
- [ ] **RNF02 - Segurança:** As passwords devem ser encriptadas na BD.
- [ ] **RNF03 - Performance:** O Kernel deve processar logs em menos de 100ms.

## Arquitetura do Sistema
*Explicação técnica das escolhas. Preenche quando consolidares a ideia.*

- **Base de Dados:** PostgreSQL (Justificação: Suporte a JSONB para módulos flexíveis).
- **Kernel/Engine:** [C++ / Node.js / etc]
- **Interface:** [Web / Desktop / Mobile]

## Modelo de Dados (Base de Dados)
*Lista as tabelas principais que fores criando.*

1. **Table `tenants`:** Guarda as empresas clientes.
2. **Table `users`:** Utilizadores do sistema vinculados a um tenant.
3. **Table `assets`:** Veículos ou equipamentos monitorizados.
4. [ADICIONAR NOVA TABELA]

---

## Dificuldades & Soluções (Brainstorming)
*Sempre que bateres com a cabeça na parede, anota aqui. É o que dá mais nota na PAP.*

- **Problema:** [Ex: Erro ao ligar o C++ ao PostgreSQL]
- **Solução:** [Ex: Instalada a biblioteca libpq e configuradas as permissões de acesso]

## Como Correr o Projeto (Notas de Dev)
*Instruções rápidas para ti próprio ou para o júri.*

1. Clonar o repo.
2. Configurar a BD no ficheiro `.env`.
3. [ADICIONAR PASSO]
