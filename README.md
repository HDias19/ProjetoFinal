# ProjetoFinal

Projeto Final de Laboratórios de Informatica da Universidade de Aveiro realizado por Henrique Dias (98153), Pedro Santos (98158)

# Tema Proposto

Este projeto visa criar uma plataforma digital de colecionismo de imagens digitais, ou de forma coloquial: uma caderneta digital de cromos. É proposto o desenvolvimento de uma plataforma Web Online que armazena as imagens originais de forma segura e que faz o acompanhamento das trocas digitais entre os colecionadores a que vamos chamar de Editora.

A editora terá utilizadores com dois perfis distintos:
 - Curadores responsáveis por fazer upload das imagens;
 - Colecionistas que podem requisitar imagens livres (não pertencentes a outro colecionista) e trocar imagens com outro colecionista.

A editora protege as imagens de roubo cifrando as mesmas com uma chave que apenas o administrador da Editora conhece e que a fornece no lançamento da plataforma web. Sempre que um curador faz upload de uma imagem, a mesma tem que ser armazenada de forma segura pelo servidor. Colecionistas podem consultar todas as imagens disponíveis, mas estas imagens contêm uma marca de água visível (gerada pelo servidor) com a identificação do utilizador que detém a imagem. Através da plataforma web, um utilizador pode ceder a propriedade de uma imagem a outro utilizador, ficando no entanto registado todo o histórico de transações. O colecionista pode assim consultar não só as suas imagens mas também as restantes imagens e quem é o detentor das mesmas. O colecionista nunca terá acesso a nenhuma imagem sem marca de água.

Existirá valor na integração dos componentes e na disponibilização de um serviço completo, mas assume-se que os componentes poderão funcionar de forma isolada. Este aspeto também é vital para que seja possível testar o funcionamento isolado de partes do sistema.
