# Assistente de Personal Trainer Automatizado

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

## 1. Biotipo Corporal

O biotipo corporal do usuário é um dos fatores mais importantes para a personalização do treino, pois determina como o corpo reage ao treino e à alimentação. Aqui estão os três biotipos principais:

- **Ectomorfo**: Corpo mais magro, com dificuldades para ganhar peso e massa muscular. Indicado para treinos com foco em hipertrofia e aumento de massa muscular.
- **Mesomorfo**: Corpo naturalmente mais musculoso, com facilidade para ganhar massa muscular e perder gordura. Pode variar o treino para emagrecimento ou ganho muscular.
- **Endomorfo**: Tendência a acumular gordura, com maior dificuldade para perder peso. O foco aqui seria em treinos que ajudem na queima de gordura e na definição muscular.

### Prompt de Biotipo

🔍 **Escolha seu biotipo corporal**  
O seu biotipo físico tem um grande impacto no tipo de treino ideal para você. Escolha o biotipo que mais se aproxima de como seu corpo é atualmente. Se não tiver certeza, opte pela descrição que você mais se identifica.

- **Ectomorfo**: Corpo mais magro, dificuldade para ganhar peso e massa muscular. Tendência a ter pouca gordura corporal.
- **Mesomorfo**: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura. Normalmente tem boa definição muscular.
- **Endomorfo**: Corpo com tendência a acumular gordura, especialmente na região abdominal, e maior dificuldade para perder peso.

🔄 **Escolha o seu biotipo:**  
- Ectomorfo  
- Mesomorfo  
- Endomorfo  

---

## 2. Dias Disponíveis para Treinar

Dependendo da sua disponibilidade, o tipo de treino será ajustado para atender às suas necessidades. Quanto mais dias você tiver para treinar, mais específico será o foco do seu plano. Escolha o número de dias que você pode se comprometer para treinar de forma consistente.

- **1 dia por semana**: Treino **Full Body** (trabalho de corpo inteiro em uma única sessão).
- **3 dias por semana**: Treino **ABC** (dividido em três dias com foco em diferentes grupos musculares).
- **5 dias por semana**: Treino **ABCDE** (dividido em cinco dias, com foco ainda mais específico em cada grupo muscular).

### Prompt de Dias Disponíveis

📅 **Quantos dias por semana você pode treinar?**

🔄 **Quantos dias você pode treinar por semana?**  
- 1 dia (Full Body)  
- 3 dias (ABC)  
- 5 dias (ABCDE)  

---

## 3. Tipo de Exercício Preferido

Escolha o tipo de treino que mais se alinha com seus gostos e objetivos. Isso ajudará a garantir que o plano seja divertido e eficaz para você.

- **Funcional**: Exercícios que simulam movimentos do dia a dia, como agachamentos, saltos, e exercícios de equilíbrio. Ideal para quem quer melhorar a agilidade e a força funcional.
- **Maquinário**: Exercícios em máquinas, ótimos para isolar músculos específicos e controlar a intensidade de forma mais precisa.
- **Peso Livre**: Exercícios com halteres, barras e kettlebells, que envolvem mais grupos musculares ao mesmo tempo e aumentam a força geral.
- **Cardio**: Focado em melhorar a resistência cardiovascular com atividades como corrida, ciclismo, natação ou caminhada acelerada.
- **HIIT (Treinamento Intervalado de Alta Intensidade)**: Treinos curtos e intensos, alternando entre esforço máximo e descanso, para melhorar a capacidade cardiovascular e queimar gordura de forma rápida.

### Prompt de Tipo de Exercício

🏋️‍♂️ **Qual tipo de exercício você prefere?**  
Escolha o tipo de treino que mais se alinha com seus gostos e objetivos.

🔄 **Escolha seu tipo de exercício preferido:**  
- Funcional  
- Maquinário  
- Peso Livre  
- Cardio  
- HIIT  

---

## 4. Geração do Plano de Treino Personalizado

✅ **Pronto para seu plano de treino personalizado!**  
Agora que você nos disse mais sobre seus objetivos e preferências, vamos gerar um plano de treino específico para você. Ele será baseado no seu biotipo, disponibilidade de dias para treinar e tipo de exercício preferido.

🔄 **Clique abaixo para gerar seu plano de treino!**

---

### Regras de Negócio:
1. **Identificação do Biotipo Corporal**: O assistente vai pedir para o usuário escolher o biotipo corporal que mais se aproxima de seu corpo atual (ectomorfo, mesomorfo ou endomorfo).
2. **Determinação dos Dias de Treino**: O assistente solicita o número de dias disponíveis por semana e sugere o tipo de treino adequado (Full Body, ABC ou ABCDE).
3. **Seleção do Tipo de Exercício**: O assistente pergunta sobre o tipo de exercício preferido (funcional, maquinário, peso livre, cardio ou HIIT).
4. **Geração do Plano de Treino**: Com base nas informações fornecidas, o assistente gera um plano de treino personalizado.

---

**Nota:** A personalização do treino visa aumentar a eficiência e a aderência do usuário ao plano de treino, garantindo que ele seja tanto eficaz quanto prazeroso.
