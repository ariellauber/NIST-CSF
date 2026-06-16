# NIST Cybersecurity Framework 2.0 - Implementation Tracker

Um modelo interativo em MS Excel para **rastreamento e avaliação da maturidade** de implementação do **NIST Cybersecurity Framework v2.0** em qualquer organização, com foco em políticas, processos e práticas de segurança cibernética.

---

## 📋 Descrição

A planilha foi desenvolvida com **mais de uma década de experiência** em maturidade de programas de segurança e fornece um mecanismo estruturado para:

- ✅ Avaliar o nível de maturidade atual de cada controle do CSF 2.0
- ✅ Definir metas de implementação realistas por função e categoria
- ✅ Rastrear progresso com dashboard visual
- ✅ Comparar políticas vs. processos operacionais reais
- ✅ Integrar a avaliação com o NIST Privacy Framework 1.0

---

## 🎯 Funcionalidades Principais

### 1. **Estrutura Completa do NIST CSF 2.0**
- **6 Funções Principais**: Governar (GV), Identificar (ID), Proteger (PR), Detectar (DE), Responder (RS), Recuperar (RC)
- **Categorias e Subcategorias** com descrições detalhadas
- **Exemplos de implementação** para cada controle
- **Referências informativas** (CRI Profile, SP 800-221A, CSF v1.1, CIS Controls v8.0)

### 2. **Avaliação em Dois Eixos**
- **Políticas**: Como as políticas, procedimentos, padrões e diretrizes atendem aos requisitos
- **Processos**: Como os processos operacionais reais implementam os requisitos

### 3. **5 Níveis de Maturidade**
| Nível | Escala | Descrição |
|-------|--------|-----------|
| **Inicial** | 0.00 - 1.49 | Básico, ad-hoc, não documentado; tecnologias limitadas |
| **Gerenciado** | 1.50 - 2.49 | Capacidade parcial; processos em algumas unidades |
| **Definido** | 2.50 - 3.49 | Implementado com tecnologia significativa |
| **Quantitativamente Gerenciado** | 3.50 - 4.49 | Madura; processos consistentes; governança em vigor |
| **Otimizado** | 4.50 - 5.00 | Avançada; tecnologia de ponta; monitoramento contínuo |

### 4. **Dashboard Visual**
Rastreamento automático com gráficos que mostram:
- Média geral de maturidade por função
- Status de políticas vs. processos
- Alinhamento com metas (Alvo/Current/Média)
- Distribuição de maturidade entre categorias

### 5. **Alinhamento com Frameworks Complementares**
- ✅ NIST Privacy Framework 1.0 (janeiro de 2020)
- ✅ CIS Controls v8.0
- ✅ NIST SP 800-221A
- ✅ NIST SP 800-218

---

## 📂 Estrutura do Arquivo

```
NIST-CSF.xlsx
├── Introdução
│   └── Instruções de uso e histórico de alterações
├── Níveis de Maturidade
│   └── Definição dos 4 níveis e critérios [CMMI]
├── NIST CSF - DASH
│   └── Dashboard executivo com métricas de maturidade
├── CSF 2.0
│   └── Detalhamento completo de todos os 230+ controles
├── NIST - Perfil
│   └── Mapeamento: Perfil Atual vs. Perfil Alvo
└── [Abas Complementares]
    └── Sumários por função (GV, ID, PR, DE, RS, RC)
```

---

## 🚀 Como Usar

### **Passo 1: Preparação**
1. Abra a aba **"Níveis de Maturidade"** e revise os critérios de cada nível
   - Os níveis podem ser ajustados conforme a realidade da sua organização
   - Exemplo: Se acha que 5% de exceção é muito para nível 3, ajuste

### **Passo 2: Definir Metas**
1. Acesse a aba **"NIST CSF - DASH"**
2. Na coluna **"Alvo 2025"**, defina o nível de maturidade esperado para cada categoria
   - Nem todos os controles terão o mesmo alvo
   - Priorize conforme sua estratégia de risco

### **Passo 3: Avaliar Situação Atual**
1. Navegue até a aba **"CSF 2.0"** ou **"NIST - Perfil"**
2. Para cada controle, insira valores de **1 a 5** nas colunas:
   - **Políticas (nota)**: Avaliação de políticas, procedimentos e diretrizes
   - **Processos (nota)**: Avaliação de implementação operacional real
3. Você pode usar valores parciais (ex: 2.5) para maior precisão

### **Passo 4: Monitorar Progresso**
1. Visualize o **Dashboard** na aba **"NIST CSF - DASH"**
2. Métricas calculadas automaticamente:
   - Média por função (Governar, Identificar, Proteger, etc.)
   - Comparação: Alvo vs. Políticas vs. Processos
   - Progressão de maturidade geral

### **Passo 5: Atualizações**
- Revise e atualize a avaliação **trimestral ou semestralmente**
- Documente em "Alterações" (veja aba Introdução) novas versões
- Ajuste metas conforme mudanças em requisitos, ameaças e tecnologia

---

## 📊 Interpretando os Resultados

### **Política vs. Processo**
- **Gap Positivo** (Política > Processo): Políticas bem definidas, mas implementação deficiente → Foco em execução
- **Gap Negativo** (Processo > Política): Implementação ocorre ad-hoc, sem documentação → Formalizar políticas
- **Alinhado**: Ambas no mesmo nível → Manutenção e melhoria contínua

### **Priorização**
Focar em controles onde:
1. Impacto de risco é **alto**
2. Lacuna (Gap) entre alvo e atual é **grande**
3. Dependência com outros controles é **crítica**

---

## 🔄 Integração com Outras Frameworks

A planilha referencia:
- **CRI Profile v2.0**: Especificações alinhadas com CSF 2.0
- **NIST SP 800-221A**: Guias de implementação
- **CIS Controls v8.0**: Controles complementares e práticas recomendadas
- **NIST Privacy Framework 1.0**: Para privacidade de dados

Você pode usar essas referências para aprofundar implementação específica de controles.

---

## 📈 Exemplo de Uso - Empresa de Saúde

**Cenário**: Organização de saúde com dados HIPAA

| Função | Alvo | Político | Processo | Status |
|--------|------|----------|----------|--------|
| **Governar (GV)** | 3.0 | 2.8 | 2.0 | ⚠️ Políticas boas, execução deficiente |
| **Identificar (ID)** | 3.0 | 3.4 | 2.8 | ✅ Próximo ao alvo |
| **Proteger (PR)** | 3.5 | 3.1 | 3.5 | ✅ Bem alinhado |
| **Detectar (DE)** | 3.0 | 2.4 | 3.0 | ⚠️ Monitoramento bom, políticas fracas |
| **Responder (RS)** | 3.0 | 3.0 | 3.0 | ✅ Equilibrado |
| **Recuperar (RC)** | 3.0 | 2.5 | 3.5 | ⚠️ Recuperação forte, políticas a melhorar |

**Ações recomendadas**:
1. Reforçar governança operacional (GV)
2. Formalizar políticas de detecção (DE)
3. Documentar processos de recuperação (RC)

---

## 🎓 Boas Práticas

### **Avaliação Honesta**
- Use dados, evidências e testes (não apenas percepção)
- Envolva stakeholders de diferentes áreas (Segurança, Ops, Auditoria)
- Reavalie regularmente - a maturidade muda com mudanças no negócio

### **Ajustar para Sua Realidade**
- Os níveis de maturidade são **orientadores**, não rígidos
- Considere tamanho, setor, requisitos regulatórios
- Exemplo: Uma startup pode ter alvo 2.0, uma instituição financeira 4.0

### **Focar em Impacto**
- Não tente alcançar nível 5 em tudo simultaneamente
- Priorize controles críticos para sua missão
- Considere custo vs. benefício de cada investimento

### **Governança Contínua**
- Revise trimestralmente
- Escale desvios significativos
- Comunique progresso à liderança

---

## 📝 Histórico de Versões

| Versão | Data | Alterações |
|--------|------|-----------|
| 2.2 | Junho - 2026 | 🔧 Atualização de Processos/Indicadores |
| 2.1 | Dezembro - 2024 | 🔧 Correções em referências de privacidade |
| 2.0 | Março - 2024 | ✅ Adoção NIST CSF 2.0 |
| 1.5 | Janeiro - 2022 | ➕ Adicionado NIST Privacy Framework |
| 1.0 | Janeiro - 2019 | 🚀 Lançamento inicial |

---

## 🔐 Segurança da Planilha

- **Compartilhamento**: Mantenha cópia controlada; versione alterações;
- **Acesso**: Restrinja a pessoal de segurança/auditoria (considerações de confidencialidade);
- **Backup**: Exporte relatórios regularmente em PDF para arquivo.

---

## ⚖️ Disclaimer

Esta planilha é um **modelo orientador** baseado em boas práticas e experiência prática com o NIST CSF. 

- Não substitui consultoria profissional de segurança
- Adapt-a para sua organização e setor
- Valide com frameworks e regulamentações aplicáveis (HIPAA, GDPR, PCI-DSS, etc.)

---

## 📚 Referências Oficiais

- **NIST Cybersecurity Framework 2.0** (Fevereiro 2024)  
  https://www.nist.gov/cyberframework

- **NIST Privacy Framework 1.0** (Janeiro 2020)  
  https://www.nist.gov/privacy-framework

- **NIST SP 800-221A** (Special Publication - Implementation Guidance)

- **CIS Controls v8.0**  
  https://www.cisecurity.org/controls/v8

---

## 💡 Contribuições

Se encontrou melhorias, ajustes ou tem sugestões:
- Documente na aba "Alterações"
- Versione mudanças significativas
- Compartilhe com a comunidade

---

## 📄 Licença

Este arquivo é fornecido como **modelo educacional** sob licença **MIT**.  
Sinta-se livre para adaptar, modificar e usar em sua organização.

---

## 👤 Autor

Ariel Lauber:
- Esp. em Segurança da Informação - UFG;
- Esp. em Governança de Tecnologia da Informação - UNICAMP-SP;
- CompTIA Linux+, Security+ e CISA+;
- NIST CSF 2.0 Lead Implementer.
- Outras coisas por ai...


**Mantido por**: Ariel Lauber / ariellauber@gmail.com  
**Última atualização**: Jun/2026.

---

**⭐ Se esta planilha foi útil, considere dar uma estrela no repositório!**
