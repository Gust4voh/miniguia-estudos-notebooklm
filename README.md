# Caderno Temático de Java com NotebookLM: Aplicando Engenharia de Prompt para Criação de um Tutor Inteligente

## Contexto

Este projeto demonstra a utilização do NotebookLM como uma ferramenta de apoio aos estudos da linguagem Java. Para isso, foram utilizados materiais de referência sobre conceitos fundamentais da linguagem, permitindo que a IA respondesse perguntas, gerasse explicações e produzisse exemplos de código.

O principal objetivo do projeto foi aplicar técnicas de Engenharia de Prompt para compreender como diferentes estratégias de elaboração de prompts influenciam diretamente a qualidade das respostas produzidas pelo NotebookLM.



# Objetivos

- Explorar os recursos do NotebookLM como ferramenta de aprendizagem ativa.
- Construir um tutor de Java baseado em materiais de referência.
- Gerar exemplos de código fundamentados nas fontes fornecidas.
- Aplicar técnicas de Engenharia de Prompt para obter respostas mais precisas e organizadas.
- Avaliar como o refinamento dos prompts impacta a qualidade das respostas.



# Materiais Utilizados

Para compor a base de conhecimento do NotebookLM, foram utilizados vídeos disponíveis no YouTube abordando os principais fundamentos da linguagem Java.

Os conteúdos contemplam temas como:

- Sintaxe Básica;
- Estruturas de Controle;
- Conversão de Tipos;
- Programação Orientada a Objetos;
- Construtores e Encapsulamento;
- Abstração;
- Herança e Polimorfismo;
- Collections;
- Boas Práticas.

## Fontes

- [POO como Você NUNCA VIU | Java 25 - Cod3r Cursos](https://www.youtube.com/watch?v=h3YCbhPqbeU)

- [Como sair do ZERO em JAVA em 1h com kipperdev - Rocketseat](https://www.youtube.com/watch?v=EpXYPB1rv4w)

- [Curso de Programação Java para Iniciantes | Fundamentos + Programação Orientada a Objetos - Fernanda Kipper](https://www.youtube.com/watch?v=nODe5lFcGpg)


# Estratégia de Engenharia de Prompt

Durante o desenvolvimento do projeto foi utilizada uma abordagem iterativa para construção dos prompts.

Em vez de utilizar apenas uma instrução simples, os prompts foram refinados progressivamente através da aplicação de técnicas de Engenharia de Prompt, como definição de contexto, especificação do público-alvo, aplicação de restrições e organização do formato esperado da resposta.

O objetivo foi analisar como pequenas modificações influenciavam a qualidade das respostas produzidas pelo NotebookLM.


# Processo de Refinamento dos Prompts

Foi utilizada a mesma tarefa durante todo o experimento: solicitar uma explicação sobre Herança em Java acompanhada de um exemplo de código.

## 1. Prompt inicial

**Objetivo:** avaliar a resposta padrão do NotebookLM.

```text
Gerar um exemplo de código sobre Herança em Java.
```


## 2. Definição de contexto

**Objetivo:** atribuir um papel ao modelo, direcionando a forma como a resposta seria construída.

```text
Você é um professor de Java.

Explique Herança em Java e gere um exemplo.
```

## 3. Definição do público-alvo

**Objetivo:** adaptar a linguagem para estudantes iniciantes.

```text
Você é um professor de Java.

Explique Herança para um estudante iniciante.
```

## 4. Aplicação de restrições

**Objetivo:** limitar o tamanho do exemplo de código, tornando a resposta mais objetiva.

```text
Você é um professor de Java.

Explique Herança para um estudante iniciante.

O exemplo deve possuir no máximo 40 linhas.
```

## 5. Estruturação da resposta

**Objetivo:** organizar melhor o conteúdo apresentado.

```text
Você é um professor de Java.

Explique Herança para um estudante iniciante.

O exemplo deve possuir no máximo 40 linhas.

Utilize a seguinte estrutura:

- Conceito
- Quando utilizar
- Vantagens
- Exemplo

Ao final apresente uma tabela contendo:

- Conceito
- Descrição
- Exemplo
```

---

## Resultados Obtidos

| Etapa | Técnica aplicada | Resultado observado |
|-------|------------------|---------------------|
| 1 | Prompt simples | Resposta correta, porém genérica. |
| 2 | Definição de contexto | Explicação mais didática. |
| 3 | Público-alvo | Linguagem simplificada para iniciantes. |
| 4 | Restrições | Código mais objetivo e direto. |
| 5 | Estrutura da resposta | Resposta organizada e de fácil consulta. |

# Dificuldades Encontradas

Durante os testes foi possível observar algumas situações que exigiram refinamento dos prompts.

- Prompts muito genéricos geravam respostas amplas e pouco direcionadas.
- A ausência de definição do público-alvo fazia com que as respostas fossem excessivamente técnicas.
- Sem especificar uma estrutura de saída, o conteúdo era apresentado de forma pouco organizada.
- A aplicação de restrições contribuiu para exemplos mais objetivos e adequados ao contexto do estudo.

Essas observações reforçam a importância da Engenharia de Prompt para orientar modelos de linguagem a produzirem respostas mais úteis.

# Prompt Final

Após o refinamento dos prompts, foi utilizada a seguinte instrução para gerar um material consolidado de estudos.

```text
Com base exclusivamente nas fontes adicionadas ao NotebookLM, elabore um miniguia de estudos sobre Java contendo:

- Resumos estruturados dos principais assuntos;
- Um glossário com os conceitos mais importantes;
- Um conjunto de prompts reutilizáveis para futuras revisões.

Organize a resposta utilizando títulos, subtítulos e listas para facilitar a consulta.
```

# Miniguia de Estudo

Como resultado final, o NotebookLM consolidou os conteúdos estudados em um único material de consulta rápida.

**Observação**: Os resumos, glossário e prompts reutilizáveis apresentados a seguir foram gerados pelo NotebookLM a partir das fontes listadas neste repositório, após o processo de refinamento dos prompts descrito anteriormente.

## Resumos Estruturados

### Fundamentos do Java

- Java utiliza a JVM (Java Virtual Machine), permitindo que aplicações sejam executadas em diferentes sistemas operacionais.
- A linguagem possui tipagem forte, proporcionando maior segurança durante o desenvolvimento.
- O JDK reúne todas as ferramentas necessárias para desenvolvimento, compilação e execução de aplicações Java.

### Programação Orientada a Objetos

- Classes definem atributos e comportamentos de um objeto.
- Objetos representam instâncias de uma classe.
- A Herança permite reutilização de código através da relação entre superclasses e subclasses.
- O Polimorfismo possibilita diferentes implementações para um mesmo comportamento.
- O Encapsulamento protege os dados utilizando modificadores de acesso.

### Modelagem e Boas Práticas

- Modelos ricos concentram regras de negócio dentro das próprias entidades.
- Records simplificam a criação de objetos imutáveis.
- Interfaces promovem desacoplamento entre componentes da aplicação.

## Glossário

| Conceito | Definição |
|----------|-----------|
| JVM | Máquina Virtual responsável pela execução das aplicações Java. |
| Bytecode | Código intermediário gerado pelo compilador Java. |
| JDK | Kit de desenvolvimento utilizado para criar aplicações Java. |
| Classe | Modelo utilizado para criação de objetos. |
| Objeto | Instância de uma classe. |
| Herança | Reutilização de atributos e métodos entre classes. |
| Polimorfismo | Permite diferentes implementações para um mesmo comportamento. |
| Interface | Contrato que define métodos que uma classe deve implementar. |
| Classe Abstrata | Classe utilizada como base para especializações. |
| Encapsulamento | Técnica utilizada para proteger os dados de uma classe. |

## Prompts Reutilizáveis

### Explicação de Conceitos

```text
Explique o conceito de [TEMA] para um estudante iniciante.

Apresente:

- definição;
- quando utilizar;
- vantagens;
- exemplo comentado.
```

### Comparação entre Conceitos

```text
Compare [CONCEITO A] e [CONCEITO B].

Explique:

- diferenças;
- vantagens;
- desvantagens;
- casos de uso.
```

### Geração de Código

```text
Gere um exemplo de código sobre [TEMA].

Explique linha por linha e destaque as boas práticas utilizadas.
```

### Exercícios

```text
Crie cinco exercícios sobre [TEMA] em Java.

Apresente também o gabarito comentado.
```

### Revisão de Código

```text
Analise o código abaixo.

Identifique:

- boas práticas;
- problemas encontrados;
- possíveis melhorias;
- versão refatorada.
```

# Conclusão

O experimento demonstrou que pequenas alterações na elaboração dos prompts influenciam significativamente a qualidade das respostas produzidas pelo NotebookLM.

A aplicação de técnicas como definição de contexto, especificação do público-alvo, aplicação de restrições e estruturação da saída resultou em respostas mais organizadas, didáticas e alinhadas ao objetivo proposto.

Além disso, o NotebookLM mostrou-se uma ferramenta eficiente para organizar conteúdos de estudo, sintetizar informações provenientes de diferentes fontes e produzir materiais de revisão, como resumos, glossários e prompts reutilizáveis. Dessa forma, foi possível compreender, na prática, como a Engenharia de Prompt potencializa o uso de modelos de IA como apoio ao aprendizado.
