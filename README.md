# RadarAds - Exemplo de landing page

Este repositório mostra como estruturar uma landing page no estilo do exemplo enviado, usando apenas HTML e CSS.

## Como rodar localmente (preview)

1. Inicie um servidor estático na raiz do projeto:

```bash
python -m http.server 8000
```

2. Acesse `http://localhost:8000` no navegador.

> Se a prévia não aparecer ao abrir o arquivo diretamente, use um servidor local (como acima) ou a extensão **Live Server** no VS Code para evitar bloqueios de assets e fontes remotas.

## Como construir algo semelhante

- **HTML por seções**: hero, benefícios, lista de recursos, prova social, planos, FAQ e CTA final.
- **Cards reutilizáveis**: mesma estrutura de `article` para benefícios, ferramentas e preços.
- **Tema escuro + acentos em amarelo**: gradientes sutis no fundo e elementos de destaque em `var(--accent)`.
- **Componentes básicos**: botão primário, botão outline, badge, header sticky e rodapé.

Edite os textos, imagens e chamadas para ação conforme seu produto.
