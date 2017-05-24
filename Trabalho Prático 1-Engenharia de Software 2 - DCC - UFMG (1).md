Trabalho Prático 1
Engenharia de Software 2 / DCC - UFMG 
===


Prof. Marco Tulio Valente


Guilherme Oliveira Souza // 
Julia Pereira Sepulveda

![](https://i.imgur.com/b7xgYeP.png)

## 1. Introdução
Este trabalho tem o objetivo de propiciar a documentação de um sistema real, e o contato com sua arquitetura bem como uma realização de documentação colaborativa utilizando GitHub.

Foi escolhida a IDE RStudio para ser documentada. 
A ferramenta está disponível para  doawload em : https://www.rstudio.com/
e através do ambiente colaborativo https://github.com/rstudio/rstudio .

RStudio é um ambiente de desenvolvimento integrado (IDE) para R. Ele inclui um console, editor que suporta execução de código direto, bem como ferramentas para plotar , depurar e gerenciar o espaço de trabalho para R.
O RStudio está disponível em open source e edições comerciais e é executado no desktop (Windows, Mac e Linux) ou em um navegador conectado ao RStudio Server ou ao RStudio Server Pro (Debian / Ubuntu, RedHat / CentOS e SUSE Linux). É o primeiro ambiente de desenvolvimento integrado para R. 
O RStudio possui algumas vantagens em relação ao R Gui:

    Highlight do código;
    Autocomplete;
    Match automático de parenteses e chaves;
    Interface intuitiva para objetos, gráficos e script;
    Criação de “projetos” com interface para controle de versão;
    Facilidade na criação de pacotes;
    Interação com HTML, entre outras.

Para melhor compreender a finalidade do RStudio é preciso compreender a finalidade do R.
![](https://i.imgur.com/ZtJL8lw.jpg)
R é uma linguagem e ambiente para computação estatística e desenvolvimento de gráficos. Trata-se de um projeto GNU que é semelhante à linguagem S(S é uma linguagem de programação estatística, desenvolvida por John Chambers, hoje é mantida por Rick Becker e Allan Wilks dos Laboratórios Bell. De acordo com John Chambers o objetivo da linguagem é "facilitar e acelerar a transformação de ideias em software."
As duas implementações modernas de S são R e S-PLUS.) O R pode ser considerado como uma implementação diferente de S. Existem algumas diferenças importantes, mas muito código escrito para S funciona inalterado sob R. R fornece uma grande variedade de ferramentas estatística (modelagem linear e não-linear, testes estatísticos clássicos, análise de séries temporais, classificação, agrupamento, ...) e técnicas gráficas, e é altamente extensível e recomendável para quem trabalha com ciência dos dados . A linguagem S é muitas vezes o veículo de escolha para a pesquisa em metodologia estatística, e R fornece um sistema Open Source para as atividades acima indicadas. Uma das vantagens de R é a facilidade com que podem ser produzidas parcelas de qualidade de publicação bem concebidas, incluindo símbolos matemáticos e fórmulas quando necessário. O usuário matem controle total da ferramenta e os padrões para as escolhas menores no design de criação dos seus gráficos.
R está disponível como Software Livre sob os termos da Licença Pública Geral GNU da Free Software Foundation em código fonte. Ele compila e executa em uma ampla variedade de plataformas UNIX e sistemas similares (incluindo FreeBSD e Linux), Windows e MacOS.


## 2. RStudio - Visão Geral

A empresa responsavel foi fundada em 2008, com produtos gratuitos e de código aberto e disponível para usuários em 2009. Porém RStudio teve publicação publica e paga. No contexto de utilização do sistema R encontramos o RStudio que é o primeiro ambiente de desenvolvimento integrado para R. Esta IDE apresenta para a versão Desktop a possibilidade de Edição Open Source e também a versão com Licença Comercial. Vasta documentação está disponível em https://www.rstudio.com/ ou em https://github.com/rstudio/rstudio.
Detalhes mais específicos da Documentação podem ser obtidos em:
https://support.rstudio.com/hc/en-us/categories/200035113-Documentation

A figura RStudio Desktop apresenta um comparativo entre as duas versões disponíveis.

Inspirado pelas inovações dos usuários R na ciência, educação e indústria, RStudio desenvolve ferramentas livres e abertas para R e produtos profissionais prontos para empresas para que as equipes escalem e compartilhem o trabalho.

A RStudio tem a missão de fornecer o software profissional de código aberto mais utilizado e prático para a empresa para o ambiente de computação estatística R. Essas ferramentas promovem a necessidade de equipar todos, independentemente de meios, para participar de uma economia global que recompensa cada vez mais a alfabetização de dados e sua análise.
O principal produto é um Integrated Development Environment (IDE), que torna fácil para qualquer pessoa analisar dados com R. Também é oferecido muitos pacotes R, incluindo Shiny e R Markdown, e uma plataforma para compartilhar aplicativos interativos e relatórios reprodutíveis para compartilhar com outros.

O RStudio tem uma equipe distribuída com sede no Distrito de Inovação de Boston, e um segundo escritório em Seattle. Sua equipe de desenvolvedores pode ser encontrada em Arkansas, British Columbia, Califórnia,  Colorado,  Connecticut, Florida,  Geórgia,  Ohio, Indiana, Maryland, Minnesota,  Nebraska, Carolina do Norte, Nova York,... na Bélgica e em Portugal! 

R possibilita a compreenção e atitudes para melhorar  o mundo através da possibilidade de análise de dados. Para que isso ocorra RStudio é um facilitador de R e disponível para Windows, Mac e Linux e de um navegador da Web para servidor Linux executando RStudio Server ou RStudio Server Pro.

As duas figuras seguintes apresentam destaques e diferenças entre as versões comerciais e livre.Bem como ao que RStudio se destina e funcionalidades.
![RStudio Desktop - Edição Aberta e Licença comercial](https://i.imgur.com/RYJLncG.jpg)

![](https://i.imgur.com/zwvsaA0.png)

O RStudio permite que os usuários compartilhem e colaborem nos resultados que produzem com o sistema R, como documentos R Markdown, aplicativos gráficos por exemplo. O código-fonte ou os artefatos renderizados podem ser implantados  através do RStudio Connect e compartilhados seletivamente com outros usuários e colaboradores de uma organização. Alguns conteúdos podem até ser agendados para serem re-executados e enviados por e-mail em um determinado cronograma. O RStudio-Connect também pode ajudar a simplificar o papel do administrador do sistema encarregado de suportar R, oferecendo:

   - Métricas detalhadas para o servidor e os processos R associados.
   - Logs para todos os processos R gerados por Connect.
   - Implementações seguras e interações com artefatos usando SSL / TLS.
   - Dimensionar uma aplicação GRÁFICA além de um único processo R para suportar a        carga adicional do visitante


## 3. Como Funciona e funcionalidades 


O RStudio é executado na maioria dos desktops ou em um servidor e acessado pela web:
![](https://i.imgur.com/dcXcDLI.png)


RStudio integra as ferramentas que você usa com R em um único ambiente:

## 4. Primeiros Passos na Utilização do Programa

#### Download e instalação do RStudio
Para instalar Rstudio é preciso baixar a última versão de R, ou uma de suas versões a partir da versão 2.11.1. E para baixar a última versão de R é necessário adicionar o repositório CRAN ao sistema.
O R está disponível para as plataformas UNIX, Windows e MacOS.

R Gui
A instalação padrão do R vem com uma interface gráfica para o usuário (Graphical User Interface – GUI). No Windows, você encontrará o R no menu iniciar e no Mac você verá o ícone do R entre seus aplicativos. Nós não vamos utilizar o R Gui durante o livro. Entretanto, faremos um brevíssimo tour antes de passarmos para o RStudio.



A configuração de instalação requer que a pasta seja armazenada em sbin, isso ocorre através do rstudio-server, que permite as funções de iniciar, parar, reiniciar o sistema, tambám para a enumeração de seções de usuário, fazer o sistema ficar offline e permitir futuras instalações para atualizar a versão corrente utilizada do sistema.
Caso a funcionalidade de instalação não aconteça na pasta sbin, é necessário manualmente requisitar que os pacotes do rstudio sejam instalados em /usr/sbin. No caso da instalação nos sistemas Debian/Ubuntu/RedHat/CentOS/openSUSE/SLES é preciso apenas especificar no comando $ sudo /usr/sbin/rstudio-server restart, que é a administração do script. Em outras plataformas é provável que a instalação ocorrerá através da fonte corretamente e instalará automaticamente, mas a instalação de Rstudio foi testada apenas nos sistemas citados anteriormente.

No R
Abra a interface gráfica do R em seu computador.A primeira tela que você verá é a do console. Agora, abra, também, uma tela de editor de texto em “file” -> “new script”.
![](https://i.imgur.com/jmORKIv.png)

Escreva os seguintes comandos no editor de texto e aperte CTRL+R (ou CMD+ENTER no Mac).

1
1+1
O comando será enviado para o console e você verá o resultado. Você poderia ter digitado o comando diretamente no console, mas isso não é uma boa prática. Acostume-se a sempre escrever em seu script (script é como chamamos o documento com os códigos de R que você produz).

1
[1] 2
Escreva os seguinte comandos no editor de texto e repita o procedimento (CTRL+R):

1
plot(1:10)
Uma nova tela será aberta com o gráfico.
![](https://i.imgur.com/lhJTNaS.png)




#### Rstudio Instalação e Configuração

Instalar o R e o RStudio é bastante fácil, pois ambos já vêm com distribuições compiladas para Windows, Mac OS ou Linux. O RStudio pode ser obtido nos sites indicados na introdução deste trabalho  

O servidor do RStudio usa vários arquivos de configuração localizados em /etc/rstudio.
Os arquivos de configuração incluem:
 - rserver.conf 
 - rsession.conf
- profiles
- ip-rules 
- load-balancer 
- health-check 
- google-accounts 
- file-locks 
- login.html 

RStudio autentica usuários através da API PAM(Pluggable Authentication Module) API. PAM normalmente é configurado por padrão para autenticar usando o sistema de banco de dados (/etc/passwd). É possível configurar a PAM para personalizar a sessão de usuário.

É possível modificar a porção do sevidor do RStudio de todos os usuários remotos apenas para o localhost. O meio para conectar esse servidor é através do proxy, modificando o endereço de www-address para /etc/rstudio/rserver.conf pelo comando: www-address=127.0.0.1

Após instalação e configuração:
Abra o RStudio em seu computador e inicie um novo Script em “File” -> “New File” -> “New RScript”. Você também pode fazer isso com CTRL + SHIFT + N. O resultado será:
![](https://i.imgur.com/REMT3Lv.png)

Podemos dividir a tela do RStudio em quatro grande áreas:

![](https://i.imgur.com/BgDHimI.png)



### 4.1 Comandos
#### Alguns Comandos simples da Rstudio:

##### - activate-offline-request   -    Gera requisito offline.
##### - activate-offline	-    Usa um arquivo para ativar offline.
##### - activate	Ativa botaõ usando um botão específico.
##### - begin-evaluation-offline	-	Começa o uso de uma versão teste verificada offline.
##### - begin-evaluation-request	-	Gera requerimento para usar versão de teste verificada.
##### - deactivate-offline	-	Desativa offline.
##### -  deactivate	-	Desativa online.

#### Alguns dos atalhos do teclado:
RStudio permite o previsor automatico de código pela Tab key. 
- Up key recupera comandos anteriores. 
- Down key desfaz a recuperação dos comandos anteriores.
- Ctrl+Up mostra uma lista dos comandos mais recentemente usados, também permite que um comando seja completado pelas opções de possíveis comandos previstos a partir de um comando pré escrito.
- Ctrl+1 muda o foco para o Editor Fonte
- Ctrl+2 muda o foco para a barra do aplicativo
- Ctrl+L limpa o que foi escrito em todo o sítio
- Esc interrompe a compilação de R
- Shift+F9 em cima da linha interrompe a compilação daquela linha (automatico)
#### Alguns dos comandos em linha:
browser() interrompe execução e inicia o ambiente browser (durante compilação).
debugonce() coloca um marcador de debug em uma função.
Para debugar toda vez que é lida debug(...) deve ser chamado na função. 
undebug(...) deve ser chamado na função quando não for para debugar mais a cada execução.
options(error = browser()) para debugar cada erro individualmente
Traceback (Callstack) compartilha o painel do ambiente. Esse comando mostra como a execução fez para atingir seu ponto atual. Desde a primeira função executada até a função sendo compilada no instante atual.
F10	        Executa próximo comando
Shift+F4	Entra na função
Shift+F6	Finaliza função ou loop
Shift+F5	Continua execução
Shift+F8	Interrompe debug


### Comandos pelo Script
Como já dito, acostume-se a escrever o código no Script ao invés de ficar escrevendo diretamente no console. Para começarmos a nos familizarizar com o RStudio, escreva o código abaixo no Script:
```xml=
1
1+1
E aperte CTRL+ENTER (CMD+ENTER no mac). Isso envia o comando para o console e o resultado é exibido logo abaixo.

1
# # [1] 2
Agora escreva o seguinte código no Script.

1
2
# Gráfico dos números de 1 a 10
 plot(1:10)
```
Há uma infinidade de outros comandos compatívies com R. 
O quadro abaixo apresenta criação de uma regressão linear , e o resultado com erro apresentado pelo RStudio. 





### 4.2 Visão de Caso de Uso
![](http://imgur.com/gsORr8I.jpg)
Esse caso de uso representa o RStudio como o ambiente de desenvolvimento que modera a interação do usuário com a linguagem R, mostrando as principais funcionalidades do RStudio.
### 4.3 Execução
![](http://imgur.com/4Td5PUG.png)
##### Documentos e Aplicativos
Abre arquivos Shiny, R Markdown, knitr, Sweave, LaTeX no Painel de Fonte. Verifica ortografia, renderiza e escolhe o formato de saída, insere código.
##### Escrita de Código
Navega nas abas, salva, busca, compila, executa o código selecionado.
##### Modo de Depuração
Abre com debug(), browse(), ou um breakpoint. O RStudio abrirá o modo de depuração quando encontrar um breakpoint durante a execução. Abre o traceback para examinar as funções que o R chamou antes do erro acontecer.
##### Escrita de Pacotes
Transforma o projeto em um pacote. Habilita a documentação roxygen com Tools > Project Options > Build Tools. E guia Roxygen em Help > Roxygen Quick Reference
##### Sistema de Projetos
O RStudio salva o histórico de chamadas, o workspace, e o diretório de trabalho associado com o projeto. E recarrega tudo quando o projeto for reaberto.
File > New Project
##### Funcionalidades RStudio Pró
Compartilha projeto com Colaboradores. Mostra colaboradores ativos. Escolhe versão R. Inicia/fecha nova Sessão R no projeto.

## 5. Equipe de Desenvolvimento.
A equipe de desenvolvimento do RStudio conta com mais de 48 colaboradores. 
Os 10 principais colaboradores com o desenvolvimento da IDE, estão abaixo indicados.
![](https://i.imgur.com/dpgqf6B.png)

A tabela indica os desenvolvedores e quantidade de comits de inclusão de código e retirada de código. 

Nome|Usuário|Comits
---------|------|--------------------------|-----------------
|JJ Allaire|jjallaire| 7,627 commits / 749,863 ++ / 366,374 --
|Kevin Ushey|kevinushey|3,817 commits / 267,601 ++ / 121,471 --
|Jonathan|jmcphers|3,000 commits / 480,046 ++ / 342,103 --
|Joe Cheng|jcheng5|1,428 commits / 295,725 ++ / 183,126 --
|Javier Luraschi|javierluraschi|1,223 commits / 35,175 ++ / 14,289 --
|Gary|gtritchie|394 commits / 127,109 ++ / 50,907 --
|Effreyhorner|jeffreyhorner|23 commits / 1,186 ++ / 511 --
|Randy Lai|randy3k|9 commits / 303 ++ / 58 --
|Steve Nolen|stevenolen|9 commits / 1,341 ++ / 583 --
|Justace Clutter|justacec|8 commits / 78 ++ / 6 --





#### 5.1 Como contribuir
É possível baixar e implementar localmente a partir da liberação de edição no github, bem como participar de comunidade de discução onde são colocados os desejos, funcionalidade como por exemplo em:

https://support.rstudio.com/hc/en-us/community/topics/200022758-Feature-Requests
onde são postadas as requests do sistema. 

#### 5.2 Issues

O sistema não apresenta Issues abertas até a presente data. O número de Issues abertas e fechadas é 0. 

#### 5.3 Labels
Assim como não há issues em aberto, não há Labels especificas. 


## 6. Evolução do Sistema
A empresa foi fundada em 2008 com produtos gratuitos e de código aberto entregues pela primeira vez em 2009. Em 2011 houve a publicação pública inicial do RStudio em 2011
Série A em 2013: Catalizador Geral, Linha de Base
RStudio Server Pro e RStudio Shiny Server Pro anunciados no final de 2013
Serviço Shinyapps.io lançado no início de 2015
RStudio Connect entregue no final de 2016.
A tabela lista as principais datas de evolução do sistema
Versão|Data
-----|---------|
|RStudio v1.0a | 21/12/2016 |
|RStudio v1.0 |1/11/2016 |
|RStudio v0.99b |18/07/2016 | 
|RStudio v0.99a |26/05/2015 | 
|RStudio v0.98b |06/03/2015 | 
|RStudio v0.98a |25/04/2014 |
|RStudio v0.97 | 11/05/2013 | 
|RStudio v0.96 | 27/08/2012 |
|RStudio v0.95 | 05/04/2012 |
|RStudio v0.94 | 03/10/2011 |
|RStudio v0.93 | 04/04/2011 |

### 6.1 Principais releases e suas funcionalidades
RStudio apresenta uma dinâmica de releases acentuada. Desde seu lançamento em  2009, até a última versão publicada foram inumeras atualizações, ao longo desse tempo.

####  Principais modificações, melhorias e correções com a versão RStudio v1.0a 21/12/2016

Dimensionamento melhorado de htmlwidgets em R Notebooks.
Permitir a alteração para o modo R Notebook sem fechar e reabrir o arquivo.
Adicionar suporte para pedaços de código knitr definidos em arquivos .R externos.
Adicionar suporte para caminhos relativos crus, como ".." na opção knitr root.dir.
Adicionar suporte para 'output.var' opção pedaço para Stan pedaços.
Melhorar a rolagem após htmlwidgets no editor.
Sempre mostre as preferências de saída do chunk (inline ou console).
Adicione suporte para widgets HTML de altura variável (figuras não-knitr).
Melhorar o suporte para caracteres não-ASCII em metadados de bloco e saída.
Adicionar suporte para blocos JavaScript e CSS e Importação de dados.

Foi Adicionado suporte para todas as configurações locais de readr (formato de data / hora, decimal, etc.).
É solicitar uma lista de fatores separados por vírgulas em vez de uma coleção
Diversos.

Adicionar atalhos Ctrl + Tab / Ctrl + Shift + Tab para navegar nas guias (somente Desktop).
Incluir arquivos .scala no localizador de arquivos fuzzy (Ctrl +.).
Adicione suporte para documentos Shiny pré-renderizados (shiny_prerendered).
Atualizar o modo de editor Stan para suportar o Stan 2.12.0.
Server Pro: Adicionar nova opção www-frame-origin para especificar permissões de enquadramento.

##### Correções de bugs

Melhorou a resiliência contra o cabeçalho YAML malformado em documentos R Markdown
Evite acionar vínculos ativos em ambientes a partir do painel Ambiente.
Corrigir a codificação de R_HOME, R_USER e R_LIBS_USER no Windows.
Corrigir a conclusão do arquivo baseado em projeto no Windows.
Respeito os pacotes carregados na conclusão do tópico de ajuda do R
Corrigir o posicionamento dos botões da barra de ferramentas do editor no cliente Safari e Mac OS
Corrigir a altura incorreta das saídas do Notebook R quando executado acima da janela de exibição
Detectar cadeias de dados multi-line corretamente
Permitir git stating para nomes de arquivos contendo um espaço no Windows
Use as configurações de proxy do Windows para atender às solicitações feitas pelo htmlwidgets
Corrigir o erro entre domínios ao abrir um link para o RStudio Server em uma nova janela
Corrigir comentário toggling para ROxygen comentários
Corrigir problemas de recursos do notebook ocorrendo em projetos em sistemas de arquivos montados
Server Pro: Permite que o usuário do servidor tenha o nome do grupo diferente do nome do usuário
Server Pro: Não exigem LDAP para suportar enumeração de usuário quando auth-required-user-group é definido

##### Principais modificações, melhorias e correções com a versão RStudio v1.0 de 01/11/2016

##### Destaques

Ferramentas de criação para Notebooks R.
Suporte integrado para o pacote sparklyr (interface R para Spark).
Ferramentas de importação de dados aprimoradas baseadas nos pacotes readr, readxl e haven.
Perfil de desempenho através da integração com o pacote profvis.
Ferramentas de criação para sites R Markdown e o pacote bookdown.
Muitos outros aprimoramentos diversos e correções de bugs.

R Notebooks

Ferramentas de criação para notebooks R
Exibição em linha para texto, látex, dados tabulares, gráficos e htmlwidgets no editor de origem
Todo o código e saída salvos em um único arquivo HTML do caderno (.nb.html)
Múltiplos mecanismos de linguagem incluindo Python, Bash, SQL, Rcpp e Stan
Ferramentas para executar várias combinações de pedaços (atual, próximo, anterior, remanescente)
Importação de dados

Importar conjunto de dados do texto via readr
Importar conjunto de dados do Excel via readxl
Importar conjunto de dados de SAS, SPSS e Stata via haven
Visualizar dados ao importar conjuntos de dados
Definir explicitamente tipos de coluna ao importar conjuntos de dados
Pré-visualizar e copiar código ao importar conjuntos de dados
perfil

Funções de perfil com base no pacote profvis
Visualize resultados de perfil dentro do IDE
O menu Perfil permite a fácil parada / início do perfilamento ou criação de perfis das linhas selecionadas.
Salvar e carregar sessões de criação de perfil anteriores
RStudio Connect

Publicar relatórios, aplicativos e gráficos para o RStudio Connect
Implementação com um clique das aplicações brilhantes
Publicar e agendar a execução periódica de relatórios de Markdown R
Definir quais usuários e / ou grupos têm permissão para visualizar o conteúdo
Faísca

Suporte integrado para o pacote sparklyr
Criar e gerenciar conexões com clusters Spark e instâncias locais do Spark
Procurar tabelas e colunas de Spark DataFrames
Visualizar as primeiras 1.000 linhas de Spark DataFrames

#### Editor de fontes

Ctrl + Enter agora executa a instrução R atual quando a seleção está vazia
Use Shift + Clique para abrir links da web no editor de código-fonte (Comando + Clique no OS X)
Enabled auto-emparelhamento de backticks (") em documentos R
Regressão fixa re: dobradura de secções não identificadas, p. '#####'
Implementação do dobramento para sub-seções em documentos R
Opção adicionada para exibição de marcadores de dobra 'final'
Mostrar tooltip da função no mouse sobre o nome da função
Adicionado opção para exibir tooltip assinatura função no cursor ocioso
O preenchimento automático permite a incompatibilidade entre '.', '_' No token
Melhorias no utilitário de refatoração 'Renomear no escopo'
Expandir comando de seleção aprende como expandir para a instrução atual
Adicionado (como comando não vinculado) Sublime Estilo de texto 'Quick Add Next'
Os vários comandos 'yank' são agora rebindable (Ctrl + Y, Ctrl + K, Ctrl + U)
Inserir operador de atribuição (Alt + -, '<-') agora é re-acessível
Inserir operador de tubulação (Cmd + Shift + M, '%>%') agora é re-acessível
Ativar implementadores de .DollarNames para fornecer tipos personalizados

#### R Markdown

Visualização in-line para equações MathJax
Mostrar formatos personalizados no menu Knit
Mostrar menu de opções e Knit w / Params para formatos personalizados
Use "Executar Documento" para formatos personalizados com tempo de execução: brilhante
Adicionar opção para suprimir Pré-visualização de malha completamente
Adicionar o painel R Markdown à caixa de diálogo de opções globais
Criar guia e visualização de suporte para sites R Markdown
Vários aprimoramentos para a criação com o pacote bookdown
Adicionar comando para limpar cache de knitr
Atualizar pandoc para 1.17.2
Atualizar MathJax para 2.6.1
C / C ++

Fornecer o preenchimento automático de caminhos de cabeçalho
Destaque de sintaxe de literais de seqüência de caracteres brutos, largos e unicode (por exemplo, R "hello")

##### Servidor


Adicionadas as opções session-default-working-dir e session-default-new-project-dir.
Adicionado pacotes sudo, lsb-release e libssl1.0.0 para dependências Debian.
Server Pro: Auditoria para eventos de autenticação e início / suspensão / saída da sessão.
Server Pro: Capacidade de configurar por tempo limite de sessão por usuário e por grupo.
Server Pro: capacidade de incluir HTML personalizado na página de início de sessão do servidor.
Server Pro: Atualização para o Nginx 1.10.1.

##### Diversos

Melhor desempenho da ferramenta 'Localizar nos arquivos'.
A tentativa de cortar ou copiar com uma seleção vazia não limpa a área de transferência.
Painel de Arquivos agora tem uma linha de cabeçalho fixa
Tentando verificar o ramo remoto do git agora verifica o controle remoto de cópia local
As parcelas publicadas são maiores e respondem a mudanças no tamanho do navegador
Implementar ligações gt / gT no modo Vim para mudar para a aba seguinte / anterior
Forneça sempre a conclusão de arquivos para o diretório atual de nível superior
Impedir o envolvimento do texto na exibição do painel Arquivos
Indicar quando os detalhes do objeto no painel de ambiente foram truncados
Melhor navegação por teclado nos widgets de arquivos do navegador
Opção adicionada para limitar o comprimento das linhas no histórico do console
Melhor desempenho quando muitas linhas de código enviadas para o console
'Save ()' já não são emitidos ao salvar o estado da sessão
Atualizar biblioteca de teste de unidade C ++ (catch) para v1.3.3 (corrigir gcc> = 5 erros de compilação)
Alterar padrão max.print para 1000 (foi 10000)
##### Correções de bugs

Corrigido um bloqueio no Windows + 64 bits R quando ocorreu um erro ao redimensionar o painel Plots.
Corrigido um problema em que um executável git definido pelo usuário às vezes não era respeitado no OS X
Visualizador de dados: corrigiu uma falha que poderia ocorrer ao chamar 'View ()' na matriz
R Markdown: ocultar a barra de ferramentas do pedaço quando o pedaço é escondido pela seção do Markdown dobrada
R Markdown: fixo

#### Principais modificações, melhorias e correções com a versão RStudio v0.99b de 18/07/2016

##### Destaques

Suporte para várias janelas de origem (separadores do editor de lágrimas fora da janela principal).
Ampliação do painel para trabalhar distração livre em um único modo.
Editor e atalhos de teclado IDE agora podem ser personalizados.
Novo modo de atalho de teclas do Emacs para o editor de origem.
Suporte para registrar addins personalizados do RStudio.
R Markdown melhorias de edição, incluindo visão de destaque e UI inline para execução de pedaços.
Suporte para relatórios de Markdown R parametrizados.
Várias melhorias do RStudio Server Pro, incluindo múltiplas sessões R simultâneas,
Uso de múltiplas versões R e projetos compartilhados para colaboração.
Editor de fontes

##### Alterações e melhorias em: 
 - Novo modo de edição do Emacs.
 - Os atalhos de teclado do Editor e do IDE agora podem ser personalizados.
 - Suporte para várias janelas de origem (separador de lágrimas fora da janela principal).
- Novas opções globais e por projeto para conversão de alimentação de linha.
- Snippets: passar parâmetros para o snippet gerando funções R.
- Comando dividido em linhas para vários cursores (Ctrl + Alt + A).
- Novos atalhos de teclado para expandir / contratar seleção atual.
- Cmd + Alt + Shift + {Acima / Abaixo} OS X.
- Ctrl + Shift + {Up / Down} caso contrário.
- Exibição aprimorada de seções no navegador de escopo R.
- Exibição de destaque de documento adicionada para documentos R e C ++.
- Novo Fechar todos exceto comando atual.
- Renomear variável no escopo (Cmd + Shift + Alt + M).
- Maior destaque contextual das palavras-chave R.
- Opção para ativar o realce das chamadas de função R.
- F2 agora navega em arquivos (por exemplo, dentro de chamadas para fonte).
- Yank antes / depois (Ctrl + K, Ctrl + U) agora usar a área de transferência do sistema em RStudio Desktop.
- Yank após o cursor (Ctrl + K) já não come caracteres de fim de linha.
- Adicionada opção controlando o comportamento 'surround on text insertion'.
- R Markdown

- Novo pedaço de execução e botões de opções sobrepostos no canto superior direito de pedaços
- Novo atalho para executar o atual pedaço (Cmd + Shift + Enter)
- Vista de destaque para navegação rápida entre seções / blocos de código
- Ctrl + PageUp e Ctrl + PageDown navegar entre as seções dentro Rmd, Rpres
- Ativado comentário / uncomment (Cmd + Shift + C) para documentos Markdown
- Comando Knit with Parameters para pré-visualizar com parâmetros variáveis
- Executar tudo agora executa pedaços no console (em vez de chamar, por exemplo, knitr :: purl)
- Reorganize os comandos da barra de ferramentas / menu para melhor descoberta
- Adicionado comando Run Chunk de instalação
- Pandoc incorporado atualizado para v1.15.2
- Atualize pdf.js embutido para v1.3
- Apoiar opções adicionais para o MS Word (índice, manter markdown)


##### Ao RStudio nesta versão foi adicionado:
 - Registrar funções R como addins que podem interagir com o IDE usando o pacote rstudioapi.
- Acessível a partir do menu Addins e pode ser vinculado a atalhos de teclado personalizados
- Comando New Session (criar nova sessão R com o mesmo projeto ou diretório de trabalho)
- Abrir projeto em uma nova janela do menu de projetos recentemente usados
- Novo comando Shiny App para criação rápida de aplicativos brilhantes
- Visualizador de dados: colunas de fator de filtro por texto ou nível
-  Aumentar o limite de carregamentos de shinyapps para 1GB a partir de 100MB
- 'Editar -> Substituir e Localizar' abre a barra de ferramentas Localizar se ainda não estiver aberta (por exemplo, com Cmd + Shift + J)
- Melhorar o desempenho do console para grandes e / ou atualizar rapidamente a saída
- Referência rápida do Roxygen disponível no menu Ajuda
- Links para folhas de batota RStudio disponíveis no menu Ajuda
- Procura de Rtools em HKCU e HKLM (para instalações de Rtools não Admin)
- Executar o comando e o atalho do aplicativo agora funciona para executar um único arquivo Aplicativos brilhantes
- Mover execução Aplicações brilhantes entre painéis IDE e janelas sem reiniciar o aplicativo
- Adicione suporte para arquivos simples e autônomos Aplicativos brilhantes
- Parse TeX comentários mágicos que começam com "%%" (compatibilidade ESS).
- Alterar padrão Rpres modelo para especificar autosize: true
- Criar automaticamente o diretório ~ / .ssh se necessário no Windows
- Adicionado modo Makefile (usado para Makefile, Makevars)
- Sempre use LF para fins de linha em Unix Makefiles em pacotes R
- Retornar variáveis ​​de ambiente como finalizações dentro Sys.getenv (), Sys.setenv () chama
- Adicionar filtro 'R Scripts' à caixa de diálogo Find in Files
- OS X: Suporte para executar comandos via AppleScript via verbo 'cmd'
 OS X: Ativar WebKit WebGL por padrão
 OS X: Ativar WebKit DeveloperExtras por padrão
 OS X: Ative a criação de diretórios na caixa de diálogo do seletor de pastas
- Windows: Atualização para SumatraPDF 3.1.1
- Adicionado a capacidade de zoom painéis (por exemplo, Ctrl + Shift + 1 para zoom painel de origem)
- Add Console on Left / Right comandos para deslocamento rápido de Console
- Adicionar metadados de produto e versão ao instalador do Windows
- Adicionar função askForPassword ao rstudioapi
- Detecção melhorada do local de instalação do Msysgit no Windows
 Servidor

- Incluir projeto ativo no título do documento (legenda da guia do navegador)
- Sair do comando sessão agora acessível a partir da barra de ferramentas global
- Opção adicionada para controlar quantos dias os usuários permanecem conectados para
- Permitir a especificação de vários grupos na opção de grupo de usuários solicitados por auth
- Suspender e continuar a executar sessões R quando o servidor é reiniciado
- Adicionar comandos kill-session e kill-all admin
- Use SHA256 para assinar cookies (SHA1 usado anteriormente)
- Usar mecanismo de bloqueio de arquivos mais resiliente para compatibilidade com volumes NFS
- Tentativa de fechar a janela do aplicativo ao desistir
- Acompanhe a versão do cliente instalada usando git commit hash em vez de tempo

#### Principais modificações, melhorias e correções com a versão RStudio v0.99a	26/05/2015

##### Destaques

Visualizador de dados.

Suporte para visualização de grandes conjuntos de dados (limite de linha de 1k removido)
Os dados podem ser filtrados, pesquisados ​​e classificados
Atualizações do visualizador para refletir as alterações nos dados


Conclusões em mais contextos incluindo S3 e S4 métodos e dplyr pipelines.
Inserção automática de parênteses de fechamento quando apropriado.
Ajuda on-line para assinaturas de funções concluídas.
Conclusão de declarações abrangendo várias linhas.
Autocomplementos especializados fornecidos para biblioteca, dados.
Para aplicações brilhantes, as autocompleições para pares ui.R + server.R
Conclusões de pacotes na biblioteca, exigem chamadas automaticamente inferidas e fornecidas mesmo quando não carregadas.
Conclusões para opções de knitr, e. Em opts_chunk $ get (), agora são fornecidos.
Complementos para símbolos dinâmicos em .C, .Call, .Fortran, .External.
Conclusões para nomes de objeto para argumentos 'fórmula', p. Lm (|, data = mtcars)

##### Diagnóstico de código R.

Os erros de sintaxe são destacados e exibidos em vermelho (por exemplo, vírgulas ausentes, parênteses sem correspondência)
As chamadas de função são verificadas e validadas com, p. Match.call ()
Avisar se a variável é usada, mas nenhuma definição está disponível no escopo
Avisar se a variável é definida mas nunca posteriormente utilizada
Diagnósticos de espaço em branco para ajudar o código a respeitar http://adv-r.had.co.nz/Style.html
##### Editor de fontes

Melhorias na navegação de arquivo / função:
Correspondência difusa em termos de pesquisa
Navegue até as posições do arquivo usando file: line: col
Incluir parâmetros no menu de navegação da função
Vários cursores:
Crie um novo cursor acima / abaixo do cursor atual com CTRL + ALT + {up / down}
Mova o cursor ativo para cima / para baixo com CTRL + SHIFT + ALT + {cima / baixo}
Crie vários cursores pressionando CTRL + ALT e clicando + arrastando o mouse
Modo Vim melhorado:
Várias correções de bugs
Seleção de bloco visual (CTRL + v)
Cursor múltiplo ciente
Macros (q)
Marcas (m)
Busca rápida (/)

##### Suporte um subconjunto de comandos em:

Use: ajuda para obter documentação sobre comandos disponíveis.
Snippets configuráveis para inserção rápida de blocos comuns de código.
As guias do editor no painel de origem agora podem ser reorganizadas.
Salve arquivos automaticamente antes do fornecimento (controlado por opção).
Suporte para vários cursores via Ctrl + Alt + Cima / Baixo.
Alt + Enter para executar o código enquanto mantém a posição do cursor.
Ctrl + Shift + E para selecionar dentro de parens / braces de correspondência.
Ctrl + Alt + Shift + E para expandir a seleção para correspondência paren / brace.
Comentar / descomentar respeita nível de recuo quando apropriado.
Novo comando Reformat Code para scripts R.
Shift + Enter agora procura para trás em Localizar / Substituir.
Localizar todas as opções adicionadas em Localizar / substituir.
Ctrl + E agora foca o editor depois de encontrar a partir da seleção.
Nova opção para controlar a continuação do comentário na inserção de novas linhas.
Reflow texto (comentário) para os modos markdown e plain text.
Atualizado para Ace (componente do editor de origem) v1.1.8.
Sintaxe destacando para GraphViz e mermaid.js diagramas.
Diagrama de pré-visualizações usando o pacote DiagrammeR (requer versão recente do GitHub).
Sintaxe modos de destaque para muitos novos idiomas, incluindo Clojure, CoffeeScript, C #, Graphviz, Go, Groovy, Haskell, Java, Julia, Lisp, Lua, Matlab, Perl, Ruby, Rust, Scala e Stan.
Conclusão de código baseado em palavra-chave e texto para várias linguagens, incluindo JavaScript, HTML, CSS, Python e SQL.
Uma grande variedade de novos temas de editor (esquemas de cores) estão agora disponíveis.
Aumentar o limite de tamanho de arquivo para 5MB (era anteriormente 2MB)
Desenvolvimento C / C ++.

Conclusão do código

Diagnósticos de código.
Navegação por código F2 (vá para a definição).
Ir para o arquivo / função para C / C ++.
Localizar usos para símbolos C ++.
Auto-indentação inteligente.
Árvore de escopo para navegação rápida dentro do arquivo.
Desenvolvimento Web (HTML / CSS / JavaScript).
Diagnóstico em linha (JSHint) sobre sintaxe e outras questões.

Área de trabalho
Manuseio aprimorado de objetos contendo ou consistindo em NULL externalptr

Depuração
Permitir que 'debugSource' seja executado em ambiente especificado pelo usuário
Heurísticas aprimoradas para localizar a estrutura da pilha onde os erros foram originados
As preenchimentos automáticos agora estão disponíveis ao depurar
Aperfeiçoamento de depuração aprimorado através de declarações envolvidas no tryCatch ()
Melhor seleção de quadro de chamada ao usar recover ()
Atalhos de teclado para Step Into (Shift + F4) e Step Out (Shift + F6)

Pacotes
Melhorias no novo pacote:
Gerar pacotes mais limpos sem avisos
Respeitar várias opções de devtools
Suporte para rocíno roxygen2 'vignette'
Insira o comando Roxygen Skeleton (Ctrl + Alt + Shift + R)
Padrão para roxygenize para Build e Reload
Verificação aprimorada do protocolo suportado com pacote packrat
Escape backslashes em nomes de biblioteca ao carregar pacotes
Chamada para biblioteca depois de Build and Reload respeitar -library argumento
Validar que as versões necessárias estão disponíveis para instalações solicitadas
Definir R_BROWSER = false e R_PDFVIEWER = false (como CRAN faz) para R CMD verificar
Lotes

Renderizar parcelas usando devicePixelRatio para retina e HDPI telas
Preservar o último tamanho exportado na caixa de diálogo Salvar gráfico como PDF
Dev.new () agora cria um novo

##### Principais modificações, melhorias e correções com a versão RStudio v0.98b	06/03/2015
#### R Markdown
Próxima geração de R Markdown com base no pandoc.
Crie documentos HTML, PDF e MS Word, bem como apresentações de beamer e ioslides.
Nova sintaxe markdown incluindo suporte expandido para tabelas, listas de definições e bibliografias.
Um modelo HTML responsivo (compatível com vários dispositivos) e temático baseado no Bootstrap.
Incluir LaTeX bruto no markdown para personalização avançada de saída PDF.
Use Shiny com R Markdown para criar documentos interativos.
Compile cadernos HTML, PDF ou MS Word de scripts R.
Veja o pacote do site do rmarkdown para mais detalhes.
Opção para visualizar R Markdown HTML no Painel do Viewer.
Aprimoramentos na pré-visualização HTML para criação de apresentações.
Pré-visualização para saída em MS Word e PDF.
Adicionado Run Previous Chunks (Ctrl + Alt + P).
Atalho de teclado para Knit é agora Ctrl + Shift + K.

##### Ferramentas de Depuração

Suporte para comandos de passo avançado R 3.1 (etapa no loop e terminar).
Permitir visualização e interpolação através de funções que não têm source-refs (via deparse).
Suporte aprimorado para depuração fora de funções, incluindo pisar dentro de loops.


##### Pacotes

Suporte integrado para packrat.
Novo modo devtools para desenvolvimento de pacotes (usa devtools para verificação, documento, teste, etc.).
Atalhos de teclado para Teste (Ctrl + Shift + T) e Documento (Ctrl + Shift + D).
A listagem de pacotes está agora agrupada por biblioteca.
Escolha o local de gravação padrão para arquivos baseados no tipo (por exemplo, R, src, man, etc.).
Não escreva saída HTML ao visualizar o pacote Rmd ou md documentação.
Executar e depurar aplicativos brilhante diretamente no IDE.
Inicie aplicações e recarregue as alterações rapidamente com o comando Executar / Recarregar (Ctrl + Enter).
Fechamento automático de janelas de aplicativos brilhantes na interrupção / saída
Suporte integrado para publicação de aplicativos para shinyapps.io.



##### Editor de fontes

Atalho do teclado (Ctrl + Shift + M) para o operador da pipe magrittr (%>%).
Localizar a partir do atalho de teclado de seleção (Mac: Cmd + E, Windows / Linux: Ctrl + F3).
Execute o comando Current Section (Mac: Cmd + Option + T, Windows / Linux: Ctrl + Alt + T).
Modos de realce de sintaxe para XML, YAML, SQL, Python e scripts de shell.
Comando para executar scripts Python e shell (Ctrl + Shift + Enter).
New Extract Refatoração de código variável (graças a Dirk Schumacher).
Diversas melhorias para realce de sintaxe R e C ++ (graças a Kevin Ushley).
Execute o código R a partir do Source Viewer usando Ctrl + Enter.
Opção para remover automaticamente espaços em branco no final das linhas.
Opção para garantir que os arquivos de origem R sempre terminam com nova linha.
Sempre use guias para indentação em Makefile e Makevars.
Ativar comando salvar imediatamente para novos documentos.

##### Servidor RStudio

Suporte para Internet Explorer 10 e 11.
Reativação melhorada da janela de satélite (por exemplo, controle de versão, visualização, etc.).
Melhoria da localização e renovação do cabeçalho reescrita para o proxy localhost.
A opção r-cran-repos agora funciona de forma consistente e substitui a opção CRAN do usuário.
Corrigir problema de exclusão da janela de conclusão no Ubuntu Chrome.
Compatibilidade com o RHEL / CentOS 7.
Pro: balanceamento de carga para maior capacidade e alta disponibilidade.
Pro: atribuir núcleos e definir prioridade de planejador e limites de recursos por usuário ou grupo.
Pro: Executar uma versão diferente de R por usuário ou grupo.
Pro: opcionalmente encaminhar credenciais para sessões PAM (por exemplo, para emissão de tickets Kerberos).
Pro: Novas opções de configuração para desativar o acesso a vários recursos.
Pro: migrar o suporte a contas do Google para a interface OAuth 2.0.
Pro: Login como link de usuário agora funciona corretamente quando executado por trás de proxies.
Pro: Atualização do nginx embutido para 1.6.2.
Pro: Impedir o uso do protocolo SSLv3.
Pro: Compatibilidade com SLES 11 (SP1, SP2 e SP3).

##### Diversos

Visualizador: comandos de histórico, zoom e exportação para widgets HTML estáticos
Publicar em RPubs de painéis Plots and Viewer.
Referência rápida do atalho do teclado (Mac: Option + Shift + K, Windows / Linux: Alt + Shift + K).
Mac: Sobreponha o nome do projeto no ícone RStudio Dock quando vários projetos estão abertos.
Mac: Adicionado comando New Window ao ícone do RStudio Dock.
Mac: Exibir PDFs de ajuda em Visualizar em vez de em uma janela interna.
Mac: Manipulação correta de downloads de arquivos no painel de ajuda.
Mac: direto / usr / bin / gnutar para / usr / bin / tar se necessário em Mavericks.
Mac: Método de assinatura de código atualizado para OS X 10.10 Yosemite.
Mac: Remove duplicado entradas PATH no OS X 10.10 Yosemite.
Mac: Eliminar animação de caixa de seleção em caixas de diálogo no OS X 10.10 Yosemite.
Windows: Adapte automaticamente tipos de letra para apresentações de alta resolução.
Linux: Improved Ubuntu renderização de fonte (espaçamento para monospace, face de fonte para proporcional).
Linux: Não ligue a R BLAS e LAPACK no RedHat / Fedora (compatibilidade R 3.1).
Menu Git / SVN na barra de ferramentas global com comandos para arquivo ativo e projeto.
Adicionado histórico, zoom e exportação para widgets HTML estáticos no painel Viewer.
Exibir / responsabilizar em comandos de GitHub para projetos de GitHub (arquivo ou seleção dirigido).
Exibir ramo Git atual no título da janela principal.
Adicionada stringsAsFactors e string.na opções para Import Dataset.
Restaurar entrada previamente inserida no console após a execução de comandos.
Aumentar o limite das parcelas activas de 30 para 100.
Adicionada documentação sobre a versão das funções do pacote rstudio.

#### Principais modificações, melhorias e correções com a versão RStudio v0.98a	25/04/2014

##### Ferramentas de Depuração

Definir pontos de interrupção dentro do editor de origem, tanto dentro como fora das funções.
Exibir valores de objeto e pilha de chamadas durante a depuração.
Percorrer o código linha a linha.
Inspetor de erro para acesso rápido a rastreadores e depurador após erros de tempo de execução.
Integração com as ferramentas tradicionais de depuração de R, como browser () e debug ().
Para obter mais informações, consulte Depuração com RStudio.
Painel de ambiente.

Procurar qualquer ambiente no caminho de pesquisa.
Filtragem por nome / valor.
Expandir listas, quadros de dados e objetos S4 inline.
Use str () para exibir valores de objeto.
Visualização de grade opcional classificável por vários atributos.
Muitos outros pequenos aprimoramentos de correção e robustez.

##### R Apresentações

Criação fácil de apresentações HTML5 baseadas em R Markdown.
Suporte extensivo para criação e pré-visualização dentro do IDE.
Muitas opções para personalizar o layout e a aparência.
Facilmente publicado como um arquivo HTML autônomo ou para RPubs.
Para obter mais informações, consulte Criação de apresentações.

##### Editor de fontes

Usar o modelo Rcpp por padrão para novos arquivos C ++.
Adicionar dobradura de código para títulos / seções de remarcação.
Opção para não restaurar documentos-fonte ao reabrir projetos.
Preservar documentos de código aberto quando o diretório de projeto subjacente é movido.
Capacidade de executar código de exemplo roxygen via Cmd / Ctrl + Enter.
Alterar dobrar / desdobrar todos os atalhos de teclado para usar 'O' em vez de '0'.
Inserir automaticamente uma nova linha no final de scripts R ao executar a última linha no arquivo.
Não avança o cursor depois de executar o código se houver uma seleção.
Detectar e fornecer notificação ao editar arquivos readonly (somente Linux e OSX).
Destaque de sintaxe TeX para arquivos .dtx e .ins
Permitir abrir arquivos de aplicativos / postscript no editor.
Desloque-se para o cursor quando reactivar o painel de origem através do atalho do teclado.
Melhore a clareza da mensagem de erro para arquivos de origem movidos ou excluídos.
O recuo automático do código R agora se adapta a recortes alternados nas linhas. subseqüentes.
Executar declarações de várias linhas mesmo quando o delimitador de linha está em branco.

Console
Control + Enter agora pode executar comandos no console.
Permitir que a tecla Esc interrompa o console mesmo se usado quando o foco está no editor de origem.
Desloque-se para o cursor quando reactivar a consola através do atalho do teclado.

Pacotes

Opção de usuário para desativar o painel Pacotes (útil se houver centenas de pacotes instalados)
Variável de ambiente (RSTUDIO_DISABLE_PACKAGES) que pode ser usada para desativar completamente o painel Pacotes.
Crie pacotes usando -with-keep-source por padrão
Definir corretamente LC_COLLATE para roxygenize (agora funciona o mesmo que devtools)
Focalizar automaticamente o console após o comando devtools Load All

#### Principais modificações, melhorias e correções com a versão RStudio v0.97	11/05/2013

Esta versão inclui uma variedade de ferramentas para suportar o desenvolvimento de pacotes R, incluindo:

Uma nova guia Build com vários comandos de desenvolvimento de pacotes e uma visão de saída de compilação e erros.
Comando Build e Reload que reconstrói o pacote e o recarrega em uma nova sessão R.
A recarga incremental é muito rápida e preserva o estado da sessão R anterior, fornecendo rotações rápidas e muito mais fluxo de trabalho interativo para o desenvolvimento de pacotes.
Comandos adicionais para verificar pacotes e criar pacotes de origem e binários.
Capacidade de criar um novo pacote baseado em arquivos de origem R existentes.

Há também uma série de características destinadas a tornar mais fácil para escrever a documentação R:
Pré-visualização e pré-visualização automática opcional para guardar os ficheiros Rd. 
Verificação ortográfica de arquivos Rd.
Realce de sintaxe, preenchimento de código e re-fluxo para comentários do Roxygen.
Capacidade de invocar automaticamente o Roxygen antes das compilações do pacote.

Também há integração com o pacote devtools, incluindo:

Carregar todo o comando e atalho de teclado (Ctrl + Shift + L) que chama devtools :: load_all.
Todas as instalações de pacotes respeitam a biblioteca de desenvolvimento criada por devtools :: dev_mode.
Restauração automática do devtools :: dev_mode ao recarregar e reiniciar as sessões R.

Rcpp
Esta versão inclui muitos novos recursos para suportar a integração contínua de R e C ++ usando Rcpp, incluindo:

Destaque de sintaxe para C / C ++.
Navegação rápida para erros e avisos gcc.

Suporte para Rcpp Atributos:
Comando w / atalho de teclado para Rcpp :: sourceCpp.
Suporte de editor para pedaços de código R incorporados em arquivos de origem C ++.
Chamadas automáticas para Rcpp :: compileAttributes para compilações de pacote.
Nova opção de projeto para criar "Pacote w / Rcpp".
Descarregamento automático de bibliotecas dinâmicas do Windows antes de compilações de pacotes.
Suporte de editor para pedaços de código Rcpp em R Markdown.

Editor de fontes
Localizar e substituir melhorias:
Pesquisa incremental.
Localizar / Substituir na seleção.
Opções para palavra inteira e envoltório.

Melhoramentos de recuo automático:
Suporte completo para auto-indent em pedaços de código Sweave / knitr.
Manipulação mais inteligente de chaves de fechamento.
Reconhecer operadores (por exemplo '+' para ggplot) como continuações de expressão.
Opção para controlar se os argumentos de função estão alinhados verticalmente.
Opção para desativar o recuo automático após colar o código no editor.
Modo de edição do Vim.
#### Principais modificações, melhorias e correções com a versão RStudio v0.96	27/08/2012
Sweave / knitr

Verificação ortográfica dos documentos Sweave e TeX.
Visualizador PDF integrado que suporta a sincronização bidirecional (SyncTeX) entre o editor e a visualização em PDF.
Suporte para tecer arquivos Rnw usando o pacote knitr (requer knitr versão 0.5 ou superior).
Analisar os logs de erros do TeX para extrair erros, avisos e caixas ruins e apresentá-los em uma lista navegável.
Publicação na Web

Editando e visualizando R Markdown e R arquivos HTML (como Sweave, exceto páginas da web).
Criação de fácil de distribuir arquivos HTML autônomos (com imagens incorporadas).
Suporte para inclusão de equações LaTeX e MathML em páginas da Web usando MathJax.
Edição de fontes

Localize em arquivos com expressões regulares.
Código de dobramento (expansão e colapso regiões de código).

#### Principais modificações, melhorias e correções com a versão RStudio v0.95	05/04/2012

Problema de inicialização do Fix R 2.15 quando bibliotecas com dependências ausentes são carregadas em .Rprofile.
 

15 de março de 2012

Diversos

Atalhos desativados depois de mostrar a caixa de diálogo de confirmação SVN.
 

28 de fevereiro de 2012

Lotes

Fix JPEG, TIFF e BMP plot exportando para R 2.14 no OS X.

15 de fevereiro de 2012

Editor de fontes

Ignorar documentos fonte corruptos na inicialização.

31 de janeiro de 2012

Controle de versão

A autenticação Git https agora funciona no Mac OS X.
Corrigir problemas de inicialização quando um layout de painel inclui apenas um painel (oculto) de Git ou SVN.
Diversos.

Corrigido vários problemas com caminhos de projeto contendo caracteres não-Ascii no Windows.
Eliminar exibição espúria de barras de rolagem para o painel Histórico com o tipo de letra Ubuntu Mono.
Inicie corretamente o Chrome no Windows para URLs externas (quando é o navegador de sistema padrão).
 

25 de janeiro de 2012

Projetos

Crie projetos que permitam alternar facilmente entre diretórios de trabalho.

Cada projeto tem seu próprio contexto RStudio:
R sessão.
Documentos de código aberto.
Arranjo de vidraças.
História.
Espaço de trabalho salvo (.RData).
Todo o código R dentro de um projeto é indexado para navegação rápida por nome de arquivo ou função.
Os projetos podem ser vinculados a repositórios de controle de versão (Git ou Subversion).
Associação de arquivos para arquivos .Rproj para abrir projetos a partir do shell.
Abra múltiplas instâncias do RStudio com diferentes projetos simultaneamente.
Navegação de código.

Navegue rapidamente para qualquer arquivo ou função dentro de um projeto usando a pesquisa typeahead.
Ir para Definição da função:
Vá para a definição de função atualmente no cursor (F2 ou Ctrl + Clicar).
Funciona tanto para o código-fonte indexado como para as funções definidas nos pacotes.
Manipulação especial para métodos S3 / S4 com definições múltiplas.
Back e Forward comandos para atravessar rapidamente contextos de navegação (incluindo interruptores de guia).

Controle de versão:
Suporte integrado para projetos vinculados aos repositórios do Git e do Subversion
Painel Git / SVN:
Ver lista de alterações atual.
Etapa ou reverter alterações.
Push / pull / atualização.

Alternar ramos

Revisar a janela de alterações:
Diff pendente alterações.
Etapa incremental / descarte de pedaços (Git).
Todas as funções do painel Git / Svn também estão disponíveis.

Janela de histórico:
Visualizar o histórico de todas as listas de alterações (e seus diffs associados) para um projeto.
Exibir listas de alterações que afetam apenas um arquivo ou diretório específico.
Alterar listas de alterações por assunto (Git).
Outras Novas Funcionalidades.

Suporte para várias instâncias simultâneas do RStudio.
Barra de ferramentas global para acessar comandos comuns de arquivos / navegação.

Melhorias no editor de código fonte:
Ir para a Linha.
Reindent Lines.
Automaticamente reentrada linhas em colar.
Salvar tudo e fechar todos os comandos.
Atualização imediata de documentos alterados em editores externos.

Manipular pacote:
Botão de controle.
Função para capturar coordenadas do mouse (manipulatorMouseClick).

##### Comando Shell:

Desktop: abre o terminal do sistema no diretório atual.
Web: terminal aberto na Web no diretório atual.
Use fontes monofásicas nativas do Ubuntu e fontes proporcionais em sistemas mais recentes do Ubuntu (11.10+).
Suporte para \ 1 .. \ 99 e \ n, \ r, \ t na pesquisa e substituição de regex.

#### Principais modificações, melhorias e correções com a versão RStudio v0.94	03/10/2011

Instalação

Corrigir o problema de empacotamento de 64 bits do Ubuntu que foi introduzido em 0.94.109.

- 3 de outubro de 2011

Editor de fontes.

Corrigir o problema de empacotamento de 64 bits do Ubuntu que foi introduzido em 0.94.109.
 

- 3 de outubro de 2011

Editor de fontes

Corrigir problemas intermitentes com autoindent.

- 22 de setembro de 2011

Temporariamente desativar o suporte para dev.hold / dev.flush (necessidade de buffer flushes para reduzir http viagens de ida e volta).
 
  - 12 de setembro de 2011
Suporte para Graphics Engine v9 (dev.hold, dev.flush e dev.capabilities).
Compatibilidade de pacotes paralelos (problema corrigido com processamento de sinal de processo filho).
Eliminar aviso readLines (para a última linha incompleta) da inicialização e após a fonte do documento ativo.
 
- 22 de agosto de 2011.

##### Diversos

Impor limites de tamanho do arquivo do editor (aviso de 1MB, limite absoluto de 5MB) no modo desktop.
Melhor capacidade de resposta do trackpad para rolagem no OSX Lion.
Use variante de nome de arquivo curto para R.home () no Windows.
Use o modo privilegiado para autenticação PAM no Ubuntu.
Corrigir escape de apóstrofos em arquivos de configurações.
Ativar nenhum botão na caixa de diálogo de atualização do pacote.
#### Principais modificações, melhorias e correções com a versão RStudio v0.93	04/04/2011

Novas características

Melhorias no editor de código-fonte

Adicionamos alguns novos recursos e opções ao editor de origem. Também recebemos muitos comentários sobre os recursos mais avançados que os usuários desejam no editor e definitivamente abordaremos isso em lançamentos futuros. Novo material no editor inclui:

- Realce todas as instâncias do texto selecionado.
- Inserir espaços para guias (soft-tabs).
- Linha de margem de impressão personalizável.
- Destaque da linha selecionada.
- Ativar / desativar os números de linha.
- Soft-wrapping opcional para arquivos de origem R.
- Os documentos sobre opções de edição de código fonte incluem mais detalhes.

Layout e aparência personalizáveis

Console e Source lado a lado. Esta configuração (e outras) são agora possíveis. As novas opções de aparência e layout incluem:

Personalizar locais de painéis e guias.
Alterar tamanho de fonte padrão para visualizações de código.
Selecione entre vários temas do editor, incluindo TextMate, Eclipse e outros.
Para obter mais detalhes, consulte os documentos sobre as opções de aparência e layout.

Trama interativa (manipular)
Esta versão inclui um pacote chamado manipular que pode ser usado para criar gráficos interativos dentro RStudio. Manipular é muito flexível e inclui os seguintes recursos:

Gerar parcelas com entradas vinculadas a controles personalizados (em vez de serem codificadas com um único valor).
Variedade de tipos de controle incluindo slider, picker e checkbox.
Os controles aparecem ao lado do gráfico e podem ser facilmente mostrados e ocultos.
Mais detalhes, bem como capturas de tela com exemplos podem ser encontrados na documentação manipular.


A primeira versão beta do RStudio era compatível com a versão binária do R distribuída a partir do CRAN. A versão atual funciona com qualquer versão do R, incluindo:

- R construído e instalado a partir da fonte usando make install.
- MacPorts ou Homebrew versões de R no MacOS X.
- Os documentos sobre o uso de diferentes versões de R descrevem como o RStudio  determina qual R deve ser executado em cada plataforma.

Codificação de caracteres

Nesta versão, melhoramos significativamente o processamento de caracteres não-ASCII, incluindo:

- Caracteres Unicode podem ser usados para entrada e saída no console.
- O editor de origem suporta caracteres Unicode e pode abrir / salvar arquivos usando qualquer codificação de caracteres.
- Uma codificação padrão de todo o produto pode ser definida e pode ser substituída em uma base por documento.
- Consulte a documentação de codificação de caracteres para obter mais detalhes.

Melhor gerenciamento de diretórios de trabalho.

Adicionamos uma série de novos recursos para facilitar a alternância entre os contextos de trabalho localizados em diretórios diferentes. Esses incluem:

Opção para especificar um diretório de trabalho inicial padrão.
Ferramentas | Altere o comando de menu Dir de trabalho para alterar o diretório de trabalho eo painel Arquivos.
Associações de arquivos opcionais para .RData e .R que inicializam RStudio dentro do diretório do arquivo aberto.
Windows: Inicialização no diretório de trabalho especificado para atalhos.
Mac: Inicialização na pasta arrastada e solta no ícone do RStudio Dock.
Linux: Inicialização no diretório de trabalho do terminal quando executado a partir da linha de comando.
Os documentos sobre diretórios de trabalho e espaços de trabalho vão mais em profundidade nesses recursos.

 

 

Outros acessórios

Console

Reconhecer \ r caractere no console para que txtProgressBar funciona como esperado
Levantar restrições no tamanho da entrada do console que pode ser enviado para R (foi de 4K total, agora é 4K por linha)
Ir para a próxima linha não-vazia na origem depois de executar através de Ctrl-Enter
Edição de fontes

Maior tamanho e legibilidade das fontes padrão no Windows & Linux
Novos atalhos de teclado:
Alt- para inserir operador de atribuição ("<-").
Ctrl + Shift + Home / End para selecionar para iniciar / terminar
Ctrl + Shift + P para Compilar PDF
Adicionar "retornar" à lista de símbolos sintaxe destacada como uma palavra-chave
Compatibilidade

Compatível com R 2.11.1 no Mac (requerido anteriormente R 2.12)
Adicionado CFBundleSignature à versão do Mac
Inicialize corretamente memory.limit para a memória física disponível no Windows de 64 bits
Certifique-se de que o R usa o Internet2 no Windows para interoperabilidade com servidores proxy.
Compatibilidade com as alterações no servidor Web interno R 2.13 (passar cabeçalhos para manipuladores personalizados).
Permitir que a área de trabalho do RStudio seja executada em conta root
Suporte aprimorado para o openSUSE (ainda requer instalação do código-fonte):
Adicionado script install-dependencies-zypper
Adicionado script init.d para gerenciamento de daemon
Embalagem e Instalação

Adicionada a função RStudio.version para mostrar a versão atual do RStudio
Nome alterado do binário RStudio do rdesktop para o rstudio (evite o conflito com o binário rdesktop existente)
Adicionado / usr / bin / rstudio soft-link
Alterar dependência de DEB e RPM no pacote de base R para "recomenda" ao invés de "depende"
Feito mais simples de instalar a partir de fonte:
Eliminado git pull exigência (agora pode construir diretamente do tarball)
Opcionalmente, use as versões instaladas do gerenciador de pacotes do sistema do Qt4 & Boost


## 7 Ferramentas e Linguagem
Conforme indicado na introdução ao RStudio, o RStudio está associado as duas implementações modernas de S que são R e S-PLUS.) O R pode ser considerado como uma implementação diferente de S.  A linguagem S é muitas vezes o veículo de escolha para a pesquisa em metodologia estatística, e R fornece um sistema Open Source para as atividades acima indicadas. Uma das vantagens de R é a facilidade com que podem ser produzidas parcelas de qualidade de publicação bem concebidas, incluindo símbolos matemáticos e fórmulas quando necessário. 


## 8 Principais módulos, componentes e Arquitetura do Sistema.

O RStudio é executado na maioria dos desktops ou em um servidor e acessado pela web:
![](https://i.imgur.com/dcXcDLI.png)


RStudio integra as ferramentas que você usa com R em um único ambiente

### 8.1 RStdio Connect
O RStudio Connect pode ser executado em infra-estrutura física, virtual ou em nuvem. As seguintes distribuições do sistema operacional Linux são suportadas:

RedHat Enterprise Linux (e CentOS) 6.0+
RedHat Enterprise Linux (e CentOS) 7.0+
Ubuntu 12.04
Ubuntu 14.04
Ubuntu 16.04
Atualmente, apenas oferecemos instaladores para a arquitetura x86-64 e exigimos privilégios de root para instalar e executar o Connect.

Se você estiver executando o RStudio Connect em um sistema com montagens NFS, observe que o banco de dados SQLite interno deve estar no armazenamento local. Consulte a Seção 4.5 do guia de administração para obter mais detalhes.

R Requisitos

A Connect recomenda uma instalação da versão R 3.0 ou superior. A seção 2.1 do guia de administração detalha como instalar R para uma variedade de plataformas.

Dimensionamento do Servidor

Os requisitos mínimos recomendados para RStudio Connect são 4 GB de RAM e 2 núcleos.

As especificações de hardware do RStudio Connect dependerão do número e tipo de aplicações, documentos e análises em execução no servidor. As especificações padrão para um servidor de produção podem variar de 8 a 16 cores e 32 a 128 GB de RAM. Algumas cargas de trabalho podem exigir servidores substancialmente maiores. Recomendamos altamente consultar com os programadores R para determinar os recursos necessários para executar as aplicações Shiny e processos de Markdown R automatizados.

##### 8.1 Módulo Principal

Após análise do sistema Rstudio, foi possível concluir que o sistema possui o módulo PAM(Pluggable Authentication Modules). Cuja responsabilidade na execução e funcionamento é para autenticação de usuários e para estabelecer um ambiente e fonte de recursos para sessões R.
Alguns dos usos da PAM:
1. Iniciar variáveis para ambiente
2. Criar automaticamente usuários locais após autenticação através do servidor da pasta.
3. Para montar drives remotos
4. Para inicializar e destruir tickets Kerberos


PAM: São feitas as configurações iniciais, e configurações básicas do sistema. Ele se relaciona com toda a parte que diz respeito ao servidor e às sessões nele geradas.
##### 8.2 Arquitetura

RStudio Desktop
RStudio é principalmente uma aplicação de serviço para o usuário. Por consistir apenas de um servidor por um client, a versão desktop é mais simples. A comunicação entre eles acontece através do socket JSON.
![](http://imgur.com/PDPaqKf.png)
RStudio Server
A versão open-source do RStudio é muito similar à versão desktop. Nesse caso, o web browser funciona como cliente e podem haver múltiplas sessões, uma por usuário. O processo chamado rserver é responsável por rotear o tráfego das sessões para o web browser.
![](http://imgur.com/PbHW0XC.png)
A comunicação entre o browser e o servidor acontece através da rede e a comunicação entre o servidor e a sessão individual acontece através do domínio Unix socket.

O processo rserver é responsável também pela página de login e sessões iniciais. 


## 9. Referências

Todos os sites foram consultados entre os dias 16 a 26/05/2017.

### https://www.rstudio.com/
### https://github.com/rstudio/rstudio

### https://www.rstudio.com/wp-content/uploads/2017/03/RStudio-Connect-Overview-02-17.pdf
### https://support.rstudio.com/hc/en-us/articles/227008088-What-are-the-system-requirements-for-RStudio-Connect-
### https://www.rstudio.com/products/rpackages/

### https://support.rstudio.com/hc/en-us/categories/200035113-Documentation



