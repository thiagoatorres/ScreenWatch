# 🖥️ ScreenWatch — Monitor de Tela & Auto-Refresh em Tempo Real

<p align="center">
  <img src="https://chromewebstore.google.com/detail/ebojgghhmomkpinadbbfeophikhaikld" alt="<img width="128" height="128" alt="Screen Monitor_icon128x128" src="https://github.com/user-attachments/assets/ace3838b-cdb7-459f-be68-424c94a77d01" />" width="120" />
</p>

<p align="center">
  <b>Uma extensão moderna para Google Chrome e Edge que monitora alterações visuais na tela e automatiza o recarregamento de abas.</b>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/ebojgghhmomkpinadbbfeophikhaikld">
    <img src="https://img.shields.io/badge/Chrome_Web_Store-v1.1.4-00ff88?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome Web Store" />
  </a>
  <a href="https://screenwatch.vercel.app">
    <img src="https://img.shields.io/badge/Landing_Page-Online-00875a?style=for-the-badge&logo=vercel&logoColor=white" alt="Landing Page" />
  </a>
  <img src="https://img.shields.io/badge/Plano-Free_%26_Pro-blue?style=for-the-badge" alt="Planos" />
</p>

---

## 📌 Sobre o Projeto

O **ScreenWatch** é um assistente inteligente desenvolvido para quem precisa acompanhar atualizações em tempo real sem precisar ficar olhando fixamente para o monitor. Ideal para traders, analistas de dados, analistas de SOC, acompanhamento de ingressos, leilões, reuniões ou lançamentos de produtos.

Com ele, o usuário pode selecionar qualquer região da tela ou aba do navegador, definir uma tolerância de sensibilidade e receber alertas sonoros no exato milissegundo em que uma divergência for detectada.

---

## 🚀 Principais Funcionalidades

- 🎯 **Seleção Customizada de Região:** Desenhe uma área específica da tela para vigiar (ex: um botão, gráfico ou valor).
- 🔄 **Page Auto Refresh Inteligente:** Recarregue abas automaticamente com intervals customizados (a partir de 5 segundos) com desvio de cache.
- 🔔 **Alertas Sonoros Instantâneos:** Notificações sonoras personalizadas ao detectar qualquer mudança na área marcada.
- 📊 **Histórico de Mudanças em Tempo Real:** Registro detalhado de logs de todas as capturas e divergências encontradas.
- 🌐 **Internacionalização (i18n):** Suporte completo para Português (PT-BR), Inglês (EN) e Espanhol (ES).
- 💎 **Modelo de Assinatura (Free / Trial / Pro):** Sistema completo de licenciamento integrado via Stripe e Supabase.

---

## 🛠️ Arquitetura & Tecnologias Utilizadas

O projeto foi construído utilizando as melhores práticas modernas de desenvolvimento web e segurança de extensões:

- **Frontend / Extensão:** JavaScript (ES6+), HTML5 Canvas, CSS3 Moderno (Glassmorphism e Variáveis HSL), Chrome Extension Manifest V3.
- **Autenticação Segura:** Supabase Auth via OAuth2 Nativo (`chrome.identity.launchWebAuthFlow`).
- **Backend & Serverless:** Supabase Edge Functions (Deno / TypeScript).
- **Gestão de Pagamentos:** Stripe Checkout & Billing Portal via Webhooks em tempo real.
- **Landing Page:** HTML5 / CSS3 / JavaScript com hospedagem de alta performance via Vercel.

---

## 🔗 Links Oficiais

- 🛒 **Baixar na Chrome Web Store:** [ScreenWatch na Chrome Web Store](https://chromewebstore.google.com/detail/ebojgghhmomkpinadbbfeophikhaikld)
- 🌐 **Website Oficial / Landing Page:** [ScreenWatch Web App](https://screenwatch.vercel.app)

---

<p align="center">
  <i>Desenvolvido com 💚 para automatizar sua rotina e maximizar sua produtividade.</i>
</p>
