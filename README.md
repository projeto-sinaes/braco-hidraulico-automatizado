
# Braço Hidráulico Automatizado

> Projeto vinculado ao SINAES – Soluções Inclusivas para Necessidades de Aprendizagem Específicas.

## Apresentação

O estudo da Hidrostática e da Hidrodinâmica na física mecânica frequentemente esbarra na barreira da abstração teórica, pois conceitos fundamentais como o Princípio de Pascal, vazão e multiplicação de força são ensinados apenas por meio de equações estáticas no quadro, limitando a compreensão dos alunos sobre como a pressão do fluido se converte em trabalho mecânico real. Essa abordagem puramente teórica gera desinteresse e dificulta a visualização prática de sistemas hidráulicos industriais, limitando a capacidade dos estudantes de integrar conceitos de física com aplicações reais de automação. Como resposta a esse problema, propõe-se o desenvolvimento de um Braço Hidráulico Automatizado construído com peças modulares em impressão 3D e corte CNC, cujas articulações se movimentam por meio de seringas atuando como pistões, controladas pelo acionamento de mini bombas d'água gerenciadas por um microcontrolador ESP32. Essa solução é altamente relevante pois une a mecânica dos fluidos à engenharia mecatrônica e ao Desenho Universal para a Aprendizagem (DUA), permitindo que estudantes com diferentes perfis manipulem variáveis físicas tangíveis e observem em tempo real como o controle do fluxo de água se transforma imediatamente em movimento articulado, preciso e autônomo na bancada.

## Objetivo geral e objetivos específicos

### Objetivo geral

Desenvolver um protótipo funcional capaz de converter o fluxo de fluidos em movimentos articulados precisos para demonstrar empiricamente os princípios da hidrostática e da automação industrial na bancada.

### Objetivos específicos

Para alcançar esses objetivos, o projeto prevê o desenvolvimento do firmware no ESP32 focado no controle de velocidade e sentido de rotação das mini bombas d'água via PWM e pontes H, em paralelo ao design mecânico em CAD e fabricação da estrutura articulada por meio de impressão 3D e corte CNC para assegurar o acoplamento perfeito das seringas como pistões. O protótipo terá seu circuito de fluidos e a repetibilidade dos movimentos validados inicialmente em testes de bancada para garantir a precisão do sistema. Por fim, sua avaliação prática e documentação definitiva ocorrerão durante a feira de inovação IFTech, onde a interação direta de estudantes e visitantes com o dispositivo servirá como teste real de usabilidade da interface, robustez do hardware e eficácia pedagógica da automação.

## Público-alvo e possibilidades de aplicação

- **Público-alvo:** alunos do ensino médio e superior.
- **Áreas ou componentes curriculares:** Física e automação indústrial.]
- **Conteúdos favorecidos:** Princípio de Pascal, pressão hidrostática, vazão volumétrica, mecânica dos fluidos, transmissão de torque, circuitos hidráulicos e sistemas de potência.
- **Possibilidades de aplicação:** Aulas, oficinas, eventos e laboratórios.

## Resultados esperados

Espera-se desenvolver um protótipo funcional de um Braço Hidráulico Automatizado, construído com peças modulares em impressão 3D e corte CNC, integrado a um microcontrolador ESP32 com mini bombas d'água acionadas por pontes H e seringas operando como atuadores hidráulicos. Esse dispositivo favorecerá a aprendizagem ao materializar as leis da hidrostática e da hidrodinâmica em movimento físico real, permitindo que os estudantes visualizem a conversão de pressão e vazão em trabalho mecânico, consolidando a transição de conceitos abstratos de fluidos para dados empíricos tangíveis de forma multissensorial e intuitiva. Além disso, após sua validação e apresentação pública na **IX IFTECH**, o projeto possui alto potencial de replicação e compartilhamento, pois todo o código-fonte, esquemáticos eletrônicos e arquivos de modelagem digital serão disponibilizados de forma *open-source*, funcionando como um kit didático de baixo custo que pode ser facilmente adaptado, expandido ou reproduzido por outros laboratórios de ensino e estudantes.

## Fundamentação e integração de conhecimentos

### Conhecimentos curriculares relacionados ao projeto

Princípio de Pascal e transmissão de pressão em fluidos confinados, pressão hidrostática, relação entre força e área em atuadores hidráulicos, vazão volumétrica e velocidade de escoamento, conservação da energia aplicada a sistemas hidráulicos (Equação de Bernoulli), torque e equilíbrio estático de corpos rígidos em braços articulados, cinemática de sistemas rotacionais e lógica de automação sequencial aplicada a microcontroladores.

### Conhecimentos pedagógicos e metodológicos

- **O estudante poderá:** Movimentar as articulações do braço controlando o fluxo de água pelas bombas, tocar e manipular os componentes mecânicos tridimensionais, testar a garra e observar a resposta física imediata dos pistões de seringa à pressão exercida pelo fluido.
- **O material ajuda a compreender:** O Princípio de Pascal, a transmissão de pressão hidrostática em um fluido confinado, a relação de multiplicação de força baseada na área dos pistões, o conceito de vazão volumétrica regulando a velocidade de movimento e a aplicação prática de circuitos hidráulicos acionados por automação eletrônica.
- **A dificuldade que procura reduzir é:** A barreira de abstração de fórmulas estáticas da física de fluidos e a falta de percepção prática sobre como a energia hidráulica realiza trabalho mecânico, reduzindo o distanciamento entre a teoria matemática dos livros e a realidade operacional de sistemas automatizados e maquinários industriais.
- **O conteúdo será apresentado por meio de:** Objetos físicos tridimensionais, o movimento visível do fluido (tingido) preenchendo as mangueiras e seringas, cores contrastantes para identificar os eixos de rotação e o estímulo tátil do controle direto das variáveis de fluxo.
- **O estudante poderá demonstrar o que aprendeu por meio de:** Testes práticos repetíveis na bancada manipulando a carga de trabalho do braço, explicações lógicas da relação entre o tempo de acionamento das bombas e o deslocamento angular obtido, cálculos reais de pressão baseados na força exercida pela garra.

### Conhecimentos técnicos mobilizados

- **Programação:** Desenvolvimento do firmware no ESP32 focado na temporização precisa, gerenciando a velocidade e o tempo exato de acionamento de cada bomba para obter deslocamentos articulares coordenados.
- **Eletrônica:** Dimensionamento e montagem dos circuitos de potência utilizando pontes H, para controlar as bombas d'água
- **Automação:** trás técnologia indústrial para a sala de uma maneira fácil e compreensível.
- **Modelagem:** Empregada no design mecânico tridimensional (CAD) do braço articulado, os eixos de rotação, os alojamentos sob medida para as seringas e as garras de fixação das mangueiras do circuito hidráulico.
- **Impressão 3D:** Utilizada na manufatura aditiva das peças estruturais complexas previamente modeladas, os suportes dos pistões e seringas, garantindo leveza, encaixes precisos e flexibilidade para ajustes no design.
- **Corte CNC:** Usinagem de alta precisão de placas planas de MDF para a base principal de sustentação da torre do braço e as partes do braço em si.


### Integração dos conhecimentos na solução

A transformação da barreira de abstração da mecânica dos fluidos em uma solução concreta ocorreu pela articulação direta entre a física, a pedagogia e a engenharia mecatrônica. Os **conhecimentos curriculares** de hidrostática e hidrodinâmica definiram as diretrizes matemáticas do projeto, como a pressão necessária para mover os pistões de seringa e a vazão volumétrica das bombas para regular a velocidade do braço. Os **conhecimentos pedagógicos** baseados no DUA (Desenho Universal para a Aprendizagem) orientaram a criação de uma experiência totalmente interativa e tátil, substituindo equações teóricas abstratas pelo controle visível do fluxo de água que move a estrutura física, eliminando o desinteresse dos estudantes. Viabilizando essa proposta, os **conhecimentos técnicos** materializaram a solução: a **modelagem CAD** e o **corte CNC** estruturaram uma base estável para suportar o torque do sistema, a **impressão 3D** fabricou articulações sob medida, a **eletrônica** forneceu a potência necessária via pontes H para controlar as mini bombas d'água, e a **programação** no ESP32 unificou todo o conjunto por meio da **automação**, permitindo que o estudante controle e observe a transmissão de forças em tempo real na bancada.

### Diferentes formas de aprendizagem

- **Formas de representação:** O conteúdo teórico de mecânica dos fluidos e automação deixa de ser puramente textual e simbólico para se manifestar de forma tridimensional e multissensorial. Os conceitos são apresentados visualmente pelo movimento macroscópico da água preenchendo as mangueiras e deslocando os êmbolos transparentes das seringas, de forma tátil pelas texturas diferenciadas das peças em impressão 3D e da base em MDF, e por meio de cores contrastantes que delimitam visualmente cada eixo de rotação e articulação do sistema.
- **Formas de participação e interação:** O estudante interage diretamente com o protótipo operando potenciômetros de controle de fluxo, manipulando fisicamente as cargas que a garra deve erguer e modificando as trajetórias de movimentação. O aprendizado ocorre por meio da exploração ativa, onde o aluno observa na hora a relação de causa e efeito: ao acionar uma bomba específica, ele vê o fluido se deslocar, sente o torque gerado na estrutura e compreende empiricamente o Princípio de Pascal em funcionamento na bancada.
- **Formas de ação e expressão:** Os estudantes possuem múltiplos caminhos para demonstrar o conhecimento adquirido, indo além das tradicionais avaliações escritas. Eles podem expressar o aprendizado programando uma nova sequência automatizada de movimentos no microcontrolador, realizando testes de bancada para medir o tempo que o fluido leva para deslocar a garra a uma determinada distância, explicando oralmente a física.

### Referências consultadas

HALLIDAY, David; RESNICK, Robert; WALKER, Jearl. Fundamentos de Física, Volume 2: Gravitação, Ondas e Termodinâmica (inclui Mecânica dos Fluidos). 10. ed. Rio de Janeiro: LTC, 2016.

ESPRESSIF SYSTEMS. ESP-IDF Programming Guide: Pulse Width Modulation (PWM) and MCPWM Drivers. Disponível em: https://docs.espressif.com/. Acesso em: abr. 2026.

## Percurso metodológico do projeto SINAES

Os projetos vinculados ao SINAES adotam como referência o Processo de Desenvolvimento de Protótipos Acadêmicos, metodologia sistematizada pela proponente a partir da experiência acumulada na orientação e no acompanhamento de projetos acadêmicos voltados à criação de materiais didáticos e protótipos tecnológicos. A metodologia foi construída com base em práticas aplicadas, observadas e progressivamente aperfeiçoadas em projetos anteriores. Sua finalidade é oferecer aos estudantes um percurso acessível para organizar a identificação do problema, o planejamento técnico, a construção, os testes e a documentação das soluções. Embora dialogue com princípios do Processo de Desenvolvimento de Produtos apresentado por Rozenfeld et al. (2006), o percurso adotado pelo SINAES possui finalidade e organização próprias, adequadas ao contexto educacional e ao desenvolvimento de protótipos acadêmicos. 

O Processo de Desenvolvimento de Protótipos Acadêmicos está organizado em quatro etapas: 
1. **Geração do Conceito:** compreender o problema ou desafio de aprendizagem, identificar o público e definir a ideia inicial, a finalidade e as características gerais da solução.
2. **Planejamento e Especificação:** organizar o desenvolvimento do projeto, definir responsabilidades, identificar capacitações necessárias e selecionar materiais, tecnologias, ferramentas e recursos, considerando requisitos, cronograma e orçamento.
3. **Desenvolvimento Incremental:** construir a solução em partes, módulos ou versões sucessivas, realizando testes durante o processo e registrando dificuldades, decisões e modificações.
4. **Validação e Aperfeiçoamento:** verificar o funcionamento técnico e a contribuição da solução para a aprendizagem, analisar sua utilização por diferentes públicos, incorporar melhorias e organizar a documentação necessária ao compartilhamento e à replicação.

Essas etapas constituem uma orientação geral, e não uma sequência rígida. Conforme as características e necessidades de cada projeto, poderão ocorrer simultaneamente, ser retomadas ou receber procedimentos complementares. As adaptações realizadas deverão ser justificadas e registradas pelas equipes, com o acompanhamento dos professores responsáveis. 

A adoção desse percurso comum busca: 
- auxiliar os estudantes na organização do desenvolvimento;
- facilitar o acompanhamento dos projetos;
- registrar decisões, dificuldades e alterações;
- favorecer a integração entre conhecimentos curriculares e técnicos;
- orientar os testes e o aperfeiçoamento das soluções;
- padronizar a documentação sem eliminar a autonomia das equipes;
- facilitar o compartilhamento e a replicação dos resultados.

## Cronograma das etapas do desenvolvimento

| Etapa do PDP | Período planejado | Período realizado | Atividades desenvolvidas | Alterações, retornos ou sobreposições |
|---|---|---|---|---|
| Geração do conceito | novembro/2025| novembro/2025 | Conversa com professor de física | definir a ideia inicial |
| Planejamento e especificação | maio/2026 | junho/2026 | desenvolvimento de esboços e reuniões com a equipe que está realizando o projeto | Definido que tipo de bomba d'água iria ser usado |
| Desenvolvimento incremental | segundo semestre 2026 |  | montagem do protótipo |  |
| Validação e aperfeiçoamento | segundo semestre 2026 |  | 	aperfeiçoamento do protótipo |  |

## Capacitações, tecnologias, materiais e orçamento

| Capacitação | Finalidade no projeto | Período | Situação |
|---|---|---|---|
| Aulas ESP-IDF | Introduzir e ensinar os alunos a programar o ESP32 por meio do VS Code usando a ESP-IDF | abril,maio/2026 | Concluída |
| Aula soldagem eletrônica | Ensinar a base da soldagem em componentes eletrônicos e placas de prototipação | junho/2026 | Concluída |
| Aula Impressão 3D | Ensinar fatiamento e comandos básicos com impressora 3D | junho/2026 | Concluída |
| Aula CNC | Ensinar a comandar e operar CNC | agosto/2026 | Prevista |

### Tecnologias, ferramentas e equipamentos

| Tecnologia, ferramenta ou equipamento | Finalidade no projeto | Forma de acesso |
|---|---|---|
| Impressora 3D | Impressão de partes do projeto | Disponível no campus |
| Fusion360 | Modelar as peças para impressão 3D ou corte CNC | Disponível no campus |
| CNC | Corte do MDF | Disponível no campus |
| VS Code | Programar usando a ESP-IDF por meio dele | Disponível sem custo |

### Materiais e orçamento

| Material ou componente | Quantidade | Finalidade | Disponibilidade | Valor estimado |
|---|---:|---|---|---:|
| ESP32 | 1 | Controle das bombas d'água, execução do código, integração do circuito | Adquirido na 1ª edição do projeto | |
| inserts de latão | 6 | possibilitar utilização de parafusos | Adquirido na 1ª edição do projeto |  |
| parafusos | 6 | prender a estruturas de PLA na madeira | Adquirido na 1ª edição do projeto |  |
| Filamento PLA | 300g | suportes para seringas, bombas e circuito | Adquirido na 1ª edição do projeto |  |
| Ponte H | 4 | Controle das bombas d'água | Adquirido na 1ª edição do projeto |  |
| Bomba d'água | 8 | Empurrar, mandar, ou puxar água das seringas | Adquirido na 1ª edição do projeto |  |
| Seringa | 4 | Funcionar como pistão | Adquirido na 1ª edição do projeto |  |
| Tubos de seringa | 2m | ligar seringas com bombas d'água | Adquirido na 1ª edição do projeto |  |
| Chapa de MDF | 1 | para a base e estruturas | Adquirido na 1ª edição do projeto |  |
| Potenciômetros | 4 | enviar sinais de controle, movimento | Adquirido na 1ª edição do projeto |  |
| **Total estimado** |  |  |  |  |

## Artefatos do projeto

| Artefato | Descrição | Formato ou localização | Situação |
|---|---|---|---|
| Apresentação do projeto | Braço Hidráulico Automatizado | [`apresentacao/`](apresentacao/) | Disponível |
| Código-fonte | Código de controle das bombas a partir dos comandos | [`codigos/`](codigos/) | Em elaboração |
| Modelo 3D | modelos de encaixes | [`modelos-3d/`](modelos-3d/) | Em elaboração |
| Imagens | Fotos do projeto funcionando | [`imagens/`](imagens/) | Previsto |
| Resultados | Exposição no IX IFTECH | [`resultados/`](resultados/) | Previsto |

> [!NOTE]
> **Possibilidades de replicação:** Ao término do projeto todos os materiais, modelos e códigos serão disponibilizados gratuitamente para replicação mediante a devida creditação, sem necessidade de licença ou autorização.
> **Créditos:** Informe a autoria dos arquivos, modelos, códigos, imagens e materiais externos utilizados.

## Produções e participação em eventos

- Inscrição na XIV IFTECH Campus Paranavaí, em outubro de 2026.
 
# Equipe

| Categoria | Nome | Curso, setor ou instituição | Participação no projeto |
|---|---|---|---|
| Estudante | Arthur Barbiratto Costa | Mecatrônica | Bolsista, estudante mentor do projeto |
| Estudante | Augusto Germano Ramos Meyer | Mecatrônica | Voluntário, estudante mentor do projeto |
| Estudante | Gabriel Antonio do Nascimento Reberti  | Mecatrônica | Desenvolvedor |
| Estudante | Ricardo da Silva Facciulo  | Mecatrônica | Desenvolvedor |
| Estudante | Gustavo Cardoso da Silva | Mecatrônica | Desenvolvedor |
| Servidor | Eduardo Augusto Castelli Astrath | Docente E.B.T.T. – Núcleo da Base Nacional Comum/Física | Orientador/Demandante |
| Servidor | Daniela Eloise Flôr  | Docente E.B.T.T. – Informação e Comunicação/Informática | Coordenadora |


## Instituição

**Instituto Federal do Paraná – Campus Paranavaí**

**Projeto SINAES – Soluções Inclusivas para Necessidades de Aprendizagem Específicas**

---

*Este repositório está em desenvolvimento. Os conteúdos serão atualizados conforme o andamento das atividades.*
