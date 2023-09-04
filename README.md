URL do admin: '/admin_kbtn0f/'
Usuário: jaqueline
Senha: jaqueline123

Steps seguidos para chegar no código do jeito que está agora:

- Configuração de máquina virtual com Ubuntu
- Configurações necessárias para rodar o magento: (Php, Mysql, Apache, ElasticSearch, Composer, VsCode, MySQL Workbench,...)
- Download e instalação do Magento via Composer
- Criação do novo Tema
- Tema Habilitado em 'Design/Configuration'
- No admin em 'Content/Pages', a página 'Home Page' foi desabilitada para pegar a versão do novo tema criado.
- Bootstrap está sendo usado no novo tema.
- Na pasta do módulo 'app/design/frontend/Jaqueline/TemaJaque' tem alguns arquivos que foram criados para sobrescrever arquivos que ja existiam como o 'Magento_Cms/templates/default/home.phtml' para alterar a home.
- Foi necessário desabilitar o módulo CSP pois pelo tempo não conseguiria configurar, e o elasticsearch por incompatibilidades.
- Módulo Mageplaza foi instalado pelo composer, mas não entendi se podia ou não usar o módulo então acabei fazendo direto no código mesmo.


O que eu faria diferente se tivesse mais tempo:

- Formataria o computador para não precisar da máquina virtual
- Pensaria nas cores, fontes e espaçamentos para ficar mais bonito/padronizado
- Buscaria imagens com algum padrão mais definido para os produtos
- Usaria SASS
- Teria usado o arquivo xml da home para chamar diferentes blocos e assim deixaria separado o código de cada parte pra facilitar a manutenção
- Chamaria os produtos do carousel de outra forma, pois sei que a forma que fiz não é a melhor, mas não conseguiria deixar pronto à tempo se fosse alterar agora.