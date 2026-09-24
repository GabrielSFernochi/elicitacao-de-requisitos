* Pergunta de empatia: Por que eu nunca lanço meus projetos no github?

* Definição: Simplesmente não adquiri o costume de fazer um commit diário após a atualização de algo em que estou trabalhando

* Ideias: 
1 - Uma automação que lance diretamente o meu código em um repositório especifico no meu github
2 - Uma barreira de segurança que me impeça de fechar o VSCode sem dar commit antes
3 - Um app que lê e reproduz automaticamente tudo que digito dentro a IDE direto no repositório escolhido

* Ideia escolhida:
1 - Uma automação que lance diretamente o meu código em um repositório especifico no meu github

* História de usuário: COMO estudante de programação, QUERO que meu código seja lançado automaticamente no meu repositório de escolha no github PARA que eu não me esqueça de atualizar meus projetos e exibir meu progresso para eventuais contratantes

* Critérios de aceitação:
1 - Dado o projeto não tenha sido associado a um repositório, quando o projeto for fechado, então antes ele solicitará a associação com um repositório do github 
2 - Dado que o projeto não tenha sido atualizado, quando for fechado, então nada será commitado no repositório de escolha
3 - Dado que o projeto tenha sido finalizado, quando alguma alteração for feita posteriormente, então será obrigatório um readme na pasta atualizações explicando o que e porque foi feito