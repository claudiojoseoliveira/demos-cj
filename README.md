# demos-cj — Demos públicas | CJ Treinamentos e Serviços

Repositório com as **demonstrações públicas** dos sistemas desenvolvidos pela
**CJ Treinamentos e Serviços**. Todos os dados são **fictícios** e cada demo
exibe uma faixa dourada de "AMBIENTE DE DEMONSTRAÇÃO" no topo.

## Demos

| Pasta | Sistema | Público-alvo |
|---|---|---|
| `demo-loja/` | Loja virtual (vitrine, sacola, checkout) | Lojas de bairro |
| `demo-oficina/` | AutoFix Pro — gestão de oficina mecânica | Oficinas |
| `demo-patrimonio/` | OmniAsset — controle de patrimônio e ativos | Empresas |
| `demo-mercadinho/` | Varejo Fácil — gestão de mercadinhos e armarinhos | Mercadinhos |
| `demo-financeiro/` | Gestor Financeiro Familiar Multicanal (PWA) | Famílias |

## Como publicar (Vercel)

Cada pasta é um site estático independente. Na Vercel, crie um projeto por demo
a partir deste repositório, definindo o **Root Directory** para a pasta da demo:

- `demo-loja` → https://demo-loja-cj.vercel.app
- `demo-oficina` → https://demo-oficina-cj.vercel.app
- `demo-patrimonio` → https://demo-patrimonio-cj.vercel.app
- `demo-mercadinho` → https://demo-mercadinho-cj.vercel.app
- `demo-financeiro` → https://demo-financeiro-cj.vercel.app

Nenhum build é necessário (arquivos já compilados). Framework preset: **Other**.
