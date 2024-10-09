## Este arquivo contém o código JavaScript principal do piano virtual. Ele realiza as seguintes funções:

1. Seleciona os elementos HTML necessários:
- PianoKeys: Elementos contendo as teclas do piano
- VolumeSlider: Elemento de controle de volume
- KeysCheck: Elemento de verificação de teclas
2. Define variáveis globais:
- mappedKeys: Array para armazenar as teclas mapeadas
- audio: Objeto Audio para reproduzir sons
3. Função playTune():
- Altera o arquivo de áudio para corresponder à tecla clicada
- Reproduz o som
- Adiciona e remove a classe "active" da tecla clicada para criar um efeito visual
4. Event Listeners:
- Clica na tecla do piano: Chama playTune()
- Tecla pressionada no teclado: Verifica se corresponde a uma tecla mapeada e chama playTune()
5. Funções auxiliares:
handleVolume(): Atualiza o volume do áudio conforme o controle de volume
showHideKeys(): Alternadamente mostra ou esconde as teclas do piano

`main.css`:

## Este arquivo contém os estilos CSS principais do piano virtual. Ele realiza as seguintes funções:

1. Estiliza o corpo da página:
- Centraliza o conteúdo
- Define cor de fundo e texto
2. Estiliza o container principal:
- Define cor de fundo preta
- Aplica borda arredondada
- Define largura e padding
3. Estiliza o cabeçalho:
- Centraliza os elementos
- Define cor de texto cinza claro
4. Estiliza o controle de volume:
- Define aparência personalizada para o input range
5. Estiliza o controle de teclas:
- Cria um checkbox personalizado
- Define animação ao clicar
6. Estiliza as teclas do piano:
- Define layout flexível
- Aplica estilos diferentes para teclas brancas e pretas
- Cria efeitos visuais quando uma tecla é tocada

 `reset.css`:

## Este arquivo contém estilos reset para normalizar o comportamento dos elementos HTML. Ele realiza as seguintes funções:

1. Define box-sizing como border-box para todos os elementos
2. Especifica a família de fonte Poppins como fallback
3. Remove margens e padding padrão de todos os elementos
4. Remove contornos de seleção de todos os elementos
   
## Esta documentação fornece uma visão geral das principais funcionalidades e estruturas dos arquivos engine.js, main.css e reset.css. O código está bem organizado e segue boas práticas de programação web.
