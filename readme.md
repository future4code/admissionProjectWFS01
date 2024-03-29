# Projeto de seleção Future4: preparado para o Futuro?

Obrigado por participar do processo seletivo da Future4. Isso é um repositório de GitHub, e nele você encontra as instruções e arquivos necessários para você participar desse processo. Para dar início, pedimos que você leia esse texto (arquivo readme.md) por completo, e siga de forma rigorosa as nossas instruções. Qualquer dúvida ou problema no processo, não exite em entrar em contato com a equipe Future4 pelo nosso Slack(future4alunos.slack.com). Boa sorte!

## 1. Processo Seletivo - Detalhes prévios
Nosso processo seletivo consiste em três etapas: avaliação do perfil do participante, realização de um projeto e entrevistas com a equipe Future4. Se você recebeu acesso à esse documento, você já passou da etapa de avaliação de perfil, superando uma montanha de outras inscrições - ou seja, estamos apostando em você! Parabéns! Você está atualmente na etapa de Projeto, e esse documento contém as informações necessárias para completar a etapa.
### 1.1 Objetivos
Os objetivos da etapa de projetos são:  
**Avaliar o engajamento dos alunos nos cursos:** Nossos cursos são muito intensos e visam um crescimento técnico e profissional acelerado dos nossos alunos. Isso exige um nível muito alto de dedicação e motivação de todos os participantes. Para evitar que o curso não seja uma má experiência para nossos alunos, nós selecionaremos apenas os alunos realmente engajados. A nossa aposta em avaliar por projeto é baseada em ser inclusivo - não queremos avaliar quem teve a melhor formação ou qualquer coisa do tipo, queremos ver quem se dedica frente a desafios, quem corre atrás e quem sabe comunicar dúvidas ao buscar soluções.  
**Simular o dia a dia do trabalho em tecnologia:** Durante nossos cursos os alunos vão criar vários projetos, individualmente e em grupo. Esses projetos são desafios semelhantes aos encontrados no dia a dia de um desenvolvedor em empresa de tecnologia. Essa etapa do processo seletivo visa simular a rotina do trabalho. Nesse momento vamos testar se essa rotina é compatível com aluno, e esperamos que o aluno faça o mesmo.  
**Avaliar o perfil dos alunos:** Uma parte importante do trabalho da Future4 é garantir a empregabilidade dos nossos alunos. Para tal, precisamos garantir que o aluno está de acordo com o perfil desejado pelas empresas de tecnologia. Como principais características avaliadas podemos destacar: ética, perfil colaborativo, facilidade de aprendizado e resiliência (muita resiliência). Quando programando, a gente se depara com muitos desafios que parecem impossíveis de serem resolvidos - e não desistir nesse momento é um traço fundamental (se prepare, você vai se deparar muitas vezes com essas situações, faz parte do processo). Com paciência e coragem para encarar tarefas que parecem impossíveis, a gente vai quebrando a cabeça, tirando dúvidas no google (o site "Stackoverflow" é presença diária na vida de quem programa), consultando pessoas mais experientes e encontrando soluções. Vale ressaltar que nosso processo seletivo não visa avaliar o conhecimento técnico do aluno. Acreditamos que nosso curso funciona para pessoas que não possuem nenhum conhecimento técnico inicial, desde que as demais características buscadas sejam satisfeitas.  

### 1.2 Regras
- O participante deve seguir as regras e instruções determinadas nesse documento.
- Todas as atividades do projeto devem ser realizadas pelo próprio aluno. Esse é um critério eliminatório do processo seletivo. Durante a etapa de entrevista, vamos avaliar se o participante dominou os conceitos aplicados no projeto.  
- Os participantes devem consultar documentações, sites e vídeos para auxiliar no desenvolvimento do projeto. Não recomendamos copiar e colar código dessas fontes, uma vez que verificaremos o entendimento do participante.    
- Os participantes são incentivados a utilizar o Slack da Future4 para tirar dúvidas sobre o seu projeto e atualizar nossa equipe sobre o seu andamento. Nossa equipe utilizará esse canal para ajudar os participantes, e essa interação será avaliada positivamente. Os alunos podem interagir entre si nos canais do Slack. Fique atento no canal do slack pois nossa equipe pode fazer perguntas e comentários sobre o seu projeto.  
- Fique atento ao dia e horário de entrega do projeto, qualquer alteração feita após essa data será desconsiderada.
- Para avaliar o projeto, nossa equipe vai baixar o zip do participante e abrir o arquivo index.html que ele construiu utilizando o browser Chrome em um Macbook. Nenhuma etapa adicional deve ser necessária para abrir o site desenvolvido por você.
- Não é permitido o uso de bibliotecas e código de terceiros. Todo o código deve ser escrito por você e isso será verificado na etapa de entrevista.  

### 1.3 Desafio
O projeto consiste na criação de um site utilizando HTML, CSS e Javascript. O site deve ter apenas uma página, o arquivo index.html (outros arquivos css e js podem ser criados). O participante deve seguir, da melhor forma que conseguir, o layout que está no arquivo wireframe.pdf. Esse repositório contém todas as imagens necessárias para construir essa página.  
Existe um campo de input de texto no final da página e um botão com o texto "Enviar". Ao clicar nesse botão, um alerta deve ser apresentado na página com o texto "O email usuario@future4.com.br foi enviado", sendo que o email deve conter o texto digitado pelo usuário da página. Esse alerta deve ser apresentado utilizando a função alert do javascript (é só um detalhezinho de Javascript - você vai encontrar um tutorial para isso no final deste documento). Sabemos que esses termos podem não fazer parte do seu dia-a-dia, mas fique tranquil@, daremos mais detalhes abaixo. :)

#### 1.3.1 Desafios extras
Você pode complementar seu projeto com alguns desafios extras. Esses desafios não são obrigatórios, não é necessário cumpri-los para ser selecionado. Recomendamos fortemente que o participante complete a totalidade do desafio inicial antes de seguir para os desafios extras.
- Preparar o site para ser apresentado em telas mobile. Fica a critério do participante a melhor forma de ajustar o conteúdo do site para plataformas mobile. Para avaliar esse desafio extra, nossa equipe vai abrir o mesmo arquivo index.html em um iphoneX.  
- Realizar a verificação de email válido no texto digitado pelo usuário no campo "email". Essa verificação deve ser realizada utilizando javascript. Se o email for inválido a mensagem "Email inválido" deve ser apresentada no site utilizando a função alert() do javascript.  
- Incluir um texto de boas vindas quando o usuário enviar seu email. Quando o usuário clicar no botão enviar, a página deve ser atualizada para incluir um texto no formato "Bem vindo usuario@future4.com.br!".  

## 2. Instruções - é hora de programar!
Siga as instruções abaixo para iniciar o seu projeto. Se é a primeira vez que você está utilizando ferramentas como github e vscode, pode ser que tudo isso seja muita coisa. Tudo bem! Estamos aqui para te ajudar nesse aprendizado, basta entrar em contato no nosso Slack que ajudaremos. Como já falamos, parte do dia-a-dia de desenvolvedores de software é enfrentar esses desafios - e avaliaremos como cada participante encara isso no nosso processo seletivo. Aqui, o seu esforço importa muito mais que o resultado final, fique tranquil@ :)
### 2.1 Github
Para participar da etapa de projeto será necessário que o participante tenha uma conta no github. Se você ainda não possui conta no github, é simples - você pode criar uma conta gratuitamente entrando em https://github.com/.
### 2.2 Editor de texto
Os participantes vão precisar criar e editar os arquivos do projeto, e para isso recomendamos que um editor de textos ou IDE seja utilizado. IDE significa "Ambiente de desenvolvimento integrado" - sendo um programa no qual você desenvolve seus projetos de software, conseguindo integrar melhor páginas/pastas, ferramentas e frameworks de programação. Cada participante pode escolher qual programa vai utilizar para editar os arquivos. Indicamos a utilização do VSCode, um dos programas gratuitos mais robustos do mercado. Você pode instalá-lo acessando as instruções nos links:
- **windows:** https://code.visualstudio.com/docs/setup/windows
- **linux:** https://code.visualstudio.com/docs/setup/linux
- **macOS:** https://code.visualstudio.com/docs/setup/mac
### 2.3 Iniciando o projeto
Para iniciar o projeto, o primeiro passo é acessar a página https://github.com/future4code/admissionProjectWFS01, clicar no botão "Clone or download" e clicar em "Download Zip". Encontre o arquivo ZIP nos seus Downloads e faça a descompressão do arquivo. 

Lembrando: se você teve alguma dificuldade nesses passos, não exite em nos procurar! Sabemos que essas primeiras vezes são cheias de entraves por questão de detalhes, e estamos do seu lado para ajudar nesse primeiro mergulho :)

### 2.4 Editando e testando o seu projeto
Para testar o seu projeto, basta clicar duas vezes no arquivo index.html da pasta do seu projeto. A página deve abrir no browser padrão utilizado (recomendamos que você use o Chrome). Toda vez que você quiser testar o seu projeto, basta abrir novamente o arquivo e dar uma olhada em como o seu site está ficando. Para fazer alterações no seu projeto, nós vamos usar um editor de texto (como indicado no item 2.2, sugerimos o VSCode). Abra o editor de texto da sua escolha, e utilize a opção de abrir pasta (open folder) para abrir a pasta do seu projeto. Todos os arquivos da pasta devem aparecer no seu editor de texto. Para fazer uma alteração no seu site, basta alterar o código no editor de texto e salvar o arquivo. Após salvar, abra o arquivo index.html novamente para testar suas alterações. Esse procedimento vai ser realizado várias vezes, até que você fique satisfeito com o seu site. Programar é isso: iterar dezenas de vezes, quebrar a cara, superar bloqueios que parecem impossíveis, mas depois ficar feliz por ter construído algo com a sua personalidade :)

### 2.5 Entregando seu projeto 
Quando finalizar o seu projeto, crie um arquivo ZIP com os seus arquivos e envie para o e-mail: w1b8y5t3a7f8n0v7@future4alunos.slack.com (é esse endereço mesmo!)

## 3. Documentação e referências
### 3.1 W3School
Toda a documentação necessária para completar o projeto pode ser encontrada no site da w3school. Os seguintes links são recomendados:  
- https://www.w3schools.com/html/default.asp 
- https://www.w3schools.com/css/default.asp
- https://www.w3schools.com/js/default.asp
Os participantes podem acessar outras referências encontradas na internet.
### 3.2 Wireframe e Referências
O arquivo wireframe.pdf deve ser utilizado como referência para a criação do projeto. O site htpps://future4.com.br pode ser considerado uma página interessante para utilizar como referência.  
## 4. E agora? O que fazer?
Sabemos que aprender a programar pode ser muito desafiador. Aqui seguem algumas dicas de como seguir no desafio de criar um site:  
- Vá seguindo os tutoriais da w3schools.com .  
Para esse projeto sugerimos que você siga o tutorial de html (https://www.w3schools.com/html/default.asp) até o item HTML Javascript (https://www.w3schools.com/html/html_scripts.asp), e a seção HTML Forms (https://www.w3schools.com/html/html_forms.asp).  
Sugerimos que você siga o tutorial de css (https://www.w3schools.com/css/default.asp) até o item CSS align (https://www.w3schools.com/css/css_align.asp).  
Sugerimos que você siga o tutorial de JavaScript (https://www.w3schools.com/js/default.asp) até o item JS String Methods (https://www.w3schools.com/js/js_string_methods.asp).  
- Use o Slack para interagir com os nossos instrutores e com os demais alunos (future4alunos.slack.com). Estamos aqui para ajudar você nessa jornada, e avaliaremos positivamente a interação dos alunos por Slack. Lembre que a nossa equipe precisa de um tempo de resposta para atender todos os alunos e as demais tarefas da nossa empresa, aproveite esse tempo para tentar superar seus desafios individualmente.  
- Se você não sabe qual o próximo passo no seu projeto, pense em uma pequena parte do site que esteja faltando ou que precise ser melhorada. Coloque como desafio resolver apenas essa parte do site e foque nesse desafio até resolvê-lo. Por exemplo, um texto do meu site está azul, mas ele deveria ser vermelho. Meu próximo desafio é fazer que esse texto azul se torne vermelho, e eu vou focar nesse desafio até que o texto esteja correto.  
- Reforçamos: estamos avaliando muito mais o seu esforço do que seu resultado final. Vocês terão aulas conosco de HTML e CSS durante o programa, caso aprovados, portanto não estamos exigindo nenhum domínio especial ou excelência no assunto. Queremos mais é verificar sua capacidade de correr atrás por conta própria e lidar com desafios :)   
