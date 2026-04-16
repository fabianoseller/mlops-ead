# mlops-ead

# DataOps e MLOps: O Coração da Estratégia de Dados

Em um mundo cada vez mais orientado por dados e impulsionado pela inteligência artificial, a gestão eficaz dos processos de dados e modelos de aprendizado de máquina é essencial para o sucesso de qualquer organização. É nesse contexto que entram em cena dois conceitos fundamentais: **DataOps** e **MLOps**.

---

## A Evolução da Gestão de Dados e IA

DataOps e MLOps são abordagens revolucionárias que buscam unir a **engenharia de dados** e o **desenvolvimento de modelos de machine learning** em um ecossistema coeso e altamente eficiente. Eles representam a evolução natural da gestão de dados, oferecendo:

* **Velocidade:** Entrega de projetos de maneira mais rápida.
* **Consistência:** Processos padronizados e repetíveis.
* **Confiabilidade:** Resultados consistentes e seguros.

---

### Objetivos do Módulo

Este módulo tem como objetivo explorar os fundamentos e princípios subjacentes a DataOps e MLOps. Vamos mergulhar nas melhores práticas para o ciclo de vida de dados e modelos, abrangendo:

1.  **Aquisição e Limpeza:** O tratamento inicial dos dados.
2.  **Implantação:** Colocando modelos em produção de forma escalável.
3.  **Monitoramento:** Garantindo a performance contínua.

> **Insight:** Ao longo deste curso, você entenderá como essas abordagens revolucionárias podem impulsionar a inovação, aumentar a eficiência operacional e garantir a governança dos dados e modelos em sua organização.

---


# Princípios

##Satisfação contínua do cliente: devem ser feitas entregas de valor, ou seja, que agreguem ao cliente e de forma contínua. Podem ser dados brutos para uma futura análise, dados agregados, relatórios ou até mesmo pipelines de dados;
Foco em análises relevantes: quando alguma análise ou insight for solicitado, ter foco naqueles que sejam úteis para o cliente;
Abraçar a mudança: é sempre importante considerar a necessidade dos clientes;
Ser coletivo com auto-organização: equipes de dados com diversos papéis trazem diversidade de ideias, ferramentas, arquiteturas e novas possibilidades. Acredita-se que dando liberdade para as equipes tomarem as melhores decisões elas poderão extrair os melhores qualidades/características de cada participante;
Interações diárias: interações diárias facilitam a comunicação e resolução de incidentes;
Redução do heroísmo: com as possibilidades de resolução dos problemas e a diversidade de problemas, as equipes devem focar em resolver um problema por vez, evitando o heroísmo de tentar resolver todos de uma vez e acabar não conseguindo sair do lugar;

## Ter reprodutibilidade: é imprescindível que todos os processos sejam reprodutíveis para que em casos de falhas, o artefato de dado possa ser gerado novamente;
Qualidade: a qualidade das entregas deve ser um dos grandes focos, evitando qualquer tipo de retrabalho, principalmente pelo custo envolvido. Exemplo: garantindo a qualidade de um pipeline de dados, evita o reprocessamento, principalmente quando o dado em questão for de um volume elevado;
Aplicar monitoramento: monitorando os processos de dados é possível corrigir alguma falha antes que o cliente perceba, garantindo a qualidade do dado entregue;
Melhorar o cycle time: ao se utilizar os princípios anteriores, o tempo de entrega acaba reduzindo como consequência da qualidade das entregas e dos próprios processos.
 

Embora haja algumas semelhanças entre DataOps e MLOps, como o uso de metodologias ágeis e a entrega contínua, eles têm objetivos e fluxos de trabalho diferentes. O DataOps se concentra na gestão de dados em toda a organização, enquanto o MLOps se concentra na implantação e gerenciamento de modelos de aprendizado de máquina em produção. Assista a seguir um vídeo abordando os conceitos deste módulo.

### Sua Jornada

Preparando-o para uma jornada emocionante e desafiadora, este módulo fornecerá os fundamentos e conhecimentos que o capacitarão a navegar com confiança pelo complexo cenário de **DataOps** e **MLOps**. 

Este é o primeiro passo para dominar as disciplinas essenciais que moldarão o futuro da análise de dados e da inteligência artificial nas empresas.

*******************

# DataOps: Data Operations

O **DataOps** é o termo que remete às operações com dados possuindo origem baseada em DevOps. O conceito nasceu como um sistema de melhores práticas, mas amadureceu para uma abordagem funcional completa para lidar com a análise de dados.

---

## 🚀 Princípios do DataOps

Para uma implantação de sucesso, seguimos uma sequência de princípios norteadores:

* **Satisfação contínua do cliente:** Entregas de valor constantes (dados brutos, relatórios ou pipelines).
* **Foco em análises relevantes:** Priorizar insights que sejam realmente úteis para o negócio.
* **Abraçar a mudança:** Flexibilidade para atender às necessidades dinâmicas dos clientes.
* **Auto-organização coletiva:** Equipes multidisciplinares com liberdade para decidir as melhores ferramentas e arquiteturas.
* **Interações diárias:** Comunicação constante para agilizar a resolução de incidentes.
* **Redução do heroísmo:** Focar em resolver um problema por vez de forma estruturada, em vez de tentar "salvar o mundo" sozinho.
* **Reprodutibilidade:** Processos devem ser replicáveis para garantir a recuperação em caso de falhas.
* **Qualidade:** Foco total em evitar retrabalho e custos desnecessários em grandes volumes de dados.
* **Monitoramento aplicado:** Identificar e corrigir falhas antes que o cliente perceba.
* **Melhoria do Cycle Time:** Redução natural do tempo de entrega como consequência da qualidade e eficiência.

---

## 📊 Por que aplicar DataOps?

A cultura DataOps traz benefícios estratégicos claros:
1.  **Agilidade:** Entregas incrementais e produtivas.
2.  **Tempo Real:** Insights rápidos para tomadas de decisão informadas.
3.  **Democratização:** Facilita o acesso aos dados para as equipes de negócio.
4.  **Alinhamento:** Une as expectativas de Negócios e TI.

---

## 🔄 Fenômenos de Drift (Desvio)

Quando trabalhamos com modelos em produção, os dados podem mudar. Entender os tipos de *Drift* é crucial para manter a eficácia da IA.

### 1. Data Drift (Desvio de Dados)
Ocorre quando as propriedades estatísticas dos **dados de entrada** mudam ao longo do tempo. O modelo deixa de generalizar bem porque os dados que ele recebe agora são diferentes dos dados com os quais ele aprendeu.
* **Solução:** Monitoramento constante, reamostragem, atualização de pesos ou atualização da base de treino.

### 2. Concept Drift (Desvio de Conceito)
Ocorre quando a **relação entre os dados e a variável alvo** muda. O comportamento do mundo mudou (ex: mudança no perfil de consumo devido a uma crise econômica).
* **Solução:** Geralmente exige refazer o modelo completamente, coletar novos dados e redefinir variáveis.

| Tipo de Drift | O que muda? | Foco da Solução |
| :--- | :--- | :--- |
| **Data Drift** | Dados de Entrada ($X$) | Atualização de dados / Reamostragem |
| **Concept Drift** | Relação ($X \rightarrow y$) | Retreinamento total / Novo Modelo |

---

> **Nota:** Enquanto o **DataOps** foca na gestão de dados em toda a organização, o **MLOps** foca especificamente no gerenciamento do ciclo de vida dos modelos de Machine Learning.
