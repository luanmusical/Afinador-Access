# Afinador-Access

Afinador, referência de instrumentos e metrônomo **totalmente acessíveis** por leitor de tela — feito por quem usa leitor de tela, para quem precisa afinar sem depender de ninguém.

- **Afinador automático**: ouve o instrumento pelo microfone e fala a nota e se você deve *apertar*, *soltar* ou se está *afinado* (com sinal sonoro duplo quando crava no centro).
- **Instrumentos**: notas de referência de violão (6 e 7 cordas, barítono), viola caipira (cebolão, rio abaixo, boiadeira…), cavaquinho, banjo, ukulele, bandolim, baixo, violino, viola, violoncelo e escala cromática.
- **Metrônomo**: BPM, compassos, subdivisões, tap tempo.
- Visual de alto contraste inspirado em equipamentos de estúdio, tema claro e escuro.

## Download

Baixe a versão mais recente na aba **[Releases](../../releases)**.

| Sistema | Arquivo | Observação |
|---|---|---|
| **Mac** (chip Apple e Intel) | `Afinador-Access-Mac-Universal.zip` | macOS 10.15 ou mais novo. VoiceOver. Atualiza sozinho. |
| **Plugin VST3 / AU para Mac** | `Afinador-Access-Plugin-Mac-Universal.zip` | Para DAWs (Reaper, Logic, Live, Cubase…). |
| **iPhone** | `Afinador-Access-iPhone.ipa` | iOS 15 ou mais novo. VoiceOver. Precisa ser assinado para instalar (veja o LEIA-ME). |
| Windows / Android | — | Distribuídos à parte. |

Cada Release traz o hash **SHA-256** de cada arquivo. Só são oficiais os arquivos publicados ali.

## Instalar no Mac

1. Abra o `.zip` e arraste o **Afinador-Access** para a pasta **Aplicativos** (é de lá que ele se atualiza sozinho).
2. Na primeira abertura o Mac avisa que não consegue verificar o desenvolvedor (o programa é independente, fora da loja da Apple):
   - **macOS 15 ou mais novo:** tente abrir uma vez, depois vá em *Ajustes do Sistema > Privacidade e Segurança*, no fim da página, e clique em **Abrir Mesmo Assim**.
   - **macOS 14 ou anterior:** no Finder, Control + clique (com VoiceOver: VO + Shift + M) no programa > **Abrir** > **Abrir**.
   - Ou no Terminal: `xattr -cr /Applications/Afinador-Access.app`
3. Permita o uso do microfone quando o Mac perguntar.

O LEIA-ME dentro do zip explica todas as teclas. Dentro do programa: menu *Ajuda > Como usar o Afinador-Access*.

## Instalar no iPhone

Como o app não está na App Store, o arquivo `.ipa` precisa ser assinado com o **seu** Apple ID (grátis) na hora de instalar. O jeito mais simples, num computador Windows ou Mac:

1. Instale o **[Sideloadly](https://sideloadly.io/)** e o iTunes (no Windows).
2. Ligue o iPhone no computador pelo cabo e confie no computador.
3. Abra o Sideloadly, arraste o `Afinador-Access-iPhone.ipa`, digite seu Apple ID e clique em **Start**.
4. No iPhone: *Ajustes > Geral > VPN e Gerenciamento de Dispositivos*, toque no seu Apple ID e em **Confiar**. No iOS 16 ou mais novo, ligue também *Ajustes > Privacidade e Segurança > Modo de Desenvolvedor*.

Com Apple ID gratuito a assinatura vale **7 dias**; depois é só repetir o passo 3 (o Sideloadly pode renovar sozinho). Alternativa: [AltStore](https://altstore.io/).

## Atualização automática

A versão de Mac confere ao abrir se há uma Release nova aqui. Se houver, pergunta se você quer baixar e instalar — respondendo *Sim*, ela baixa, instala e reabre sozinha.

## Contato

Dicas, críticas e sugestões: **afinador@luanmusical.com**

Luan Richard — L-R Productions

## Licença

Veja [LICENSE](LICENSE).
