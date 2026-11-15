# 💸 App de Finanças Pessoais da Victoria com Vibe Coding

PRD Refinado no Copilot Web:

```
# PRD – Organizador de Finanças Pessoais: Granaê
## 1. Visão do Produto
Construir uma aplicação web de finanças pessoais baseada em conversas em linguagem natural, permitindo que os usuários registrem receitas, despesas e metas financeiras de maneira simples e intuitiva.
A experiência deve se assemelhar a conversar com um assistente financeiro pessoal, eliminando a necessidade de preenchimento manual de formulários complexos e reduzindo a barreira de entrada para usuários iniciantes em educação financeira.
---
## 2. Problema
Muitas pessoas abandonam aplicativos de controle financeiro porque:
- Exigem cadastro manual excessivo;
- Possuem interfaces complexas;
- Demandam conhecimento financeiro prévio;
- Não oferecem orientações personalizadas;
- Falham em criar o hábito de acompanhamento financeiro.
Como consequência, os usuários perdem visibilidade sobre seus gastos, têm dificuldade em economizar e não conseguem atingir seus objetivos financeiros.
---
## 3. Objetivos do Produto
Permitir que qualquer pessoa organize suas finanças através de uma interface conversacional.
O sistema deve ajudar o usuário a:
- Registrar receitas e despesas rapidamente;
- Entender seus padrões de gasto;
- Acompanhar metas financeiras;
- Receber recomendações de economia personalizadas;
- Desenvolver hábitos financeiros saudáveis.
---
## 4. Público-Alvo
Pessoas que desejam iniciar sua organização financeira pessoal.
### Características
- Idade entre 18 e 45 anos;
- Pouca experiência com aplicativos financeiros;
- Utilizam smartphone diariamente;
- Buscam simplicidade e praticidade;
- Desejam economizar e alcançar metas financeiras.
---
## 5. Proposta de Valor
"Organize suas finanças conversando naturalmente com um assistente financeiro inteligente."
Exemplos de interação:
- "Gastei R$ 50 com almoço."
- "Recebi R$ 4.000 de salário."
- "Quero economizar R$ 5.000 para viajar."
- "Quanto gastei com transporte este mês?"
---
## 6. Escopo do MVP
### Funcionalidade 1 – Registro de Transações via Chat
O usuário poderá registrar receitas e despesas através de mensagens em linguagem natural.
Exemplos:
- "Gastei R$ 80 no mercado."
- "Paguei R$ 25 de Uber."
- "Recebi R$ 1.000 por um trabalho freelancer."
O sistema deverá identificar automaticamente:
- Tipo da transação (receita ou despesa);
- Valor;
- Categoria;
- Data da operação.
### Funcionalidade 2 – Classificação Automática
Categorias padrão do MVP:
- Alimentação
- Transporte
- Moradia
- Saúde
- Educação
- Lazer
- Compras
- Receitas
- Outros
O usuário poderá editar manualmente uma classificação incorreta.
### Funcionalidade 3 – Metas Financeiras
Permitir a criação e acompanhamento de metas financeiras.
Dados de uma meta:
- Nome da meta;
- Valor desejado;
- Prazo opcional;
- Valor acumulado;
- Percentual de progresso.
Exemplos:
- Reserva de emergência;
- Viagem;
- Compra de notebook;
- Entrada de imóvel.
### Funcionalidade 4 – Agente Financeiro
O Agente Financeiro deverá analisar os dados cadastrados e gerar recomendações simples e educativas.
Exemplos:
- "Você gastou 20% mais com alimentação este mês."
- "Transporte é sua segunda maior categoria de gastos."
- "Economizando R$ 10 por dia, você pode acumular cerca de R$ 300 por mês."
### Funcionalidade 5 – Dashboard Financeiro
Exibir uma visão consolidada das finanças.
Indicadores:
- Saldo atual;
- Receitas do mês;
- Despesas do mês;
- Progresso das metas;
- Categorias com maiores gastos.
Visualizações:
- Resumo financeiro;
- Gráfico de gastos por categoria;
- Evolução mensal simplificada;
- Recomendações do Agente Financeiro.
---
## 7. Fluxo Principal do Usuário
### Primeiro Acesso
1. Usuário cria conta.
2. Sistema apresenta breve introdução.
3. Usuário informa sua primeira transação.
4. Sistema registra e confirma o lançamento.
5. Dashboard é atualizado automaticamente.
### Uso Recorrente
1. Usuário envia mensagens no chat.
2. Sistema interpreta a intenção.
3. Transação é registrada.
4. Dashboard é atualizado.
5. Agente Financeiro gera insights personalizados.
---
## 8. Telas do MVP
### Tela Inicial
- Saldo atual;
- Receitas e despesas do mês;
- Resumo rápido;
- Acesso ao chat.
### Tela de Conversa
- Histórico de mensagens;
- Campo de entrada;
- Respostas do Agente Financeiro.
### Tela de Transações
- Lista de movimentações;
- Filtros básicos;
- Edição e exclusão de registros.
### Tela de Metas
- Cadastro de metas;
- Acompanhamento visual do progresso.
### Dashboard
- Indicadores financeiros;
- Gráficos simplificados;
- Recomendações automáticas.
---
## 9. Requisitos Não Funcionais
### Performance
- Resposta inferior a 3 segundos.
### Usabilidade
- Interface amigável para iniciantes.
- Design mobile-first.
- Navegação intuitiva.
### Compatibilidade
- Desktop;
- Tablets;
- Smartphones.
### Acessibilidade
- Boa legibilidade;
- Contraste adequado;
- Componentes acessíveis.
---
## 10. Critérios de Aceite
### Registro de Gastos
Dado que o usuário envie:
"Gastei R$ 50 com almoço."
O sistema deve:
- Detectar o valor R$ 50;
- Classificar como Alimentação;
- Registrar a transação;
- Exibir mensagem de confirmação.
### Registro de Receitas
Dado que o usuário envie:
"Recebi R$ 3.000 de salário."
O sistema deve:
- Identificar como receita;
- Registrar o valor;
- Atualizar o saldo.
### Metas
Quando o usuário criar uma meta financeira:
- A meta deve ser salva;
- O progresso deve ser exibido visualmente;
- O percentual concluído deve ser calculado automaticamente.
### Recomendações
Quando houver histórico suficiente:
- O sistema deve gerar ao menos uma recomendação personalizada.
---
## 11. Métricas de Sucesso
- 70% dos usuários realizam ao menos um registro financeiro no primeiro dia.
- 50% retornam à aplicação em até 7 dias.
- 80% das transações são categorizadas corretamente.
- NPS superior a 40 durante a validação inicial.
---
## 12. Fora de Escopo do MVP
Não desenvolver nesta versão:
- Open Finance;
- Integração bancária automática;
- Controle de investimentos;
- Gestão de cartões de crédito;
- Compartilhamento familiar;
- Planejamento tributário;
- Múltiplas contas por usuário.
Estas funcionalidades poderão ser consideradas em versões futuras.
---
## 13. Plano de Validação Inicial
### Objetivo
Validar se a experiência conversacional reduz a dificuldade de organização financeira para usuários iniciantes.
### Participantes
Entre 5 e 10 pessoas do público-alvo.
### Testes
- Registrar despesas e receitas;
- Criar metas financeiras;
- Consultar relatórios;
- Interagir com o Agente Financeiro.
### Indicadores de Sucesso
- 80% dos participantes registram uma transação sem ajuda.
- Tempo médio inferior a 1 minuto para o primeiro registro.
- Feedback positivo sobre simplicidade e facilidade de uso.
```
Interações com o Lovable:


- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
