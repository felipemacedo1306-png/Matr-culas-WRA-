<!DOCTYPE html>  
<html lang="pt-BR" class="scroll-smooth">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>WRA Sports - Escola de Futebol | Matrículas Abertas</title>  
    <!-- Tailwind CSS CDN -->  
    <script src="https://cdn.tailwindcss.com"></script>  
    <script>  
        tailwind.config = {  
            theme: {  
                extend: {  
                    colors: {  
                        brand: {  
                            dark: '#071318',  
                            card: '#0D1F29',  
                            border: '#1E3A4C',  
                            green: '#10B981',  
                            greenDark: '#059669',  
                            gold: '#FACC15',  
                            goldDark: '#EAB308'  
                        }  
                    }  
                }  
            }  
        }  
    </script>  
    <!-- FontAwesome para ícones -->  
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">  
    <!-- Google Fonts Inter -->  
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400,500,600,700;800&display=swap" rel="stylesheet">  
    <style>  
        body { font-family: 'Inter', sans-serif; }  
    </style>  
</head>  
<body class="bg-brand-dark text-slate-100 antialiased selection:bg-brand-green selection:text-white">  
  
    <!-- Header / Navbar -->  
    <header class="sticky top-0 z-50 bg-brand-dark/95 backdrop-blur-md border-b border-brand-border">  
        <div class="max-w-4xl mx-auto px-4 h-16 flex items-center justify-between">  
            <div class="flex items-center gap-3">  
                <img src="logo-wra.jpg" alt="Logo WRA Sports" class="w-10 h-10 rounded-full object-cover border-2 border-brand-gold shadow-md">  
                <span class="font-extrabold text-lg tracking-wider text-white">WRA <span class="text-brand-green">SPORTS</span></span>  
            </div>  
            <a href="#matricula" class="bg-brand-green hover:bg-brand-greenDark text-white text-sm font-bold px-4 py-2 rounded-xl transition shadow-lg shadow-brand-green/20">  
                Matricular Agora  
            </a>  
        </div>  
    </header>  
  
    <!-- Hero Section -->  
    <section class="relative overflow-hidden pt-8 pb-12 px-4 border-b border-brand-border bg-gradient-to-b from-brand-card to-brand-dark">  
        <div class="max-w-4xl mx-auto text-center">  
            <div class="inline-flex items-center gap-2 bg-brand-border/80 border border-brand-gold/30 px-3 py-1.5 rounded-full text-xs font-semibold text-brand-gold mb-6">  
                <i class="fa-solid fa-fire text-brand-gold"></i> Vagas Limitadas para 2026  
            </div>  
              
            <!-- Logo Grande em Destaque -->  
            <div class="flex justify-center mb-6">  
                <img src="logo-wra.jpg" alt="WRA Sports Escola de Futebol" class="w-28 h-28 rounded-2xl object-cover border-4 border-brand-gold shadow-2xl ring-4 ring-brand-green/20">  
            </div>  
  
            <h1 class="text-3xl md:text-5xl font-extrabold tracking-tight text-white mb-4">  
                Formando <span class="text-brand-green">Atletas</span> & Cidadãos  
            </h1>  
            <p class="text-slate-300 text-sm md:text-base max-w-xl mx-auto mb-8 leading-relaxed">  
                Metodologia profissional de treinamento de futebol para crianças e jovens em Colombo - PR. Garanta a vaga do seu filho em poucos cliques.  
            </p>  
  
            <div class="grid grid-cols-3 gap-3 max-w-lg mx-auto mb-8 text-center">  
                <div class="bg-brand-border/50 p-3 rounded-xl border border-brand-border">  
                    <span class="block font-bold text-brand-gold text-lg">Sub-7 a 17</span>  
                    <span class="text-xs text-slate-400">Categorias</span>  
                </div>  
                <div class="bg-brand-border/50 p-3 rounded-xl border border-brand-border">  
                    <span class="block font-bold text-brand-green text-lg">2 Unidades</span>  
                    <span class="text-xs text-slate-400">Em Colombo</span>  
                </div>  
                <div class="bg-brand-border/50 p-3 rounded-xl border border-brand-border">  
                    <span class="block font-bold text-white text-lg">100%</span>  
                    <span class="text-xs text-slate-400">Prático</span>  
                </div>  
            </div>  
  
            <a href="#matricula" class="inline-flex items-center justify-center gap-2 w-full sm:w-auto bg-gradient-to-r from-brand-green to-brand-greenDark hover:opacity-95 text-white font-bold text-base px-8 py-4 rounded-2xl shadow-xl shadow-brand-green/30 transition transform active:scale-95">  
                <i class="fa-solid fa-futbol"></i> Fazer Matrícula / Aula Experimental  
            </a>  
        </div>  
    </section>  
  
    <!-- Formulário Interativo em Etapas -->  
    <main id="matricula" class="max-w-xl mx-auto px-4 py-12">  
        <div class="bg-brand-card border border-brand-border rounded-3xl p-6 md:p-8 shadow-2xl relative">  
              
            <!-- Indicador de Etapas -->  
            <div class="flex items-center justify-between mb-8 pb-4 border-b border-brand-border text-xs font-semibold text-slate-400">  
                <div id="step-indicator-1" class="flex items-center gap-1.5 text-brand-green">  
                    <span class="w-6 h-6 rounded-full bg-brand-green text-white flex items-center justify-center font-bold text-xs">1</span> Atleta  
                </div>  
                <div class="h-0.5 flex-1 bg-brand-border mx-3"></div>  
                <div id="step-indicator-2" class="flex items-center gap-1.5 text-slate-500">  
                    <span class="w-6 h-6 rounded-full bg-brand-border text-slate-400 flex items-center justify-center font-bold text-xs">2</span> Plano  
                </div>  
                <div class="h-0.5 flex-1 bg-brand-border mx-3"></div>  
                <div id="step-indicator-3" class="flex items-center gap-1.5 text-slate-500">  
                    <span class="w-6 h-6 rounded-full bg-brand-border text-slate-400 flex items-center justify-center font-bold text-xs">3</span> Pagamento  
                </div>  
            </div>  
  
            <form id="formMatricula" onsubmit="enviarMatricula(event)">  
  
                <!-- ETAPA 1: Dados do Atleta -->  
                <div id="etapa-1" class="space-y-4">  
                    <h2 class="text-lg font-bold text-white flex items-center gap-2">  
                        <i class="fa-solid fa-user-pen text-brand-green"></i> 1. Dados do Aluno & Responsável  
                    </h2>  
  
                    <div>  
                        <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Nome Completo do Atleta</label>  
                        <input type="text" id="nomeAtleta" required placeholder="Ex: Lucas Gabriel da Silva" class="w-full bg-brand-dark border border-brand-border rounded-xl px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-green text-sm">  
                    </div>  
  
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">  
                        <div>  
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Data de Nascimento</label>  
                            <input type="date" id="nascimento" required onchange="calcularCategoria()" class="w-full bg-brand-dark border border-brand-border rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-green text-sm">  
                        </div>  
                        <div>  
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Categoria Calculada</label>  
                            <input type="text" id="categoriaCalculada" readonly placeholder="Selecione a data" class="w-full bg-brand-dark/50 border border-brand-border rounded-xl px-4 py-3 text-brand-gold font-bold text-sm cursor-not-allowed">  
                        </div>  
                    </div>  
  
                    <div>  
                        <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Escolha a Unidade WRA</label>  
                        <select id="unidade" required class="w-full bg-brand-dark border border-brand-border rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-green text-sm">  
                            <option value="">Selecione uma unidade...</option>  
                            <option value="Roça Grande - Rod. da Uva, 2152">Unidade Roça Grande (Rod. da Uva, 2152)</option>  
                            <option value="Santa Fé - Av. Santos Dumont, 461">Unidade Santa Fé (Av. Santos Dumont, 461)</option>  
                        </select>  
                    </div>  
  
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">  
                        <div>  
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">Nome do Responsável</label>  
                            <input type="text" id="nomeResponsavel" required placeholder="Seu nome completo" class="w-full bg-brand-dark border border-brand-border rounded-xl px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-green text-sm">  
                        </div>  
                        <div>  
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1">WhatsApp para Contato</label>  
                            <input type="tel" id="whatsapp" required placeholder="(41) 99999-9999" class="w-full bg-brand-dark border border-brand-border rounded-xl px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-green text-sm">  
                        </div>  
                    </div>  
  
                    <button type="button" onclick="irParaEtapa(2)" class="w-full mt-6 bg-brand-green hover:bg-brand-greenDark text-white font-bold py-3.5 rounded-xl transition flex items-center justify-center gap-2 shadow-lg shadow-brand-green/20">  
                        Avançar para Escolha de Plano <i class="fa-solid fa-arrow-right"></i>  
                    </button>  
                </div>  
  
                <!-- ETAPA 2: Escolha de Modalidade / Plano -->  
                <div id="etapa-2" class="space-y-4 hidden">  
                    <h2 class="text-lg font-bold text-white flex items-center gap-2">  
                        <i class="fa-solid fa-tag text-brand-green"></i> 2. Escolha o Plano ou Entrada  
                    </h2>  
                    <p class="text-xs text-slate-400">Selecione como deseja iniciar na WRA Sports:</p>  
  
                    <div class="space-y-3">  
                        <label class="block relative border border-brand-border hover:border-brand-green rounded-2xl p-4 cursor-pointer transition bg-brand-dark/40 has-[:checked]:border-brand-green has-[:checked]:bg-brand-green/10">  
                            <div class="flex items-center justify-between">  
                                <div class="flex items-center gap-3">  
                                    <input type="radio" name="plano" value="Aula Experimental Gratuita (R$ 0,00)" checked class="text-brand-green focus:ring-brand-green h-4 w-4">  
                                    <div>  
                                        <span class="block font-bold text-white text-sm">Aula Experimental</span>  
                                        <span class="text-xs text-slate-400">Conheça a estrutura e participe de um treino</span>  
                                    </div>  
                                </div>  
                                <span class="font-extrabold text-brand-green text-sm">Grátis</span>  
                            </div>  
                        </label>  
  
                        <label class="block relative border border-brand-border hover:border-brand-green rounded-2xl p-4 cursor-pointer transition bg-brand-dark/40 has-[:checked]:border-brand-green has-[:checked]:bg-brand-green/10">  
                            <div class="flex items-center justify-between">  
                                <div class="flex items-center gap-3">  
                                    <input type="radio" name="plano" value="Matrícula + Kit Uniforme (R$ 149,90)" class="text-brand-green focus:ring-brand-green h-4 w-4">  
                                    <div>  
                                        <span class="block font-bold text-white text-sm">Matrícula + Kit Uniforme</span>  
                                        <span class="text-xs text-slate-400">Taxa de matrícula + Camisa, calção e meiões oficiais</span>  
                                    </div>  
                                </div>  
                                <span class="font-extrabold text-brand-gold text-sm">R$ 149,90</span>  
                            </div>  
                        </label>  
  
                        <label class="block relative border border-brand-border hover:border-brand-green rounded-2xl p-4 cursor-pointer transition bg-brand-dark/40 has-[:checked]:border-brand-green has-[:checked]:bg-brand-green/10">  
                            <div class="flex items-center justify-between">  
                                <div class="flex items-center gap-3">  
                                    <input type="radio" name="plano" value="Pacote Completo Matrícula + 1º Mês (R$ 249,90)" class="text-brand-green focus:ring-brand-green h-4 w-4">  
                                    <div>  
                                        <span class="block font-bold text-white text-sm">Pacote Completo (Matrícula + 1º Mês)</span>  
                                        <span class="text-xs text-slate-400">Garante a vaga, uniforme completo e o primeiro mês</span>  
                                    </div>  
                                </div>  
                                <span class="font-extrabold text-brand-gold text-sm">R$ 249,90</span>  
                            </div>  
                        </label>  
                    </div>  
  
                    <div class="flex gap-3 pt-4">  
                        <button type="button" onclick="irParaEtapa(1)" class="w-1/3 bg-brand-border hover:bg-brand-border/80 text-slate-300 font-bold py-3.5 rounded-xl transition text-sm">  
                            <i class="fa-solid fa-arrow-left"></i> Voltar  
                        </button>  
                        <button type="button" onclick="irParaEtapa(3)" class="w-2/3 bg-brand-green hover:bg-brand-greenDark text-white font-bold py-3.5 rounded-xl transition flex items-center justify-center gap-2 shadow-lg shadow-brand-green/20 text-sm">  
                            Ir para Pagamento / Finalizar <i class="fa-solid fa-arrow-right"></i>  
                        </button>  
                    </div>  
                </div>  
  
                <!-- ETAPA 3: Pagamento & Confirmação -->  
                <div id="etapa-3" class="space-y-4 hidden">  
                    <h2 class="text-lg font-bold text-white flex items-center gap-2">  
                        <i class="fa-solid fa-shield-check text-brand-green"></i> 3. Confirmação & Pagamento  
                    </h2>  
  
                    <div class="bg-brand-dark/60 border border-brand-border rounded-2xl p-4 space-y-2 text-sm">  
                        <div class="flex justify-between text-slate-300">  
                            <span>Atleta:</span>  
                            <span id="resumoAtleta" class="font-semibold text-white">---</span>  
                        </div>  
                        <div class="flex justify-between text-slate-300">  
                            <span>Unidade:</span>  
                            <span id="resumoUnidade" class="font-semibold text-white">---</span>  
                        </div>  
                        <div class="flex justify-between text-slate-300">  
                            <span>Plano Escolhido:</span>  
                            <span id="resumoPlano" class="font-semibold text-brand-gold">---</span>  
                        </div>  
                    </div>  
  
                    <!-- Bloco PIX / Cartão Dinâmico -->  
                    <div id="blocoPagamento" class="bg-brand-dark border border-brand-border rounded-2xl p-4 text-center space-y-3">  
                        <div id="infoPix">  
                            <div class="bg-white p-3 inline-block rounded-xl mb-2">  
                                <!-- QR Code Ilustrativo / Pix -->  
                                <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=00020126580014br.gov.bcb.pix0136wra.sports.matriculas@gmail.com5204000053039865802BR5925WRA%20SPORTS%20MATRICULAS6009COLOMBO62070503***63041C3A" alt="QR Code Pix" class="w-32 h-32 mx-auto">  
                            </div>  
                            <p class="text-xs text-slate-400">Escaneie o QR Code acima ou clique no botão para copiar a chave Pix da escola:</p>  
                            <button type="button" onclick="copiarPix()" class="w-full bg-brand-border hover:bg-brand-border/80 text-brand-gold font-bold py-2.5 rounded-xl text-xs transition border border-brand-gold/30">  
                                <i class="fa-solid fa-copy"></i> Copiar Chave Pix (CNPJ/E-mail)  
                            </button>  
                        </div>  
                        <p class="text-xs text-slate-400 pt-2">Prefere pagar no Cartão de Crédito? Você poderá solicitar o link seguro diretamente no WhatsApp da secretaria.</p>  
                    </div>  
  
                    <div class="flex gap-3 pt-4">  
                        <button type="button" onclick="irParaEtapa(2)" class="w-1/3 bg-brand-border hover:bg-brand-border/80 text-slate-300 font-bold py-3.5 rounded-xl transition text-sm">  
                            <i class="fa-solid fa-arrow-left"></i> Voltar  
                        </button>  
                        <button type="submit" class="w-2/3 bg-gradient-to-r from-brand-green to-brand-greenDark hover:opacity-95 text-white font-bold py-3.5 rounded-xl transition flex items-center justify-center gap-2 shadow-xl shadow-brand-green/30 text-sm">  
                            <i class="fa-brands fa-whatsapp text-lg"></i> Enviar para WhatsApp  
                        </button>  
                    </div>  
                </div>  
  
            </form>  
        </div>  
    </main>  
  
    <!-- Unidades & Horários -->  
    <section class="max-w-4xl mx-auto px-4 py-8 border-t border-brand-border">  
        <h3 class="text-center text-xl font-bold text-white mb-6">Nossas Unidades em Colombo - PR</h3>  
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4">  
            <div class="bg-brand-card border border-brand-border rounded-2xl p-5">  
                <div class="flex items-center gap-3 mb-3">  
                    <div class="w-10 h-10 rounded-xl bg-brand-green/20 text-brand-green flex items-center justify-center font-bold">  
                        <i class="fa-solid fa-location-dot"></i>  
                    </div>  
                    <div>  
                        <h4 class="font-bold text-white text-base">Unidade Roça Grande</h4>  
                        <span class="text-xs text-brand-gold">Matriz & Treinamentos</span>  
                    </div>  
                </div>  
                <p class="text-xs text-slate-300 mb-3"><i class="fa-solid fa-map-pin text-brand-green mr-1"></i> Rodovia da Uva, 2152 - Roça Grande, Colombo - PR</p>  
                <p class="text-xs text-slate-400"><i class="fa-regular fa-clock text-slate-500 mr-1"></i> Terça a Sábado: 08:30 às 20:00</p>  
            </div>  
  
            <div class="bg-brand-card border border-brand-border rounded-2xl p-5">  
                <div class="flex items-center gap-3 mb-3">  
                    <div class="w-10 h-10 rounded-xl bg-brand-green/20 text-brand-green flex items-center justify-center font-bold">  
                        <i class="fa-solid fa-location-dot"></i>  
                    </div>  
                    <div>  
                        <h4 class="font-bold text-white text-base">Unidade Santa Fé</h4>  
                        <span class="text-xs text-brand-gold">Campos Oficiais</span>  
                    </div>  
                </div>  
                <p class="text-xs text-slate-300 mb-3"><i class="fa-solid fa-map-pin text-brand-green mr-1"></i> Av. Santos Dumont, 461 - Santa Fé, Colombo - PR</p>  
                <p class="text-xs text-slate-400"><i class="fa-regular fa-clock text-slate-500 mr-1"></i> Terça a Sábado (Conforme escala de turmas)</p>  
            </div>  
        </div>  
    </section>  
  
    <!-- FAQ Rápido -->  
    <section class="max-w-4xl mx-auto px-4 py-8 border-t border-brand-border">  
        <h3 class="text-center text-xl font-bold text-white mb-6">Dúvidas Frequentes</h3>  
        <div class="space-y-3 max-w-2xl mx-auto">  
            <details class="bg-brand-card border border-brand-border rounded-xl p-4 text-sm group">  
                <summary class="font-bold text-white cursor-pointer flex justify-between items-center">  
                    Quais documentos são necessários para a matrícula?  
                    <i class="fa-solid fa-chevron-down text-xs text-slate-400 group-open:rotate-180 transition"></i>  
                </summary>  
                <p class="text-xs text-slate-300 mt-3 leading-relaxed">  
                    RG ou Certidão de Nascimento do aluno, RG do responsável, comprovante de residência e atestado médico apto para prática esportiva.  
                </p>  
            </details>  
            <details class="bg-brand-card border border-brand-border rounded-xl p-4 text-sm group">  
                <summary class="font-bold text-white cursor-pointer flex justify-between items-center">  
                    A aula experimental paga alguma taxa?  
                    <i class="fa-solid fa-chevron-down text-xs text-slate-400 group-open:rotate-180 transition"></i>  
                </summary>  
                <p class="text-xs text-slate-300 mt-3 leading-relaxed">  
                    Não! A primeira aula experimental é 100% gratuita para que o atleta conheça a metodologia e a nossa estrutura.  
                </p>  
            </details>  
        </div>  
    </section>  
  
    <!-- Rodapé -->  
    <footer class="bg-brand-dark border-t border-brand-border py-8 text-center text-xs text-slate-500">  
        <div class="max-w-4xl mx-auto px-4 space-y-2">  
            <p class="font-bold text-slate-300">WRA Sports - Escola de Futebol Oficial</p>  
            <p>Colombo, Paraná - Todos os direitos reservados.</p>  
        </div>  
    </footer>  
  
    <!-- Botão Flutuante WhatsApp -->  
    <a href="https://wa.me/5541999044171?text=Olá!%20Vim%20pelo%20site%20e%20gostaria%20de%20tirar%20dúvidas%20sobre%20as%20matrículas." target="_blank" class="fixed bottom-6 right-6 z-50 bg-brand-green hover:bg-brand-greenDark text-white w-14 h-14 rounded-full flex items-center justify-center text-2xl shadow-2xl shadow-brand-green/50 transition transform hover:scale-110">  
        <i class="fa-brands fa-whatsapp"></i>  
    </a>  
  
    <!-- Scripts de Controle do Formulário -->  
    <script>  
        const CONFIG_WRA = {  
            whatsappEscola: '5541999044171', // WhatsApp Oficial  
            chavePix: 'wra.sports.matriculas@gmail.com' // Chave Pix para cópia  
        };  
  
        function calcularCategoria() {  
            const dataNascInput = document.getElementById('nascimento').value;  
            if (!dataNascInput) return;  
  
            const anoNascimento = new Date(dataNascInput).getFullYear();  
            const anoAtual = new Date().getFullYear();  
            const idade = anoAtual - anoNascimento;  
  
            let categoria = '';  
            if (idade <= 7) categoria = 'Sub-7';  
            else if (idade <= 9) categoria = 'Sub-9';  
            else if (idade <= 11) categoria = 'Sub-11';  
            else if (idade <= 13) categoria = 'Sub-13';  
            else if (idade <= 15) categoria = 'Sub-15';  
            else categoria = 'Sub-17';  
  
            document.getElementById('categoriaCalculada').value = `${categoria} (${idade} anos)`;  
        }  
  
        function irParaEtapa(etapa) {  
            // Validação simples da etapa 1  
            if (etapa === 2) {  
                const nomeAtleta = document.getElementById('nomeAtleta').value;  
                const nascimento = document.getElementById('nascimento').value;  
                const unidade = document.getElementById('unidade').value;  
                const nomeResp = document.getElementById('nomeResponsavel').value;  
                const whatsapp = document.getElementById('whatsapp').value;  
  
                if (!nomeAtleta || !nascimento || !unidade || !nomeResp || !whatsapp) {  
                    alert('Por favor, preencha todos os campos da etapa 1 antes de continuar.');  
                    return;  
                }  
            }  
  
            // Atualizar visibilidade das etapas  
            document.getElementById('etapa-1').classList.add('hidden');  
            document.getElementById('etapa-2').classList.add('hidden');  
            document.getElementById('etapa-3').classList.add('hidden');  
  
            document.getElementById(`etapa-${etapa}`).classList.remove('hidden');  
  
            // Atualizar indicadores visuais  
            for (let i = 1; i <= 3; i++) {  
                const ind = document.getElementById(`step-indicator-${i}`);  
                if (i <= etapa) {  
                    ind.classList.remove('text-slate-500');  
                    ind.classList.add('text-brand-green');  
                    ind.querySelector('span').classList.remove('bg-brand-border', 'text-slate-400');  
                    ind.querySelector('span').classList.add('bg-brand-green', 'text-white');  
                } else {  
                    ind.classList.remove('text-brand-green');  
                    ind.classList.add('text-slate-500');  
                    ind.querySelector('span').classList.remove('bg-brand-green', 'text-white');  
                    ind.querySelector('span').classList.add('bg-brand-border', 'text-slate-400');  
                }  
            }  
  
            // Se for para a etapa 3, preencher resumo e ajustar Pix  
            if (etapa === 3) {  
                document.getElementById('resumoAtleta').innerText = document.getElementById('nomeAtleta').value;  
                document.getElementById('resumoUnidade').innerText = document.getElementById('unidade').value;  
                  
                const planoSelecionado = document.querySelector('input[name="plano"]:checked').value;  
                document.getElementById('resumoPlano').innerText = planoSelecionado;  
  
                const blocoPix = document.getElementById('blocoPagamento');  
                if (planoSelecionado.includes('Gratuita')) {  
                    blocoPix.innerHTML = `  
                        <div class="py-4">  
                            <i class="fa-solid fa-circle-check text-brand-green text-3xl mb-2"></i>  
                            <h4 class="font-bold text-white text-base">Aula Experimental 100% Gratuita!</h4>  
                            <p class="text-xs text-slate-300 mt-1">Nenhum pagamento necessário agora. Clique em enviar para agendar sua aula no WhatsApp.</p>  
                        </div>  
                    `;  
                }  
            }  
  
            window.scrollTo({ top: 300, behavior: 'smooth' });  
        }  
  
        function copiarPix() {  
            navigator.clipboard.writeText(CONFIG_WRA.chavePix);  
            alert('Chave Pix copiada com sucesso: ' + CONFIG_WRA.chavePix);  
        }  
  
        function enviarMatricula(event) {  
            event.preventDefault();  
  
            const atleta = document.getElementById('nomeAtleta').value;  
            const nascimento = document.getElementById('nascimento').value;  
            const categoria = document.getElementById('categoriaCalculada').value;  
            const unidade = document.getElementById('unidade').value;  
            const responsavel = document.getElementById('nomeResponsavel').value;  
            const whatsapp = document.getElementById('whatsapp').value;  
            const plano = document.querySelector('input[name="plano"]:checked').value;  
  
            const mensagem = `*⚽ NOVA MATRÍCULA / INSCRIÇÃO - WRA SPORTS*  
              
• *Atleta:* ${atleta}  
• *Nascimento/Categoria:* ${nascimento} (${categoria})  
• *Unidade:* ${unidade}  
• *Responsável:* ${responsavel}  
• *WhatsApp:* ${whatsapp}  
• *Modalidade/Plano:* ${plano}  
  
_Enviado através do site oficial de matrículas._`;  
  
            const urlWhatsApp = `https://wa.me/${CONFIG_WRA.whatsappEscola}?text=${encodeURIComponent(mensagem)}`;  
            window.open(urlWhatsApp, '_blank');  
        }  
    </script>  
</body>  
</html>  
