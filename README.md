# VectorStudio - PNG para SVG

O VectorStudio é uma aplicação web rápida, rodando inteiramente no navegador, que converte imagens (PNG/JPG) em gráficos vetoriais escaláveis (SVG) monocromáticos de alta qualidade.

Ele utiliza o poderoso algoritmo **Potrace** compilado para WebAssembly (Wasm) para rastrear caminhos matemáticos e desenhar curvas suaves diretamente no seu navegador, sem precisar enviar seus arquivos para nenhum servidor.

## 🚀 Funcionalidades
- **Conversão Instantânea:** Arraste e solte imagens para vetorizá-las em um piscar de olhos.
- **100% Client-Side:** Privacidade garantida. Suas imagens nunca saem do seu computador ou celular.
- **Poder do Wasm:** Utiliza a biblioteca `@cadit-app/potrace-ts` para máximo desempenho e precisão no traçado.
- **Saída Responsiva:** O código já injeta automaticamente um `viewBox` inteligente para que os SVGs gerados se adaptem a qualquer tamanho de tela sem cortes.
- **Design Premium:** Estética moderna com "Glassmorphism", modo escuro (Dark Mode) e transições suaves.

## 🛠️ Como usar
Você poderá acessar o app diretamente através do GitHub Pages.
Ou, se preferir usar localmente, basta clonar este repositório e abrir o arquivo `index.html` em qualquer navegador! Não precisa rodar `npm install` e nem configurar servidores.

1. Arraste e solte um arquivo PNG ou JPG na área "Imagem Original".
2. Aguarde milissegundos enquanto o algoritmo Wasm processa a arte.
3. Clique em **Baixar SVG** para salvar o seu novo arquivo vetorial na máquina.

## 💻 Tecnologias Utilizadas
- **HTML5 & Vanilla CSS** para uma interface ultra rápida e sem bibliotecas pesadas.
- **ES Modules & WebAssembly** para a lógica pesada de processamento fluir direto no navegador.
- **Potrace-ts** ([esm.sh/@cadit-app/potrace-ts](https://esm.sh/@cadit-app/potrace-ts)) como motor do algoritmo de vetorização.

## 📝 Licença
Este projeto utiliza o código base do Potrace, que é licenciado sob a Licença GPL-2.0. Sendo assim, qualquer modificação e redistribuição também deve seguir os termos da GPL-2.0.
