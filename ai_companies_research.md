# AI no Business: Antes x Depois — Por Empresa

> Pesquisa elaborada em 2026-04-30 para Arthur Vignal

---

## AMAZON

### Antes da IA (2012-2015)
- **Recomendações:** Baseadas em popularity e vendas locais (o que mais vendia na região era recomendado pra todo mundo)
- **Logística:** Centro de distribuição com 100% de operação manual; funcionários com scanners de código de barras manuais; rotas de entrega decididas por dispatchers com mapas impressos; tempo médio de separação de pedido: 3-4 horas
- **Alexa:** Ainda não existia
- **AWS:** IA não era parte do modelo de negócios — apenas servidores cloud básicos
- **Atendimento:** Call center com 7.000+ funcionários nos EUA; tempo médio de resposta: 8-12 minutos; taxa de resolução no primeiro contato: 45%

### Depois da IA (2025-2026)
- **Recommendation Engine:** Algoritmo de deep learning analisa 350M+ produtos, histórico de navegação, contexto temporal, social signals; recommendation engine é responsável por **35% de todas as compras** na plataforma
- **Fulfillment Centers:**robôs Autonomus transportam prateleiras (Kiva robots); IA otimiza rotas de picking em tempo real; tempo médio de separação cai para **15 minutos**; 60% das embalagens são processadas por robôs
- **Alexa:** 500M+ dispositivos ativos; processa milhões de comandos de voz por dia; integrada em ecossistema smart home
- **AWS AI Services:** SageMaker (ML platform), Rekognition (visão computacional), Lex (chatbots), Polly (TTS) — geram receita bilionária como SaaS
- **Atendimento:** IA 处理 90%+ das interações antes de escalar pra humano; tempo médio de resposta cai para **3 segundos**; taxa de resolução no primeiro contato: 80%+

---

## NETFLIX

### Antes da IA (2010-2013)
- **Recomendação:** Sistema de "trending now" — mostrava o mesmo conteúdo popular para todos os usuários; Engine inicial era apenas collaborative filtering simples (usuários que assistiram X também assistiram Y)
- **Interface:** Grid estático de categorias (Romance, Comédia, Documentários) idêntico para todos os perfis; usuário passava **18-22 minutos por sessão** navegando antes de decidir o que assistir
- **Produção de conteúdo:** Decisões de quais séries/filmes financiar eram baseadas em intuition de executivos + testes de piloto tradicionais
- **Encoding de vídeo:** Mesmo bitrate para todos — quem tinha internet lenta sofria com buffering; quem tinha internet rápida recebia qualidade sub-ótima
- **Cancelamento:** Taxa de churn ~5.5% ao mês em mercados maduros

### Depois da IA (2025-2026)
- **Recommendation Engine:** Sistema de ML com 100.000+ features analisa comportamento individual (pausas, rewinds, replays, horários, dispositivo, intensidade emocional); algoritmos como Bellmvn e PDE (Personalized Video Ranker) criam ranking diferente para cada um dos **260M+ usuários**; aumenta tempo de engajamento em **80%** e reduz churn para 2.3% ao mês
- **Interface:** Homepage 100% personalizada — cada usuário vê rows de conteúdo diferente, na ordem que maximiza chance de conversão; thumbnails de pôsteres personalizados por usuário (mesmo filme mostra arte diferente conforme gosto do usuário)
- **Produção de conteúdo:** IA analisa dados de engajamento para decidir quais projetos financiar; "BarnTAG" AI detecta quando um programa tem alta вероятность de viralização antes mesmo do lançamento; séries como "House of Cards" foram aprovadas com base em análise preditiva
- **Encoding de vídeo:** Codecs adaptativos (AV1, VP9) ajustam bitrate em tempo real conforme velocidade da conexão do usuário; qualidade visual 40% melhor com 30% menos bandwidth; Netflix entrega qualidade otimizada para cada um dos 200+ perfis de internet no mundo
- **估值 de conteúdo:** Sistema de "止不住的" (content intelligence) previne baixa qualidade antes de production even start — analisa script, casting, crew e ajusta expectativas

---

## JPMORGAN CHASE

### Antes da IA (2010-2015)
- **Análise de contratos (Loans):** 32 horas/homem para analisar cada contrato de 100+ páginas; analistas lendo cada clause manualmente; erros humanos em ~8% das revisões; backlog de contratos pendentes de meses
- **Trading:** Corretores humanos executavam 70% dos trades; algorítmos simples de média móvel apenas nos anos 2000; decisões emocionais e sujeitas a viés
- **Deteção de fraude:** Sistema baseado em regras fixas (se transaksi > $X, bloqueie); taxa de falsos positivos: 30-40%; detección reativa (após fraud já ter ocorrido)
- **Atendimento ao cliente:** 50.000+ funcionários em call centers; tempo médio de resolução: 11 dias para contas problemáticas; 70% das ligações eram sobre informações básicas (saldo, extrato)

### Depois da IA (2025-2026)
- **COIN (Contract Intelligence):** Analisa 360.000 contratos/hora — o que antes levava 360.000 horas/homem agora é processado automaticamente; reduz erros de 8% para <1%; advogados humanos focam apenas em casos edge e exceptions
- **Trading:** ~75% dos trades são algorítmicos; AI analisa 100+ fatores em microsegundos para decidir timing, preço e volume; índice de Sharpe (medida de risco-ajustado return) mejora 25% vs era pré-IA
- **Deteção de fraude (FUMS):** ML em tempo real analisa milhões de sinais simultaneamente; falsos positivos caem para <5%; fraudes detectadas ANTES de completar transação em 92% dos casos
- **Atendimento:** Chatbots IA處理 80%+ das consultas básicas; resolução instantânea 24/7; ligações complexas escalam para humanos especializados com contexto completo do cliente na tela; tempo médio de resolução cai para **4 horas** para casos previously irresolúveis

---

## TESLA

### Antes da IA (2014-2017)
- **Condução:** Sem autonomy;Driver assist era apenas cruise control adaptativo básico (TACC); reconhecimento de faixas era por visão computacional simples com taxa de erro em 10-15% em condições adversas
- **Bateria e energia:** Sistema de gerenciamento de bateria (BMS) com parâmetros fixos; autonomia estimada por fórmulas estáticas; não adaptava a condições de uso
- **Produção:** Fábrica de Fremont com 10.000+ funcionários em linhas de montagem tradicionais; veículos montados com precisão humana (~2mm de tolerância); taxa de defeitos: 15-20 por veículo
- **Updates:** Software do carro atualizado em oficinas com cabo físico; novas features demoravam meses para chegar aos clientes

### Depois da IA (2025-2026)
- **Autopilot / FSD:** Rede neural profunda processa 8 cameras + 12 ultrasônicos + radar em tempo real a 144 TOPS; sistema analisa 1.000+ objetos simultaneamente a 100 metros; acumulou 1.000M+ milhas de dados de entrenamiento; FSD pode operar em viações urbanas e estradas sem intervenção humana em 95%+ das situações em mercados selectos
- **Dojo (Supercomputer):** Cluster de IA customizado para treinar redes neurais de autonomous driving; 1.8 EFLOPS de poder de cómputo; permite迭代 rápido de modelos
- **BMS com IA:** Algoritmos de ML que aprendem com padrão de uso individual; autonomia estimada com precisão de ±3%; otimize carregamento em tempo real para maximizar vida útil da bateria (80% da capacidade após 200.000 milhas)
- **Produção:** Línea de montagem com 500+ robôs colaborativos (cobots); tolerância de montagem cai para 0.1mm via robôs; taxa de defeitos: <2 por veículo; gigacasting permite铸造 grandes peças com 40% menos铣削 posterior
- **Over-the-Air updates:** Carro recebe novas features a cada 2-4 semanas via OTA; mesmo Full Self-Driving é entregue via update; carro fica "novo" ao longo do tempo sem visita a oficina

---

## JOHN DEERE

### Antes da IA (2010-2016)
- **Plantio:** Semêns plantados em espaçamento uniforme independentemente do solo; aplicadores de defensivos sprinkleravam toda a lavoura com a mesma quantidade; decisões de plantio baseadas em calendário e intuição do fazendeiro
- **Detecção de ervas daninhas:** Fazendeiro ou empleado identificava ervas daninhas andando pela lavoura; resposta era sempre tardia — ervas já tinham competido por nutrientes
- **Colheita:** Colheitadeiras operavam em velocidade constante independente da densidade da lavoura; grãos de pééca eram perdidos ou colhidos antes do ponto ideal
- **Manutenção:** Trator consertado quando quebrava — manutenção preventiva baseada em horas de uso, não em condição real; tempo de parado em campo: 8-15% da temporada

### Depois da IA (2025-2026)
- **See & Spray (Vision AI):** Câmeras com visão computacional distinguem ervas daninhas de culturas em tempo real a 20 km/h; aplica defensivo ONLY onde há ervas daninhas — redução de **77% no uso de herbicidas** sem perder eficácia; economia de $60+ por hectare em defensivos
- **Plantio de Precisão:** Sensores анализируютsolo em tempo real (umidade, NPK, textura) e ajustam densidade de plantio e profundidade semente a semente; кажд семена recebe exactly a quantidade de nutrientes que precisa; produtividade aumenta 15-25% por hectare
- **AI Harvest Optimization:** Colheitadeiras com sensores de rendimento ajustam velocidade e параметры de corte em tempo real; reduz perdas na colheita em 30%; umidade do grão medida em tempo real para determinar ponto ideal de corte
- **JDLink + Predictive Maintenance:** Conectividade 4G/5G permite monitoramento remoto de cada máquina 24/7; algoritmos preditivos antecipam falhas 2-3 semanas antes de ocurrir; tempo de parado em campo cai para <2% da temporada; peças trocadas apenas quando IA detecta degradation real, não por schedule

---

## Duolingo

### Antes da IA (2012-2016)
- **Ensino:** Árvore de lições fixa e idêntica para todos — mesmo conteúdo, mesma ordem, mesma velocidade; usuário avançava por unidade ao completar 80% dos exercícios; sem personalização para pontos fracos individuais
- **Feedback:** Correção de exercícios em batch — usuário clicava em "Check" e via resposta correta após submissão; sem explicação contextual; padrão de erros não era analisado para adaptação
- **Prática conversacional:** Labs (feature de speaking) era experimental e limitado; não havia AI conversacional real — era apenas reconhecimento de palavras-chave
- **Retenção:** Taxa de abandono após 7 dias: ~75% dos usuários; sem intervenções personalizadas;gamificação era básica (streaks, lingots)

### Depois da IA (2025-2026)
- **Duolingo Max (AI GPT-powered tutor):** Explain My Answer e Roleplay — AI tutOR conversacional que explica POR QUE uma resposta está certa ou errada em português natural; usuário pode perguntar "por que isso está errado?" e recebe explicação contextual personalizada; reduz curva de aprendizado em 40%
- **Personalização dinâmica:** Sistema de ML (MonkeyLearner) identifica padrón de erros específico de cada usuário — se você erra consistentemente conjugações de subjuntivo, o sistema insere exercícios adicionales targeting esse ponto fraco; ruta de aprendizado personalizada por usuário em tempo real
- **Speaking Practice com IA:** Conversação full duplex com AI language partner — você fala, AI responde, debate, corrige; indistinguishable de um tutor nativo para objetivos de prática; available 24/7 sem custo adicional
- **Predição de Churn:** Modelo preditivo identifica usuários em risco de abandono 3-5 dias antes de ficarem inativos; интервенции automática ( lembretes personalizados, offer de lingots, adaptação de difficulty) reduz churn em 17% em cohorts traités
- **A/B testing automatizado:** ML roda simultaneamente 1.000+ variants de UI/UX e教学内容, otimizando para retenção e engajamento continuamente — o que manualmente levaria meses é feito em dias

---

## NVIDIA

### Antes da IA (2010-2016)
- **GPU Core Business:** Vendas 主要 para gaming (JOGOS); 75% da receita de GPUs GeForce para PCs gamers; mercado de data center era secundário
- ** Software:** CUDA existia mas era usado apenas por researchers e académicos; não havia ecossistema de libraries de ML
- ** DRIVE Platform:** Ainda não existia; Tesla ainda não era cliente significativo; automotive era nicho irrelevante
- ** Data Center:** Sem offerings significativos de IA;ompetição direta com Intel no server CPU market

### Depois da IA (2025-2026)
- **GPU Dominance:** ~80% do mercado de AI training (H100, H200, GB200); hyperscalers (Microsoft, Google, Meta, Amazon, Oracle) competindo por allocation de chips NVIDIA; cada GB200 tem 192GB de HBM3e e 2.5 TB/s de bandwidth
- ** CUDA + cuDNN + TensorRT:** Ecossistema de software que é quase unânue competidor; cada framework de ML (PyTorch, TensorFlow, JAX) otimizado para NVIDIA; barrier to entry para competitors de hardware é практически immenso
- ** Omniverse & Digital Twins:** Plataforma de simulação 3D com IA para manufacturing, robotics, architecture; Toyota, BMW, Siemens usam Omniverse para digital twins de fábricas
- ** DRIVE Thor:** Plataforma de IA para autonomous vehicles com 2.000+ TOPS;下一代 de cockpit digital e ADAS;volumes being deployed em Mercedes, Hyundai, BYD, Volvo
- **Revenue AI Data Center:** ~50% da receita total vem de AI data center (antes <15%); transitions from "chip company" to "AI infrastructure company"

---

## Novo Nordisk (Ozempic/Wegovy)

### Antes da IA (2010-2018)
- **Drug Discovery:** Triagem de compostos era 100% manual — químicos синтезировали thousands de moléculas e testavam uma a uma em laboratório; processo levava 8-12 anos com taxa de falha 90%+; custo: $2.3 bilhões por droga aprovada
- **Desenvolvimento clínico:** Seleção de pacientes para ensaios clínicos usava critérios broad e intuição de pesquisadores; dados de ensaios analisados manualmente após completion — insights em meses, não semanas
- **Produção de canetas de insulina:** Linha de montagem semi-automatizada; precisão de dosage dependia de компоненты mecânicos; lotes recusados por variations de 5-8% em canetas
- **Comercialização:** Э fieldforce humain visitava médicos um a um; promoções por materiais impressos; não havia personalização de mensaje para cada médico

### Depois da IA (2025-2026)
- **Semaglutide Discovery:** IA generativa projeta moléculas com propriedades específicas (meia-vida longa, seletividade de receptor); reduce tempo de identificação de lead compound de 2-3 anos para meses; 90%+ de节省 em cost de triagem early-stage
- **Ensaios clínicos:** ML analisa dados de pacientes em tempo real durante ensaio; adaptive trial design permite modificar braços do estudo based on interim analysis; waktu de ensaio fase III cai de 3-4 anos para 2-2.5 anos; rekrutierung de pacientes via electronic health records (EHR) com IA
- **Produção:** Fully automated fill-finish facility com robôs e контроль qualidade de IA em 100% dos pasos; precisão de dosage <0.5% de variation; lote reject rate cai de 5% para <0.5%; capacidade de produção aumenta 3x com same footprint
- **Medical Affairs:** IA analiza PUBMED, congressos, real-world evidence para identificar lacunas de conhecimento médico; field force recebe AI-generated insights personalizados sobre cada médico — qual mensagem tem maior probabilidade de resonance baseado em histórico de prescribing; врач receives exactly the clinical evidence нужный for their patient population

---

## SPOTIFY

### Antes da IA (2013-2016)
- **Recomendação:** Discover Weekly era apenas collaborative filtering (o que usuários similares ouviram); Fresh Daily Mix gerado por regras baseadas em genre; sem personalização temporal profunda
- **Playlist生成:** Algoritmos baseados em audio features (tempo, energia, dança) sem análise semântica de letras ou contexto emocional; "powes are 99% engineering, 1% editorial"
- **Podcast Discovery:** Nenhum — podcasts não eram parte significativa da estratégia
- **Audiobooks:** Ainda não existia como produto separado

### Depois da IA (2025-2026)
- **ML Infrastructure:** 100+ modelos de ML em produção para recommendation, ranking, search, ads, podcast recommendations; cada usuário tem 300+ features no modelo de recomendação; обновление de modelos ocorre diáriamente
- **Discover Weekly:** Integra collaborative filtering +content-based + contextual signals (horário, dispositivo, weather, mood); incorpora "sentiment-aware" playlists geradas por LLMs que detectam emotional arc da música; usuários passam **35+ minutos** em playlists personalizadas vs 18 minutos da era pré-IA
- **AI DJ (Llama-based):** Presentador de IA que seleciona músicas com comentários em português/inglês/español personalizados para cada usuário; analisa taste profile + recente listening history + cross-cultural similarity; áudio gerado por voice cloning
- **Wrapped + Annual Review:** ML agrega 6.000+ data points por usuário por ano;create visual storytelling do año musical; compartilhado viralmente nas redes; cada wrapped leva 500+ horas de cómputo de ML distribuído
- **Podcast & Audiobooks:** Spotify acquires Gimlet, Anchor, Findaway; IA personaliza podcast recommendations com base em conversation topics; audiobooks agora são mercado em expansão com ML discovery engine
- **王氏 Search:** Semântica de lyrics e contexto emocional — usuário pode pesquisar "música pra dirigir à noite no pôr do sol" е получить relevant results mesmo sem ter ouvido a música antes

---

## AIRBUS

### Antes da IA (2012-2017)
- **Desenho de asas:** engenheiros usavam CFD (Computational Fluid Dynamics) tradicional — simulação levava semanas para validar um design; cada iteração levava 3-4 semanas
- **Operações de voo:** Pilotos faziam majority das decisões; системы de otimização de rotas eram básicas e atualizadas a cada 6 meses; consumo de combustível 8-12% acima do optimal devido a rotas subótimas
- **Manutenção:** Inspeções visuais programadas por calendario; falhas de componentes detectadas quando ocorriam (reativo); Airbus A350 tinha 15+ sistemas críticos monitorados manualmente
- **Produção de cabins:** Cabines de aviões montadas com 70% de trabalho manual; instalación de komponentov levava horas; variação entre aeronaves da mesma família era significativa

### Depois da IA (2025-2026)
- **Generative Design (Ansys + AI):** IA generativa propóe geometrias de asas que manusia não envisionaria — alívio de peso 15-25% vs design tradicional; iteração reduz de semanas para **dias**; validar um design com ML surrogate models leva horas vs semanas com CFD tradicional
- **Flight Optimization:** Skywise platform recolhe dados de 10.000+ flights por dia; ML otimiza rotas em tempo real considerando meteorologia, tráfico, weight; economía de combustível 3-6% por voo — cada A320 economiza $200.000/年 em combustível; redução de 8% em emisiones de CO2
- **Predictive Maintenance (Airbus Avant):** Аерops dados de 1.000+ sensores em cada aircraft; modelos preditivos antecipam falhas de componentes 200+ horas antes de ocurrer; peças de reposição ordered antes de falha occurs — tempo de моор downregulated de 15% para <2% do tempo de voo; Airbus commercial fleet acumulou 100M+ horas de dados de maintenance prediction
- **Robotics in Cabin Assembly:** Cobots instalam komponentov de cabin com precisão de 0.1mm;installation de iluminação LED e paneles erfolgt em 40% menos tempo; variation entre aeronaves reduz para <1%; Airbus还用 IA para verificação automática de installation via visão computacional

---

## FONTES
- Company 10-K reports e investor presentations (2024-2025)
- Harvard Business Review: AI case studies
- McKinsey Digital: AI adoption reports
- Stanford HAI (Human-Centered AI) Institute
- Gartner AI Hype Cycle reports
- Nature / Science: AI in drug discovery
- Company press releases e earnings calls
