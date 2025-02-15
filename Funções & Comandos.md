# Funções & Comandos
No MOD Macro existe diversos comandos ou funções para serem utilizadas. Para quem ja utilizou o excel deve entender perfeitamente o significado da palavra `função`.
Por lá usamos o prefixo `=` para avisar ao excel que vamos digitar algum comando. No entanto no MOD de Macro não é preciso de nenhum prefixo, o MOD entende que tudo
que for digitado se trata de **Funções** ou **comandos** como muita gente diz.
###### 
Abaixo está uma tabela com todas as **FUNÇÕES** inclusas no MOD de Macro

| Nome | Forma de Usar | Descrição |
|------|-------------|-----------|
| CLEARCRAFTING | `CLEARCRAFTING()` | Limpa a fila de criação automática |
| CRAFT | `CRAFT(<item[:damage]>,[amount],[throw],[verbose])` | Adiciona um pedido de criação automática na fila |
| CRAFTANDWAIT | `CRAFTANDWAIT(<item[:id]>,[amount],[throw],[verbose])` | Adiciona um pedido de criação automática na fila e espera pela conclusão |
| DISCONNECT | `DISCONNECT()` | Desconecta do jogo ou servidor atual |
| GETID | `GETID(<x>,<y>,<z>,<#idvar>,[#datavar])` | Obtém o ID e, opcionalmente, o valor de dados do bloco nas coordenadas especificadas |
| GETIDREL | `GETIDREL(<xoffset>,<yoffset>,<zoffset>,<#idvar>,[#datavar])` | Obtém o ID e, opcionalmente, o valor de dados do bloco nas coordenadas relativas ao jogador |
| GETITEMINFO | `GETITEMINFO(<item[:damage]>,[<&namevar>],[#maxstacksize],[&type],[#dropid])` | Obtém o nome e outras informações do item pelo ID |
| ELSE | `ELSE` | Define uma condição alternativa em um bloco de decisão |
| ELSEIF | `ELSEIF(<condition>)` | Define uma condição adicional dentro de um bloco de decisão |
| ENDIF | `ENDIF` | Finaliza uma estrutura de decisão IF |
| GETSLOT | `GETSLOT(<item[:damage]>,<#idvar>,[startfromslotid])` | Obtém o ID do slot contendo um item correspondente ao ID especificado |
| GETSLOTITEM | `GETSLOTITEM(<slotid>,<#idvar>,[#stacksizevar],[#datavar])` | Obtém informações sobre o item no slot especificado |
| IF | `IF(<condition>)` | Define uma condição para a execução do código |
| IFBEGINSWITH | `IFBEGINSWITH(<haystack>,<needle>)` | Verifica se uma string começa com outra string |
| IFCONTAINS | `IFCONTAINS(<haystack>,<needle>)` | Verifica se uma string contém outra string |
| IFENDSWITH | `IFENDSWITH(<haystack>,<needle>)` | Verifica se uma string termina com outra string |
| IFMATCHES | `IFMATCHES(<subject>,<pattern>,[&target],[group])` | Verifica se uma string corresponde a um padrão de expressão regular |
| INVENTORYDOWN | `INVENTORYDOWN([amount])` | Rola o número especificado de slots para baixo na barra de atalho |
| INVENTORYUP | `INVENTORYUP([amount])` | Rola o número especificado de slots para cima na barra de atalho |
| ITEMID | `ITEMID(<item>)` | Obtém o ID numérico legível do item |
| ITEMNAME | `ITEMNAME(<id>)` | Obtém a descrição do item para um ID numérico |
| LOGTO | `LOGTO(<target>,<text>)` | Exibe o texto especificado no destino fornecido |
| MATCH | `MATCH(<subject>,<pattern>,[&target],[group],[default])` | Executa uma correspondência de expressão regular |
| NEXT | `NEXT` | Finaliza um loop FOR-NEXT |
| PROMPT | `PROMPT(<&target>,<paramstring>,[prompt],[override],[default])` | Exibe uma caixa de entrada de texto para o usuário |
| REPLACE | `REPLACE(<&subject>,<search>,[replace])` | Substitui todas as ocorrências de uma string por outra |
| SET | `SET(<target>,[value])` | Define o valor de uma variável |
| UNSET | `UNSET(<flag>)` | Remove a definição de uma variável |
| UNTIL | `UNTIL(<condition>)` | Finaliza um loop DO-UNTIL baseado em uma condição |
| WHILE | `WHILE(<condition>)` | Finaliza um loop DO-WHILE enquanto a condição for verdadeira |

