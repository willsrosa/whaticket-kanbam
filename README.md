# WhaTicket Saas</br>
Versão em Testes</br>
Adicionado Módulo Kanban</br>
Funcionando com Baileys 6.5.0 - Setembro de 2023 </br>
</br> Atualizado referencias para a bilioteca @WhiskeySockets/Baileys</br>
Modificado AnyWASocket, WALegacySocket, LegacyAuthenticationCreds</br>
Corrigio Bot repete menu</br>
Atualizações Fontend</br>
</br> Adicionado conexões Insta e Facebook - Em Revisão
</br> Adicionado Lista de Tarefas (Função que usa o cache do navegador)

Tipo de Chatbot = Somente Texto <br> Removido as opções depreciadas, Listas e Botões.

</br> Não é necessário estar com celular ativo e conectado a internet para receber mensagens.
Envio de mídia > Ok.</br>
Agendamento de mensagens > Ok.</br>
Importar contatos do telefone > OK. </br>
Envio de campanhas > Ok. </br>
Download e Importação de Lista de Contatos em Campanhas. > OK </br>
Criar contatos de campanha direto no painel. > OK </br>
CallBack GerenciaNet via Insomnia. > Ok </br>
Midia no Chat. > Ok</br>
Escutar Audios > Ok </br>
Localização Fixa. > Ok - Não funciona em tempo real, mesmo na api oficial</br>

Planos Futuros:
Atualização de Material UI 4 para MUI 5
Correção de Webhook Facebook (Messenger e Direct).

Em Observação:
Tickets de Admin são fechados automaticamente na avaliação </br>
(verificar se corrigiu) Tickets de usuários recebem a nota e só fecham e enviam disparo da mensagem de encerramento quando clica novamente em resolver.
Ao modificar gerenciamento de horários limpe as configurações anteriores primeiro.

Personalizações:

** Alterar Cores Primárias:</br>
/frontend/src/App.js</br>
/frontend/src/layout/index.js
/frontend\src\pages\Chat\ChatMessages.js

** Cores do Chat Interno:
frontend\src\pages\Chat\ChatList.js</br>

** Logo e LogoLogin:
/frontend/src/assets

** Icone e Favicon:
/frontend/public

** Comando para rebuild, caminho absoluto /home/deploy/"nome"/
  
```bash
cd /frontend
npm run build


URL WEBHOOK META:

```bash
https://api.seudominio.com.br/webhook/fb
