# 🤖 Prompts Utilizados no NotebookLM

## Objetivo

Esta seção documenta os prompts utilizados durante a pesquisa sobre Massoterapia.

O objetivo foi utilizar o NotebookLM não apenas para gerar resumos, mas para:

- explorar as fontes;
- comparar informações;
- identificar lacunas;
- diferenciar fatos de interpretações;
- verificar a origem das informações;
- evitar respostas inventadas;
- melhorar progressivamente a qualidade das respostas.

---

# 1. Prompt de Curadoria das Fontes

### Objetivo

Identificar quais fontes eram mais relevantes para os objetivos do projeto.

### Prompt

> Analise todas as fontes disponíveis neste notebook e selecione de 3 a 5 fontes mais relevantes para um estudo introdutório e profissional sobre Massoterapia.
>
> Priorize fontes acadêmicas, científicas, institucionais ou de autores reconhecidos.
>
> Para cada fonte selecionada, informe:
>
> - título;
> - autor ou instituição;
> - tipo de fonte;
> - principais temas abordados;
> - contribuição para o estudo;
> - limitações.
>
> Ao final, apresente um ranking das fontes selecionadas e justifique a ordem de relevância.

### Resultado esperado

Criar uma base de fontes confiável e diversificada para o projeto.

---

# 2. Prompt de Anatomia e Cinesiologia

### Objetivo

Compreender os principais conhecimentos anatômicos relacionados à Massoterapia.

### Prompt

> Com base exclusivamente nas fontes disponíveis neste notebook, explique os principais conhecimentos de anatomia e cinesiologia importantes para a Massoterapia.
>
> Organize a resposta em:
>
> 1. posição anatômica;
> 2. planos e eixos;
> 3. ossos;
> 4. músculos;
> 5. articulações;
> 6. movimentos;
> 7. anatomia palpatória;
> 8. relação entre anatomia, movimento e Massoterapia.
>
> Para cada informação:
> - indique a fonte;
> - diferencie informação diretamente apresentada pela fonte de síntese do NotebookLM;
> - informe quando houver informação presente em apenas uma fonte;
> - identifique lacunas.
>
> Não utilize informações externas ao notebook.

---

# 3. Prompt sobre Manobras

### Objetivo

Identificar as principais manobras e técnicas mencionadas nas fontes.

### Prompt

> Com base exclusivamente nas fontes disponíveis neste notebook, identifique as principais manobras e técnicas de Massoterapia mencionadas.
>
> Para cada uma, informe:
>
> - nome;
> - conceito apresentado pelas fontes;
> - finalidade ou efeitos mencionados;
> - cuidados ou contraindicações citados;
> - fonte.
>
> Não crie passo a passo de execução caso ele não esteja presente nas fontes.
>
> Diferencie claramente informações diretamente apresentadas pelas fontes de sínteses realizadas pelo NotebookLM.
>
> Ao final, identifique quais técnicas possuem detalhamento prático suficiente e quais apresentam lacunas.

### Principal aprendizado

As fontes apresentaram nomes e características gerais de diversas técnicas, mas não forneceram detalhamento suficiente para ensinar a execução completa das manobras.

---

# 4. Prompt sobre Indicações, Contraindicações e Segurança

### Objetivo

Identificar situações de segurança relacionadas ao atendimento.

### Prompt

> Com base exclusivamente nas fontes disponíveis neste notebook, analise as indicações, contraindicações, precauções e sinais de alerta relacionados à Massoterapia.
>
> Organize em:
>
> 1. indicações;
> 2. contraindicações;
> 3. situações que exigem adaptação;
> 4. sinais de alerta;
> 5. situações que exigem encaminhamento ou avaliação profissional.
>
> Para cada item:
> - indique a fonte;
> - diferencie fato de síntese;
> - não crie classificações que não estejam presentes nas fontes;
> - sinalize informações que aparecem em apenas uma fonte.
>
> Não utilize conhecimento externo.

### Principal aprendizado

A IA conseguiu organizar informações dispersas, mas algumas classificações foram sínteses do próprio NotebookLM e não deveriam ser tratadas automaticamente como classificações oficiais.

---

# 5. Prompt sobre Drenagem Linfática Manual

### Objetivo

Investigar o que as fontes realmente apresentavam sobre Drenagem Linfática Manual.

### Prompt

> Com base exclusivamente nas fontes disponíveis neste notebook, analise o conteúdo relacionado à Drenagem Linfática Manual.
>
> Organize em:
>
> 1. definição;
> 2. sistema linfático;
> 3. objetivos;
> 4. indicações;
> 5. contraindicações;
> 6. cuidados;
> 7. diferenças entre drenagem corporal e facial;
> 8. técnicas e manobras mencionadas;
> 9. pressão, ritmo, direção e sequência;
> 10. lacunas das fontes.
>
> Não invente informações.
>
> Se as fontes não apresentarem detalhes técnicos, informe explicitamente essa ausência.
>
> Diferencie informações diretamente apresentadas pelas fontes de sínteses do NotebookLM.

### Principal aprendizado

Conhecer a anatomia do sistema linfático não significa possuir conhecimento técnico suficiente para executar uma drenagem linfática.

---

# 6. Prompt sobre Massagem Facial, Lifting e Kobido

### Objetivo

Investigar a presença e o nível de detalhamento das técnicas faciais.

### Prompt

> Com base exclusivamente nas fontes disponíveis neste notebook, analise o conteúdo relacionado a:
>
> - massagem facial;
> - drenagem facial;
> - lifting facial manual;
> - Shiatsu facial;
> - Kobido.
>
> Para cada técnica, informe:
>
> - definição;
> - objetivos;
> - indicações;
> - contraindicações;
> - anatomia relacionada;
> - manobras;
> - pressão;
> - ritmo;
> - sequência;
> - formação necessária;
> - fonte.
>
> Não invente informações.
>
> Caso uma técnica seja apenas mencionada nas fontes, informe que existe uma lacuna de conteúdo.
>
> Diferencie claramente fatos, sínteses e lacunas.

### Principal aprendizado

As fontes apresentaram algumas técnicas faciais, mas não forneceram conteúdo técnico suficiente para construir protocolos completos.

---

# 7. Prompt sobre Formação Profissional e Mercado

### Objetivo

Investigar formação, competências, possibilidades de atuação e mercado de trabalho.

### Prompt

> Com base exclusivamente nas fontes disponíveis neste notebook, analise o que elas apresentam sobre formação profissional e mercado de trabalho na área de Massoterapia.
>
> Organize a resposta em:
>
> 1. Formação profissional em Massoterapia
> 2. Curso Técnico em Massoterapia
> 3. Carga horária e requisitos de formação
> 4. Conteúdos e competências esperadas na formação
> 5. Técnicas que aparecem nas matrizes ou programas de formação
> 6. Biossegurança e ética profissional
> 7. Possibilidades de atuação profissional
> 8. Atuação em clínicas, spas, estética, empresas, atendimento domiciliar e serviço público, somente quando mencionadas nas fontes
> 9. Mercado de trabalho
> 10. Limites das informações disponíveis
>
> Para cada informação:
> - indique a fonte;
> - diferencie claramente informação diretamente apresentada pela fonte de interpretação ou síntese do NotebookLM;
> - informe quando a informação estiver presente em apenas uma fonte;
> - sinalize divergências entre as fontes;
> - identifique lacunas do acervo.
>
> Não invente requisitos profissionais.
>
> Não afirme que determinada formação é obrigatória se as fontes não sustentarem essa afirmação.
>
> Não confunda profissão regulamentada, curso técnico, curso livre e especialização.
>
> Não utilize informações externas ao conteúdo do notebook.
>
> Quando houver informações normativas ou legais, sinalize que elas devem ser verificadas em fontes oficiais atualizadas.

---

# 🔄 Evolução dos Prompts

Durante o projeto, os prompts foram ficando mais específicos.

Inicialmente, a pesquisa poderia resultar apenas em um resumo dos conteúdos.

Com o refinamento dos prompts, passaram a ser solicitadas informações como:

- origem da informação;
- fonte correspondente;
- distinção entre fato e interpretação;
- informações de fonte única;
- divergências;
- lacunas;
- necessidade de verificação externa.

Essa evolução tornou a pesquisa mais crítica e reduziu o risco de tratar uma resposta gerada pela IA como se fosse automaticamente uma informação comprovada.

---

# 🧠 Estratégias de Prompt Engineering utilizadas

## 1. Restrição de fontes

Foi utilizada repetidamente a instrução:

> "Com base exclusivamente nas fontes disponíveis neste notebook..."

Isso reduziu a possibilidade de incorporar conhecimento externo sem identificação.

## 2. Separação entre fato e síntese

Os prompts passaram a solicitar explicitamente:

> "Diferencie informação diretamente apresentada pela fonte de síntese do NotebookLM."

## 3. Identificação de lacunas

Foi solicitado que a IA informasse quando o acervo não possuía informações suficientes.

## 4. Identificação de fonte única

Foi solicitado que informações encontradas em apenas uma fonte fossem sinalizadas.

## 5. Verificação externa

Informações legais, regulatórias e normativas foram marcadas como informações que necessitam de consulta a fontes oficiais atualizadas.

---

# 📌 Conclusão

O processo demonstrou que a qualidade da resposta depende não apenas da ferramenta utilizada, mas também da forma como a pergunta é estruturada.

O refinamento dos prompts permitiu transformar o NotebookLM em uma ferramenta de análise e auditoria das fontes, e não apenas em um gerador de resumos.
