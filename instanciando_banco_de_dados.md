Antes de começar, tenha uma assinatura ativa no Azure, gratuita ou paga. Acesse o portal, busque por "SQL" e selecione "Instância Gerenciada de SQL". Clique em "Criar" e escolha essa opção. Preencha as informações básicas: assinatura, grupo de recursos, nome único da instância, região, camada de serviço (como "Uso geral") e crie um login com autenticação SQL.

 1. Confirmar assinatura
 2. Grupo de recursos, escolha um novo ou um já existente.
 3. Nome da instância, qualquer um é válido.
 4. Região onde deseja hospedar.
 5. Login e senha

 
Na configuração da instância, defina o número de vCores, armazenamento e tipo de backup. Se estiver em plano gratuito, mantenha os valores mínimos. Na etapa de rede, selecione ou crie uma rede virtual e sub-rede, mantendo o acesso público desabilitado para mais segurança.

Em rede, o ponto de extremidade público, geralmente você desabilita.

As etapas seguintes envolvem configurações de segurança (que podem ser mantidas como padrão), ajustes como fuso horário e collation, e a criação de tags para organização. Por fim, clique em “Revisar + criar” e confirme. Após alguns minutos, sua instância estará pronta para uso.

