# Especificação Técnica de Projeto: Mini-Site Premium & Biolink NFC
**Cliente:** Aline Ferrão — Mentora & Terapeuta  
**Agência:** MKT SANGÃO Inteligência Digital  
**Status:** Pronto para Produção (HTML/CSS/JS)

---

## 👑 1. Direção Estratégica (CEO Digital & Growth)

Este mini-site foi planejado não apenas para ser um hub de links comum, mas uma **plataforma de conversão e posicionamento de alto padrão (SaaS Mystique)**. Aline Ferrão atua em nichos de altíssima conexão emocional e espiritual (Constelação, Sagrado Feminino, Medicinas Ancestrais). Logo, o site precisa equilibrar a **profundidade mística** com a **facilidade de conversão instantânea**.

### ⚡ Direcionadores de ROI:
*   **Velocidade de Abertura Extrema:** Otimizado para cartões NFC. O cliente aproxima o celular e o templo digital de Aline abre em menos de 1 segundo.
*   **Ação em 1 Clique:** Botão "Salvar Contato" integrado nativamente via API VCF para garantir entrada na agenda dos clientes.
*   **Funil de Eventos Integrado:** Estrutura dinâmica para exibição de vivências com call-to-action (CTA) direto para reservas via WhatsApp com mensagens personalizadas.

---

## 🎨 2. Direção de Arte & Experiência Visual (UX/UI)

A paleta de cores e o design devem refletir a força do **Sagrado Feminino**, a energia solar do mel/ouro e a profundidade das medicinas ancestrais (Ayahuasca).

### 🎨 Paleta de Cores (SaaS Glassmorphism):
*   **Fundo Principal:** `#0F0712` (Roxo profundo quase preto, representando o mistério e o cosmos) ou `#0D0C0A` (Preto terroso profundo).
*   **Acentos e Detalhes:** `#E5A93B` (Ouro vibrante/Mel, representando a Abelha Rainha e a prosperidade) e `#7F4CA5` (Púrpura espiritual).
*   **Texto Principal:** `#F4EFEA` (Off-white suave para leitura confortável).
*   **Efeito de Vidro (Glassmorphism):** Containers com `background: rgba(25, 15, 30, 0.6)` e bordas finas com `rgba(229, 169, 59, 0.15)`.

### 🔮 Elementos de Design Premium:
*   **Glow Orbs:** Duas esferas de luz suave no fundo em ouro degradê desfocadas (`filter: blur(140px)`).
*   **Borda Ativa (Running Light):** Animação sutil de luz dourada circulando os botões de ação imediata ("Salvar Contato" e "Agendar Consulta").
*   **Tipografia:** Títulos em `'Playfair Display', serif` ou `'Syne', sans-serif` para transmitir autoridade e elegância; textos em `'DM Sans', sans-serif`.

---

## 🏗️ 3. Arquitetura de Informação (Estrutura do Site)

A página flui de forma vertical e intuitiva, guiando a usuária da conexão profunda à conversão:

### Seção 1: Top Bar & Utilities
*   **Botão "QR Code":** Abre um modal elegante com o código para compartilhar o site facilmente.
*   **Botão "Compartilhar":** Dispara a API nativa do celular para compartilhamento rápido.

### Seção 2: Header de Posicionamento (Branding)
*   **Avatar Circular:** Foto premium de Aline com moldura em gradiente dourado pulsante.
*   **Nome:** Aline Ferrão.
*   **Subtítulo/Bio Curta:** 
    *   *Mentora Espiritualista | Consteladora Familiar | Facilitadora de Medicinas Ancestrais*
*   **Selo de Atuação:** 🌹 "Amor e propósito."
*   **Quick CTAs:** 
    *   Botão Esticado: `💾 Salvar Contato` (Dispara arquivo `.vcf` automático).
    *   Botão Ícone: `📞 Ligar` / `💬 WhatsApp`.

### Seção 3: O Manifesto (Conexão e Conversão de Alma)
Nesta seção, aplicamos técnicas de *Storytelling* e *Emotional Copywriting* com abas interativas ou dropdowns de leitura fluida:
*   **Abas Interativas (Tab Control):**
    *   **A Sacerdotisa:** Texto de conexão profunda sobre o despertar feminino.
    *   **Alma de Mulher:** Poema que toca diretamente as emoções do público feminino.

### Seção 4: Hub de Links Dinâmicos (Terapias e Cursos)
Botões estruturados com gradientes suaves:
1.  **💬 Mentoria Individual & Escuta Consciente:** Direto para atendimento personalizado.
2.  **🌹 Constelação Familiar Individual:** Detalhes de atendimento clínico.
3.  **📈 Acolhimento & Escuta Consciente:** Sessões de suporte terapêutico.
4.  **📸 Instagram Oficial:** Canal de conteúdo diário.

### Seção 5: Calendário de Eventos & Vivências (Alta Conversão)
Uma vitrine dinâmica e esteticamente impecável para os eventos de Aline Ferrão. Cada evento é apresentado como um card premium com imagem de fundo, tags de informações e botão direto para inscrição.

---

## 📅 4. Banco de Dados de Eventos (Pronto para o Desenvolvedor)

Abaixo está a estruturação técnica dos eventos atuais para alimentação do código ou sistema de gestão de Aline:

### Evento 1: Encontro com a Abelha Rainha (Honey Jar)
*   **Título:** ✨ SAVE THE DATE | Encontro com a Abelha Rainha 🐝
*   **Proposta:** Vivência e Feitio de um Honey Jar (Patuá simbólico de manifestação e abundância através da energia do mel e sabedoria das abelhas).
*   **Data:** 07 de Julho (19h às 23h).
*   **Local:** Hub Colmeia Vital.
*   **Diferencial:** Todos os materiais inclusos. Vagas Limitadas.
*   **Botão WhatsApp (CTA):** "Garantir minha vaga na Colmeia"
*   **Texto WhatsApp pré-definido:** `Olá Aline! Quero garantir minha participação na Vivência da Abelha Rainha no dia 07/07.`

### Evento 2: Constelação Familiar em Grupo
*   **Título:** 🌳 Constelação Familiar em Grupo
*   **Proposta:** Olhar com respeito para a sua história, reconhecer seu lugar no sistema familiar e abrir espaço para novos movimentos de cura e prosperidade.
*   **Data:** 09 de Julho (19h às 23h).
*   **Local:** Hub Colmeia Vital — Cachoeirinha/RS.
*   **Valores:** Participação: R$ 44,00 | Para constelar uma questão: Consultar disponibilidade.
*   **Botão WhatsApp (CTA):** "Inscrever-me para Constelar/Participar"
*   **Texto WhatsApp pré-definido:** `Olá Aline, gostaria de me inscrever para a Constelação Familiar em Grupo no dia 09/07.`

### Evento 3: Sagrado Feminino & Sagrado Masculino (Ayahuasca)
*   **Título:** 🌿 Jornada Ancestral: Equilíbrio Sagrado
*   **Proposta:** Vivência de profundo reencontro com a essência por meio da Ayahuasca e medicinas ancestrais (Rapé, Sananga, Medicina da Abelha, Sopro do Própolis, Cachimbo Sagrado, Aromaterapia e Fitoenergética). Foco no acolhimento do masculino pela Mãe Terra.
*   **Data:** 19 de Julho.
*   **Condução:** Aline Ferrão (Servidora da Luz de Oxum).
*   **Botão WhatsApp (CTA):** "Sentir o Chamado"
*   **Texto WhatsApp pré-definido:** `Olá Aline, senti o chamado para a jornada das Medicinas Ancestrais do dia 19 de Julho. Como posso participar?`

### Evento 4: Cerimônia de Inverno (Ayahuasca & Cura)
*   **Título:** ❄️ Jornada de Inverno: Recolher-se para Renascer
*   **Proposta:** Espaço sagrado de introspecção para liberar pesos, aquecer o coração e recordar a luz interior através da Ayahuasca, Rapé, Sananga, Jurema, Cachimbo Sagrado e Medicinas da Abelha.
*   **Música ao Vivo:** Txana Miguel & Txana Kauã + Banda Sagrado Ser.
*   **Facilitadores:** Aline Ferrão e Johnatan Luz.
*   **Data:** 24 de Julho de 2026 (Sexta-feira), 20h.
*   **Local:** Hub Colmeia Vital – Cachoeirinha/RS.
*   **Botão WhatsApp (CTA):** "Iniciar meu Renascimento"
*   **Texto WhatsApp pré-definido:** `Olá Aline! Desejo participar da Cerimônia de Ayahuasca de Inverno no dia 24/07/2026.`

### Evento 5: Celebração Ancestral (Música & Rezo)
*   **Título:** 🔥 Celebração Ancestral
*   **Proposta:** Uma noite especial de rezo, música e profunda conexão com as Sagradas Medicinas, honrando nossa ancestralidade.
*   **Atração Especial:** Banda 4 Direções (em turnê nacional).
*   **Condução:** Aline Ferrão e Johnatan Luz.
*   **Data:** 06 de Novembro de 2026, 20h.
*   **Local:** Hub Colmeia Vital.
*   **Botão WhatsApp (CTA):** "Reservar meu Ingresso"
*   **Texto WhatsApp pré-definido:** `Olá Aline, quero reservar meu lugar na Celebração Ancestral com a Banda 4 Direções em Novembro de 2026.`

---

## 💻 5. Engenharia de Automação & Código (Developer & Automation)

### Script de Geração Dinâmica de VCF (Salvar Contato Offline):
Para o botão "Salvar Contato" funcionar de forma autônoma e em qualquer smartphone sem precisar de banco de dados, o desenvolvedor utilizará o seguinte bloco de código Vanilla Javascript:

```javascript
function baixarContatoAline() {
  const vcard = `BEGIN:VCARD
VERSION:3.0
N:Ferrão;Aline;;;
FN:Aline Ferrão
ORG:Mentoria & Terapias;
TITLE:Mentora Espiritualista & Consteladora
TEL;TYPE=CELL,VOICE;MSG=true:+5551986261999
EMAIL;TYPE=PREF,INTERNET:contato@alineferrao.com.br
URL:https://instagram.com/alineferrao_terapeuta/
NOTE:🔮 Mentora Espiritualista | 💫 Consteladora Familiar | 🌹 Amor e Propósito
END:VCARD`;

  const blob = new Blob([vcard], { type: 'text/vcard;charset=utf-8;' });
  const url = URL.createObjectURL(blob);
  const newLink = document.createElement('a');
  newLink.download = 'Aline_Ferrao_Terapeuta.vcf';
  newLink.href = url;
  newLink.click();
}
```

---

## 📈 6. Plano de Growth & Tráfego Pago

1.  **Campanha de Tráfego Local (Meta Ads):** Criação de anúncios direcionados a Cachoeirinha/RS e região metropolitana de Porto Alegre, focando em pessoas interessadas em espiritualidade, autoconhecimento, constelação e meditação.
2.  **Destino do Anúncio (O Mini-Site):** O anúncio levará diretamente para o mini-site configurado no domínio oficial de Aline. Devido à velocidade de carregamento de 1 segundo, o bounce rate (taxa de rejeição) cairá drasticamente se comparado a páginas pesadas em WordPress.
3.  **Uso de NFC Físico:** Nos encontros presenciais e constelações em grupo no Hub Colmeia Vital, Aline poderá passar o cartão NFC diretamente nos celulares dos participantes, gerando efeito "Uau!" instantâneo e garantindo que todos salvem seu contato no ato.

evento 
🌿 QUANDO O ADULTO ASSUME A VIDA Quantas vezes você percebe que cresceu… mas, diante de algumas situações, ainda reage a partir da criança que um dia esperou? Esperou ser escolhida. Esperou reconhecimento. Esperou um pedido de desculpas. Esperou que alguém viesse preencher aquilo que faltou. A criança espera. O adulto escolhe. No dia 23/07, abriremos um novo campo de Constelação Familiar em Grupo para olhar os lugares onde ainda permanecemos pequenos diante da própria história. Um movimento para honrar quem veio antes, deixar a criança descansar e permitir que o adulto possa escolher, sustentar e seguir. ✨ Talvez a Vida não esteja parada. Talvez ela apenas esteja esperando você se apresentar diante dela. “Querida Vida… agora eu venho.” 🌿 Constelação Familiar em Grupo 📅 23/07 ✨ Energia de troca para participar: R$ 44,00 🌳 Para constelar: consultar disponibilidade 📍 Hub Colmeia Vital 🐝 Consteladora: Aline Ferrão 📲 Informações e reservas: 51 98626-1999 A criança espera ser escolhida. O adulto escolhe a própria vida.🌻
