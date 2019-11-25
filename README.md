# SIAD -  Sistema Integrado de Agendamento para Departamentos

Professor: Eliane Araujo

Equipe:

- Eduardo Henrique Silva
- Gabriel Almeida
- Gustavo Santos
- João Pedro Barbosa
- Matheus Araújo
- Rafael Azevedo

## Contextualizção

### A problemática

<p style="text-align: justify;"> Em uma instituição acadêmica tempo é um recurso bastante valioso. Docentes, discentes e técnicos administrativos possuem calendário e prazos muito apertados para realizar suas atividades. Essa problemática tende a ficar mais caótica durante certas épocas do ano acadêmico, devido a eventos específicos que demandam um esforço extra de todas as partes. 

Um exemplo bastante comum desses eventos são os períodos de matrícula e ajustes de matrículas. De um lado, o coordenador tem que dividir o seu tempo entre resolver problemas relativos às cadeiras que estão sendo ofertadas e atender os alunos que têm problemas relativos às suas respectivas matrículas. Por outro lado, os alunos ficam divididos entre assistir aula e ficar esperando em filas longas na porta de suas coordenações esperando para ser atendido, onde nem mesmo sabe se vai ou não ser atendido.</p>

### Impacto

<p style="text-align: justify;">Docentes e técnicos administrativos que prestam atendimento e alunos que necessitam de atendimento acabam tendo que recorrer a métodos nada dinâmicos e intuitivos para gerenciar e realizar seu agendamentos diários. Essa métodos vão do mais arcaico, como agenda física, ao mais moderno, como bloco de notas ou agendas digitais. Porém o maior problema desses métodos é a necessidade da interação humana para gerenciá-los.</p>

### A proposta de solução

<p style="text-align: justify;">Com um sistema de agendamento os Docentes, discentes e técnicos administrativos terão uma possibilidade de maior controle sobre seus agendamentos de maneira fácil e intuitiva. O sistema de agendamento vai permitir que docentes e técnicos administrativos crie e gerencie departamentos virtuais que poderão prestar atendimentos ao alunos. O sistema vai permitir que os alunos possam fazer agendamento e gerenciá-los.</p>

## Features

<p style="text-align: justify;">Neste tópico será descrito as features que o SIAD será capaz de realizar.</p>

### Cadastro

<p style="text-align: justify;">O cadastro no aplicativo será realizado pelas coordenações e departamentos que farão uso do aplicativo. Essa medida facilitará o uso por parte dos alunos e dará um controle aos departamento sobre quem pode usar o app para fazer o agendamento.</p>

### Login

#### Primeiro Login

<p style="text-align: justify;">O primeiro login na plataforma será feito usando a matrícula como login e o CPF como senha. Ao fazer o login o usuário será redirecionado para o uma tela onde irá cadastrar sua senha pessoal e intransferível.</p>

<img alt="Tela de alteração de senha" align="center" src ="Prototipagem/Primeiro Login.jpg">

#### Demais Logins

<p style="text-align: justify;">Após ter sido feito o primeiro login os próximos logins serão feitos usando a matrícula e a senha cadastrada.</p>

<img alt="Tela de alteração de senha" align="center" src ="Prototipagem/Login.jpg">

### Fazer Agendamento

<p style="text-align: justify;">Para fazer o agendamento, um aluno vai selecionar um dos departamentos que ele que pretende ter atendimento, selecione um horário de atendimento, o motivo e uma breve descrição do motivo. Se ele for elegível para aquele departamento o agendamento será feito.

Um aluno é elegível, se sua matrícula é aceita para o departamento alvo. Por exemplo, não faz sentido um aluno de de Engenharia Elétrica querer atendimento na coordenação de Geografia.

Os horários de agendamentos são disponibilizados e controlados pelos departamentos que farão uso do aplicativo.
</p>

<img alt="Tela de alteração de senha" align="center" src ="Prototipagem/Print para melhor visualização.png">

### Acompanhar Agendamento

<p style="text-align: justify;">Um aluno poderá acompanhar os agendamentos que fez nos departamentos da Universidade. Ao Abrir um agendamento, poderá visualizar algumas informações adicionais e poderá desmarcar caso, ache necessário.</p>

<img alt="Tela de alteração de senha" align="center" src ="Prototipagem/Print 2.png">

### Notificação de Agendamento pelo APP

<p style="text-align: justify;">Cerca de 5 minutos antes do atendimento o aluno receberá uma notificação em seu dispositivo avisando-o do atendimento.</p>

### Perfil e Histórico do Aluno

<p style="text-align: justify;">Tanto o aluno como o departamento poderão visualizar seus perfis.</p>

#### Aluno

<p style="text-align: justify;">Um aluno terá acesso a seu perfil que contém informações pessoais e acadêmicas, bem como uma foto de perfil. O mesmo poderá alterar algumas das informações pessoais e académicas contidas. Além disso, poderá ver um histórico dos últimos agendamentos que realizou.</p>

#### Departamento

<p style="text-align: justify;">Um departamento também tem um perfil contendo informações sobre o departamento e <code>(e.g coordenador)</code>. Algumas informações poderão ser alteradas.

Além disso o departamento terá acesso ao perfil e histórico dos alunos que possui agendamentos para no departamentos.</p>

## Tecnologias

<p style="text-align: justify;">A principal prerrogativa para a escolha de algumas tecnologias é que os alunos da graduação interessados, possam contribuir no desenvolvimento e manutenção do projeto. Com isso queremos incentivar ao graduandos a contribuir em projetos open source.</p>

### Spring Boot e PostgreSQL

<p style="text-align: justify;">Spring Boot é uma framework baseada em java para desenvolvimento de backend. Já o PostgreSQL é uma aplicação de gerenciamento de banco de dados SQL.  O principal motivo para a escolha dessas tecnologias é que em algum momento da graduação os alunos se deparam com essas ferramentas sendo utilizadas como suporte nas disciplinas. Além disso, Spring Boot é baseada em java, linguagem que é bastante discutida no curso.

Com isso a escolhas dessas tecnologias facilita a possibilidade de contribuição dos alunos ao projeto.</p>

### Integração com o Heroku

<p style="text-align: justify;">O principal motivo da escolha do Heroku para implantação da aplicação é  sua integração padrão com o PostgreSQL, o que facilita o gerenciamento do banco de dados da aplicação Online.</p>

### GitHub

<p style="text-align: justify;">O GitHub é uma plataforma de controle de versionamento bastante disseminada e utilizada dentro da comunidade, sendo essa uma ótima escolha para a disponibilização e controle do versionamento do projeto.</p>

### ReactJS e PWA

<p style="text-align: justify;">Para o aplicativo cliente foi escolhido o ReactJS para o desenvolvimento de uma aplicação web no conceito de PWA (Progressive Web App), fazendo com que o design se adapte ao dispositivo de acesso e forneça uma experiência agradável ao usuário.

Apesar dessas tecnologias não serem ensinadas ao longo da graduação, elas são bastante utilizadas pelo mercado e é uma ótima opção para aqueles que querem aprender novas tecnologias front end.</p>

## Elicitação de Requisitos

### Entrevista com os Potenciais Clientes

<p style="text-align: justify;">Como parte da modelagem do sistema, a elicitação dos requisitos foi feita a partir de entrevistas realizadas com alguns coordenadores e observando as demandas e queixas dos alunos. Entrevistou-se os coordenadores de Letras e Meteorologia. Para dar dinâmica a entrevista e manter o foco na obejetivo da mesma, a equipe elaborou algumas perguntas rápidas e diretas que foram feitas aos coordenadores.</p>

#### Coordenador de Letras ( Português)

<p style="text-align: justify;">O coordenador relatou algumas queixas relativas ao interação com o controle acadêmico e forma como ele recebe e atende os alunos na coordenação. Durante as conversa fizemos algumas perguntas pertinentes a modelagem.

<b>Pergunta:</b> Quais são as dificuldades enfrentadas com relação ao acesso dos alunos ao coordenador?

<i><b>Resposta:</b> Ele disse que sempre que pode estar disponível e deixa na porta de sua sala um calendário semanal com seus compromissos dentro da universidade para que os alunos possam o procurar e ter acesso. porém relatou que ainda assim muitos alunos têm medo de ir até a coordenação para conversar com ele e isso muitas vezes gera problemas para o aluno a longo prazo.</i>

<b>Pergunta:</b> Existe Alguma época que é mais caótica na coordenação?

<i><b>Resposta:</b> O coordenador relatou que em geral a época, mais caótica é a de ajuste de matrículas, pois, como o controle é muito restritivo com relação às matrículas (citou o exemplo da quantidade mínimas de carga horária), muitos alunos acabam tendo que ir até a coordenação para ter que refazer sua matrícula.</i>

<b>Pergunta:</b> Quais São as funcionalidade que o senhor gostaria de ter em um aplicativo de agendamento?

<i><b>Resposta:</b> Ele disse que gostaria de que pudesse ver de forma clara ou que a ferramenta o alertasse a quantidade alunos que ele vai atender, o horário (relatou em turnos) e quais problemas irá receber para lidar (citou o exemplo de ajuste de matrícula).</i>
</p>

#### Coordenador de Meteorologia

<p style="text-align: justify;">

<b>Pergunta:</b> Quais são as dificuldades enfrentadas com relação ao acesso dos alunos ao coordenador?

<i><b>Resposta:</b></i>

<b>Pergunta:</b> Existe Alguma época que é mais caótica na coordenação?

<i><b>Resposta:</b></i>

<b>Pergunta:</b> Quais São as funcionalidade que o senhor gostaria de ter em um aplicativo de agendamento?

<i><b>Resposta:</b></i>
</p>

### User Stories (US)

ID | US-01
--- | :----
Título | Cadastro de Usuário do Departamento
Motivação | No intuito de utilizar o sistema e gerenciar os agendamentos do seu departamento, o cadastro se faz necessário.
Descrição: | O módulo de cadastro é dividido em duas partes:
Descrição: | - A primeira parte é um formulário simples de cadastro de  informações relativas ao docente ou servidor que vai atender neste departamento. Se o departemento tiver mais de uma pessoa que atende, deve colocar os dados do responsável pelo departamento. As informações são: Nome, Sobrenome, Identificador Único na universidade (e.g SIAPE), email.
Descrição: | - A segunda parte é um formulário sobre as informações do departamento que está criando. As informações que irá inserir são: Nome do departamento, localização dentro da universidade, Dias de atendimento e horários. Haverá também uma tabela dinâmica com duas colunas ( atendimento/tempo), onde será adicionado os tipos de atendimento e o tempo que leva cada um.
