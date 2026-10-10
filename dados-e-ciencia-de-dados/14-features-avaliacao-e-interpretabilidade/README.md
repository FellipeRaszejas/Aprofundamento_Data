# 14 · Engenharia de features, avaliação e interpretabilidade

> **Status:** `[ ] Não iniciado` · `[ ] Em andamento` · `[ ] Em revisão` · `[ ] Validado`
>
> **Início:** ____/____/______ · **Conclusão:** ____/____/______ · **Horas estudadas:** ______
>
> **Autoavaliação (0 a 4):** ____ *(ver escala no README principal)*

## 🎯 Objetivo da etapa

Construir boas representações, avaliar modelos com a métrica certa e explicar suas decisões.

## 📁 Estrutura sugerida da pasta

```
14-features-avaliacao-e-interpretabilidade/
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

- [ ] Engenharia de features: numéricas, categóricas, temporais, texto
- [ ] Encoding de categorias de alta cardinalidade
- [ ] Agregações e features de janela
- [ ] Tratamento de desbalanceamento
- [ ] Seleção de features
- [ ] Métricas por problema: AUC, PR-AUC, F1, RMSE, MAPE, métricas de ranking
- [ ] Escolha do limiar e custo de erros
- [ ] Calibração de probabilidades
- [ ] Quantificação de incerteza (conformal prediction)
- [ ] Interpretabilidade: importâncias, SHAP, LIME, PDP/ICE
- [ ] Análise de erros e de subgrupos
- [ ] Feature stores e consistência treino/serviço

## ✅ Critérios de validação (capacidades)

Só marque se você consegue fazer **sem ajuda e sem copiar tutorial**. Ao marcar, anote a evidência (arquivo, link, relatório).

- [ ] Escolho a métrica conforme o custo de erro do negócio  
  - Evidência: 
- [ ] Crio features temporais sem vazamento  
  - Evidência: 
- [ ] Calibro probabilidades e verifico a calibração  
  - Evidência: 
- [ ] Interpreto um modelo com SHAP e discuto os limites  
  - Evidência: 
- [ ] Defino o limiar de decisão com base em custo e benefício  
  - Evidência: 
- [ ] Analiso desempenho por subgrupo e identifico disparidades  
  - Evidência: 

## 🛠️ Entregáveis obrigatórios

- [ ] Relatório de análise de erros com plano de melhorias  
  - Link/caminho: 
- [ ] Catálogo de features com definição e risco de vazamento  
  - Link/caminho: 
- [ ] Relatório de interpretabilidade de um modelo  
  - Link/caminho: 

## ❓ Perguntas de autoavaliação

Responda **de memória, em voz alta ou por escrito**, antes de consultar qualquer material. Depois confira e anote o que errou.

1. Quando PR-AUC é melhor que ROC-AUC?
   - Resposta (sem consultar):

2. Como evitar vazamento em features temporais?
   - Resposta (sem consultar):

3. O que SHAP mede e não mede?
   - Resposta (sem consultar):

4. Por que calibrar probabilidades?
   - Resposta (sem consultar):

5. Como escolher o limiar de decisão?
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

