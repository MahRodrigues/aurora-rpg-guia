---
{"dg-publish":true,"permalink":"/combate/"}
---


# ⚔️ O Sistema de Combate

## ⏱️ O Fluxo do Turno
Em Aurora, o tempo em combate flui de forma quase simultânea.
1. **Iniciativa:** Quem já agiria* > Maior Agilidade > Alternado por times.
2. **Fase de Ações:** Todos declaram e realizam suas Ações Narrativas (ataque, movimento, etc).
3. **Eventos de Ambiente:** Armadilhas e cenários ativam.
4. **Fase de Reações:** Após ver o resultado das ações, todos podem gastar sua **Reação**.

> [!abstract] A Filosofia da Simultaneidade
> Ações à distância ocorrem ligeiramente antes de movimentos.
> Se dois guerreiros se atacam, ambos rolam e os danos acontecem ao mesmo tempo (é possível os dois caírem nocauteados juntos).

---

## 🏃 O que posso fazer? (Ações)
*Você tem 1 Ação Narrativa (e uma Reação) por turno.*

| Tipo | Descrição | Bônus/Efeito |
| :--- | :--- | :--- |
| **Mover e Atacar** | Padrão. Avança e bate. | - |
| **Só Mover** | Corre pelo cenário. | +2 na Defesa Passiva |
| **Engajar** | Foca no oponente à frente. | +1 Atk / +1 Def (Só 1 ataque) |
| **Mirar** | Foca no alvo à distância. | +1 Atk (Imóvel) |
| **Magia** | Conjura feitiço/poder. | Varia |
| **Ação Dupla** | Abdica da Ação para ter +1 Reação. | Ganha 2 Reações no turno |

---

## 🛡️ O Sistema de Reações (Defesa Ativa)
*Esta é a parte mais importante para sobreviver. A Reação é decidida pelo **JOGADOR** após ver o perigo.*

Você pode usar sua reação para **Atacar Novamente** (sem defesa), **Mover** ou usar uma **Defesa Ativa**.

### ✋ Defesa Ativa (Redução de Dano)
Se você for atingido, pode gastar sua reação para tentar diminuir o estrago.
* **Mecânica:** Jogue os dados do Atributo Defensivo (pegue os 3 maiores).
* **Efeito:** Subtraia o resultado do Dano ou Efeito recebido.

> [!example]- Exemplo de Esquiva
> Você levou **11 de dano**. Decide usar Reação para **Esquivar (Agilidade)**.
> Você rola sua Agilidade e tira **8**.
> **Dano Final:** 11 - 8 = **3 de dano**.

| Tipo de Ameaça | Atributo para Reagir |
| :--- | :--- |
| Ataques Físicos | **Agilidade** (Esquiva) ou **Vigor** (Aparar) |
| Ataques à Distância | Apenas **Agilidade** |
| Explosões / Área | **Agilidade** |
| Venenos / Empurrões | **Vigor** (Usa os 4 maiores dados) |
| Magia Mental / Ilusão | **Lucidez** (Foco) |

---

## 🩸 Resolução: Ataque e Dano

### ⚔️ Combate Físico (Armas)
> [!fail] Como Calcular o Dano Físico
> **Passo 1 (Acerto):** `d20 + Bônus` VS `Armadura do Alvo`.
> **Passo 2 (Dano):** O valor que **ultrapassar** a Armadura é o Dano Direto.
> 
> *Exemplo: Tirei 18 no ataque. A armadura do Orc é 12. Causei **6 de dano**.*
> 
> **💥 Crítico:** Se critar, soma o valor do atributo (Vigor/Agilidade) direto no dano final.
> **⚖️ Empate:** A vitória é da Defesa (Errou)

### Combate Mágico (Feitiços)
> [!quote] Ataque Mágico (Magias de Efeito/Dano)
> **Ataque:** `Dados de Flama (d4) + Bônus` VS `Defesa do Alvo (Vigor/Agilidade/Lucidez)`.
> 
> **Cálculo de Dano:**
> 1. Verifique quanto o ataque passou da defesa (Margem de Sucesso).
> 2. Role os dados de **Flama** da magia.
> 3. **Dano Final =** (Resultado da Flama) + (Margem de Sucesso).
> 4. **Efeitos Secundários (ex: Congelar, Pegar Fogo):** > Só funcionam se o Ataque superar a Defesa em **+1 ponto**. (Empate ou vitória simples não ativam o efeito, só o dano).
> 
> *Nota: Se o ataque for MENOR que a defesa, subtraia a diferença do dano da Flama.*
> **⚖️ Empate:** A vitória é da Defesa (Errou)

> [!info] Rajada Mágica (Cantrip)
> *Ataques simples de pura energia.*
> **Mecânica:** `d20 + Agilidade` VS `Defesa (Esq)`.
> **Dano:** O valor que ultrapassar a defesa é o dano. (Não rola Flama).

## Exemplos Práticos (Entenda a Matemática)

> [!success]- Exemplo 1: Syvius e a Labareda (Sucesso) 
> Syvius conjura fogo nos guardas. 
> > * **Ataque Mágico:** Rolou **15**. 
> >* **Defesa dos Guardas:** Eles têm **9** (e foram pegos de surpresa, sem reação). 
> >* **A Margem:** O ataque passou por **6** pontos (15 - 9).
> 
**O Dano:** Syvius rola a Flama da magia (4d4) e tira **8**. 
> **Total:** 8 (Dano Base) + 6 (Margem) = **14 de Dano**. 
> > *Resultado: Os guardas queimam.*

> [!danger]- Exemplo 2: O Dia Ruim de Krok (Falha Parcial) 
> Krok tenta congelar um Elfo. 
> > * **Ataque Mágico:** Rolou **10**. 
> > * **Defesa do Elfo:** Tinha 9, mas usou Reação (Vigor) e rolou +5. Total: **14**. 
> > * **A Margem:** Krok perdeu por **4** pontos (14 - 10). 
> 
> **O Efeito:** Como o ataque foi menor que a defesa, o **Congelamento falha**. 
> **O Dano:** Krok rola a Flama (3d4) e tira **9**. > **Total:** 9 (Dano Base) - 4 (Margem Negativa) = **5 de Dano**. 
> > > *Resultado: O Elfo toma dano, mas não congela.*

---

## 📐 Distâncias e Defesas Passivas

**Distâncias:**
* 🟥 **Adjacente:** Corpo a corpo.
* 🟨 **Perto:** Precisa mover para bater.
* 🟦 **Longe:** Ação de movimento não alcança.

> [!tip]- 📝 Fórmulas das Defesas Passivas (Consulta)
> *Use para preencher a ficha.*
> 
> **🛡️ Armadura (CA):** Bônus Armadura + Agilidade + Ações.
> **🧪 Resistência (Vigor):** Vigor + Sorte + Classe + Itens.
> **💨 Esquiva (Agilidade):** Agilidade + Sorte + Classe + Itens.
> **👁️ Foco (Lucidez):** Lucidez + Sorte + Classe + Itens.