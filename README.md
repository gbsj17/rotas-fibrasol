# 🚚 Logística Fibrasol — PWA & Sistema de Rotas

O **Logística Fibrasol** é uma aplicação web progressiva (PWA) desenvolvida para otimizar o acompanhamento, gestão e execução de rotas de entregas em tempo real. O sistema integra administradores, motoristas e representantes em uma interface fluida, responsiva e pronta para dispositivos móveis (Android / iOS).

---

## 📌 Principais Funcionalidades

### 👨‍💼 Painel do Administrador
* **Gestão de Rotas:** Importação automática de itinerários via links do Google Maps ou listas de endereços.
* **Atribuição Dinâmica:** Envio imediato de cargas para motoristas e vinculo de representantes para acompanhamento.
* **Histórico e Relatórios:** Agrupamento de cargas finalizadas por mês, métricas de cidades atendidas e estatísticas de desempenho individual.
* **Gestão de Acessos:** Cadastro, alteração de credenciais/PINs e controle de sessões para Admins, Motoristas e Representantes.

### 🚛 Painel do Motorista
* **Acompanhamento Passo a Passo:** Checklist dinâmico das paradas da rota com atualização em tempo real no Firebase.
* **Integração GPS:** Botão direto para navegação via Google Maps.
* **Modo Resumo:** Estatísticas rápidas de quilometragem estimada, dias de viagem e cargas concluídas no mês.

### 💼 Painel do Representante
* **Acompanhamento de Cargas:** Busca rápida por número de carga ou motorista para adicionar itinerários ao painel de monitoramento.
* **Status em Tempo Real:** Visualização do progresso das entregas por cidade e histórico de cargas concluídas.

---

## 🚀 Tecnologias Utilizadas

* **Frontend:** HTML5, Tailwind CSS, Font Awesome
* **Backend & Banco de Dados:** Firebase Firestore (Tempo Real) com Fallback inteligente para LocalStorage
* **Arquitetura PWA:** Service Worker (`sw.js`) para suporte a instalação mobile e funcionamento otimizado
* **Hospedagem:** GitHub Pages

---

## 📋 Histórico de Versões (Patch Notes)

### 🟢 v1.0.3 (Versão Atual)
* **Menu Flutuante & Patch Notes:** Adição de ícone de engrenagem no topo com badge de notificação e botão de atualização manual com limpeza de cache.
* **Sessão Persistente:** Correção do fluxo de autenticação para manter motoristas e representantes logados continuamente ao recarregar a página no Android.
* **Gestão de Equipe:** Adicionada a funcionalidade de alteração de senha e desconexão remota de usuários diretamente pelo painel Admin.
* **Splash Screen de 2s:** Tela de abertura estendida para 2 segundos com indicador visual de conexão ao Firebase.
* **Transições Suaves:** Animações ajustadas para 0.5s no estilo Android puro, eliminando deslocamentos/tremores no layout.

### 🟡 v1.0.2
* Adição do card/guia interativo de instalação do PWA para navegadores mobile.
* Métricas e dashboard de desempenho mensal de motoristas no painel de administração.

---

## 📱 Como Instalar como PWA no Celular

### Android (Chrome)
1. Acesse o link da aplicação no Chrome.
2. Toque nos três pontos (**⋮**) no canto superior direito.
3. Selecione **"Adicionar à tela inicial"** ou **"Instalar aplicativo"**.

### iPhone (Safari)
1. Acesse o link da aplicação no Safari.
2. Toque no botão de **Compartilhar** no rodapé.
3. Role e selecione **"Adicionar à Tela de Início"**.

---

Desenvolvido para **Logística Fibrasol** • *Sincronização em Tempo Real*
