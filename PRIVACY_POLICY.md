# Política de Privacidade - Amb. Helper

Última atualização: 7 de maio de 2026

Esta Política de Privacidade descreve como a extensão Amb. Helper trata dados ao fornecer ferramentas operacionais de consulta e utilidades de texto no navegador Chrome.

## Finalidade da extensão

A Amb. Helper tem como objetivo facilitar consultas operacionais em sistemas usados pela Ambiental, como Sienge, Sofit, Inlog, Zepp, Invertexto e TextHelper API, além de oferecer utilitários locais como transformação de texto, geração de senhas, documentos de teste e QR Code.

## Dados tratados

A extensão pode tratar os seguintes tipos de dados, conforme a funcionalidade usada pelo usuário:

- Informações de identificação pessoal, como nome, CPF, CNPJ, e-mail, identificadores de credores, fornecedores ou colaboradores retornados pelos sistemas consultados.
- Informações financeiras e de pagamento, como dados de títulos, pedidos de compra, parcelas, apropriações, anexos, informações bancárias e chaves PIX retornadas pelo Sienge.
- Informações de autenticação, como usuários, senhas e tokens informados pelo próprio usuário na aba Credenciais.
- Informações de localização e telemetria operacional, quando o usuário consulta dados de veículos por meio de sistemas como Inlog ou Sofit.
- Conteúdo de sites específicos, quando a extensão é executada em páginas autorizadas do Sienge ou Zepp para apoiar fluxos operacionais.

## Como os dados são usados

Os dados são usados exclusivamente para:

- Executar as consultas solicitadas pelo usuário.
- Exibir os resultados das consultas em janelas da extensão.
- Permitir ações operacionais dentro dos sistemas suportados.
- Salvar localmente as credenciais configuradas pelo usuário.
- Manter estados temporários de carregamento, erro e resultado das consultas.

A extensão não usa os dados para publicidade, rastreamento comportamental, criação de perfil de usuário ou venda de informações.

## Armazenamento de credenciais

As credenciais configuradas pelo usuário são salvas no armazenamento local do Chrome, usando `chrome.storage.local`.

As credenciais:

- Não são empacotadas no código da extensão.
- Não são sincronizadas via Chrome Sync.
- Não são vendidas ou compartilhadas para fins externos ao funcionamento da extensão.
- São usadas somente para autenticar chamadas aos sistemas configurados pelo usuário.

O usuário pode remover as credenciais a qualquer momento pela aba Credenciais da extensão.

## Compartilhamento com terceiros

A extensão pode enviar dados aos serviços externos necessários para executar as consultas solicitadas pelo usuário, incluindo:

- APIs do Sienge.
- APIs do Sofit.
- APIs do Inlog.
- APIs do Zepp.
- API Invertexto.
- TextHelper API.
- API Groq, quando o usuário utiliza funcionalidades de análise por inteligência artificial.

Esses envios acontecem apenas quando necessários para cumprir a funcionalidade acionada pelo usuário.

A extensão não vende dados do usuário e não transfere dados a terceiros para publicidade, análise comportamental, determinação de crédito, empréstimos ou finalidades não relacionadas ao propósito da extensão.

## Permissões do Chrome

A extensão solicita permissões para:

- Armazenar credenciais e estados temporários localmente.
- Escrever na área de transferência quando o usuário solicita copiar um resultado.
- Exibir notificações operacionais.
- Adicionar opções ao menu de contexto para consultas rápidas a partir de texto selecionado.
- Ajustar a posição e tamanho de janelas popup de resultado.
- Acessar hosts externos específicos necessários para consultas operacionais.

As permissões são usadas apenas para as funcionalidades declaradas da extensão.

## Código remoto

A extensão não executa JavaScript ou WebAssembly remoto. Todo o código executável da extensão está incluído no pacote instalado no Chrome.

A extensão realiza chamadas HTTPS para APIs externas, mas essas chamadas não carregam nem executam código remoto dentro da extensão.

## Retenção e exclusão de dados

Os dados de credenciais permanecem armazenados localmente no navegador até que o usuário os remova pela aba Credenciais, limpe os dados da extensão no Chrome ou desinstale a extensão.

Estados temporários de consulta podem ser substituídos automaticamente durante o uso da extensão ou removidos ao limpar os dados locais da extensão.

## Segurança

A extensão foi projetada para reduzir a exposição de credenciais no pacote publicado, exigindo que cada usuário configure suas próprias credenciais localmente.

Ainda assim, credenciais armazenadas no navegador dependem da segurança do dispositivo, do perfil do Chrome e do ambiente do usuário. Recomenda-se proteger o dispositivo com autenticação, manter o navegador atualizado e rotacionar credenciais quando houver suspeita de exposição.

## Compromissos sobre dados do usuário

Declaramos que:

- Não vendemos nem transferimos dados do usuário a terceiros fora dos casos necessários para executar as funcionalidades solicitadas.
- Não usamos nem transferimos dados do usuário para fins não relacionados ao objetivo único da extensão.
- Não usamos nem transferimos dados do usuário para determinar credibilidade, crédito ou elegibilidade para empréstimos.

## Contato

Em caso de dúvidas sobre esta Política de Privacidade ou sobre o tratamento de dados pela extensão, entre em contato com o responsável pela publicação da extensão no Chrome Web Store.
