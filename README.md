# GS Store - Sistema de Comprovantes

Oi, tudo bem? Bem-vindo ao **GS Store - Sistema de Comprovantes**, um projetinho web que fiz pra ajudar a loja de celulares GS Store a gerenciar vendas e ordens de serviço (OS) de um jeito simples e rápido. Com ele, você cadastra clientes, produtos ou reparos, gera PDFs bonitinhos com o logo da loja e ainda tem uma interface que funciona direitinho no celular. Tudo isso num único arquivo HTML, pra facilitar a vida!

## O que esse sistema faz?

É um sistema pra loja de celulares que te deixa:
- **Cadastrar vendas**: Adiciona produtos, cliente, forma de pagamento e gera um comprovante em PDF.
- **Abrir ordens de serviço (OS)**: Registra reparos em celulares, com modelo, tipo de conserto e orçamento, também com PDF no final.
- **Formatar dados direitinho**: Usa máscaras pra CPF, telefone, CEP e valores em reais (R$ 1.234,56).
- **Buscar endereço automático**: Digita o CEP e os campos de endereço são preenchidos via API ViaCEP.
- **Mostrar frases motivacionais**: Todo dia tem uma frase nova pra dar aquele gás!
- **Ser responsivo**: Funciona no computador e no celular, com um menu hamburger que desliza suave.

## Funcionalidades
- Interface com modais pra vendas e OS, estilizada com **Bootstrap** e **Tailwind CSS**.
- Máscaras de input (CPF, telefone, CEP, moeda) com **IMask.js**.
- Geração de PDFs com logo usando **jsPDF**.
- Menu hamburger responsivo e animações de exclusão de itens.
- Integração com **ViaCEP** pra buscar endereços.
- Frases motivacionais diárias com JavaScript puro.
- Tudo num único `index.html`, perfeito pra hospedagem estática.

## Pré-requisitos
Pra rodar o sistema, você precisa:
- Um navegador moderno (Chrome, Firefox, Edge, etc.).
- Conexão com internet (pra carregar os CDNs e usar a API ViaCEP).
- O arquivo `logo.png` na raiz do projeto (pro PDF e header da página).
- Um servidor web (pode ser local, tipo Live Server no VS Code, ou hospedagem como Vercel/Netlify).

## Como configurar
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/dpereirajuli/GeradorComprovanteComercio
   cd GeradorComprovanteComercio
