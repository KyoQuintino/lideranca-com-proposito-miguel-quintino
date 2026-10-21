# Liderança com Propósito — Miguel Quintino

Projeto do site de apresentação e venda do e-book **Liderança com Propósitos**, de Rick Warren. Esta cópia foi preparada para o repositório GitHub com os arquivos de arte locais, para que o projeto não dependa dos assets hospedados no Manus.

## Conteúdo do repositório

- `client/`: site, estilos, configuração da Hotmart e imagens públicas usadas pela página.
- `client/public/assets/lideranca-com-propositos-capa.png`: capa final do e-book.
- `client/public/assets/lideranca-com-propositos-divulgacao.png`: arte horizontal para divulgação e hero do site.
- `assets/source/Lideranca-com-Propositos-Rick-Warren.pdf`: PDF-fonte fornecido para este projeto.
- `hotmart-copy.md`: título e descrição do produto para cadastro na Hotmart.

## Desenvolvimento

Requer Node.js e pnpm. Execute `pnpm install`, depois `pnpm dev` para desenvolvimento. Use `pnpm check` para verificar os tipos, `pnpm test` para testes e `pnpm build:static` para gerar o site estático.

## Checkout Hotmart

O endereço de checkout fica em `client/public/product-config.js`. O valor atual é o link fornecido pelo responsável pelo produto. O código ativa os botões somente para URLs HTTPS em `hotmart.com` ou subdomínios Hotmart. O pagamento é feito na Hotmart; o site não coleta dados de cartão.

Os espaços para depoimentos foram intencionalmente mantidos como placeholders e o selo do site é editorial, sem garantia ou certificação.
