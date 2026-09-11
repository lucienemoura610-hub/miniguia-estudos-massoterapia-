# 🩹 Cicatrizes do Processo e Aprendizados

## 1. Contexto

Durante a construção do Mini Guia de Estudos em Massoterapia, o NotebookLM foi utilizado para analisar as fontes selecionadas e responder a diferentes perguntas sobre o tema.

O processo mostrou que elaborar bons prompts é tão importante quanto escolher uma boa ferramenta de Inteligência Artificial.

Além das respostas obtidas, foram registradas limitações, lacunas e situações em que a IA poderia gerar interpretações além do que estava efetivamente presente nas fontes.

---

## 2. Primeira cicatriz: separar fato de interpretação

### O que aconteceu?

Algumas respostas apresentavam informações diretamente encontradas nas fontes junto com sínteses produzidas pelo NotebookLM.

### Problema identificado

Sem uma solicitação específica, poderia ser difícil distinguir:

- o que estava escrito na fonte;
- o que era uma interpretação;
- o que era uma organização feita pela IA.

### Ajuste realizado

Os prompts passaram a solicitar explicitamente:

> "Diferencie informação diretamente apresentada pela fonte de síntese ou interpretação do NotebookLM."

### Aprendizado

Uma resposta bem escrita não significa necessariamente que todas as informações apresentadas sejam fatos diretamente sustentados pelas fontes.

---

## 3. Segunda cicatriz: não preencher lacunas com conhecimento externo

### O que aconteceu?

Ao pesquisar as manobras de Massoterapia, percebeu-se que as fontes apresentavam nomes e características gerais das técnicas, mas não forneciam passo a passo completo.

### Problema identificado

Existia o risco de solicitar à IA uma explicação prática e receber informações que não estavam presentes no acervo.

### Ajuste realizado

Foi incluída nos prompts a instrução:

> "Não invente informações e não utilize conhecimento externo."

Também foi solicitado que a IA identificasse explicitamente quando o acervo não possuía determinada informação.

### Aprendizado

Uma lacuna da fonte deve ser apresentada como lacuna, e não preenchida automaticamente pela Inteligência Artificial.

---

## 4. Terceira cicatriz: efeitos gerais x efeitos específicos

### O que aconteceu?

Durante a análise das manobras, foi identificado que alguns efeitos gerais atribuídos à Massoterapia poderiam ser interpretados como efeitos específicos de determinada técnica.

### Problema identificado

Uma associação indireta poderia ser apresentada como se houvesse evidência específica para uma determinada manobra.

### Ajuste realizado

Os prompts passaram a solicitar a diferenciação entre:

- efeitos gerais da Massoterapia;
- efeitos específicos de uma técnica;
- sínteses produzidas pela IA.

### Aprendizado

É necessário verificar se a fonte realmente associa determinado efeito à técnica analisada.

---

## 5. Quarta cicatriz: classificações criadas pela IA

### O que aconteceu?

Ao pesquisar contraindicações, o NotebookLM organizou informações encontradas nas fontes em categorias como contraindicações absolutas e relativas.

### Problema identificado

Essa organização poderia parecer uma classificação oficial, mesmo quando resultava da combinação de informações presentes em diferentes fontes.

### Ajuste realizado

Foi solicitado que o NotebookLM identificasse quando determinada classificação fosse uma síntese própria.

### Aprendizado

Uma classificação criada pela IA não deve ser tratada automaticamente como classificação oficial da literatura.

---

## 6. Quinta cicatriz: anatomia não substitui treinamento prático

### O que aconteceu?

Na pesquisa sobre Drenagem Linfática Manual, o acervo apresentava informações sobre o sistema linfático, mas não apresentava detalhes suficientes sobre a execução da técnica.

### Problema identificado

Conhecer a anatomia do sistema linfático não significa possuir conhecimento técnico suficiente para executar uma drenagem linfática.

### Ajuste realizado

O prompt passou a investigar separadamente:

- anatomia;
- objetivos;
- indicações;
- contraindicações;
- pressão;
- ritmo;
- direção;
- sequência;
- manobras.

### Aprendizado

Conhecimento teórico e domínio técnico são competências diferentes.

---

## 7. Sexta cicatriz: lacuna nas técnicas faciais

### O que aconteceu?

Massagem facial, drenagem facial, lifting manual e Kobido apareceram nas fontes, mas sem detalhamento técnico suficiente.

### Problema identificado

A simples presença do nome de uma técnica não significa que o acervo contenha conhecimento suficiente para ensinar sua execução.

### Ajuste realizado

Foi solicitado que o NotebookLM verificasse individualmente:

- definição;
- objetivos;
- indicações;
- contraindicações;
- anatomia;
- manobras;
- pressão;
- ritmo;
- sequência;
- formação.

### Aprendizado

Quando a fonte apenas menciona uma técnica, essa menção deve ser registrada como tal.

---

## 8. Sétima cicatriz: informações legais precisam de verificação

### O que aconteceu?

Na pesquisa sobre formação e mercado de trabalho apareceram informações relacionadas a legislação, requisitos educacionais, concursos e regulamentação profissional.

### Problema identificado

Informações legais e regulatórias podem sofrer alterações e possuem contexto jurídico específico.

### Ajuste realizado

Os prompts passaram a exigir que informações normativas fossem sinalizadas como informações que precisam de verificação em fontes oficiais atualizadas.

### Aprendizado

A Inteligência Artificial pode ajudar a organizar uma pesquisa jurídica ou regulatória, mas não deve ser tratada como substituta da consulta à fonte oficial vigente.

---

## 9. O que funcionou melhor nos prompts

Algumas estratégias apresentaram resultados especialmente úteis:

### Restringir o conjunto de fontes

> "Com base exclusivamente nas fontes disponíveis neste notebook..."

### Pedir identificação da fonte

> "Para cada informação, indique a fonte."

### Separar fato e síntese

> "Diferencie claramente informação diretamente apresentada pela fonte de interpretação ou síntese."

### Solicitar lacunas

> "Identifique o que as fontes não apresentam."

### Proibir invenções

> "Não invente informações."

### Solicitar verificação externa

> "Quando houver informações normativas ou legais, sinalize que devem ser verificadas em fontes oficiais atualizadas."

---

## 10. Evolução do processo

O processo de pesquisa evoluiu de perguntas mais amplas para prompts mais estruturados.

### Inicialmente

O objetivo era obter informações sobre o tema.

### Durante o processo

Passou-se a investigar:

- origem da informação;
- fonte;
- nível de detalhamento;
- divergências;
- lacunas;
- interpretações da IA.

### Resultado

O NotebookLM passou a ser utilizado não apenas para gerar respostas, mas também para auxiliar na análise crítica do próprio conteúdo produzido.

---

## 11. Principais aprendizados

### Aprendizado 1

**Prompt melhor estruturado gera uma análise mais controlada.**

### Aprendizado 2

**A IA deve ser tratada como ferramenta de apoio, não como fonte primária.**

### Aprendizado 3

**Nem toda informação apresentada em uma resposta está necessariamente explícita nas fontes.**

### Aprendizado 4

**Reconhecer uma lacuna é melhor do que preenchê-la sem evidência.**

### Aprendizado 5

**Fontes diferentes podem apresentar perspectivas diferentes sobre o mesmo tema.**

### Aprendizado 6

**Informações legais e regulatórias precisam de verificação em fontes oficiais.**

### Aprendizado 7

**Conhecimento teórico não substitui treinamento prático supervisionado.**

---

## 12. Conclusão

As "cicatrizes" do projeto mostram que o processo de pesquisa foi também um processo de aprendizagem sobre o uso responsável da Inteligência Artificial.

Os principais avanços não foram apenas os conteúdos encontrados, mas a capacidade de:

- questionar respostas;
- identificar limitações;
- verificar a origem das informações;
- reconhecer interpretações;
- identificar lacunas;
- melhorar os prompts;
- evitar conclusões não sustentadas pelas fontes.

Dessa forma, o projeto utilizou o NotebookLM como ferramenta de pesquisa, organização e análise crítica, mantendo as fontes como base principal do conhecimento.
