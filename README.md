
<h1>
  <img src="./logo-ImobXChange-Pro.png" alt="Logo ImobXChange Pro" width="40" height="40" align="bottom" />
  ImobXchange Pro
</h1>

## ℹ️ Sobre o aplicativo

O **ImobXchange Pro** é uma ferramenta de apoio às atividades de suporte do sistema **IMOB**, voltada à transferência de configurações de modelos de fichas de impressão entre ambientes do sistema. Ela evita que a equipe precise reproduzir manualmente cada configuração: basta exportar o modelo de um ambiente para um arquivo e importá-lo no ambiente de destino. Também permite exportar as imagens associadas às páginas do modelo.

Como as operações são feitas no ambiente selecionado, confira cuidadosamente os dados de conexão antes de importar ou exportar.

## ✨ O que é possível fazer

- Configurar e validar a conexão com o ambiente desejado.
- Escolher uma classe de negócio do catálogo fornecido com o aplicativo.
- Consultar os modelos de impressão disponíveis para a classe selecionada.
- Exportar um modelo de ficha de impressão para um arquivo `.mfimp`.
- Importar um arquivo `.mfimp` no ambiente conectado, transferindo o modelo e seus componentes sem substituir intencionalmente os demais modelos.
- Exportar para uma pasta as imagens armazenadas nas páginas do modelo selecionado.

A extensão `.mfimp` significa **modelo de ficha de impressão**. É usada tanto na exportação quanto na importação de modelos.

## 💻 Requisitos

- Computador Windows compatível com o instalador da versão escolhida.
- Acesso ao banco de dados de origem ou destino.
- Credenciais autorizadas para consultar e exportar modelos e, quando necessário, importar configurações.

O instalador distribuído nas **Releases** do GitHub inclui os componentes necessários para executar o aplicativo, sem exigir instalações adicionais de componentes de execução. Ainda são necessários um computador Windows compatível e acesso aos ambientes utilizados.

## 📥 Instalação

1. Acesse a página **Releases** deste repositório no GitHub.
2. Baixe o instalador da versão desejada.
3. Execute o instalador e siga as instruções exibidas.
4. Configure a conexão com o ambiente que será utilizado.

Utilize somente instaladores publicados nas Releases oficiais deste repositório. Consulte as notas da versão para obter informações sobre alterações, requisitos ou limitações específicas.

## ⚙️ Configuração da conexão

Os dados iniciais de conexão servem apenas para preencher os campos da aplicação. O usuário pode informar e validar os dados correspondentes ao ambiente de origem ou destino que precisa acessar; a conexão não fica limitada aos valores sugeridos. Se os dados forem alterados, valide novamente antes de continuar.

> 🔒 **Segurança:** informe a senha somente na janela de validação. Não a inclua em arquivos de configuração, documentação, capturas de tela ou chamados. A senha permanece apenas em memória durante a sessão e é descartada ao fechar a janela ou alterar os dados de conexão.

## 🚀 Uso

### 🔌 Validar e conectar

1. Abra o ImobXchange Pro.
2. Confira os dados de conexão do ambiente desejado.
3. Acione a validação de acesso e informe a senha solicitada.
4. Aguarde a mensagem que confirma o resultado da conexão.

### 📤 Consultar e exportar um modelo

1. Com a conexão validada, selecione a classe de negócio.
2. Aguarde o carregamento dos modelos disponíveis no ambiente.
3. Selecione o modelo desejado.
4. Acione **Exportar modelo** e escolha o caminho e o nome do arquivo.
5. O arquivo será salvo com a extensão `.mfimp`.

### 📥 Importar um modelo

1. Valide a conexão e confira que o ambiente ativo é o destino correto.
2. Acione **Importar modelo** e selecione um arquivo `.mfimp` válido.
3. Aguarde a conclusão e confira a mensagem de status.

A importação adiciona o modelo e seus dados ao ambiente conectado. Antes de importar, confirme que o destino está correto e siga os procedimentos de segurança e backup da organização.

### 🖼️ Exportar imagens

1. Valide a conexão e selecione a classe e o modelo que contém as imagens.
2. Acione **Exportar imagens**.
3. Escolha a pasta de destino.
4. Confira a mensagem de resultado e os arquivos gerados. Páginas sem imagem ou com conteúdo inválido podem não gerar arquivo.

## 📚 Catálogo de classes de negócio

As opções de classe apresentadas pelo aplicativo vêm de um catálogo distribuído junto com o programa. A presença de uma classe na lista não garante que existam modelos correspondentes no ambiente conectado.

## 🛡️ Segurança e cuidados operacionais

- Confirme o ambiente de origem ou destino antes de cada operação.
- Siga os procedimentos de backup e autorização da organização antes de importar em ambientes importantes.
- Utilize credenciais autorizadas e restrinja o acesso aos arquivos exportados.
- Não compartilhe senhas, strings de conexão, arquivos `.mfimp`, imagens exportadas ou logs que contenham informações confidenciais.
- Armazene arquivos exportados em diretórios com acesso restrito, conforme as regras da organização.
- Aguarde o término de uma operação antes de iniciar outra.

## 🧰 Solução de problemas

### 🔌 Não foi possível conectar

Confira os dados de conexão e a senha. Verifique também a disponibilidade do ambiente, a conectividade de rede e se suas credenciais estão autorizadas.

### 📋 A classe não apresenta modelos

Confirme se a classe selecionada possui modelos no ambiente conectado e se suas credenciais permitem consultá-los. As classes disponíveis são apresentadas a partir do catálogo que acompanha o aplicativo.

### 📥 A importação falha

Confirme que o arquivo `.mfimp` é válido, que o ambiente conectado é o destino pretendido e que suas credenciais permitem importar. Verifique a mensagem exibida pelo aplicativo.

### 🖼️ Imagens não são exportadas

Confirme que o modelo possui imagens associadas às páginas e que a pasta escolhida permite gravação. Consulte a mensagem final da operação para identificar páginas vazias ou com conteúdo não reconhecido.

## 📌 Finalidade e escopo

O aplicativo destina-se a facilitar o suporte ao **IMOB**, especialmente quando é necessário replicar uma configuração de ficha de impressão em outro ambiente. A exportação e a importação do arquivo `.mfimp` tornam essa transferência mais simples do que refazer manualmente a configuração. Também é possível exportar as imagens associadas ao modelo. O aplicativo é uma ferramenta auxiliar para essas atividades; recursos que não aparecem na interface ou nas notas da Release não devem ser considerados suportados.

## 🐞 Reportar um problema

Ao abrir um chamado, informe a versão do aplicativo, a versão do Windows, a operação realizada e o texto da mensagem apresentada. Remova senhas, dados pessoais, endereços internos e outros dados sensíveis de capturas de tela, logs e arquivos de exemplo.
