# 🎥 Guia para o Vídeo Explicativo (máx. 5 minutos)

## ⏱️ Roteiro Sugerido

### 1. INTRODUÇÃO (30 segundos)
**O que mostrar:**
- Apresentação pessoal
- Objetivo do projeto: "Classificar mensagens como Spam ou Não Spam usando MLP"
- Tecnologias: Python, Scikit-learn, TF-IDF

**Script sugerido:**
> "Olá! Neste vídeo vou apresentar meu projeto de classificação de spam usando uma rede neural MLP. O objetivo é treinar um modelo capaz de identificar automaticamente se uma mensagem é spam ou não, utilizando Python e Scikit-learn."

---

### 2. DATASET E PRÉ-PROCESSAMENTO (1 minuto)
**O que mostrar:**
- Célula 2-4: Carregar dados e mostrar distribuição
- Célula 4: Explicar TF-IDF brevemente

**Script sugerido:**
> "Utilizei um dataset do Kaggle com mais de 700 mil mensagens. Aqui vemos a distribuição entre spam e não-spam. Para processar o texto, usei TF-IDF, que transforma as palavras em valores numéricos, limitando ao vocabulário de 5000 palavras mais relevantes."

**Dica:** Execute as células para mostrar os gráficos!

---

### 3. MODELO MLP (1 minuto)
**O que mostrar:**
- Célula 6: Explicar arquitetura do MLP
- Mostrar o treinamento acontecendo

**Script sugerido:**
> "O modelo MLP tem 2 camadas ocultas com 100 e 50 neurônios, usa a função de ativação ReLU e o otimizador Adam. Implementei early stopping para evitar overfitting. Aqui vemos o modelo treinando..."

**Dica:** Pode acelerar o vídeo na parte do treinamento se demorar muito!

---

### 4. CROSS-VALIDATION (1 minuto)
**O que mostrar:**
- Célula 7: Resultados do 10-fold CV
- Célula 8: Gráfico com as métricas por fold

**Script sugerido:**
> "Para validar o modelo, usei 10-fold cross-validation. Aqui vemos as 4 métricas principais: acurácia, precisão, recall e F1-score. Os resultados são consistentes em todos os folds, mostrando que o modelo generaliza bem."

**Dica:** Destaque a consistência entre os folds!

---

### 5. RESULTADOS FINAIS (1 minuto)
**O que mostrar:**
- Célula 9-10: Métricas no teste
- Matriz de confusão visual
- Comparação CV vs Teste

**Script sugerido:**
> "No conjunto de teste final, o modelo alcançou [X]% de acurácia. A matriz de confusão mostra que temos poucos falsos positivos e negativos. Aqui vemos a comparação entre cross-validation e teste final - os resultados são muito próximos!"

---

### 6. DEMONSTRAÇÃO PRÁTICA (1 minuto)
**O que mostrar:**
- Célula 11: Testar exemplos reais
- Mostrar a função predict_spam funcionando

**Script sugerido:**
> "Para demonstrar na prática, vou testar algumas mensagens. Esta aqui 'Win a free iPhone' foi corretamente classificada como spam com [X]% de confiança. Já esta mensagem normal 'meeting for lunch' foi classificada como não-spam."

**Dica:** Teste 2-3 mensagens interessantes!

---

### 7. CONCLUSÃO (30 segundos)
**O que mostrar:**
- Célula 12: Resumo final
- Arquivos do projeto

**Script sugerido:**
> "Em resumo, o projeto alcançou excelentes resultados com [X]% de acurácia. O código está completo com todas as métricas solicitadas, visualizações e documentação. Obrigado pela atenção!"

---

## 🎬 Dicas de Gravação

### Antes de Gravar:
1. ✅ **Execute todo o notebook** para ter todos os resultados prontos
2. ✅ **Reinicie o kernel** e rode célula por célula
3. ✅ **Prepare os exemplos** de teste que vai usar
4. ✅ **Teste o áudio** e a gravação da tela

### Durante a Gravação:
1. 🎤 **Fale claramente** e em ritmo moderado
2. 🖱️ **Movimente o mouse** para destacar pontos importantes
3. 📊 **Pause nos gráficos** para dar tempo de visualizar
4. ⏱️ **Controle o tempo** - deixe um cronômetro visível

### Ferramentas de Gravação:
- **Windows**: OBS Studio, ShareX, Xbox Game Bar
- **Screen Recorder**: Loom, Screencast-O-Matic
- **Edição**: DaVinci Resolve (grátis), Camtasia

---

## 📋 Checklist do Vídeo

### Conteúdo Obrigatório:
- [ ] Explicação do objetivo
- [ ] Demonstração do dataset
- [ ] Explicação do pré-processamento (TF-IDF)
- [ ] Arquitetura do MLP
- [ ] Validação (10-fold Cross-Validation)
- [ ] Métricas: Acurácia, Precisão, Recall, F1-Score
- [ ] Matriz de Confusão
- [ ] Demonstração prática (teste com exemplos)

### Qualidade Técnica:
- [ ] Áudio claro e sem ruídos
- [ ] Tela em boa resolução (mínimo 720p)
- [ ] Tempo entre 3-5 minutos
- [ ] Código visível e legível
- [ ] Gráficos visíveis

---

## 🎯 O Que os Professores Avaliam

1. **Compreensão Técnica** (40%)
   - Você entende o que é MLP?
   - Explica bem o TF-IDF?
   - Interpreta as métricas corretamente?

2. **Implementação** (30%)
   - Código funciona?
   - Está bem organizado?
   - Usa as bibliotecas corretas?

3. **Apresentação** (20%)
   - Vídeo claro e objetivo?
   - Boa didática?
   - Dentro do tempo?

4. **Resultados** (10%)
   - Métricas adequadas?
   - Visualizações claras?
   - Análise dos resultados?

---

## 💡 Dicas Extras

### Para Impressionar:
1. 🌟 **Mostre entusiasmo** pelo projeto
2. 🌟 **Explique o "porquê"** das escolhas (ex: "Escolhi ReLU porque...")
3. 🌟 **Interprete os resultados** (não só mostre números)
4. 🌟 **Demonstre conhecimento** sobre overfitting, cross-validation, etc.

### Para Evitar:
1. ❌ Ler o código em voz alta
2. ❌ Ficar muito tempo em silêncio
3. ❌ Velocidade muito rápida ou muito lenta
4. ❌ Esquecer de explicar termos técnicos
5. ❌ Ultrapassar os 5 minutos

---

## 📤 Upload do Vídeo

### YouTube (Recomendado):
1. Faça upload como "não listado" se quiser privacidade
2. Título sugestivo: "Classificação de Spam com MLP - [Seu Nome]"
3. Descrição: Cole o resumo do projeto
4. Copie o link e envie no AVA

### Alternativas:
- Google Drive (com permissão de visualização)
- OneDrive
- Vimeo

---

## ⏰ Timeline Exemplo (5 minutos)

```
00:00 - 00:30  →  Introdução
00:30 - 01:30  →  Dataset e TF-IDF
01:30 - 02:30  →  Modelo MLP
02:30 - 03:30  →  Cross-Validation
03:30 - 04:30  →  Resultados e Matriz de Confusão
04:30 - 05:00  →  Demonstração Prática e Conclusão
```

---

## 🎓 Exemplo de Script Completo

Para uma versão mais completa, veja o arquivo: [script_exemplo_completo.txt]

---

Boa sorte com o vídeo! 🎬✨

Qualquer dúvida, consulte o README.md ou revise o notebook!


