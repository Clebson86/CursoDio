# Introdução ao Git :open_file_folder:

Git é um sistema de controle de versão distribuído gratuito e de código aberto projetado para lidar com tudo, desde projetos pequenos a muito grandes com velocidade e eficiência.

Git é fácil de aprender e ocupa uma área pequena com desempenho extremamente rápido. Ele supera as ferramentas SCM como Subversion, CVS, Perforce e ClearCase com recursos como ramificação local barata, áreas de teste convenientes e vários fluxos de trabalho.

### * Ramificação e fusão 

O recurso do Git que realmente o diferencia de quase todos os outros SCM existentes é seu modelo de ramificação.

O Git permite e encoraja você a ter vários branches locais que podem ser totalmente independentes uns dos outros. A criação, fusão e exclusão dessas linhas de desenvolvimento leva segundos.

Isso significa que você pode fazer coisas como:

Troca de contexto sem atrito. Crie um branch para testar uma ideia, comprometa-se algumas vezes, volte para onde você se ramificou, aplique um patch, volte para onde você está experimentando e faça o merge.
Codelines com base em funções. Tenha um branch que sempre contém apenas o que vai para a produção, outro no qual você mescla o trabalho para teste e vários outros menores para o trabalho do dia a dia.
Fluxo de trabalho baseado em recursos. Crie novas ramificações para cada novo recurso em que está trabalhando, para que possa alternar perfeitamente entre eles e, em seguida, exclua cada ramificação quando esse recurso for mesclado em sua linha principal.
Experimentação descartável. Crie um branch para experimentar, perceba que não vai funcionar e apenas exclua - abandonando o trabalho - sem que ninguém mais o veja (mesmo que você tenha enviado outros branches nesse ínterim).

Notavelmente, ao enviar para um repositório remoto, você não precisa enviar todos os seus branches. Você pode optar por compartilhar apenas um de seus branches, alguns deles ou todos eles. Isso tende a liberar as pessoas para experimentar novas ideias sem se preocupar em ter que planejar como e quando irão mesclá-las ou compartilhá-las com outras pessoas.

Existem maneiras de fazer isso com outros sistemas, mas o trabalho envolvido é muito mais difícil e sujeito a erros. O Git torna esse processo incrivelmente fácil e muda a maneira como a maioria dos desenvolvedores trabalha quando o aprende.

### * Distribuído

Um dos melhores recursos de qualquer SCM distribuído, incluindo o Git, é que ele é distribuído. Isso significa que em vez de fazer um "checkout" da dica atual do código-fonte, você faz um "clone" de todo o repositório.

Backups múltiplos
Isso significa que, mesmo se você estiver usando um fluxo de trabalho centralizado, cada usuário basicamente terá um backup completo do servidor principal. Cada uma dessas cópias pode ser enviada para substituir o servidor principal no caso de um travamento ou corrupção. Na verdade, não existe um único ponto de falha no Git, a menos que haja apenas uma única cópia do repositório.

Qualquer fluxo de trabalho
Devido à natureza distribuída do Git e ao excelente sistema de ramificação, um número quase infinito de fluxos de trabalho pode ser implementado com relativa facilidade.

Fluxo de Trabalho Estilo Subversion
Um fluxo de trabalho centralizado é muito comum, especialmente de pessoas em transição de um sistema centralizado. O Git não permitirá que você faça push se alguém tiver feito push desde a última vez que você fez o push, portanto, um modelo centralizado onde todos os desenvolvedores fazem push para o mesmo servidor funciona perfeitamente.

![Workflow A](https://git-scm.com/images/about/workflow-a@2x.png)



* **[Link da fonte](https://git-scm.com/)**

  

