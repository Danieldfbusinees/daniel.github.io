# daniel.github.io
Daniel Goncalves
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Análise Comparativa de Editais - CBTU Gestão de Documentos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f6f8fa; /* GitHub-like light background */
        }
        .card {
            background-color: white;
            border-radius: 0.5rem; /* Slightly less rounded corners */
            border: 1px solid #d0d7de; /* GitHub border color */
            transition: all 0.2s ease-in-out;
        }
        .card:hover {
            transform: translateY(-4px);
            box-shadow: 0 8px 16px -4px rgb(0 0 0 / 0.1);
        }
        .tag {
            display: inline-block;
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-weight: 600; /* Bolder tags */
            font-size: 0.75rem;
        }
        .tag-high { background-color: #FEE2E2; color: #B91C1C; border: 1px solid #FCA5A5; }
        .tag-medium { background-color: #FEF3C7; color: #B45309; border: 1px solid #FBBF24;}
        .tag-low { background-color: #DBEAFE; color: #1E40AF; border: 1px solid #93C5FD;} /* Changed to blue */
        .section-title {
            border-left: 4px solid #2da44e; /* GitHub green */
            padding-left: 1rem;
        }
        .gh-link {
            display: inline-flex;
            align-items: center;
            color: #0969da; /* GitHub link blue */
            text-decoration: none;
            font-weight: 500;
        }
        .gh-link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body class="text-gray-900">

    <div class="container mx-auto p-4 sm:p-6 lg:p-8">
        <!-- Header -->
        <header class="text-center mb-10 pb-6 border-b border-gray-300">
             <div class="flex justify-center items-center gap-4 mb-4">
                <svg height="32" aria-hidden="true" viewBox="0 0 16 16" version="1.1" width="32" data-view-component="true" class="octicon-mark-github">
                    <path d="M8 0c4.42 0 8 3.58 8 8a8.013 8.013 0 0 1-5.45 7.59c-.4.08-.55-.17-.55-.38 0-.19.01-.82.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.28.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21-.15.46-.55.38A8.013 8.013 0 0 1 0 8c0-4.42 3.58-8 8-8Z"></path>
                </svg>
                <h1 class="text-3xl sm:text-4xl font-bold text-gray-900">Análise Comparativa de Editais</h1>
            </div>
            <p class="mt-2 text-lg text-gray-600">CBTU - Gestão de Documentos</p>
             <a href="https://github.com/" target="_blank" rel="noopener noreferrer" class="gh-link mt-4">
                Ver no GitHub
                <svg class="w-4 h-4 ml-1" fill="currentColor" viewBox="0 0 16 16"><path fill-rule="evenodd" d="M8.636 3.636a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5z"></path><path fill-rule="evenodd" d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0v-5z"></path></svg>
            </a>
        </header>

        <!-- Document Identification -->
        <div class="mb-12 p-6 bg-white border border-gray-300 rounded-lg">
            <h2 class="text-xl font-semibold text-gray-800 mb-4">Editais Analisados</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="bg-gray-50 p-4 rounded-md border border-gray-200">
                    <h3 class="font-bold text-gray-700">Edital Antigo</h3>
                    <p class="text-sm text-gray-600">PREGÃO ELETRÔNICO № 90005-2024/GALIC/AC/CBTU</p>
                </div>
                <div class="bg-gray-50 p-4 rounded-md border border-gray-200">
                    <h3 class="font-bold text-gray-700">Edital Novo</h3>
                    <p class="text-sm text-gray-600">PREGÃO ELETRÔNICO № 90008-2025/GALIC/AC/CBTU</p>
                </div>
            </div>
        </div>
        
        <!-- Analysis Sections -->
        <main class="space-y-12">

            <!-- Section 1: Identificação e Prazos -->
            <div>
                <h2 class="text-2xl font-bold mb-6 section-title">1. Identificação e Prazos do Processo</h2>
                <div class="card p-6">
                    <h3 class="font-semibold text-lg mb-3">Atualização de Numeração e Prazos</h3>
                    <p class="mb-2"><strong>O que mudou:</strong> A licitação foi republicada com nova numeração e novos prazos.</p>
                    <ul class="list-disc list-inside mb-4 space-y-1 text-gray-700">
                        <li><strong>Número:</strong> De 90005-2024 para 90008-2025.</li>
                        <li><strong>Processo:</strong> De 920/2024 para 2378-2025.</li>
                        <li><strong>Data da Sessão:</strong> De 14/11/2024 para 16/10/2025.</li>
                    </ul>
                    <p class="mb-4"><strong>Análise da mudança:</strong> Trata-se de uma atualização padrão para um novo processo licitatório. A mudança mais relevante é a data, que concede um novo cronograma para preparação.</p>
                    <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                        <p><strong>Localização nos editais:</strong></p>
                        <p class="text-gray-600"><strong>Edital 2024:</strong> Capa e pág. 2. | <strong>Edital 2025:</strong> Capa e pág. 2.</p>
                    </div>
                </div>
            </div>
            
            <!-- Section 2: Objeto da Licitação -->
            <div>
                <h2 class="text-2xl font-bold mb-6 section-title">2. Objeto da Licitação e Escopo dos Serviços</h2>
                <div class="card p-6">
                    <h3 class="font-semibold text-lg mb-3">Refinamento do Texto do Objeto</h3>
                     <p class="mb-4"><strong>O que mudou:</strong> O texto do objeto foi refinado e simplificado, mas o escopo geral dos serviços (transferência, guarda, tratamento, digitalização, etc.) foi mantido. O Edital 2024 era mais prolixo na descrição inicial, detalhando "troca de caixas e etiquetas" e "elaboração de inventário" já no preâmbulo. O Edital 2025 consolida a descrição de forma mais clara em uma tabela no item 1.2.</p>
                    <p class="mb-4"><strong>Análise da mudança:</strong> A mudança é primariamente textual, buscando maior clareza. Não há uma alteração substantiva no escopo principal do que deve ser executado. A estratégia de composição de preços e planejamento operacional pode ser mantida, com foco nos serviços listados no Termo de Referência.</p>
                    <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                        <p><strong>Localização nos editais:</strong></p>
                        <p class="text-gray-600"><strong>Edital 2024:</strong> Preâmbulo e item 1.1, pág. 4-5. | <strong>Edital 2025:</strong> Preâmbulo e item 1.1/1.2, pág. 4-5.</p>
                    </div>
                </div>
            </div>
            
            <!-- Section 3: Condições de Participação e Habilitação -->
            <div>
                <h2 class="text-2xl font-bold mb-6 section-title">3. Condições de Participação e Habilitação (Mudanças de Alto Impacto)</h2>
                <div class="space-y-6">
                    <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">3.1. Vistoria Técnica</h3>
                             <span class="tag tag-high">Alto Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> Toda a seção sobre a vistoria técnica (item 1.7 e subitens no Edital 2024) foi <strong>completamente removida</strong> no Edital 2025. O Edital 2024 considerava a vistoria "imprescindível", exigindo uma declaração de visita ou de declínio do direito de vistoriar, sob pena de inabilitação.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> A remoção da obrigatoriedade da vistoria (ou da declaração de declínio) simplifica o processo para licitantes de fora de Brasília, reduzindo custos e barreiras logísticas. Isso tende a <strong>aumentar a competitividade</strong> do certame. Contudo, o risco de uma empresa precificar o serviço de forma inadequada por não conhecer as instalações e o estado real do acervo aumenta. A sua empresa, caso já conheça as instalações, passa a ter uma vantagem competitiva informacional.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Itens 1.7 a 1.7.10, pág. 5-6. | <strong>Edital 2025:</strong> Seção inexistente.</p>
                        </div>
                    </div>
                    <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">3.2. Subcontratação</h3>
                             <span class="tag tag-high">Alto Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> As regras de subcontratação foram drasticamente simplificadas e restringidas. O Edital 2024 permitia subcontratar até 25% da transferência (RJ/BH), 25% da higienização, 25% da digitalização e, excepcionalmente, 100% do armazenamento em caso de força maior. O Edital 2025 permite subcontratar <strong>apenas 25% do serviço de transferência</strong> das caixas do Rio de Janeiro e Belo Horizonte para Brasília.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> A restrição severa na subcontratação exige que a empresa licitante tenha capacidade própria para executar quase a totalidade dos serviços, especialmente higienização, digitalização e armazenamento. Isso <strong>limita a participação de empresas que dependem de parcerias</strong> para complementar seu portfólio de serviços. A estratégia de negócio deve se basear na capacidade interna, e o preço deve refletir essa estrutura.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Item 4.12 e subitens, pág. 10-11. | <strong>Edital 2025:</strong> Item 4.13, pág. 9.</p>
                        </div>
                    </div>
                     <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">3.3. Qualificação Econômico-Financeira</h3>
                             <span class="tag tag-medium">Médio Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> O critério para comprovação de Patrimônio Líquido (PL) foi alterado. O Edital 2024 exigia PL de, no mínimo, 10% do <strong>valor estimado da contratação</strong>. O Edital 2025 exige PL de, no mínimo, 10% do <strong>valor da sua proposta</strong>.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> Esta é uma flexibilização importante. Como o valor da proposta vencedora é, por definição, inferior ao valor estimado, a exigência de capital se torna menor. Isso pode permitir a participação de empresas com menor capital social, mas que sejam competitivas em preço.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Item 9.23, pág. 25. | <strong>Edital 2025:</strong> Item 9.24, pág. 23.</p>
                        </div>
                    </div>
                     <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">3.4. Qualificação Técnica</h3>
                             <span class="tag tag-medium">Médio Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> A exigência para o atestado de armazenamento foi tornada mais rigorosa. O Edital 2024 pedia atestado de armazenamento de no mínimo 10.000 caixas por um período mínimo de 12 meses. O Edital 2025 pede atestado para a mesma quantidade (10.000 caixas), mas por um período mínimo de <strong>12 a 30 meses</strong>.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> A nova redação "12 a 30 meses" pode ser interpretada como uma exigência de um único contrato com duração nesse intervalo. Isso pode ser um fator restritivo, visando contratar empresas com experiência em contratos de maior duração e complexidade. É crucial verificar se seus atestados se enquadram nesse novo requisito.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Item 9.27.3, pág. 25. | <strong>Edital 2025:</strong> Item 9.31, pág. 24.</p>
                        </div>
                    </div>
                    <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg text-red-700">3.5. Exigências para a Contratação (Pré-assinatura)</h3>
                             <span class="tag tag-high">Altíssimo Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> Uma extensa lista de exigências que deveriam ser comprovadas <strong>antes da assinatura do contrato</strong> foi <strong>completamente removida</strong>. O item 14.5 do Edital 2024 exigia a comprovação de galpão em um raio de 50km, apólice de seguro, certificados dos bombeiros, comprovante de dedetização, brigada de incêndio, plano de contingência, entre outras declarações.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> A remoção dessas exigências pré-contratuais é a flexibilização mais significativa do edital. No modelo anterior, a empresa vencedora precisava ter toda a infraestrutura pronta e documentada antes mesmo de ter o contrato assinado, o que representava um grande risco e custo inicial. Agora, presume-se que essas condições serão verificadas durante a execução do contrato. Isso <strong>reduz drasticamente a barreira de entrada e o risco para o licitante</strong>, que não precisa mais investir em uma estrutura completa sem a garantia do contrato. A estratégia pode ser mais agressiva, com o planejamento do investimento na infraestrutura ocorrendo após a homologação.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Item 14.5 e subitens, pág. 31-32. | <strong>Edital 2025:</strong> Seção inexistente.</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Section 4: Procedimentos da Licitação -->
            <div>
                 <h2 class="text-2xl font-bold mb-6 section-title">4. Procedimentos da Licitação</h2>
                 <div class="space-y-6">
                     <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">4.1. Modo de Disputa</h3>
                             <span class="tag tag-medium">Médio Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> O modo de disputa foi alterado de "Aberto e Fechado" para apenas "Aberto".</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> No modo "Aberto e Fechado", após a fase de lances abertos, os melhores classificados dão um lance final sigiloso. No modo "Aberto", a disputa continua em tempo real até que não haja mais lances. Isso muda a dinâmica da disputa. A estratégia de lances deve ser focada na agilidade e no monitoramento constante, sem a "cartada final" do lance fechado.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Tabela de Informações Gerais, pág. 2 e item 7.12, pág. 15. | <strong>Edital 2025:</strong> Tabela de Informações Gerais, pág. 2 e item 1.5, pág. 5.</p>
                        </div>
                    </div>
                    <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">4.2. Prova de Conceito (POC)</h3>
                             <span class="tag tag-high">Alto Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> A exigência de realização de Prova de Conceito (POC) para o software de gestão web, detalhada nos itens 8.19 a 8.19.3 do Edital 2024, foi <strong>completamente removida</strong>.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> A remoção da POC simplifica enormemente a fase de julgamento, eliminando um processo que poderia ser demorado, custoso e subjetivo. Isso reduz os custos de participação na licitação e o risco de desclassificação por uma falha na demonstração. Empresas que possuem um software robusto, mas que poderiam ter dificuldades em uma demonstração sob pressão, são beneficiadas. A estratégia deve focar em comprovar a qualidade do software através da documentação e da proposta, e não mais de uma demonstração prática.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Itens 8.19 a 8.19.3, pág. 21. | <strong>Edital 2025:</strong> Seção inexistente.</p>
                        </div>
                    </div>
                     <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">4.3. Consulta ao CADIN</h3>
                             <span class="tag tag-low">Baixo/Médio Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> O Edital 2025 incluiu uma seção específica (item 8.5) detalhando a consulta ao Cadastro Informativo de Créditos não Quitados (CADIN) como fator impeditivo para a contratação, estabelecendo um prazo de 5 dias úteis para regularização.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> Trata-se de uma adequação a uma exigência legal mais recente. Para empresas com a situação fiscal em dia, o impacto é nulo. Para outras, serve como um alerta para verificar e regularizar pendências no CADIN antes da sessão pública para evitar a inabilitação.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Não mencionado explicitamente nesta fase. | <strong>Edital 2025:</strong> Item 8.5 e subitens, pág. 16.</p>
                        </div>
                    </div>
                 </div>
            </div>
            
            <!-- Section 5: Condições Contratuais -->
            <div>
                 <h2 class="text-2xl font-bold mb-6 section-title">5. Condições Contratuais</h2>
                 <div class="space-y-6">
                      <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg text-red-700">5.1. Prazo de Vigência</h3>
                             <span class="tag tag-high">Altíssimo Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> O prazo de vigência do contrato foi drasticamente reduzido. O Edital 2024 previa <strong>30 (trinta) meses</strong>, enquanto o Edital 2025 prevê <strong>12 (doze) meses</strong>.</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> A redução do prazo de 30 para 12 meses altera fundamentalmente o cálculo de retorno sobre o investimento (ROI). Custos de implantação, mobilização e aquisição de ativos (se necessário) precisam ser amortizados em um período muito mais curto. Isso pode levar a um <strong>aumento no preço mensal dos serviços</strong>. A estratégia de precificação deve ser revista completamente para garantir a viabilidade do projeto no novo prazo.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Item 15.4, pág. 33. | <strong>Edital 2025:</strong> Item 15.4, pág. 30.</p>
                        </div>
                    </div>
                     <div class="card p-6">
                        <div class="flex justify-between items-start mb-2">
                             <h3 class="font-semibold text-lg">5.2. Índice de Reajuste</h3>
                             <span class="tag tag-medium">Médio Impacto</span>
                        </div>
                        <p class="mb-4"><strong>O que mudou:</strong> O índice de reajuste anual foi alterado. O Edital 2024 utilizava o <strong>IPCA/IBGE</strong> (Índice de Preços ao Consumidor Amplo). O Edital 2025 passou a utilizar o <strong>Índice de Preços ao Produtor Amplo (IPA)</strong>. A fórmula apresentada no Edital 2025 também aparenta conter um erro de digitação (`R = Po[(1-1)/ ]`).</p>
                        <p class="mb-4"><strong>Análise da mudança:</strong> O IPA tende a ser mais volátil que o IPCA, pois reflete os custos da indústria e do atacado antes de chegarem ao consumidor. Dependendo do cenário econômico, isso pode ser benéfico ou prejudicial. É fundamental que a empresa analise as projeções para ambos os índices ao formular sua proposta. O erro na fórmula deve ser objeto de um pedido de esclarecimento.</p>
                        <div class="bg-gray-100 p-3 rounded-md text-sm border border-gray-200">
                           <p><strong>Localização nos editais:</strong></p>
                           <p class="text-gray-600"><strong>Edital 2024:</strong> Item 18.1, pág. 37. | <strong>Edital 2025:</strong> Item 18.1, pág. 31.</p>
                        </div>
                    </div>
                 </div>
            </div>

            <!-- Section 6: Resumo Estratégico -->
            <div>
                 <h2 class="text-2xl font-bold mb-6 section-title">Resumo Estratégico e Recomendações</h2>
                 <div class="card p-6 bg-green-50 border border-green-200">
                     <p class="mb-4 text-gray-800">O Edital 2025 representa uma <strong>flexibilização significativa das barreiras de entrada</strong>, mas com um <strong>aumento do risco contratual</strong> devido ao prazo de vigência drasticamente menor.</p>
                     <ul class="space-y-4">
                        <li class="flex items-start">
                            <svg class="w-6 h-6 text-green-700 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                            <div><strong>Aumento da Competitividade:</strong> A remoção da vistoria obrigatória, da POC e, principalmente, das exigências de infraestrutura pré-contrato, provavelmente atrairá um número maior de concorrentes. A disputa de preços tende a ser mais acirrada.</div>
                        </li>
                         <li class="flex items-start">
                             <svg class="w-6 h-6 text-green-700 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0v-4m6 4v-4m6 4v-4m-9-4h5m6 0h2"></path></svg>
                             <div><strong>Foco na Capacidade Interna:</strong> A restrição à subcontratação exige que sua empresa possua (ou desenvolva rapidamente) capacidade própria para a maior parte dos serviços. A estratégia de formar consórcios ou parcerias extensas foi inviabilizada.</div>
                         </li>
                         <li class="flex items-start">
                             <svg class="w-6 h-6 text-green-700 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 7h6m0 10v-3m-3 3h.01M9 17h.01M9 14h.01M12 14h.01M15 11h.01M12 11h.01M9 11h.01M7 21h10a2 2 0 002-2V5a2 2 0 00-2-2H7a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
                             <div><strong>Reprecificação é Obrigatória:</strong> O novo prazo de vigência de 12 meses obriga a uma revisão completa da planilha de custos. O modelo financeiro deve ser refeito para garantir que todos os investimentos sejam pagos e o lucro seja obtido nesse período mais curto.</div>
                         </li>
                          <li class="flex items-start">
                             <svg class="w-6 h-6 text-green-700 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
                             <div><strong>Menor Risco na Entrada, Maior Risco na Execução:</strong> A empresa assume menos riscos para participar da licitação, mas o contrato de curta duração aumenta a incerteza sobre a continuidade e a diluição dos custos fixos a longo prazo.</div>
                         </li>
                          <li class="flex items-start">
                             <svg class="w-6 h-6 text-green-700 mr-3 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                             <div><strong>Ação Imediata:</strong> É recomendável submeter um <strong>pedido de esclarecimento</strong> sobre a fórmula de reajuste apresentada no item 18.1 do Edital 2025 para garantir a segurança jurídica do cálculo.</div>
                         </li>
                     </ul>
                 </div>
            </div>

        </main>

        <!-- Footer -->
        <footer class="text-center mt-12 pt-6 border-t border-gray-300">
            <p class="text-sm text-gray-500">Relatório gerado em 15/10/2025. Análise de especialista sênior para fins de estratégia de negócio.</p>
        </footer>
    </div>
</body>
</html>
