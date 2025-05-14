---
mode: 'agent'
description: 'Geração de roteiro com base em anotações de viagem'
---

Seu objetivo é criar um roteiro para um dia de visita ao parque {input:parque}.

Pergunta qualquer input não informado

Deve seguir o formato:

```markdown
### {Nome da área}

- [ ] **{hora} - {local} - {atividade}**
  - {detalhes}

- [ ] **{hora} - {local} - {atividade}**

### {Nome da área}

- [ ] **{hora} - {local} - {atividade}**
  - {detalhes}

- [ ] **{hora} - {local} - {atividade}**
```

Utilize as Dicas: {input:dicas} e siga a estratégia: {input:estrategia}.

Inclua o roteiro no arquivo {input:arquivo}.
