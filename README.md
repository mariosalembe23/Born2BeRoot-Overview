# BORN2BEROOT | 42 LUANDA

Projecto para criação do nosso sistema operacional Somente pela Linha de Comando através da Máquina Virtual(Debian ou Rocky)

# NOTA
Eu creio que todos os projectos que temos feito na 42 LUANDA serve ou servirá para alguma coisa mais lá pra frente, e conhecer sobre virtualização é um grande macete para desenvolvedores, principalmente para quem trabalhará com Segurança da Informação.

## CONCEITOS OBRIGATÓRIOS

**X.org:** também conhecido como X Window System, é um sistema de janelas de código aberto para sistemas operacionais baseados em Unix, incluindo Linux e sistemas BSD. Ele fornece uma infraestrutura para gerenciar a exibição de gráficos em computadores, permitindo que os aplicativos gráficos sejam executados em um ambiente de janelas.

**Partição ou particionamento:** em computação, refere-se ao ato de dividir um disco rígido ou outra unidade de armazenamento em seções separadas, chamadas de partições. Cada partição age como se fosse um disco rígido separado, com seu próprio sistema de arquivos e estrutura de armazenamento.

**LVM (Logical Volume Manager):** é um conjunto de ferramentas de gerenciamento de armazenamento disponível em sistemas operacionais Unix-like, como Linux. Ele oferece uma camada de abstração entre os dispositivos de armazenamento físico, como discos rígidos e SSDs, e os sistemas de arquivos que são criados sobre eles.

- Explicação mais Simples sobre LVM:

**O LVM (Logical Volume Manager):** é como uma caixa de ferramentas para administrar o espaço de armazenamento do seu computador. Em vez de lidar diretamente com discos rígidos ou partições, você trabalha com "volumes lógicos" que o LVM cria a partir desses discos.

- Diferença entre ***aptitude*** e ***apt:***
Enquanto o "apt" é uma ferramenta mais simples e direta para operações de gerenciamento de pacotes, o "aptitude" oferece recursos mais avançados e uma interface de usuário interativa para usuários que precisam de funcionalidades mais complexas.
<br>
- Diferença entre ***SELinux*** e ***AppArmor:***
 Tanto SELinux quanto AppArmor são sistemas de segurança poderosos que ajudam a proteger sistemas Linux contra ameaças. A escolha entre eles geralmente depende das necessidades específicas do sistema e das preferências do administrador de segurança.

### BÓNUS (DIRETÓRIO /etc/ - Um dos Diretórios mais importantes em Sistemas Unix)
O diretório /etc no Linux é um dos diretórios mais importantes do sistema de arquivos e contém arquivos de configuração para uma variedade de programas e serviços. Aqui está para o que serve e o que você pode encontrar dentro dele:

- Arquivos de configuração do sistema: O /etc é usado para armazenar arquivos de configuração do sistema, que controlam o comportamento de vários componentes do sistema operacional. Isso inclui configurações de inicialização do sistema, configurações de rede, configurações de segurança, configurações de permissões de usuário, entre outras.

- Configurações de serviços e aplicativos: Muitos serviços e aplicativos instalados no sistema Linux têm seus próprios arquivos de configuração armazenados em subdiretórios do /etc. Por exemplo, o Apache tem seus arquivos de configuração no diretório /etc/apache2, o MySQL tem seus arquivos de configuração em /etc/mysql, e assim por diante.

- Scripts de inicialização e desligamento: O /etc também pode conter scripts de inicialização e desligamento, que são executados durante a inicialização ou desligamento do sistema. Por exemplo, o diretório /etc/init.d pode conter scripts de inicialização de serviços.

- Lista de diretórios: Além de arquivos de configuração, o /etc também pode conter links simbólicos ou arquivos de texto listando outros diretórios importantes do sistema, como /etc/passwd (que contém informações sobre contas de usuário) e /etc/group (que contém informações sobre grupos de usuários).

**Feito por ***msalembe - Mário Salembe*** em 42 | LUANDA**
