<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domine o Tráfego Pago - De R$90,00 por Apenas R$19,97</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&family=Varela+Round&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00ff88;
            --dark: #121212;
            --darker: #0a0a0a;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--darker);
            color: white;
            overflow-x: hidden;
        }
        
        .heading-font {
            font-family: 'Varela Round', sans-serif;
        }
        
        .btn-primary {
            background-color: var(--primary);
            color: var(--darker);
            font-weight: 700;
            padding: 15px 40px;
            border-radius: 50px;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 255, 136, 0.4);
        }
        
        .btn-primary:active {
            transform: translateY(1px);
        }
        
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .gradient-text {
            background: linear-gradient(90deg, #00ff88, #00b8ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .feature-card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            transition: all 0.3s;
            overflow: hidden;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            border-color: var(--primary);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .check-icon {
            color: var(--primary);
            font-weight: bold;
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(0, 255, 136, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(0, 255, 136, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 255, 136, 0); }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-black/80 to-black/20 z-0"></div>
        <img src="https://placehold.co/1920x1080" alt="Background futurístico digital com gráficos de dados, setas ascendentes e elementos abstratos em verde neon representando crescimento e marketing digital" class="absolute inset-0 w-full h-full object-cover opacity-30">
        
        <div class="relative z-10 max-w-7xl mx-auto px-4 py-24 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <span class="inline-block px-4 py-2 rounded-full bg-green-900/30 text-green-400 text-sm mb-4">OFERTA POR TEMPO LIMITADO</span>
                    <h1 class="heading-font text-4xl md:text-6xl font-bold leading-tight mb-6">
                        Domine o <span class="gradient-text">Tráfego Pago</span> e Construa Seu Negócio Online
                    </h1>
                    <p class="text-lg text-gray-300 mb-8">
                        O guia definitivo para iniciantes que querem dominar o marketing digital e multiplicar suas vendas com anúncios pagos, sem complicação!
                    </p>
                    <div class="mb-8">
                        <div class="inline-flex items-center space-x-4 bg-black/40 px-6 py-3 rounded-full">
                            <span class="text-2xl font-bold line-through text-gray-400">R$ 90,00</span>
                            <span class="text-4xl font-bold text-green-400">R$ 19,97</span>
                            <span class="px-3 py-1 bg-green-900/40 text-green-400 rounded-full text-sm">85% OFF</span>
                        </div>
                    </div>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#oferta" class="btn-primary pulse text-center">
                            QUERO GARANTIR MEU ACESSO
                        </a>
                        <a href="#detalhes" class="px-6 py-4 border border-white/20 rounded-full text-center hover:bg-white/5 transition">
                            SAIBA MAIS
                        </a>
                    </div>
                </div>
                <div class="flex justify-center">
                    <div class="relative max-w-md">
                        <img src="https://placehold.co/600x800" alt="Ebook moderno sobre tráfego pago com capa preta e detalhes em verde neon, mostrando gráficos de crescimento e ícones de mídias sociais" class="floating w-full max-w-xs rounded-xl shadow-2xl transform rotate-1">
                        <div class="absolute -bottom-6 -left-6 -z-10 w-full h-full bg-gradient-to-br from-green-500 to-blue-500 rounded-xl opacity-20"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-black/40 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">10K+</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Alunos</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">4.9</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Avaliação</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">92%</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Conclusão</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">24/7</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Suporte</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="detalhes" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">O Que Você Vai <span class="gradient-text">Aprender</span>?</h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Tudo que você precisa saber para começar a vender com tráfego pago, mesmo que nunca tenha usado antes.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0z"></path>
                            <path d="M9 10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Fundamentos do Tráfego Pago</h3>
                    <p class="text-gray-300">Entenda os pilares essenciais e como usar plataformas como Meta Ads e Google Ads para conseguir clientes.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m16.2 7.8 2.9-2.9"></path>
                            <path d="M18 12h4"></path>
                            <path d="m16.2 16.2 2.9 2.9"></path>
                            <path d="M12 18v4"></path>
                            <path d="m4.9 19.1 2.9-2.9"></path>
                            <path d="M2 12h4"></path>
                            <path d="m4.9 4.9 2.9 2.9"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Criação de Anúncios</h3>
                    <p class="text-gray-300">Aprenda a criar anúncios irresistíveis que convertem e a segmentar o público certo para seu produto.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <rect x="2" y="7" width="20" height="14" rx="2" ry="2"></rect>
                            <path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Pixel e Conversões</h3>
                    <p class="text-gray-300">Domine a instalação do Pixel e acompanhamento de conversões para otimizar seus resultados.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m16.2 7.8 2.9-2.9"></path>
                            <path d="M18 12h4"></path>
                            <path d="m16.2 16.2 2.9 2.9"></path>
                            <path d="M12 18v4"></path>
                            <path d="m4.9 19.1 2.9-2.9"></path>
                            <path d="M2 12h4"></path>
                            <path d="m4.9 4.9 2.9 2.9"></path>
                            <circle cx="12" cy="12" r="3"></circle>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Otimização de Campanhas</h3>
                    <p class="text-gray-300">Aprenda técnicas avançadas para melhorar continuamente seus anúncios e reduzir custos por lead.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M12 16v-4"></path>
                            <path d="M12 8h.01"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Escalando os Resultados</h3>
                    <p class="text-gray-300">Métodos comprovados para escalar suas campanhas bem-sucedidas e atingir mais clientes.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m5 5 2.5 2.5"></path>
                            <path d="M7 12H2"></path>
                            <path d="m19 5-2.5 2.5"></path>
                            <path d="M17 12h5"></path>
                            <circle cx="12" cy="12" r="5"></circle>
                            <path d="m15 9-3 3-3 3"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Bônus Exclusivos</h3>
                    <p class="text-gray-300">Lista de ferramentas, planilhas de acompanhamento e modelos prontos para você replicar.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gradient-to-b from-black/30 to-black/70 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">O Que Dizem Nossos <span class="gradient-text">Alunos</span></h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Veja os resultados de quem já aplicou os métodos ensinados neste curso.</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://placehold.co/80" alt="Retrato de homem sorrindo, cerca de 30 anos, em fundo desfocado, usando camisa social clara" class="rounded-full w-16 h-16 object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">Rafael Silva</h4>
                            <div class="flex text-yellow-300 text-sm mt-1">
                                ★ ★ ★ ★ ★
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Consegui aumentar minhas vendas em 300% aplicando apenas os conceitos básicos que aprendi aqui. O investimento valeu cada centavo!"</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://placehold.co/80" alt="Mulher jovem sorrindo, cabelos castanhos, usando óculos, em escritório moderno" class="rounded-full w-16 h-16 object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">Ana Carolina</h4>
                            <div class="flex text-yellow-300 text-sm mt-1">
                                ★ ★ ★ ★ ★
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Finalmente entendi como funcionam os anúncios e como segmentar corretamente. Em 1 mês já estava tendo resultados que não conseguia em 6 meses antes."</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://placehold.co/80" alt="Homem maduro com barba, sorrindo, vestindo camiseta escura em ambiente de coworking" class="rounded-full w-16 h-16 object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">Marcos Antônio</h4>
                            <div class="flex text-yellow-300 text-sm mt-1">
                                ★ ★ ★ ★ ★
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"O suporte é fantástico! Tive dúvidas sobre a instalação do Pixel e recebi uma resposta em menos de 1 hora com um vídeo explicando tudo."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section id="oferta" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-r from-green-900/40 to-green-800/30 rounded-3xl p-8 md:p-12 border border-white/10 overflow-hidden">
                <div class="relative z-10 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="heading-font text-4xl font-bold mb-6">Comece Agora Mesmo <span class="gradient-text">Por Apenas R$19,97</span></h2>
                        <p class="text-lg text-gray-200 mb-8">Este é um investimento pequeno para ter acesso a um conhecimento que pode transformar seus resultados online. Garanta agora mesmo!</p>
                        
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>Acesso vitalício ao material atualizado</span>
                            </li>
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>Suporte exclusivo para alunos</span>
                            </li>
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>Bônus exclusivos para os primeiros compradores</span>
                            </li>
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>7 dias de garantia incondicional</span>
                            </li>
                        </ul>
                        
                        <div class="mb-8">
                            <div class="inline-flex items-center space-x-4 bg-black/40 px-6 py-3 rounded-full">
                                <span class="text-2xl font-bold line-through text-gray-400">R$ 90,00</span>
                                <span class="text-4xl font-bold text-green-400">R$ 19,97</span>
                                <span class="px-3 py-1 bg-green-900/40 text-green-400 rounded-full text-sm">85% OFF</span>
                            </div>
                        </div>
                        
                        <a href="https://kiwify.com.br/SEU-LINK-AQUI" class="btn-primary inline-block w-full lg:w-auto text-center">
                            QUERO GARANTIR MEU ACESSO AGORA
                        </a>
                        
                        <div class="mt-4 text-sm text-gray-300">
                            Pagamento 100% seguro via Kiwify | Suporte 24/7
                        </div>
                    </div>
                    
                    <div class="flex justify-center">
                        <div class="relative max-w-md w-full">
                            <img src="https://placehold.co/600x800" alt="Mockup de celular mostrando plataforma de ensino com interface moderna em tons de preto e verde, exibindo módulos do curso" class="rounded-xl shadow-2xl w-full">
                            <div class="absolute -inset-4 -z-10 bg-gradient-to-tr from-green-500/30 to-blue-500/20 rounded-2xl blur-lg"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">Perguntas <span class="gradient-text">Frequentes</span></h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Tire suas dúvidas sobre o curso e como ele pode te ajudar.</p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Para quem é este curso?
                    </h3>
                    <p class="text-gray-300 pl-9">Este curso é perfeito para iniciantes que querem aprender tráfego pago do zero ou para quem já tem alguma experiência mas quer melhorar seus resultados. Não é necessário nenhum conhecimento prévio - começamos do absoluto básico.</p>
                </div>
                
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Por quanto tempo terei acesso?
                    </h3>
                    <p class="text-gray-300 pl-9">O acesso é vitalício! Você terá acesso a todas as atualizações do material sem custo adicional. Nosso compromisso é manter o conteúdo sempre atualizado com as melhores práticas do mercado.</p>
                </div>
                
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Como é feita a compra?
                    </h3>
                    <p class="text-gray-300 pl-9">A compra é feita 100% online através da plataforma Kiwify, totalmente segura e com processamento de pagamento rápido. Você pode pagar com cartão de crédito, débito ou boleto bancário.</p>
                </div>
                
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        E se eu não gostar do curso?
                    </h3>
                    <p class="text-gray-300 pl-9">Oferecemos 7 dias de garantia incondicional. Se por qualquer motivo você não estiver satisfeito, basta nos enviar um email dentro deste prazo e devolvemos 100% do seu dinheiro, sem perguntas.</p>
                </div>
                
                <div class="feature-card p-8">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Quando vou receber o acesso?
                    </h3>
                    <p class="text-gray-300 pl-9">O acesso é liberado imediatamente após a confirmação do pagamento. Para cartões de crédito e débito, isso geralmente ocorre em poucos minutos. No caso de boleto, pode levar até 3 dias úteis para a compensação.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="py-16 bg-black/70 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="heading-font textOferecemos - possível já que o4xl font-bold mb-6">Está Pronto Para <span class="gradient-text">Transformar</span> Seus Resultados?</h2>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto mb-8">Não perca essa oportunidade de aprender tráfego pago de forma simples e prática por um valor especial por tempo limitado.</p>
            <a href="https://kiwify.com.br/SEU-LINK-AQUI" class="btn-primary inline-block mb-6">
                QUERO GARANTIR MEU ACESSO POR R$19,97
            </a>
            <p class="text-sm text-gray-400">Oferecemos 7 dias de garantia. Risco zero para você!</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-black border-t border-white/10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center">
                <p class="text-gray-400 text-sm">© 2023 Domine o Tráfego Pago. Todos os direitos reservados.</p>
                <p class="text-gray-500 text-xs mt-2">Este produto não garante resultados. Os resultados podem variar de acordo com o empenho e dedicação de cada aluno.</p>
            </div>
        </div>
    </footer>

    <script>
        // Animações simples para melhorar a experiência
        document.addEventListener('DOMContentLoaded', function() {
            // Animação suave para links internos
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    if(targetId === '#') return;
                    
                    const targetElement = document.querySelector(targetId);
                    if(targetElement) {
                        targetElement.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                });
            });
            
            // Adiciona classe de animação quando os elementos entram na viewport
            const observerOptions = {
                threshold: 0.1
            };
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if(entry.isIntersecting) {
                        entry.target.classList.add('animate-fadeIn');
                    }
                });
            }, observerOptions);
            
            document.querySelectorAll('.feature-card').forEach(card => {
                observer.observe(card);
            });
        });
    </script>
</body>
</html>

```

🎨 **Generating images based on descriptions...**

✅ **Images generated successfully! Here's your updated content:**

`index.html`
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domine o Tráfego Pago - De R$90,00 por Apenas R$19,97</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&family=Varela+Round&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00ff88;
            --dark: #121212;
            --darker: #0a0a0a;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--darker);
            color: white;
            overflow-x: hidden;
        }
        
        .heading-font {
            font-family: 'Varela Round', sans-serif;
        }
        
        .btn-primary {
            background-color: var(--primary);
            color: var(--darker);
            font-weight: 700;
            padding: 15px 40px;
            border-radius: 50px;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 255, 136, 0.4);
        }
        
        .btn-primary:active {
            transform: translateY(1px);
        }
        
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .gradient-text {
            background: linear-gradient(90deg, #00ff88, #00b8ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .feature-card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            transition: all 0.3s;
            overflow: hidden;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            border-color: var(--primary);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .check-icon {
            color: var(--primary);
            font-weight: bold;
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(0, 255, 136, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(0, 255, 136, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 255, 136, 0); }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-black/80 to-black/20 z-0"></div>
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/2b17c818-b322-4c24-b471-f95b70d54bf9.png" alt="Background futurístico digital com gráficos de dados, setas ascendentes e elementos abstratos em verde neon representando crescimento e marketing digital" class="absolute inset-0 w-full h-full object-cover opacity-30">
        
        <div class="relative z-10 max-w-7xl mx-auto px-4 py-24 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <span class="inline-block px-4 py-2 rounded-full bg-green-900/30 text-green-400 text-sm mb-4">OFERTA POR TEMPO LIMITADO</span>
                    <h1 class="heading-font text-4xl md:text-6xl font-bold leading-tight mb-6">
                        Domine o <span class="gradient-text">Tráfego Pago</span> e Construa Seu Negócio Online
                    </h1>
                    <p class="text-lg text-gray-300 mb-8">
                        O guia definitivo para iniciantes que querem dominar o marketing digital e multiplicar suas vendas com anúncios pagos, sem complicação!
                    </p>
                    <div class="mb-8">
                        <div class="inline-flex items-center space-x-4 bg-black/40 px-6 py-3 rounded-full">
                            <span class="text-2xl font-bold line-through text-gray-400">R$ 90,00</span>
                            <span class="text-4xl font-bold text-green-400">R$ 19,97</span>
                            <span class="px-3 py-1 bg-green-900/40 text-green-400 rounded-full text-sm">85% OFF</span>
                        </div>
                    </div>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#oferta" class="btn-primary pulse text-center">
                            QUERO GARANTIR MEU ACESSO
                        </a>
                        <a href="#detalhes" class="px-6 py-4 border border-white/20 rounded-full text-center hover:bg-white/5 transition">
                            SAIBA MAIS
                        </a>
                    </div>
                </div>
                <div class="flex justify-center">
                    <div class="relative max-w-md">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/cf258897-abb4-4cd1-aa65-eac8f3e4d898.png" alt="Ebook moderno sobre tráfego pago com capa preta e detalhes em verde neon, mostrando gráficos de crescimento e ícones de mídias sociais" class="floating w-full max-w-xs rounded-xl shadow-2xl transform rotate-1">
                        <div class="absolute -bottom-6 -left-6 -z-10 w-full h-full bg-gradient-to-br from-green-500 to-blue-500 rounded-xl opacity-20"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-black/40 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">10K+</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Alunos</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">4.9</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Avaliação</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">92%</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Conclusão</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">24/7</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Suporte</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="detalhes" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">O Que Você Vai <span class="gradient-text">Aprender</span>?</h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Tudo que você precisa saber para começar a vender com tráfego pago, mesmo que nunca tenha usado antes.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0z"></path>
                            <path d="M9 10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Fundamentos do Tráfego Pago</h3>
                    <p class="text-gray-300">Entenda os pilares essenciais e como usar plataformas como Meta Ads e Google Ads para conseguir clientes.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m16.2 7.8 2.9-2.9"></path>
                            <path d="M18 12h4"></path>
                            <path d="m16.2 16.2 2.9 2.9"></path>
                            <path d="M12 18v4"></path>
                            <path d="m4.9 19.1 2.9-2.9"></path>
                            <path d="M2 12h4"></path>
                            <path d="m4.9 4.9 2.9 2.9"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Criação de Anúncios</h3>
                    <p class="text-gray-300">Aprenda a criar anúncios irresistíveis que convertem e a segmentar o público certo para seu produto.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <rect x="2" y="7" width="20" height="14" rx="2" ry="2"></rect>
                            <path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Pixel e Conversões</h3>
                    <p class="text-gray-300">Domine a instalação do Pixel e acompanhamento de conversões para otimizar seus resultados.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m16.2 7.8 2.9-2.9"></path>
                            <path d="M18 12h4"></path>
                            <path d="m16.2 16.2 2.9 2.9"></path>
                            <path d="M12 18v4"></path>
                            <path d="m4.9 19.1 2.9-2.9"></path>
                            <path d="M2 12h4"></path>
                            <path d="m4.9 4.9 2.9 2.9"></path>
                            <circle cx="12" cy="12" r="3"></circle>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Otimização de Campanhas</h3>
                    <p class="text-gray-300">Aprenda técnicas avançadas para melhorar continuamente seus anúncios e reduzir custos por lead.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M12 16v-4"></path>
                            <path d="M12 8h.01"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Escalando os Resultados</h3>
                    <p class="text-gray-300">Métodos comprovados para escalar suas campanhas bem-sucedidas e atingir mais clientes.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m5 5 2.5 2.5"></path>
                            <path d="M7 12H2"></path>
                            <path d="m19 5-2.5 2.5"></path>
                            <path d="M17 12h5"></path>
                            <circle cx="12" cy="12" r="5"></circle>
                            <path d="m15 9-3 3-3 3"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Bônus Exclusivos</h3>
                    <p class="text-gray-300">Lista de ferramentas, planilhas de acompanhamento e modelos prontos para você replicar.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gradient-to-b from-black/30 to-black/70 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">O Que Dizem Nossos <span class="gradient-text">Alunos</span></h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Veja os resultados de quem já aplicou os métodos ensinados neste curso.</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/968ce310-774a-4368-a08b-c23ffd087847.png" alt="Retrato de homem sorrindo, cerca de 30 anos, em fundo desfocado, usando camisa social clara" class="rounded-full w-16 h-16 object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">Rafael Silva</h4>
                            <div class="flex text-yellow-300 text-sm mt-1">
                                ★ ★ ★ ★ ★
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Consegui aumentar minhas vendas em 300% aplicando apenas os conceitos básicos que aprendi aqui. O investimento valeu cada centavo!"</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/9605225d-c800-48d4-b086-454fb20eb64d.png" alt="Mulher jovem sorrindo, cabelos castanhos, usando óculos, em escritório moderno" class="rounded-full w-16 h-16 object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">Ana Carolina</h4>
                            <div class="flex text-yellow-300 text-sm mt-1">
                                ★ ★ ★ ★ ★
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"Finalmente entendi como funcionam os anúncios e como segmentar corretamente. Em 1 mês já estava tendo resultados que não conseguia em 6 meses antes."</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/28f35e7f-13b2-494b-819c-d549725581fa.png" alt="Homem maduro com barba, sorrindo, vestindo camiseta escura em ambiente de coworking" class="rounded-full w-16 h-16 object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">Marcos Antônio</h4>
                            <div class="flex text-yellow-300 text-sm mt-1">
                                ★ ★ ★ ★ ★
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">"O suporte é fantástico! Tive dúvidas sobre a instalação do Pixel e recebi uma resposta em menos de 1 hora com um vídeo explicando tudo."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section id="oferta" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-gradient-to-r from-green-900/40 to-green-800/30 rounded-3xl p-8 md:p-12 border border-white/10 overflow-hidden">
                <div class="relative z-10 grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <h2 class="heading-font text-4xl font-bold mb-6">Comece Agora Mesmo <span class="gradient-text">Por Apenas R$19,97</span></h2>
                        <p class="text-lg text-gray-200 mb-8">Este é um investimento pequeno para ter acesso a um conhecimento que pode transformar seus resultados online. Garanta agora mesmo!</p>
                        
                        <ul class="space-y-4 mb-8">
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>Acesso vitalício ao material atualizado</span>
                            </li>
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>Suporte exclusivo para alunos</span>
                            </li>
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>Bônus exclusivos para os primeiros compradores</span>
                            </li>
                            <li class="flex items-start">
                                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="check-icon mr-3 mt-1 flex-shrink-0">
                                    <polyline points="20 6 9 17 4 12"></polyline>
                                </svg>
                                <span>7 dias de garantia incondicional</span>
                            </li>
                        </ul>
                        
                        <div class="mb-8">
                            <div class="inline-flex items-center space-x-4 bg-black/40 px-6 py-3 rounded-full">
                                <span class="text-2xl font-bold line-through text-gray-400">R$ 90,00</span>
                                <span class="text-4xl font-bold text-green-400">R$ 19,97</span>
                                <span class="px-3 py-1 bg-green-900/40 text-green-400 rounded-full text-sm">85% OFF</span>
                            </div>
                        </div>
                        
                        <a href="https://kiwify.com.br/SEU-LINK-AQUI" class="btn-primary inline-block w-full lg:w-auto text-center">
                            QUERO GARANTIR MEU ACESSO AGORA
                        </a>
                        
                        <div class="mt-4 text-sm text-gray-300">
                            Pagamento 100% seguro via Kiwify | Suporte 24/7
                        </div>
                    </div>
                    
                    <div class="flex justify-center">
                        <div class="relative max-w-md w-full">
                            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/2e0d7a44-3a09-45c0-b2c9-ead0f4e42ef3.png" alt="Mockup de celular mostrando plataforma de ensino com interface moderna em tons de preto e verde, exibindo módulos do curso" class="rounded-xl shadow-2xl w-full">
                            <div class="absolute -inset-4 -z-10 bg-gradient-to-tr from-green-500/30 to-blue-500/20 rounded-2xl blur-lg"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">Perguntas <span class="gradient-text">Frequentes</span></h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Tire suas dúvidas sobre o curso e como ele pode te ajudar.</p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Para quem é este curso?
                    </h3>
                    <p class="text-gray-300 pl-9">Este curso é perfeito para iniciantes que querem aprender tráfego pago do zero ou para quem já tem alguma experiência mas quer melhorar seus resultados. Não é necessário nenhum conhecimento prévio - começamos do absoluto básico.</p>
                </div>
                
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Por quanto tempo terei acesso?
                    </h3>
                    <p class="text-gray-300 pl-9">O acesso é vitalício! Você terá acesso a todas as atualizações do material sem custo adicional. Nosso compromisso é manter o conteúdo sempre atualizado com as melhores práticas do mercado.</p>
                </div>
                
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Como é feita a compra?
                    </h3>
                    <p class="text-gray-300 pl-9">A compra é feita 100% online através da plataforma Kiwify, totalmente segura e com processamento de pagamento rápido. Você pode pagar com cartão de crédito, débito ou boleto bancário.</p>
                </div>
                
                <div class="feature-card p-8 mb-6">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        E se eu não gostar do curso?
                    </h3>
                    <p class="text-gray-300 pl-9">Oferecemos 7 dias de garantia incondicional. Se por qualquer motivo você não estiver satisfeito, basta nos enviar um email dentro deste prazo e devolvemos 100% do seu dinheiro, sem perguntas.</p>
                </div>
                
                <div class="feature-card p-8">
                    <h3 class="text-xl font-bold mb-4 flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400 mr-3">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M9.09 9a3 3 0 0 1 5.83 1c0 2-3 3-3 3"></path>
                            <path d="M12 17h.01"></path>
                        </svg>
                        Quando vou receber o acesso?
                    </h3>
                    <p class="text-gray-300 pl-9">O acesso é liberado imediatamente após a confirmação do pagamento. Para cartões de crédito e débito, isso geralmente ocorre em poucos minutos. No caso de boleto, pode levar até 3 dias úteis para a compensação.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="py-16 bg-black/70 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="heading-font textOferecemos - possível já que o4xl font-bold mb-6">Está Pronto Para <span class="gradient-text">Transformar</span> Seus Resultados?</h2>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto mb-8">Não perca essa oportunidade de aprender tráfego pago de forma simples e prática por um valor especial por tempo limitado.</p>
            <a href="https://kiwify.com.br/SEU-LINK-AQUI" class="btn-primary inline-block mb-6">
                QUERO GARANTIR MEU ACESSO POR R$19,97
            </a>
            <p class="text-sm text-gray-400">Oferecemos 7 dias de garantia. Risco zero para você!</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-12 bg-black border-t border-white/10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center">
                <p class="text-gray-400 text-sm">© 2023 Domine o Tráfego Pago. Todos os direitos reservados.</p>
                <p class="text-gray-500 text-xs mt-2">Este produto não garante resultados. Os resultados podem variar de acordo com o empenho e dedicação de cada aluno.</p>
            </div>
        </div>
    </footer>

    <script>
        // Animações simples para melhorar a experiência
        document.addEventListener('DOMContentLoaded', function() {
            // Animação suave para links internos
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    if(targetId === '#') return;
                    
                    const targetElement = document.querySelector(targetId);
                    if(targetElement) {
                        targetElement.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                });
            });
            
            // Adiciona classe de animação quando os elementos entram na viewport
            const observerOptions = {
                threshold: 0.1
            };
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if(entry.isIntersecting) {
                        entry.target.classList.add('animate-fadeIn');
                    }
                });
            }, observerOptions);
            
            document.querySelectorAll('.feature-card').forEach(card => {
                observer.observe(card);
            });
        });
    </script>
</body>
</html>

```
### YOU
me manda os codigos exatamente como voce deixou esse explo do lado quero meu site assim. e retira isso ''### Generated by BLACKBOX.AI https://www.blackbox.ai ### YOU monte uma pagina de vendas pra mim anunciar um produto que a aba de pagamento sera na kiwify, faça algo preto com verde e graficos de funco, sera sobre trafego pago para iniciante, de 90,00 reais por 19,97, algo moderno e orinal, fontes arredondas para chamar a atençao e vender, botoes animados e de acordo com o site. ### BLACKBOX.AI Vou criar uma página de vendas moderna com o tema preto e verde, focada em tráfego pago para iniciantes, com design atrativo, botões animados e integração com Kiwify. O layout será responsivo e persuasivo, com uma abordagem direta para conversão. `index.html` ```html''
### BLACKBOX.AI

Claro! Aqui está o código da página de vendas, formatado conforme solicitado, sem as informações adicionais:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domine o Tráfego Pago - De R$90,00 por Apenas R$19,97</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700;800&family=Varela+Round&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #00ff88;
            --dark: #121212;
            --darker: #0a0a0a;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--darker);
            color: white;
            overflow-x: hidden;
        }
        
        .heading-font {
            font-family: 'Varela Round', sans-serif;
        }
        
        .btn-primary {
            background-color: var(--primary);
            color: var(--darker);
            font-weight: 700;
            padding: 15px 40px;
            border-radius: 50px;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0, 255, 136, 0.4);
        }
        
        .btn-primary:active {
            transform: translateY(1px);
        }
        
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        .gradient-text {
            background: linear-gradient(90deg, #00ff88, #00b8ff);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .feature-card {
            background: rgba(255, 255, 255, 0.03);
            border: 1px solid rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            transition: all 0.3s;
            overflow: hidden;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            border-color: var(--primary);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .check-icon {
            color: var(--primary);
            font-weight: bold;
        }
        
        .pulse {
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(0, 255, 136, 0.7); }
            70% { box-shadow: 0 0 0 10px rgba(0, 255, 136, 0); }
            100% { box-shadow: 0 0 0 0 rgba(0, 255, 136, 0); }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-black/80 to-black/20 z-0"></div>
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/2b17c818-b322-4c24-b471-f95b70d54bf9.png" alt="Background futurístico digital com gráficos de dados, setas ascendentes e elementos abstratos em verde neon representando crescimento e marketing digital" class="absolute inset-0 w-full h-full object-cover opacity-30">
        
        <div class="relative z-10 max-w-7xl mx-auto px-4 py-24 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <span class="inline-block px-4 py-2 rounded-full bg-green-900/30 text-green-400 text-sm mb-4">OFERTA POR TEMPO LIMITADO</span>
                    <h1 class="heading-font text-4xl md:text-6xl font-bold leading-tight mb-6">
                        Domine o <span class="gradient-text">Tráfego Pago</span> e Construa Seu Negócio Online
                    </h1>
                    <p class="text-lg text-gray-300 mb-8">
                        O guia definitivo para iniciantes que querem dominar o marketing digital e multiplicar suas vendas com anúncios pagos, sem complicação!
                    </p>
                    <div class="mb-8">
                        <div class="inline-flex items-center space-x-4 bg-black/40 px-6 py-3 rounded-full">
                            <span class="text-2xl font-bold line-through text-gray-400">R$ 90,00</span>
                            <span class="text-4xl font-bold text-green-400">R$ 19,97</span>
                            <span class="px-3 py-1 bg-green-900/40 text-green-400 rounded-full text-sm">85% OFF</span>
                        </div>
                    </div>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#oferta" class="btn-primary pulse text-center">
                            QUERO GARANTIR MEU ACESSO
                        </a>
                        <a href="#detalhes" class="px-6 py-4 border border-white/20 rounded-full text-center hover:bg-white/5 transition">
                            SAIBA MAIS
                        </a>
                    </div>
                </div>
                <div class="flex justify-center">
                    <div class="relative max-w-md">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/cf258897-abb4-4cd1-aa65-eac8f3e4d898.png" alt="Ebook moderno sobre tráfego pago com capa preta e detalhes em verde neon, mostrando gráficos de crescimento e ícones de mídias sociais" class="floating w-full max-w-xs rounded-xl shadow-2xl transform rotate-1">
                        <div class="absolute -bottom-6 -left-6 -z-10 w-full h-full bg-gradient-to-br from-green-500 to-blue-500 rounded-xl opacity-20"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-black/40 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">10K+</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Alunos</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">4.9</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Avaliação</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">92%</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Conclusão</div>
                </div>
                <div class="bg-white/5 backdrop-blur-sm p-6 rounded-xl border border-white/5">
                    <div class="text-4xl font-bold text-green-400 mb-2">24/7</div>
                    <div class="text-white/70 text-sm uppercase tracking-wider">Suporte</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="detalhes" class="py-20 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">O Que Você Vai <span class="gradient-text">Aprender</span>?</h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Tudo que você precisa saber para começar a vender com tráfego pago, mesmo que nunca tenha usado antes.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0z"></path>
                            <path d="M9 10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-4z"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Fundamentos do Tráfego Pago</h3>
                    <p class="text-gray-300">Entenda os pilares essenciais e como usar plataformas como Meta Ads e Google Ads para conseguir clientes.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m16.2 7.8 2.9-2.9"></path>
                            <path d="M18 12h4"></path>
                            <path d="m16.2 16.2 2.9 2.9"></path>
                            <path d="M12 18v4"></path>
                            <path d="m4.9 19.1 2.9-2.9"></path>
                            <path d="M2 12h4"></path>
                            <path d="m4.9 4.9 2.9 2.9"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Criação de Anúncios</h3>
                    <p class="text-gray-300">Aprenda a criar anúncios irresistíveis que convertem e a segmentar o público certo para seu produto.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <rect x="2" y="7" width="20" height="14" rx="2" ry="2"></rect>
                            <path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Pixel e Conversões</h3>
                    <p class="text-gray-300">Domine a instalação do Pixel e acompanhamento de conversões para otimizar seus resultados.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m16.2 7.8 2.9-2.9"></path>
                            <path d="M18 12h4"></path>
                            <path d="m16.2 16.2 2.9 2.9"></path>
                            <path d="M12 18v4"></path>
                            <path d="m4.9 19.1 2.9-2.9"></path>
                            <path d="M2 12h4"></path>
                            <path d="m4.9 4.9 2.9 2.9"></path>
                            <circle cx="12" cy="12" r="3"></circle>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Otimização de Campanhas</h3>
                    <p class="text-gray-300">Aprenda técnicas avançadas para melhorar continuamente seus anúncios e reduzir custos por lead.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <circle cx="12" cy="12" r="10"></circle>
                            <path d="M12 16v-4"></path>
                            <path d="M12 8h.01"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Escalando os Resultados</h3>
                    <p class="text-gray-300">Métodos comprovados para escalar suas campanhas bem-sucedidas e atingir mais clientes.</p>
                </div>
                
                <div class="feature-card p-8">
                    <div class="w-16 h-16 rounded-xl bg-green-400/10 flex items-center justify-center mb-6">
                        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-green-400">
                            <path d="M12 2v4"></path>
                            <path d="m5 5 2.5 2.5"></path>
                            <path d="M7 12H2"></path>
                            <path d="m19 5-2.5 2.5"></path>
                            <path d="M17 12h5"></path>
                            <circle cx="12" cy="12" r="5"></circle>
                            <path d="m15 9-3 3-3 3"></path>
                        </svg>
                    </div>
                    <h3 class="text-xl font-bold mb-4">Bônus Exclusivos</h3>
                    <p class="text-gray-300">Lista de ferramentas, planilhas de acompanhamento e modelos prontos para você replicar.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gradient-to-b from-black/30 to-black/70 relative overflow-hidden">
        <div class="absolute inset-0 bg-grid-white/5"></div>
        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="heading-font text-4xl font-bold mb-6">O Que Dizem Nossos <span class="gradient-text">Alunos</span></h2>
                <p class="max-w-2xl mx-auto text-lg text-gray-300">Veja os resultados de quem já aplicou os métodos ensinados neste curso.</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                <div class="feature-card p-8">
                    <div class="flex items-center mb-6">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b
