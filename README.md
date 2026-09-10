🚛 RedFleet - Gestão de Frota Técnica

O RedFleet é um sistema web moderno e responsivo para controle e gestão unificada de veículos da equipe técnica. Projetado com interface Dark & Red elegante, o sistema permite cadastrar veículos, anexar fotos, acompanhar a quilometragem, monitorar o estado de conservação, exportar relatórios em PDF e importar dados via CSV.

🚀 Funcionalidades Principais

Dashboard & Métricas em Tempo Real:

Total de veículos na frota.

Indicadores por estado de conservação (Excelente/Bom, Regular, Crítico/Oficina).

Cálculo automático de porcentagens e status operacionais.

Visualização Flexível (Planilha & Galeria):

Modo Planilha: Tabela interativa no estilo planilha para rápida conferência de dados, ordenação e filtros.

Modo Galeria: Exibição em cards com destaque visual para fotos e informações principais.

Cadastro e Edição de Veículos:

Upload e pré-visualização de fotos (armazenadas localmente via Base64).

Registro de marca, modelo, placa, ano, combustível e cor.

Controle de quilometragem (KM) e técnico/equipe responsável.

Estado de conservação (Excelente, Bom, Regular, Ruim/Crítico).

Status operacional (Ativo, Em Manutenção, Aguardando Vistoria, Inativo).

Campo de observações de campo e avarias.

Exportação de Relatórios em PDF:

Geração de relatórios completos formatados em PDF em modo paisagem (A4) através das bibliotecas jsPDF e AutoTable.

Importação de Dados via CSV:

Carregamento em lote de múltiplos veículos a partir de um arquivo de texto no formato CSV.

Persistência de Dados Local:

Todos os dados cadastrados e alterações são gravados no localStorage do navegador, garantindo retenção de dados sem necessidade de servidor backend.

🛠️ Tecnologias Utilizadas

HTML5 & JavaScript (ES6+): Lógica dinâmica em Vanilla JS para manipulacão do DOM e gerenciamento de estado.

Tailwind CSS (CDN): Framework de estilização utilitária com suporte a modo escuro e cores personalizadas.

FontAwesome 6 (CDN): Ícones vetoriais modernos.

jsPDF & AutoTable: Biblioteca JavaScript para geração e exportação de documentos PDF diretamente no cliente.

Google Fonts (Inter): Tipografia moderna e legível.

💻 Como Executar o Projeto

Faça o download ou clone o arquivo index.html.

Abra o arquivo index.html em qualquer navegador web moderno (Google Chrome, Edge, Firefox, Safari ou Brave).

Nenhuma instalação ou servidor Node.js/backend é necessário.

📄 Estrutura do Arquivo CSV para Importação

Para importar veículos via arquivo CSV, certifique-se de que as colunas estejam separadas por ponto e vírgula (;) conforme o padrão abaixo:

ID;Modelo;Marca;Placa;Ano;Estado;Status;Quilometragem;Tecnico;Combustivel;Cor;Observacoes
1;Strada Freedom;Fiat;ABC-1D23;2023;Bom;Ativo;45000;Carlos Silva;Flex;Branco;Sem avarias
2;Saveiro Robust;Volkswagen;XYZ-9876;2022;Regular;Ativo;62000;Equipe Fibra;Flex;Prata;Pequeno risco na porta


Nota: A primeira linha do arquivo CSV é tratada como cabeçalho e será ignorada na importação.

🎨 Tema e Design

Background Principal: #09090b (Dark Base)

Superfícies e Cards: #121215 e #18181b (Dark Surface/Card)

Acentos e Destaques: Tons de vermelho marca (#ef4444, #dc2626, #b91c1c)

Status Badges:

🟢 Excelente / Bom: Verde Emerald

🟡 Regular / Atenção: Amarelo Amber

🔴 Ruim / Crítico: Vermelho Brand

📝 Licença

Este projeto é disponibilizado para uso livre e adaptação técnica.
