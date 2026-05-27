# 📂 Resumo: Hierarquia de Diretórios do Linux (FHS)

A **File System Hierarchy (FHS)** é a estrutura padrão de diretórios utilizada pelos sistemas operacionais Linux. 

Compreender a fundo essa estrutura de diretórios é fundamental para a **administração de sistemas, troubleshooting e segurança**, além de facilitar enormemente a navegação e o gerenciamento de ambientes corporativos.

---

## 🗺️ Mapa de Diretórios do Sistema

Abaixo está o mapeamento da raiz do sistema e suas respectivas funções:

| Diretório | Descrição Prática |
| :--- | :--- |
| **`/`** | **Diretório raiz** do sistema. A base de toda a árvore de arquivos, de onde tudo se origina. |
| **`/bin`** | Comandos e executáveis essenciais do sistema (disponíveis para todos os usuários). |
| **`/boot`** | Arquivos estáticos necessários para a inicialização (boot) do sistema, como o Kernel. |
| **`/dev`** | Representação lógica dos dispositivos de hardware (discos, terminais, etc.). |
| **`/etc`** | Arquivos de configuração global do sistema e dos serviços instalados. |
| **`/home`** | Diretórios pessoais dos usuários comuns (equivalente à pasta "Usuários" do Windows). |
| **`/lib`** | Bibliotecas essenciais utilizadas pelos programas do sistema e pelos módulos do Kernel. |
| **`/media`** | Ponto de montagem automático para mídias removíveis (pendrives, CDs, DVDs). |
| **`/mnt`** | Ponto de montagem temporária de dispositivos e sistemas de arquivos pelo administrador. |
| **`/opt`** | Diretório para a instalação de softwares e pacotes opcionais ou de terceiros. |
| **`/root`** | Diretório pessoal e exclusivo do superusuário (administrador `root`). |
| **`/sbin`** | Ferramentas administrativas e executáveis do sistema (geralmente requerem privilégios de `root`). |
| **`/srv`** | Dados específicos servidos pelo sistema (utilizado por serviços como servidores Web ou FTP). |
| **`/tmp`** | Arquivos temporários criados por aplicações ou usuários (limpo no reinício do sistema). |
| **`/usr`** | Aplicações, bibliotecas, documentação e recursos voltados aos usuários (a maior parte dos programas fica aqui). |
| **`/var`** | Dados variáveis do sistema, como arquivos de **logs**, cache, spool de impressão e bancos de dados. |

---

> **💡 Dica Prática:** No seu terminal CentOS, digite `cd /` e depois `ls -lah` para visualizar todos esses diretórios e suas permissões ao vivo!