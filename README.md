# Central de Missões EETEPA

Painel de aula lúdica para abrir missões, cadastrar equipes fictícias, controlar tempo, pontuar evidências e exportar relatórios.

> Projeto educacional inspirado na EETEPA Vilhena Alves. Não é sistema oficial institucional e não usa dados reais de estudantes.

## Visão Geral

**Código:** L-01  
**Foco disciplinar:** Informática, Redes e Ciência de Dados  
**Formato:** jogo web conduzido pelo professor  
**Tempo sugerido:** 25 a 35 minutos  
**Demonstração pública:** https://albertomateus9.github.io/eetepa-mission-control-classroom/

Este projeto transforma uma aula técnica em uma experiência de jogo educacional. A fantasia central é: Sala de comando do professor com rádio de eventos, mesa tática e ocorrências rápidas.

## Como Conduzir A Dinâmica

- **Verbo de jogo:** despachar ocorrências.
- **Mecânica:** Sorteie uma ocorrência, atribua papéis e peça uma decisão técnica em até uma frase.
- **Papel da equipe:** Cada equipe assume um papel de operação e entrega uma decisão curta para o professor validar no mapa.
- **Recompensa da rodada:** Despacho validado.
- **Registro final:** exporte o relatório para guardar pontuação, evidências e próximos passos.

## Roteiro Do Professor

- **Objetivo:** Organizar uma aula gamificada com equipes, fases, tempo e evidências de aprendizagem.
- **Preparação:** Projete o painel, combine regras rápidas e crie equipes fictícias ou nomes escolhidos pela turma.
- **Condução:** Leia a fase, acione o tempo, circule entre as equipes e pontue evidências observáveis.
- **Fechamento:** Use o relatório exportado para registrar decisões, pontuação e melhorias para a próxima aula.
- **Critérios:** use a rubrica do app para pontuar evidência, colaboração, comunicação e melhoria.

## Missões

- **Apresentar o Caso (5 min):** Criar um nome de equipe, escolher papéis e explicar a primeira decisão em uma frase. Evidência: Cartão de papéis da equipe e primeira decisão registrada.
- **Despachar a Missão (8 min):** Escolher uma carta de missão, identificar o risco e definir uma ação segura. Evidência: Nota curta com risco identificado e ação escolhida.
- **Fechar e Pontuar (7 min):** Apresentar o que funcionou, o que falhou e o que deve melhorar. Evidência: Relatório final de aprendizagem da equipe.

## Competências

- colaboração em equipe
- comunicação técnica
- resolução de problemas
- avaliação formativa

## Como Rodar

Abra `index.html` diretamente ou sirva a pasta:

```bash
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Política De Dados

- Usa apenas missões sintéticas e equipes fictícias.
- Guarda estado apenas no `localStorage` do navegador.
- Não possui login, servidor, API externa ou registro real de estudante.

## Licença

MIT. Consulte [LICENSE](LICENSE).
