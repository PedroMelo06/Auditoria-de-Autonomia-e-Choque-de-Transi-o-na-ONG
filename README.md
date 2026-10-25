# Auditoria-de-Autonomia-e-Choque-de-Transi-o-na-ONG

# Auditoria de Autonomia e Choque de Transição na ONG — Gestão de Crise
**Disciplina:** Metodologia Ativa / Engenharia de Software  
**Docente:** Prof. Marco Machado  
**Aluno:** Pedro Lucas Lopes de Melo | **RA:** UC24101086  

---

## Situação-Problema
Substituição imprevista da funcionária capacitada por voluntário sem letramento digital na reta final da implantação, gerando receio de dependência institucional e risco de cancelamento pela coordenação da entidade.

---

## 1. Recálculo Matemático do IAS em Contingência (Slide 9)

### 1.1 Premissas e Diagnóstico de Queda
O Índice de Autonomia e Soberania (IAS) avalia a sustentabilidade da solução sem tutela externa. A métrica divide-se em 5 critérios com pontuação de 1 a 5 (pontuação máxima global = 25 pontos):
* **C1:** Domínio Operacional Básico (Nota 1 a 5)
* **C2:** Estabilidade e Tolerância a Falhas da Infraestrutura (Nota 1 a 5)
* **C3:** Independência e Documentação Física / Poka-Yoke (Nota 1 a 5)
* **C4:** Multiplicação Interna e Transferência de Conhecimento (Nota 1 a 5)
* **C5:** Governança e Soberania de Dados (Nota 1 a 5)

Com o afastamento por motivos de saúde da única colaboradora instruída, o **Critério 4 (Multiplicação Interna) despencou criticamente de 4 para 1**.

$$\text{IAS Global (\%)} = \left( \frac{\sum_{i=1}^{5} C_i}{25} \right) \times 100 \ge 80\% \quad \implies \quad \sum C_i \ge 20 \text{ pontos}$$

### 1.2 Cálculo Compensatório de Contingência
Com $C_4 = 1$, os demais quatro critérios precisam somar no mínimo 19 pontos para atingir os 20 pontos indispensáveis à aprovação ($IAS \ge 80\%$):

* **Critério 1 (Domínio Operacional Básico):** Nota **5 / 5** (Elevação através de simplificação drástica com interface de tela única e botão único de ação).
* **Critério 2 (Estabilidade e Tolerância a Falhas):** Nota **5 / 5** (Aplicação de contêineres offline/persistentes sem dependência de internet ou nuvem em tempo real).
* **Critério 3 (Documentação Física e Poka-Yoke):** Nota **5 / 5** (Elevação máxima com a fixação de guia visual plastificado de 1 página e calhas identificadas por cores).
* **Critério 4 (Multiplicação Interna):** Nota **1 / 5** (Pontuação reduzida em contingência).
* **Critério 5 (Governança e Soberania de Dados):** Nota **4 / 5** (Bases em posse integral da creche/ONG com cópia física de segurança).

$$\text{Total Acumulado} = 5 + 5 + 5 + 1 + 4 = 20 \text{ pontos}$$

$$\mathbf{IAS_{\text{Contingência}}} = \left( \frac{20}{25} \right) \times 100 = \mathbf{80{,}0\%} \quad \text{[APROVADO / SOBERANIA ASSEGURADA]}$$

*Ação compensatória:* A perda na transmissão presencial entre colaboradores ($C_4$) foi neutralizada com a elevação para nota máxima em suporte visual físico ($C_3$) e robustez sem atrito da interface ($C_1$), preservando o patamar de conformidade institucional.

---

## 2. 'Protocolo de 1 Página' para o Novo Voluntário

Guia plastificado de manuseio imediato para operação autônoma em 15 minutos:

```text
=====================================================================
          PROTOCOLO OPERACIONAL DE ATENDIMENTO (1 PÁGINA)
=====================================================================

1. ACESSO IMEDIATO SEM COMPLEXIDADE:
   * Ligue o terminal no botão central da tomada na parede.
   * Não precisa memorizar usuários nem senhas complexas:
     O sistema inicializa direto na tela de entrega.
   * Se pedir desbloqueio pontual, a credencial padrão está escrita
     à mão na etiqueta amarela colada atrás do monitor.

2. ATENDIMENTO EM APENAS 2 CLIQUES:
   * Solicite o número de documento ou telefone da pessoa atendida.
   * Digite os números no campo central visível e clique em [BUSCAR].
   * Verifique o nome na lista e aperte o retângulo verde [CONFIRMAR ENTREGA].
   * Pronto! O sistema dá baixa no registro e emite o aviso de sucesso sozinho.

3. PLANO DE SOCORRO (SEM DEPENDER DE TELEFONEMAS):
   * O sistema travou ou a tela congelou?
     Pressione o botão liga/desliga do gabinete por 5 segundos até apagar,
     aguarde 10 segundos e ligue de novo (reinício limpo e automático).
   * O computador não ligou?
     Pegue a prancheta de atendimento na gaveta azul da mesa e anote
     o CPF e nome na folha manual de emergência. Continue o atendimento
     sem parar a fila e sem ligar para ninguém.
=====================================================================

## 3. Pitch Escrito contra o Risco de Abandono (Direcionado ao Conselho Diretor)
Ao Conselho Diretor e Coordenação da Instituição:

A preocupação levantada pela Direção é legítima e reflete o zelo pela entidade, mas a intervenção não foi concebida sob a ótica assistencialista de gerar dependência da universidade. Alicerçado nos princípios do Humanismo Solidário, o propósito do projeto é a emancipação real da comunidade: não implementei uma barreira tecnológica, transferi uma capacidade instalada definitiva. A contingência decorrente do afastamento da colega capacitada demonstrou exatamente a robustez da solução, que foi construída à prova de ausências individuais: a operação agora está guiada por um protocolo físico visual acessível a voluntários sem letramento digital prévio, operando com rotinas de socorro transparentes e sem qualquer necessidade de suporte externo. O projeto não pertence ao meio acadêmico, é patrimônio operacional autônomo da instituição. Manter o encerramento do processo é consagrar a soberania tecnológica da ONG.

## 4. Síntese Autoral Individual
Execução e Análise Individual: Pedro Lucas Lopes de Melo

O valor central da engenharia em contextos comunitários reside na frugalidade e na garantia de continuidade. A substituição repentina de operadores expõe a fragilidade de sistemas que dependem da memória individual. A transição da dependência pessoal para a emancipação através de procedimentos à prova de erro (poka-yoke) e documentação física direta protege a soberania da instituição, assegurando que o atendimento à comunidade nunca seja paralisado por barreiras técnicas ou imprevistos humanos.
