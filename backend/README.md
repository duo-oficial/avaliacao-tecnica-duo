# Resumo para iniciar o teste

Veja instruções de teste, instruções de envio e critérios de avaliação no resumo:

[Resumo da Avaliação Técnica DUO Studio Interativo](https://github.com/duo-oficial/instrucoes-para-processo-seletivo)

# Descrição do Projeto

## Visão geral
O gerente de projeto com quem você trabalha deseja criar um novo produto, uma nova landing page MOBILE e DESKTOP de mídia social chamado Creative. O Creative é um formulário simples para captação de dados de clientes e divulgação de materiais.

O Creative tem apenas duas páginas, a página inicial e a página de download de materiais, que são descritas abaixo. Outros dados e ações também são detalhados a seguir.

# Páginas
- ## Home
    - Dados do formúlário
        > A página inicial, por padrão, só terá um formulário simples. Os usuários podem se cadastrar e você deverá construir um backend que receba esses dados e salve em um banco de dados.

        - Nome
            - Apenas caracteres alfanuméricos podem ser usados ​​para nome de usuário
            - Máximo de 14 caracteres para nome de usuário
        - Telefone
            - Apenas números.
            - Deve-se limpar a máscara dos dados caso venha caracteres não númericos.        
        - E-mail
            - Deverá ser um e-mail válido.
        - Assunto
            - Máximo de 100 caracteres para assunto.
        - Mensagem
            - Máximo de 500 caracteres para mensagem.
<br/>

# O que você deve contruir:

- Crie uma API RESTful e um sistema de back-end correspondente para lidar com os recursos detalhados acima. Essa API RESTful se comunicaria com o aplicativo JS de página única. Essa API que você cria deve habilitar todos os recursos para a página.
- Você deve implementar um banco de dados real, pronto para produção, e as consultas devem ter bom desempenho.
- Não implemente recursos adicionais além do explicado na visão geral.
- Escreva alguns testes automatizados para este projeto.
- Não construa um front-end.
