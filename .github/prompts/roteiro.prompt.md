---
mode: 'agent'
description: 'Geração de roteiro com base em anotações de viagem'
---

Seu objetivo é criar um roteiro para um dia de visita ao parque {input:parque}.

Deve seguir o formato:

```markdown
### {Nome da área 1}

- {Curiosidades da área 1}

- [ ] **{hora} - {atividade 1}**
  - {detalhes}

- [ ] **{hora} - {atividade 2}**
  - {detalhes}

- Atrações Opcionais
  - [ ] {opcional 1}
  - [ ] {opcional 2}
  - [ ] {opcional 3}

### {Nome da área 2}

- {Curiosidades da área 2}

- [ ] **{hora} - {atividade 3}**
  - {detalhes}

- [ ] **{hora} - {atividade 4}**
  - {detalhes}

- Atrações Opcionais
  - [ ] {opcional 4}
  - [ ] {opcional 5}
  - [ ] {opcional 6}
```

Utilize as Dicas: {input:dicas}.
Siga a estratégia: {input:estrategia}.

Inclua o roteiro no arquivo {input:arquivo}.
