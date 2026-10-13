# 🔥 Sem-Banha Smokehouse & Brasa Brasileira • Versão PC / Desktop

Sistema completo desenvolvido para **PC / Desktop (MacBook Air / Windows)** com base nas telas do Figma para o restaurante e churrascaria **Sem-Banha Smokehouse (Mesa 14)**.

> 🚀 **100% Web / PC:** Não precisa de Android Studio, Flutter ou emulador! Roda diretamente em qualquer navegador moderno (Chrome, Edge, Opera, Firefox, Safari).

---

## 🖥️ Como Abrir no seu PC

Você tem duas opções simples:

1. **Opção 1:** Dê dois cliques no arquivo `abrir_no_navegador.bat` ou no arquivo `index.html`.
2. **Opção 2:** Arraste o arquivo `index.html` para uma aba do Google Chrome ou Microsoft Edge.

---

## 🥩 As 5 Telas Implementadas Fielmente do Figma

### 1. Início / Home (`MacBook Air - 3`)
- **Cabeçalho Fixo do Salão:** Identificador `MESA 14 • SALÃO PRINCIPAL`, total da comanda em tempo real e botão interativo `🔔 Chamar Garçom`.
- **Hero Banner da Brasa:** Apresentação da casa com carnes maturadas, lenha de laranjeira e rock/blues.
- **Card de Status da Mesa 14:** Mostra a comanda aberta `#3842`, 4 pessoas, total de R$ 350,80, 7 itens pedidos e tempo de permanência (1h 45min).
- **Banner do Passaporte Pitmaster (Nível Ouro):** Barra de progresso interativa com os 8 selos (7 já conquistados e o 8º com animação pulsante para a Câmera Social).
- **Grid de Pratos Clássicos da Brasa (3 colunas):** Feijoada da Casa, Baião de Dois, Escondidinho, Strogonoff de Filé Mignon, Chimarrão Gaúcho e Costela 12h no Fogo de Chão.
- **Como Funciona:** Guia visual dos 3 passos da experiência Sem-Banha.
- **Barra de Suporte Rápido:** Solicitação com 1 clique de pratos/copos extras, balde de gelo ou chamada de garçom.

---

### 2. Cardápio Completo com Comanda Lateral Fixa (`Top Left`)
- **Filtros por Categoria:** Carnes Nobres & Defumadas, Burgers & Smoked, Chopps & Bebidas, Sobremesas da Brasa.
- **Grid de Itens:** Fotos em alta resolução, tags temáticas (*Mais Pedido*, *Tradição Nordestina*, *Assinatura Pitmaster*), preços e botão `+ Adicionar`.
- **Sidebar de Comanda Lateral Fixa (Desktop):**
  - Lista de itens em tempo real com indicador de quantidade (`2x`, `1x`), observações e botão de remoção.
  - Total a pagar atualizado dinamicamente.
  - Botão de ação direta: `💳 Pagar & Liberar Câmera Social ➔`.
- **Banner Desafio do Chopp na Brasa:** Torre de 2,5L com promoção de torresmo pururucado.

---

### 3. Mesa 14 - Comanda #3842 & Divisão de Conta (`MacBook Air - 4`)
- **Itens Pedidos na Mesa:** Histórico com horários dos pedidos e status "Entregue na Mesa".
- **Divisão Interativa da Conta:**
  - Botões seletores para divisão entre **1, 2, 3, 4, 5 ou 6 pessoas**.
  - Cálculo instantâneo do valor individual (ex: **R$ 87,70 / pessoa** ao dividir por 4).
- **Resumo Financeiro:**
  - Subtotal dos itens.
  - Taxa de serviço de 10% opcional com **switch toggle liga/desliga**.
  - Desconto fidelidade do passaporte.
  - Total final da mesa.
- **Formas de Pagamento na Mesa:**
  - **PIX Instantâneo:** Modal com QR Code e chave Copia e Cola funcional.
  - **Cartão de Crédito/Débito/VR:** Solicitação da maquininha direto na mesa.
  - **Carteiras Digitais:** Apple Pay / Google Pay via NFC.
- **Bônus Exclusivo:** Explicação do desbloqueio da Câmera Social e do 8º Selo ao concluir o pagamento.

---

### 4. Estúdio Social da Mesa (`MacBook Air - 5`)
- **Câmera ao Vivo com Webcam do PC:**
  - Utiliza `navigator.mediaDevices.getUserMedia` para exibir a câmera do seu computador em tempo real espelhada.
  - Botão de alternância para fotos de demonstração em alta definição caso não haja webcam conectada.
- **Molduras Temáticas Selecionáveis:**
  - 🔥 *Parrilla Clássica*
  - 🪵 *Fogo de Chão*
  - 👑 *Golden Smoke*
  - 🍺 *Noite de Chopp*
- **Carimbos Selecionáveis da Comitiva:**
  - 👑 *Comitiva da Brasa*
  - 🏆 *Mesa 14 Venceu!*
  - 🍻 *O Brinde Perfeito*
  - 🔥 *Fogo & Brasa Pura*
  - 🍖 *Costela Master 12h*
- **Controles de Estúdio:**
  - **Temporizador Interativo (3s):** Contagem regressiva visual dinâmica na tela (`3... 2... 1...`) com bipe sonoro e disparo automático.
  - **Efeito Flash:** Flash estroboscópico de estúdio fotográfico.
  - **Composição Gráfica em Tempo Real no Canvas:** A foto final gerada mescla o frame escolhido, o carimbo oficial selecionado, o logotipo `🔥 SEM-BANHA SMOKEHOUSE`, data e horário, tornando o arquivo baixado um cartão souvenir oficial pronto para impressão ou redes sociais!
- **Feedback Sensorial & Áudio Web API:**
  - Cliques de obturador mecânico de câmera ao fotografar.
  - Notificação sonora sutil ao adicionar itens ao carrinho.
  - Sino de atendimento ao chamar o garçom.
  - Fanfarra arpejada de vitória ao carimbar o 8º selo lendário.
  - Botão de controle de áudio (`🔊 Áudio` / `🔇 Mudo`) no cabeçalho.
- **Atmosfera Visual Imersiva:**
  - Partículas sutis de brasas e faíscas incandescentes flutuando em segundo plano (`HTML5 Canvas`), evocando o ambiente autêntico de uma parrilla e defumadora nobre.
- **Ações Finais:**
  - `⭐ Salvar Foto & Carimbar Selo #08`: Valida o último selo com fanfarra comemorativa e abre o passaporte completo!
  - `⬇️ Salvar em Alta Definição (HD)`: Faz o download do cartão souvenir renderizado em alta resolução para o computador.
  - `🖨️ Imprimir Foto Polaroid no Caixa`.
  - `📲 Postar no Instagram Stories`.
- **Mural das 8 Mesas Conquistadas:** Galeria com as comitivas recentes que venceram o desafio.

---

### 5. Passaporte Pitmaster & Brasa Social (`Top Right`)
- **Status Pitmaster Ouro:** Badge comemorativo de 8 de 8 selos coletados pela Mesa 14.
- **Grade dos 8 Selos:** Exibição com emojis, títulos das conquistas e horários de validação.
- **Voucher de Resgate do Brinde Oficial:**
  - QR Code para leitura do garçom.
  - Código: `#SEMBANHA-LENDARIO-3842`.
  - Recompensa: **Tábua Degustação Premium + Chopp Artesanal 500ml cortesia**.
  - Botão para chamar o garçom e validar o brinde.
- **Exibição da Foto Oficial da Comitiva:** Exibe a foto tirada no estúdio da Mesa 14 com a moldura e carimbos aplicados.
- **Mural Histórico de Visitas:** Registro de outras mesas campeãs.

---

## 🌐 Publicando no GitHub Pages (Para os Professores)

Como é um projeto web puro (`HTML/CSS/JS` em um único arquivo `index.html`), para colocar no ar:
1. Crie ou use o repositório no seu GitHub.
2. Suba o arquivo `index.html`.
3. Vá em **Settings** > **Pages** > Selecione o branch `main` e a pasta `/ (root)`.
4. Pronto! O link estará acessível publicamente em segundos para os professores abrirem no PC ou notebook.
