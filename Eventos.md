# Disparar macro após eventos
O Mod macro contem um tela de configurações no MOD, essa tela permiti atribuir configurarmos para dispara alguma macro quando o ***X*** evento ocorre.
Para configurar esse ***disparo*** de macro, basta acessar o **Menu MACRO** por meio das teclas que já vem padronizadas com o MOD: `SHIFT esquerdo + "`
###### 
Agora basta abrir o menu de **eventos** indo no botão ► conforme a imagem: 
#### ![Menu](https://i.imgur.com/WNdgxG1.png)
Escolha qual evento você deseja. A tabela abaixo contem todos os detalhes de cada eventp:
| Evento                      | Função | Imagem |
|-----------------------------|--------|--------|
| **onJoinGame**              | Ativado quando o jogador entra no servidor. | ![onJoinGame](https://i.imgur.com/ztvbUpD.png) |
| **onChat**                  | Disparado quando qualquer mensagem de chat é recebida. | ![onChat](https://i.imgur.com/MHo8vK2.png) |
| **onHealthChange**          | Ativado quando a barra de vida do jogador muda. | ![onHealthChange](https://i.imgur.com/EBwintH.png) |
| **onFoodChange**            | Disparado quando a barra de fome do jogador muda. | ![onFoodChange](https://i.imgur.com/GGKSOcU.png) |
| **onArmourChange**          | Ativado quando a armadura equipada pelo jogador muda. | ![onArmourChange](https://i.imgur.com/UgZgmEJ.png) |
| **onWorldChange**           | Executado quando o jogador muda de mundo/dimensão. | ![onWorldChange](https://i.imgur.com/FS7Zztq.png) |
| **onModeChange**            | Disparado quando o modo de jogo do jogador é alterado (ex: Survival para Criativo). | ![onModeChange](https://i.imgur.com/gm9zGZO.png) |
| **onInventorySlotChange**   | Ativado quando o jogador muda o item que está segurando na hotbar. | ![onInventorySlotChange](https://i.imgur.com/Miwhio0.png) |
| **onOxygenChange**          | Executado quando o nível de oxigênio do jogador muda (mergulhando). | ![onOxygenChange](https://i.imgur.com/yDGLCLD.png) |
| **onXPChange**              | Disparado quando a barra de experiência do jogador muda. | ![onXPChange](https://i.imgur.com/tfUHbmz.png) |
| **onLevelChange**           | Ativado quando o nível de experiência do jogador muda. | ![onLevelChange](https://i.imgur.com/lLJw7hi.png) |
| **onItemDurabilityChange**  | Disparado quando a durabilidade do item na mão do jogador muda. | ![onItemDurabilityChange](https://i.imgur.com/zbQ6Bqm.png) |
| **onWeatherChange**         | Ativado quando o clima do jogo muda (ex: sol para chuva). | ![onWeatherChange](https://i.imgur.com/549LuWz.png) |
| **onPickupItem**            | Disparado quando o jogador coleta um item do chão. | ![onPickupItem](https://i.imgur.com/p057VlK.png) |
| **onPlayerJoined**          | Executado quando um jogador entra no servidor (se aplicável). | ![onPlayerJoined](https://i.imgur.com/vqmmWTr.png) |
| **onShowGui**               | Ativado quando uma interface gráfica (GUI) do jogo é aberta. | ![onShowGui](https://i.imgur.com/LY7gi9j.png) |
| **onArmourDurabilityChange**| Disparado quando a durabilidade da armadura do jogador muda. | ![onArmourDurabilityChange](https://i.imgur.com/gLMGEyy.png) |
| **onAutoCraftingComplete**  | Ativado quando um item é automaticamente craftado. | ![onAutoCraftingComplete](https://i.imgur.com/PW83f7O.png) |
| **onConfigChange**          | Executado quando uma configuração do mod é alterada. | ![onConfigChange](https://i.imgur.com/uOizTJ9.png) |
| **onSendChatMessage**       | Disparado quando o jogador envia uma mensagem no chat. | ![onSendChatMessage](https://i.imgur.com/6ZD4ifF.png) |

# Exemplo de configuração
Vamos utilizar o evento **onWorldChange** para digitar algum comando quando trocamos de mundo no minecraft. Para aqueles que jogam em servidor multiplayers que possuem 
o comando `/pvp off` como é o caso o servdidor da Craftlandia, é algo muito útil para desativar o pvp quando trocamos de mundo. Pois bem, vamos fazer uma
MACRO para que ao trocarmos de mundo, automaticamente o comando seja acionado.
######
1. Vamos clicar sobre o evento **onWorldChange**
###### ![onWorldChange](https://i.imgur.com/FS7Zztq.png)
2. No campo de texto localizado na parte inferior da tela:
###### ![Campo de texto](https://i.imgur.com/e8AiEob.png)
Vamos digitar o comando que queremos, no caso `/pvp off`
######
3. E agora bastar salvar e fechar o menu
###### ![Salvar](https://i.imgur.com/9ySxP1L.png)

###
Escrito em 15/02/2025
