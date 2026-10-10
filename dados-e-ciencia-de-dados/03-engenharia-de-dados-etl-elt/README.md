# 03 · Engenharia de dados: ETL/ELT e pipelines

> **Status:** `[ ] Não iniciado` · `[ ] Em andamento` · `[ ] Em revisão` · `[ ] Validado`
>
> **Início:** ____/____/______ · **Conclusão:** ____/____/______ · **Horas estudadas:** ______
>
> **Autoavaliação (0 a 4):** ____ *(ver escala no README principal)*

## 🎯 Objetivo da etapa

Construir pipelines confiáveis, idempotentes e observáveis que movem e transformam dados.

## 📁 Estrutura sugerida da pasta

```
03-engenharia-de-dados-etl-elt/
├── README.md          ← este arquivo (validação)
├── notas/             ← resumos com suas próprias palavras
├── exercicios/        ← práticas, katas, implementações do zero
├── projetos/          ← entregáveis desta etapa
├── dados/             ← datasets usados, dicionários de dados, fontes e licenças
├── referencias/       ← livros, artigos, documentação, anotações de cursos
└── evidencias/        ← prints, relatórios, links de repositório/dashboard, feedbacks
```

## 📚 Checklist de tópicos

Marque quando você **estudou e consegue explicar** o tópico, não apenas leu. Itens com nomes de ferramentas mudam rápido: **confirme o que está vigente** antes de estudar.

- [ ] ETL vs. ELT e quando usar cada um
- [ ] Ingestão: APIs, arquivos, bancos, CDC (captura de mudanças)
- [ ] Transformação com SQL e dbt
- [ ] Orquestração: Airflow, Prefect, Dagster
- [ ] Idempotência, reprocessamento e backfill
- [ ] Tratamento de falhas, retries e alertas
- [ ] Incremental vs. carga total
- [ ] Testes de dados e contratos
- [ ] Padrão medalhão (bronze, prata, ouro)
- [ ] Gerenciamento de dependências entre pipelines
- [ ] Segredos, configuração e ambientes
- [ ] Boas práticas de código e CI/CD para dados

## ✅ Critérios de validação (capacidades)

Só marque se você consegue fazer **sem ajuda e sem copiar tutorial**. Ao marcar, anote a evidência (arquivo, link, relatório).

- [ ] Construo um pipeline ELT incremental e reexecutável  
  - Evidência: 
- [ ] Implemento CDC ou ingestão incremental de uma fonte real  
  - Evidência: 
- [ ] Modelo transformações em camadas com dbt ou equivalente  
  - Evidência: 
- [ ] Reprocesso (backfill) um período sem duplicar dados  
  - Evidência: 
- [ ] Configuro alertas e retries adequados  
  - Evidência: 
- [ ] Escrevo testes de dados que quebram o pipeline quando algo está errado  
  - Evidência: 

## 🛠️ Entregáveis obrigatórios

- [ ] Pipeline completo orquestrado, versionado e testado  
  - Link/caminho: 
- [ ] Projeto dbt (ou equivalente) com camadas e testes  
  - Link/caminho: 
- [ ] Runbook de operação e recuperação do pipeline  
  - Link/caminho: 

## ❓ Perguntas de autoavaliação

Responda **de memória, em voz alta ou por escrito**, antes de consultar qualquer material. Depois confira e anote o que errou.

1. O que é idempotência e por que importa?
   - Resposta (sem consultar):

2. Quando ELT é melhor que ETL?
   - Resposta (sem consultar):

3. O que é CDC?
   - Resposta (sem consultar):

4. O que é o padrão medalhão?
   - Resposta (sem consultar):

5. Como evitar duplicidade em reprocessamentos?
   - Resposta (sem consultar):

## 🔎 Lacunas e dúvidas abertas

| Data | Dúvida / lacuna | Plano para resolver | Resolvido? |
|---|---|---|---|
|  |  |  | [ ] |

## 🧾 Materiais consultados

| Tipo (livro, curso, artigo, vídeo) | Título / link | Partes consultadas | Nota (0-5) |
|---|---|---|---|
|  |  |  |  |

## 🏁 Parecer final da etapa

Esta etapa está **validada** quando:

- [ ] Todos os critérios de validação estão marcados com evidência.
- [ ] Todos os entregáveis obrigatórios estão concluídos e **reproduzíveis** (código, dados e instruções permitem refazer).
- [ ] As conclusões foram **verificadas com método** (validação, testes, checagens de qualidade), não apenas observadas.
- [ ] Você usou **dados reais** (ou realistas) em pelo menos um entregável e documentou origem e licença.
- [ ] Você acertou ao menos 80% das perguntas de autoavaliação sem consultar.
- [ ] Você conseguiu explicar a etapa para outra pessoa (ou gravou uma explicação) sem apoio de anotações.
- [ ] Alguém revisou pelo menos um dos seus entregáveis e você incorporou o feedback.
- [ ] Você registrou as lacunas restantes e decidiu quando voltar a elas.

**Data da validação:** ____/____/______

**Observações finais:**

