# BRASA — Barbearia Demo

Site demonstrativo responsivo, em português, construído com HTML, CSS e JavaScript sem dependências de execução. Marca, profissionais, serviços e preços fictícios.

## Abrir

Abre `index.html` no navegador, ou usa a extensão Live Server no VS Code. Não é necessário instalar pacotes ou fazer deploy.

## Funcionalidades

- Layout responsivo com fotografia, preto e dourado envelhecido e títulos retro.
- Os seis links de marcação abrem https://brasademo.setmore.com/tomas num novo separador, sem depender de JavaScript.
- A escolha do serviço, disponibilidade, dados do cliente e confirmação são tratados pelo Setmore. O site não guarda reservas.
- O link fornecido é da agenda do Tomás; não pré-seleciona os serviços ilustrativos do site.
- É necessário configurar os serviços, preços e durações na conta Setmore: a página pública ainda apresentava reuniões gratuitas de exemplo no momento da integração.

As fontes são carregadas do Google Fonts; sem internet são usadas fontes locais de fallback. Não existem analytics ou integrações de pagamento. Fotografia local proveniente do Unsplash: https://images.unsplash.com/photo-1503951914875-452162b0f3f1 . A identidade visual inspira-se no conceito Peaky Blades (https://www.behance.net/gallery/223128327/Peaky-Blades-Barbershop-website-Concept), mantendo a marca fictícia BRASA.

## Estrutura

`index.html`: conteúdo e componentes; `styles.css`: identidade visual e responsividade; `app.js`: atualização do ano no rodapé.

Antes de adaptar a um cliente real, substituir dados fictícios, confirmar a configuração do Setmore e rever os requisitos de privacidade aplicáveis.
