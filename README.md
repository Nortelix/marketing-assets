# Nortelix — marketing-assets

Repositório **público** com os ficheiros das publicações de marketing da Nortelix: imagens de email marketing, redes sociais, folhetos e marca.

> Tudo o que está aqui é público na internet. Não colocar dados de clientes, preços internos, contratos nem capturas com dados reais.

## Estrutura

```
marca/                      Logótipos e elementos de marca
  nortelix/                 Logótipos Nortelix (original, branco, versões para email)
email/                      Campanhas de email marketing
  AAAA-MM-tema/             Uma pasta por campanha
    email.html              HTML pronto a enviar (tabelas, estilos inline, sem JavaScript)
    img/                    Imagens usadas no email
redes-sociais/              Publicações para LinkedIn, Facebook e Instagram
  AAAA-MM-tema/             Uma pasta por publicação ou carrossel
folhetos/                   Folhetos e brochuras em PDF
```

## Links públicos

Cada ficheiro fica acessível em:

```
https://raw.githubusercontent.com/Nortelix/marketing-assets/main/<caminho-do-ficheiro>
```

Exemplo: `https://raw.githubusercontent.com/Nortelix/marketing-assets/main/marca/nortelix/nortelix-logo.png`

Os links são permanentes enquanto o ficheiro não for renomeado nem apagado. **Não renomear nem apagar ficheiros de campanhas já enviadas**: os emails antigos deixariam de mostrar as imagens.

## Regras de nomes

- Pastas de campanha: `AAAA-MM-tema` (ex.: `2026-11-field-service-demonstracao`).
- Ficheiros: minúsculas, hífenes, sem acentos nem espaços (ex.: `slide-1-capa.jpg`).
- Imagens de email: largura máxima 600 px no email, exportadas a 2x (até 1200 px), JPG para fotografias/capturas, PNG para logótipos; idealmente menos de 100 KB cada.
- Imagens de redes sociais: 1080×1080 (quadrado), 1080×1920 (story), 1200×627 (link LinkedIn/Facebook).

## Campanhas

| Pasta | Conteúdo |
|---|---|
| `email/2026-11-field-service-demonstracao` | Email "Os seus técnicos merecem melhor do que folhas de Excel" — pedido de demonstração Odoo + Nortelix Field Service |
| `redes-sociais/2026-11-field-service-carrossel` | Carrossel de 6 slides (LinkedIn, Facebook, Instagram) |
| `marca/nortelix` | Logótipo original, branco transparente e versões para email |
