# Projeto de Prática Profissional em ADS
## Trabalho realizado para a disciplina de Praticas Profissionais da Universidade Presbiteriana Mackenzie 

Link Aplicação: https://react-ads-loko.herokuapp.com/

Pontos importantes:

Não acessar a aplicação com a opção do navegador “DNS Seguro” habilitada.

Não acessar a aplicação com a opção do navegador “HTTPS” – Conexões

Essas limitações se devem ao fato do Back-End e Banco de Dados estarem hospedados no provedor cloud Azure, vinculado a um plano de uso de estudante. Nesse sentido, o Azure por padrão não habilita o protocolo de comunicação SSL e TTL para esse tipo de plano de uso, bloqueando qualquer chamada que seja feita a aplicação utilizando um protocolo seguro.

Limitações do Sistema:

Não pode haver jogos com resultados empatados.

A quantidade máxima de jogos permitida para cada campeonato são 3, sendo que somente dois jogos são criados pelo usuário. O terceiro e último jogo são criados pela aplicação, quando os vencedores dos jogos cadastrados pelos usuários forem definidos (esse comportamento está exemplificado no vídeo de demonstração)

