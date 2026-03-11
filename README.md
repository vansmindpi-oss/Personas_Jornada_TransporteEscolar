# Personas_Jornada_TransporteEscolar — VansMind (Jornada do Usuário)

> Objetivo: mapear a experiência real (AS-IS) e a experiência desejada com o VanLink (TO-BE),
> identificando dores, oportunidades e requisitos para o MVP.

---

# 1) Personas (definitivas)

## Persona A — Responsável (pai/mãe)
**Nome:** Mariana (35)  
**Contexto:** trabalha, rotina corrida, filho estuda em turno fixo, precisa de previsibilidade.  
**Objetivo:** contratar uma van confiável e acompanhar embarque/desembarque sem ansiedade.  
**Dores:** falta de transparência, atrasos sem aviso, comunicação fragmentada, medo por segurança.

---

## Persona B — Motorista/Van
**Nome:** Carlos (45)  
**Contexto:** opera uma van escolar, gerencia várias famílias, rota fixa com variações por trânsito/clima.  
**Objetivo:** organizar rota, vagas e comunicação com menos retrabalho e menos conflitos.  
**Dores:** excesso de mensagens, listas manuais, acusações sem registro, dificuldade de gerenciar mudanças.

---

## Persona C — Escola (stakeholder indireto)
**Nome:** Coordenação Escolar (representada por Paula, 39)  
**Contexto:** recebe reclamações de atrasos, mas não gerencia transporte diretamente.  
**Objetivo:** reduzir atrasos recorrentes e ruído com responsáveis; ter canal de comunicação em casos críticos.  
**Dores:** baixa visibilidade, conflitos “sobram” para a escola, falta de informação objetiva.

---

# 2) Jornada do Usuário — AS-IS (como é hoje, sem o VanLink)

## 2.1 Jornada do Responsável (AS-IS)
### Etapa 1 — Descoberta / Busca
- Procura indicação em grupos (pais, vizinhos, escola)
- Pede contatos no WhatsApp
**Dor:** poucas opções e pouca informação confiável

### Etapa 2 — Comparação e negociação
- Faz perguntas repetidas: rota, horário, preço, vagas, monitor(a)
- Compara por prints e mensagens
**Dor:** informação despadronizada e difícil de comparar

### Etapa 3 — Contratação informal
- Combina por mensagem (sem contrato/registro organizado)
- Pagamento combinado “no boca a boca”
**Dor:** falta de clareza e histórico do que foi acordado

### Etapa 4 — Rotina diária (embarque)
- Espera no ponto
- Se atrasar, manda mensagem
**Dor:** ansiedade; sem aviso padronizado

### Etapa 5 — Durante o trajeto
- Sem visibilidade do andamento
- Depende de resposta do motorista
**Dor:** insegurança e dependência total do WhatsApp

### Etapa 6 — Desembarque
- Confirma “na confiança” que chegou
- Em caso de atraso, reclama no grupo
**Dor:** não existe check-out; sem prova/registro

### Etapa 7 — Problemas e ocorrências
- Se houver problema, vira “conversa” e discussão
- Sem histórico formal
**Dor:** conflitos, acusações e desgaste

---

## 2.2 Jornada do Motorista (AS-IS)
### Etapa 1 — Captação de clientes
- Indicação, grupos, boca a boca
**Dor:** difícil crescer sem rede; demanda irregular

### Etapa 2 — Organização de rota e lista
- Caderno/planilha/WhatsApp
- Ajustes manuais
**Dor:** alto risco de erro e retrabalho

### Etapa 3 — Comunicação diária
- Mensagens repetidas (atraso, “já passou?”, “pegou meu filho?”)
**Dor:** sobrecarga e distração

### Etapa 4 — Embarque/desembarque
- Sem registro formal
**Dor:** se houver reclamação, não há histórico

### Etapa 5 — Ocorrências
- Tenta justificar por mensagem
**Dor:** perde tempo; conflitos aumentam

---

## 2.3 Jornada da Escola (AS-IS)
- Recebe reclamações de atraso
- Não tem dados objetivos (quantos atrasos, por quê)
**Dor:** escola vira “mediadora” sem ferramentas

---

# 3) Jornada do Usuário — TO-BE (como fica com o VanLink)

## 3.1 Jornada do Responsável (TO-BE)
### Etapa 1 — Descoberta / Busca (no VanLink)
- Seleciona: escola + bairro + turno
- Vê lista de rotas disponíveis com:
  - horários previstos
  - vagas
  - preço (opcional no MVP)
  - reputação/histórico (simples no MVP)
**Ganho:** comparação padronizada e rápida

### Etapa 2 — Solicitação de vaga
- Envia solicitação com dados mínimos (fictícios no protótipo):
  - aluno (apelido/código)
  - ponto/bairro
  - turno
**Ganho:** processo claro; sem troca de mil mensagens

### Etapa 3 — Aprovação e confirmação
- Motorista aprova ou recusa
- Status visível: pendente/aprovado/recusado
**Ganho:** transparência e registro

### Etapa 4 — Rotina diária (embarque)
- Responsável acompanha:
  - “rota em operação”
  - aviso de atraso (motivo + previsão)
  - check-in (embarcou)
**Ganho:** menos ansiedade, mais previsibilidade

### Etapa 5 — Durante o trajeto (MVP sem GPS)
- Sem mapa em tempo real (fora do escopo)
- Mas com:
  - avisos oficiais de atraso/ocorrência
  - status do trajeto por etapa (opcional)
**Ganho:** comunicação objetiva sem spam

### Etapa 6 — Desembarque
- Motorista registra check-out (desembarcou)
- Responsável recebe confirmação no painel
**Ganho:** segurança e rastreabilidade básica

### Etapa 7 — Histórico e suporte
- Histórico do dia: atrasos, ocorrências, check-in/out
- Caso de problema: registro objetivo
**Ganho:** menos conflito e mais clareza

---

## 3.2 Jornada do Motorista (TO-BE)
### Etapa 1 — Cadastro de rota e vagas
- Cria rota com:
  - escola
  - bairros
  - horários
  - vagas disponíveis
**Ganho:** organização e controle de capacidade

### Etapa 2 — Recebimento de solicitações
- Lista de solicitações com filtros
- Aprovar/recusar com justificativa curta
**Ganho:** triagem rápida

### Etapa 3 — Operação diária (lista do dia)
- “Minha rota hoje” com lista de alunos
- Botões rápidos:
  - check-in
  - check-out
  - faltou hoje (opcional)
**Ganho:** menos erro e menos mensagens

### Etapa 4 — Avisos e ocorrências
- Envia aviso padronizado para todos da rota:
  - “Atraso: trânsito (10 min)”
  - “Ocorrência: chuva forte”
**Ganho:** 1 aviso → todos informados

### Etapa 5 — Histórico e redução de conflitos
- Registros guardados por data
**Ganho:** transparência e proteção do motorista também

---

## 3.3 Jornada da Escola (TO-BE) — Indireta
- (Opcional no MVP) Recebe painel agregado sem dados sensíveis:
  - rotas por turno
  - índices de atraso (sem nomes de alunos)
**Ganho:** menos ruído e mais informação em dias críticos

---

# 4) Pontos de dor críticos (AS-IS) e oportunidades (TO-BE)

## Dores críticas AS-IS
- Falta de confirmação (check-in/out)
- Atrasos sem aviso padronizado
- Comparação difícil (informação espalhada)
- Falta de histórico e registro
- Excesso de mensagens e conflitos

## Oportunidades TO-BE (prioridades do MVP)
1. Check-in/out simples
2. Aviso de atraso com motivo + previsão
3. Cadastro padronizado de rotas/vagas
4. Solicitação de vaga com status
5. Histórico básico por dia/rota

---

# 5) Critérios de sucesso (para validar com usuários)
- Responsável consegue:
  - encontrar rota em menos de 2 minutos
  - solicitar vaga sem conversa longa
  - ver check-in/out do dia
- Motorista consegue:
  - registrar check-in/out com poucos cliques
  - avisar atraso uma vez para todos
- Redução de:
  - mensagens repetidas
  - conflitos por falta de informação
