# Jardim Kids — protótipo funcional

## O que está incluído
- Interface responsiva em português, inglês e espanhol (português inicial).
- Rotina visual com tarefas e horários editáveis.
- Marcação de tarefas concluídas.
- Área de responsáveis com PIN local.
- Adição, edição e remoção de tarefas.
- Exportação e importação de dados em JSON.
- Jogos simples de memória, associação, caminho e sequência de peças.
- Pausa tranquila com guia visual.
- Manifest e service worker para instalação e cache offline.

## Importante
Este é um protótipo inicial, não um produto clínico nem uma solução de segurança forte. O PIN é uma barreira local de interface; não use para proteger dados sensíveis. Dados ficam no armazenamento do navegador deste dispositivo. Use a exportação para fazer cópias.
Notificações web variam por navegador/dispositivo; esta versão pede permissão e faz um teste imediato, mas não agenda lembretes em segundo plano.
O manifest não inclui ícones de instalação personalizados ainda.

## Publicar no GitHub Pages
1. Crie um repositório separado chamado `jardim-kids` para não substituir o projeto anterior.
2. Envie `index.html`, `manifest.json` e `sw.js` para a raiz do repositório.
3. No GitHub, abra Settings → Pages.
4. Em Build and deployment, escolha Deploy from a branch, selecione `main` e `/ (root)`, e salve.
5. Aguarde a publicação; o GitHub mostrará o link do site na mesma página.
6. Abra o link no Chrome Android e use o menu para instalar, se a opção estiver disponível.
