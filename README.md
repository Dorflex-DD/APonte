<p align="center">
  <img src="docs/imagens/aponte-icone.png" width="96" alt="Ícone do APonte">
</p>

<h1 align="center">APonte</h1>

<p align="center">
  <b>Um mouse e um teclado para vários computadores Windows da mesma rede.</b><br>
  Com copiar e colar, envio de arquivos e a tela do outro computador.
</p>

<p align="center">
  <a href="https://github.com/Dorflex-DD/APonte/releases/latest"><img src="https://img.shields.io/github/v/release/Dorflex-DD/APonte?label=vers%C3%A3o&color=2B579A" alt="Versão mais recente"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011%20(64%20bits)-2B579A" alt="Windows 10 e 11 (64 bits)">
  <img src="https://img.shields.io/badge/.NET-11-2B579A" alt=".NET 11">
  <img src="https://img.shields.io/badge/idiomas-portugu%C3%AAs%20%7C%20english-2B579A" alt="Português e inglês">
</p>

<p align="center">
  <b>Português</b> · <a href="README.en.md">English</a>
</p>

<p align="center">
  <img src="docs/imagens/pt/destaque.png" width="900" alt="Janela principal do APonte com um computador conectado e um pedido de conexão">
</p>

<h3 align="center">
  <a href="https://github.com/Dorflex-DD/APonte/releases/latest">⬇ Baixar a versão mais recente (GitHub)</a>
  &nbsp;·&nbsp;
  <a href="https://gitlab.com/fabioffg/APonte/-/releases/permalink/latest">⬇ Baixar (GitLab)</a>
</h3>

> ⚠️ **Aviso:** aos finais de semana (sábado e domingo) qualquer acesso fica fechado.
>
> **Uso gratuito, somente com autorização por escrito do autor.** Veja [Licença](#licença).

## Download

Os dois endereços acima sempre abrem a versão mais recente. Em cada versão há quatro pacotes para Windows x64:

| Pacote | Arquivo | Para quem |
|---|---|---|
| **Instalador, com runtime** | `APonte_v…_instalador_com-runtime.msi` | Recomendado. Já inclui o .NET 11. |
| Instalador, sem runtime | `APonte_v…_instalador_sem-runtime.msi` | Menor. Usa o .NET Desktop Runtime 11 x64 já instalado. |
| Portátil, com runtime | `APonte_v…_executavel_com-runtime.zip` | Sem instalar: descompacte e abra. Já inclui o .NET 11. |
| Portátil, sem runtime | `APonte_v…_executavel_sem-runtime.zip` | Sem instalar e menor. Usa o .NET Desktop Runtime 11 x64 já instalado. |

Baixe em [GitHub › versão mais recente](https://github.com/Dorflex-DD/APonte/releases/latest) ou em [GitLab › versão mais recente](https://gitlab.com/fabioffg/APonte/-/releases/permalink/latest). Junto dos pacotes ficam o histórico de versões (`CHANGELOG.txt`), o leia-me e a lista de conferência `SHA256.txt` com a assinatura.

## O que ele faz

- **Mouse e teclado compartilhados.** Leve o ponteiro até a borda da tela e ele passa para o outro computador; o teclado acompanha. `Ctrl+Alt+Pause` devolve o controle ao computador local.
- **Sua mesa.** Arraste as telas dos outros computadores para onde elas estão de verdade na sua mesa. A tela sempre encaixa encostada em um dos quatro lados (esquerda, direita, acima ou abaixo), monitor a monitor, também em computadores com vários monitores. Uma prévia tracejada mostra onde ela vai ficar, a linha azul mostra por onde o mouse passa e a posição fica salva. No computador cliente a Sua mesa mostra também as telas do servidor, na posição que ele arrumou, e acompanha na hora.
- **Passagem por monitor.** Com o botão direito num monitor, escolha se o mouse passa ou não por ele. Se o mouse do cliente não passa para o servidor porque a opção "Clientes podem controlar este PC" está desligada, a própria mesa avisa.
- **Copiar e colar entre os computadores.** Textos, imagens e prints, arquivos e pastas. Cada tipo pode ser ligado ou desligado.
- **Enviar arquivos.** Arraste para a janela do APonte, escolha pelo seletor de arquivos ou use o item do APonte no menu do botão direito do Explorador de Arquivos.
- **Ver a tela do outro computador.** Numa janela, por monitor ou todos juntos, também em tela cheia.
- **Conexão só com aprovação.** Cada computador novo precisa ser aprovado uma vez. Os aprovados ficam na janela Conectar, a um clique, e dá para esquecer um computador ou todos.
- **Serviço do Windows.** Com o instalador, o controle funciona também na tela de entrada do Windows.
- **Atualização pelo próprio app.** O APonte avisa quando há versão nova, baixa e instala. Ele procura por dois caminhos: primeiro no GitLab e, se não houver resposta, no GitHub. Nos dois, o pacote só é instalado depois de conferido por uma lista SHA-256 assinada.
- **Configurações com busca.** Todas as opções numa janela só, separadas por assunto, com um campo para procurar o que você precisa.
- **Backup.** Importar e exportar as configurações.
- **Registro e diagnóstico.** Histórico de conexões, arquivos e erros, com busca e filtros, e pacote de diagnóstico.
- **Tema claro e escuro**, cor de destaque e tamanho da interface, em português e inglês.
- **Perto do relógio.** O APonte pode iniciar com o Windows, continuar no ícone ao lado do relógio e reconectar sozinho.

## Como começar

1. **Instale o APonte** nos computadores, todos na mesma rede.
2. No computador cujo mouse e teclado você vai usar, clique em **Permitir conexão**. Em cada um dos outros, clique em **Conectar**, digite o nome ou o endereço do primeiro e diga de que lado ele fica.
3. **Aprove o pedido** que aparece e, se quiser, arraste as telas na **Sua mesa** para deixá-las como estão na sua mesa de verdade. Pronto: leve o mouse até a borda.

## Imagens

Imagens do próprio APonte, com dados de exemplo.

<p align="center">
  <img src="docs/imagens/pt/principal-conectado.png" width="820" alt="Janela principal conectada, com um computador de dois monitores encostado"><br>
  <sub><b>Sua mesa</b> com um computador de dois monitores encostado à direita: contadores, atalhos para começar, dados deste computador e atividade.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/mesa-arrastando.png" width="820" alt="Arrastando as telas de um computador na Sua mesa"><br>
  <sub><b>Arrastando um computador</b> para o outro lado: a prévia tracejada mostra onde cada monitor vai encaixar e a linha azul, por onde o mouse passa.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/mesa-cliente.png" width="820" alt="Sua mesa no computador cliente, com as telas do servidor"><br>
  <sub><b>No cliente</b>: a Sua mesa mostra também as telas do servidor, como ele as arrumou, com a linha azul por onde o mouse passa.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/passagem-por-monitor.png" width="820" alt="Monitor com a passagem do mouse desligada"><br>
  <sub><b>Passagem por monitor</b>: o monitor 2 do outro computador ficou sem passagem; o mouse entra e sai só pelo monitor 1.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/principal-conectado-escuro.png" width="820" alt="Janela principal no tema escuro"><br>
  <sub><b>Tema escuro</b>: a mesma janela, com as mesmas funções.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/principal-sem-conexao.png" width="820" alt="Janela principal sem conexão"><br>
  <sub><b>Sem conexão</b>: a mesa mostra só este computador; <i>Permitir conexão</i> e <i>Conectar</i> ficam à mão.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/menu-arquivo.png" width="820" alt="Botão Arquivo com o menu aberto"><br>
  <sub><b>Menu Arquivo</b>: configurações, importar e exportar, ajuda e os computadores recentes.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/tela-remota.png" width="820" alt="Janela com a tela do outro computador"><br>
  <sub><b>Ver a tela do outro</b>: por monitor ou todos, com tela cheia.</sub>
</p>

| | |
|:---:|:---:|
| <img src="docs/imagens/pt/conectar.png" alt="Janela Conectar"><br><sub><b>Conectar</b>: nome ou endereço, porta, o lado e a lista dos computadores aprovados.</sub> | <img src="docs/imagens/pt/aprovar.png" alt="Pedido de conexão"><br><sub><b>Pedido de conexão</b>: só entra quem você permitir.</sub> |
| <img src="docs/imagens/pt/enviar.png" alt="Enviando arquivos"><br><sub><b>Enviar arquivos</b> com andamento e velocidade.</sub> | <img src="docs/imagens/pt/sobre.png" alt="Sobre o APonte"><br><sub><b>Sobre</b>: versão, novidades, termos e verificação de atualização.</sub> |
| <img src="docs/imagens/pt/menu-mesa.png" alt="Menu do botão direito na tela da mesa"><br><sub><b>Botão direito</b> numa tela da mesa: ver a tela, enviar arquivos e posição.</sub> | <img src="docs/imagens/pt/registro.png" alt="Registro"><br><sub><b>Registro</b> com busca e filtros.</sub> |

<p align="center">
  <img src="docs/imagens/pt/config-windows.png" width="760" alt="Configurações, página Windows"><br>
  <sub><b>Configurações</b>: os assuntos à esquerda e todas as opções numa rolagem só.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/config-busca.png" width="760" alt="Busca nas Configurações"><br>
  <sub><b>Procurar nas configurações</b>: digite e fica só o que combina.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/config-aparencia.png" width="760" alt="Configurações, página Aparência"><br>
  <sub><b>Configurações › Aparência</b>: tema, cor de destaque, tamanho e idioma.</sub>
</p>

<p align="center">
  <img src="docs/imagens/pt/config-rede.png" width="760" alt="Configurações, página Rede e computadores aprovados"><br>
  <sub><b>Configurações › Rede</b> e <b>Computadores aprovados</b>: esquecer um computador ou todos.</sub>
</p>

## Requisitos

- Windows 10 ou 11 (64 bits).
- Computadores na mesma rede.
- [.NET Desktop Runtime 11 x64](https://dotnet.microsoft.com/download/dotnet/11.0), **somente** para os pacotes `sem-runtime`. Os pacotes `com-runtime` já incluem o .NET 11.

O instalador abre em português. Para inglês, execute `msiexec /i "arquivo.msi" TRANSFORMS=:1033`.

## Atualizações

- O APonte avisa quando há versão nova e faz a atualização (**Configurações › Atualizações** ou **Sobre › Verificar atualização**). A verificação pode ser desligada nas Configurações.
- A busca da versão nova usa dois caminhos: o GitLab e, se ele não responder, o GitHub. A conferência da assinatura é a mesma nos dois.
- Atualizar mantém as configurações e os computadores aprovados.
- Se você usa a 1.6.125, 1.6.126 ou 1.6.127 com apenas o .NET 10, instale antes o [.NET Desktop Runtime 11 x64](https://dotnet.microsoft.com/download/dotnet/11.0) ou baixe o pacote `com-runtime` no mesmo formato que já usa.
- **Portátil, à mão:** feche o APonte, apague tudo na pasta dele, menos a pasta `dados`, e descompacte o pacote novo. Nunca descompacte por cima.
- O histórico completo de versões acompanha cada versão (`CHANGELOG.txt`; em inglês, `CHANGELOG.en.txt`).

## Segurança e privacidade

- **Rede local.** Os computadores conversam diretamente entre si, pela sua rede. Não há conta nem cadastro.
- **Aprovação.** Um computador novo só entra depois que você permite. Nome e endereço não bastam: cada computador tem uma identidade própria, que é conferida a cada conexão, e a conexão entre eles é cifrada.
- **Atualizações conferidas.** Antes de instalar uma versão nova, o APonte confere os pacotes por uma lista SHA-256 assinada pelo autor.
- **Seus dados ficam com você.** O APonte grava seus dados apenas na própria pasta e não envia informações ao autor. A verificação de versão nova consulta apenas os endereços públicos de publicação (GitLab e GitHub).

## Licença

**Uso gratuito, somente com autorização por escrito do autor.**
Peça a autorização **somente por e-mail** para **fabio.s91@icloud.com**, com o nome do app no assunto: **APonte**.
Empresas precisam de autorização própria. Não pode modificar, copiar para outras pessoas nem vender.
Uso sem autorização sujeita a multa e indenização. Termos de Uso completos em [LICENSE](LICENSE).

As bibliotecas de terceiros continuam regidas por suas próprias licenças, listadas na pasta `Licencas` de cada pacote.

## Autor

Fabio Fernando Giacomelli

© 2024-2026 Fabio Fernando Giacomelli. Todos os direitos reservados.
