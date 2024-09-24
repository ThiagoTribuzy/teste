# Processo Seletivo BSF - QA Engineer 
## Etapa I - Fundamentos de Teste
Nesta primeira etapa, queremos mapear sua capacidade analítica, de construção de estratégia e cenários em uma aplicação.\
Aplicação alvo: [infojobs.com.br](https://www.infojobs.com.br)

1 - Acesse a aplicação indicada\
2 - Identifique e Mapeie os cenários de testes possíveis;\
3 - Descreva uma estratégia de testes para a execução;\
2 - Elabore um plano de teste para essa aplicação;\
4 - Identifique eventuais bug;\
5 - Liste melhorias que forem identificadas;\
6 - Forneça parecer sobre a aplicação.

    1. Mapeamento de Cenários de Testes
        Cenários principais:
            1. Cadastro de Usuário:
                - Cadastro de um novo usuário (candidato).
                - Cadastro de um novo usuário (empresa).
                - Validação de campos obrigatórios.
                - Validação de e-mail.
            2. Login:
                - Login com credenciais válidas.
                - Login com credenciais inválidas.
                - Recuperação de senha.
                
            3. Busca de Vagas:
                - Busca por palavras-chave.
                - Filtros por localização, tipo de vaga, salário.
                - Visualização de detalhes da vaga.
            4. Aplicação a Vagas:
                - Aplicar a uma vaga com sucesso.
                - Aplicar a uma vaga sem preencher campos obrigatórios.
                - Cancelar aplicação.
            5. Gerenciamento de Currículo:
                - Upload de currículo.
                - Edição de informações do currículo.
                - Visualização do currículo.
            6. Notificações e Alertas:
                - Configuração de alertas de vagas.
                - Recebimento de notificações.
    
    2. Estratégia de Testes
        Tipos de Testes:
            - Funcional: Verificar se todas as funcionalidades estão operando conforme o esperado.
            - Usabilidade: Avaliar a experiência do usuário, navegação e layout.
            - Desempenho: Testar a resposta da aplicação sob carga (ex: muitos usuários simultâneos).
            - Segurança: Testar vulnerabilidades (ex: injeção de SQL, XSS).
            - Compatibilidade: Verificar a aplicação em diferentes navegadores e dispositivos.
            
    3. Plano de Teste
        Objetivo do Teste: Garantir que a aplicação InfoJobs funcione corretamente e atenda às necessidades dos usuários.
        Escopo:
            - Testes funcionais, usabilidade, desempenho e segurança.
        Recursos Necessários:
            - Equipe de testes (testadores).
            - Ambiente de teste configurado (servidores, banco de dados).
        Cronograma:
            - Planejamento e configuração: 1 semana.
            - Execução dos testes: 2 semanas.
            - Análise de resultados e relatórios: 1 semana.
        Critérios de Aceitação:
            - Todos os testes críticos devem passar sem erros.
            - Funcionalidades principais devem estar operacionais.
            
    4. Identificação de Bugs
        Exemplos de bugs que podem ser identificados:
            - Campos que não validam entradas corretamente (ex: e-mails).
            - Links quebrados em páginas.
            - Funcionalidade de busca que não retorna resultados corretos.
            - Problemas na responsividade do layout em dispositivos móveis.
            
    5. Melhorias Identificadas
            - Interface: Melhorar a usabilidade do formulário de cadastro, tornando os campos mais intuitivos.
            - Filtros de Busca: Adicionar mais filtros para busca de vagas.
            - Notificações: Permitir que os usuários personalizem mais os tipos de notificações que desejam receber.
            - Acessibilidade: Implementar melhorias de acessibilidade para usuários com deficiência.
            
    6. Parecer sobre a Aplicação
        A aplicação InfoJobs apresenta um bom conjunto de funcionalidades que atende às necessidades básicas de candidatos e empresas.
        Contudo, melhorias na usabilidade, na interface e na performance são essenciais para proporcionar uma experiência mais fluida.
        Testes rigorosos devem ser conduzidos para identificar e corrigir bugs e garantir a segurança dos dados dos usuários.

## Etapa II - Automação de Teste Web I

Nesta segunda etapa, queremos iniciar nosso entendimento sobre seu domínio de automação de testes Web.\
Aplicação alvo: [buscacep.correios.com.br](https://buscacepinter.correios.com.br/app/cep/index.php)

Descreva e automatize os seguintes cenários:\
1 - Realizar a busca com o valor “69005-040”;\
2 - Realizar a busca com o valor “Lojas Bemol”;

## Etapa III - Automação de Teste Web II
Nesta terceira etapa, queremos aprofundar nosso entendimento e compreender como seria sua construção em métodos de validação.\
Aplicação alvo: [trivago.com.br](https://www.trivago.com.br)

Descreva e automatize o seguinte fluxo:\
1 - Acessar o site;\
2 - Pesquise por Manaus;\
3 - Ordene as opções listadas por “Avaliações e Sugestões”;\
4 - Verifique o primeiro nome da lista;\
5 - Verifique a avaliação;\
6 - Verifique o valor;

## Etapa IV - Automação de Teste de API
Nesta última etapa, queremos mapear o seu domínio de técnicas de testes em API.\
Aplicação alvo: [serverest.dev](https://serverest.dev)

Descreva e automatize os seguintes cenários:\
1 - Criação de um usuário\
2 - Verificar se o usuário foi criado\
3 - Criação de um produto\
4 - Verificar se o produto foi criado
