Documentação do Projeto: Gerenciador de IPs Corporativo-CPD
1. Introdução
O Gerenciador de IPs Corporativo é uma solução web desenvolvida sob medida para o departamento de TI da O Varejão Auto-Peças. O projeto nasceu da necessidade de substituir planilhas manuais e descentralizadas por um sistema centralizado, seguro e inteligente, capaz de organizar e controlar a alocação de endereços IP em toda a infraestrutura de rede da empresa.

O objetivo principal é eliminar problemas comuns como conflitos de IP, falta de padronização, dificuldade de rastreamento de dispositivos e a perda de tempo em tarefas manuais de gerenciamento.

2. Funcionalidades Principais
A plataforma foi construída com um foco em usabilidade e eficiência, oferecendo as seguintes funcionalidades:

Cadastro Centralizado de Dispositivos: Um formulário completo permite registrar qualquer dispositivo na rede com informações detalhadas, incluindo:

Nome do Dispositivo

Endereço IP

Nome do Usuário

N° de Patrimônio

Tipo (Desktop, Notebook, Impressora, etc.)

Setor/Localização

Status (Ativo/Inativo)

Gestão de Servidores: Uma opção dedicada permite marcar um dispositivo como "Servidor" e especificar sua localização (Matriz ou Galpão), facilitando a identificação de ativos críticos.

Prevenção de Conflitos em Tempo Real: O sistema valida os dados no momento do cadastro para impedir a inserção de um endereço IP ou N° de Patrimônio que já esteja em uso, garantindo a integridade da rede.

Visualização e Filtragem Avançada: Uma interface limpa e organizada exibe todos os dispositivos em uma tabela. Ferramentas de busca e filtros por tipo e status permitem que a equipe de TI encontre informações rapidamente.

Importação e Exportação de Dados (CSV):

Importação: Permite popular o banco de dados em massa a partir de uma planilha CSV, ideal para migrar dados de sistemas antigos.

Exportação: Gera um relatório completo de todos os dispositivos em formato CSV, facilitando auditorias e backups.

Acesso Seguro: A plataforma é protegida por uma tela de login com credenciais fixas, garantindo que apenas pessoal autorizado do CPD tenha acesso às informações da rede.

3. Tecnologias Utilizadas
O projeto foi desenvolvido com uma arquitetura moderna, focada em performance, segurança e escalabilidade, utilizando as seguintes tecnologias:

Frontend (Interface do Usuário):

HTML5 e CSS3: Para a estruturação semântica do conteúdo.

Tailwind CSS: Um framework CSS moderno que permitiu a criação de um design limpo, responsivo e de fácil manutenção sem a necessidade de arquivos de estilo complexos.

JavaScript (Vanilla): Toda a interatividade, manipulação de dados e comunicação com o banco de dados foram construídas com JavaScript puro, garantindo leveza e performance.

Backend e Banco de Dados (Serverless):

Google Firebase: A plataforma foi construída sobre os serviços do Google Firebase, eliminando a necessidade de um servidor backend tradicional.

Firestore: Utilizado como banco de dados NoSQL em tempo real, garantindo que todas as informações exibidas estejam sempre atualizadas.

Firebase Authentication: Gerencia o acesso seguro à aplicação.

Firebase Hosting: Para a hospedagem segura e rápida do site com um clique.

4. Benefícios para a Empresa
A implementação do Gerenciador de IPs traz benefícios diretos para a operação do O Varejão Auto-Peças:

Organização e Confiabilidade: Centraliza todas as informações da rede em um único local.

Redução de Erros: Minimiza drasticamente a ocorrência de conflitos de IP.

Economia de Tempo: Automatiza tarefas que antes eram manuais e demoradas.

Documentação Centralizada: Facilita a auditoria e o rastreamento de todos os ativos de rede.
