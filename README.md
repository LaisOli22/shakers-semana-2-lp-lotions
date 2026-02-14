# shakers-semana-2-lp-lotions

## 📌 Desafio - Semana 2

Criação de uma Landing Page exclusiva para a nova coleção de loções da Frederico Business utilizando Shopify + Liquid.

O foco do desafio é:

- Fluxo correto de desenvolvimento Shopify (template → section → schema)
- Uso correto dos objetos `page`, `product` e `collection`
- Uso de `schema` para permitir configuração via Admin
- Organização de código
- Versionamento com Git (branch + commits + PR)

---

## O que foi implementado

### Template exclusivo

- `templates/page.lotion-lp.json`
- Template para página principal da campanha

### Section principal

- `sections/lotion-lp.liquid`

A section:

- Exibe título e conteúdo da página (`page.title`, `page.content`)
- Permite selecionar um **produto principal**
- Permite selecionar uma **coleção**
- Lista produtos da coleção dinamicamente
- Possui fallback para uso como homepage
- CSS separado em arquivo próprio

### Estilização

- Arquivo dedicado em `assets/section-lotion-lp.css`
- Layout responsivo

---

## Como rodar localmente

### Instalar Shopify CLI

```bash
npm install -g @shopify/cli @shopify/theme
```

### Login na loja

```bash
shopify login
```

### Rodar ambiente de desenvolvimento

```bash
shopify theme dev
```

---

## Como configurar no Admin

### Criar produtos em:

- Admin → Products → Add product

### Criar coleção manual:

- Admin → Products → Collections → Create collection

### Configurar no Editor:

- Online Store → Themes → Customize

Selecionar:

- Produto principal → Coleção

### Link do Pull request

### Link do Vídeo
