# Manuscrito — Downloads e Beta

**Manuscrito** é um aplicativo desktop para escrita, organização e desenvolvimento de projetos literários e de roteiro.

Este é o repositório público oficial de **downloads, testes beta e notas de versão**. O código-fonte de desenvolvimento não é publicado aqui.

## Beta atual

**Manuscrito 1.0.0 — Beta 1**

Disponível para Windows, macOS e Linux. Os builds de macOS e Linux são experimentais até concluirmos os testes em máquinas reais.

➡️ [Baixar o Beta 1](https://github.com/gabrielinacioluz-ui/manuscrito-releases/releases/tag/v1.0.0-beta.1)

## Qual arquivo devo baixar?

| Seu computador | Arquivo |
| --- | --- |
| Windows 10/11 64 bits | `Manuscrito_1.0.0_Windows_x64-setup.exe` |
| Mac com Apple Silicon (M1, M2, M3, M4 ou posterior) | `Manuscrito_1.0.0_macOS_Apple-Silicon.dmg` |
| Mac com processador Intel | `Manuscrito_1.0.0_macOS_Intel.dmg` |
| Ubuntu/Debian e derivados x64 | `Manuscrito_1.0.0_Linux_amd64.deb` |

O **AppImage para Linux ainda não está disponível**, pois o empacotamento permanece em validação.

## Antes de testar

Esta é uma versão beta. Para o teste, prefira projetos de teste ou mantenha uma cópia de segurança dos arquivos importantes.

Baixe instaladores somente desta página oficial de Releases. Evite executáveis enviados por terceiros ou hospedados fora deste repositório.

## Instalação

### Windows

1. Baixe o arquivo `.exe`.
2. Execute o instalador.
3. Se o Windows exibir um aviso de segurança, confira se o arquivo foi baixado deste repositório antes de continuar.
4. Abra o Manuscrito pelo Menu Iniciar.
5. Ao terminar os testes, confirme também se ele aparece em **Aplicativos instalados** e se a desinstalação funciona.

### macOS — Apple Silicon ou Intel

1. Descubra o processador do Mac em **menu Apple → Sobre Este Mac**.
2. Baixe o `.dmg` correspondente.
3. Abra o arquivo e mova o Manuscrito para **Aplicativos**, se o instalador apresentar essa opção.
4. Tente abrir o Manuscrito.

Os builds beta do macOS ainda não possuem o fluxo definitivo de assinatura/notarização. Por isso, o macOS pode impedir a primeira abertura. **Não desative globalmente as proteções do sistema.** Registre a mensagem exibida e envie-a junto com o resultado do teste. Isso faz parte da validação desta versão.

### Linux — Debian/Ubuntu x64

Baixe `Manuscrito_1.0.0_Linux_amd64.deb` e instale pelo gerenciador de pacotes gráfico da distribuição, quando disponível.

Também é possível instalar pelo terminal:

```bash
sudo apt install ./Manuscrito_1.0.0_Linux_amd64.deb
```

Se o sistema informar dependências ausentes ou incompatibilidade, copie a mensagem completa para o relatório de teste.

## O que testar

Use o [checklist único do Beta](./BETA_CHECKLIST.md). Ele cobre:

- instalação e primeira abertura;
- criação de Romance, Novela, Conto, Roteiro, Poesia, Dramaturgia e HQ;
- formatação local de fonte, tamanho, cor e marca-texto;
- ferramentas estruturadas de Roteiro;
- corretor e dicionário;
- persistência e troca entre projetos;
- temas e interface;
- exportações DOCX, PDF e EPUB;
- encerramento e desinstalação.

## Encontrou um bug?

Anote:

- sistema operacional e versão;
- processador/arquitetura;
- versão do Manuscrito;
- o que estava fazendo;
- resultado esperado;
- resultado obtido;
- passos para reproduzir;
- mensagem de erro completa;
- print ou vídeo, quando possível.

Não envie manuscritos pessoais ou arquivos confidenciais para demonstrar um bug. Use um projeto de teste sempre que possível.

## Estado das plataformas

| Plataforma | Build | Teste em máquina real |
| --- | --- | --- |
| Windows x64 | ✅ Gerado | ✅ Validação interna inicial |
| macOS Apple Silicon | ✅ Gerado | 🧪 Beta |
| macOS Intel | ✅ Gerado | 🧪 Beta |
| Linux x64 (.deb) | ✅ Gerado | 🧪 Beta |
| Linux AppImage | ⏸️ Pendente | — |

## Sobre este repositório

Este repositório contém somente materiais públicos de distribuição e documentação do beta. A licença e o modelo definitivo de distribuição do Manuscrito ainda estão em definição. A publicação dos instaladores neste repositório não torna público o código-fonte de desenvolvimento.
