# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure ⚙️🖥️

Neste desafio da DIO, o objetivo foi criar uma **Máquina Virtual (VM)** no Azure e explorar, de forma prática, os principais recursos de **configuração e dimensionamento**, fundamentais para garantir desempenho, segurança, economia e controle no ambiente de nuvem.

Abaixo você encontrará um passo a passo completo e direto para executar essa tarefa utilizando o **Portal do Azure**.

## 🧩 Etapas para Criar uma Máquina Virtual

### 1. Acessar o Portal e Iniciar a Criação da VM
- Acesse o [Portal do Azure](https://portal.azure.com).
- No menu lateral esquerdo, clique em **Máquinas Virtuais**.
- Na tela de configuração inicial, preencha os dados básicos como:
  - **Nome da VM**
  - **Região**
  - etc.
- Em **Opções de escala**, selecione a opção de **dimensionamento automático**, que permite que a máquina ajuste sua capacidade automaticamente conforme a demanda.

### 2. Configurar o Disco
- Escolha o **tamanho do disco** dependendo do desempenho desejado.
- Você pode adicionar discos adicionais ou manter o disco padrão do sistema.

### 3. Configurar a Rede Virtual
- Crie uma **Rede Virtual (VNet)**e.
- Configure uma **sub-rede**, **endereço IP público** e defina as **regras de segurança (NSG)** para controlar o tráfego de entrada e saída.
- Essas configurações são essenciais para garantir que sua VM esteja acessível e protegida.

### 4. Configurar Gerenciamento
- Esta seção permite automatizar e controlar vários aspectos da operação da VM. Aqui, você pode:
  - Habilitar **identidade gerenciada** atribuída pelo sistema.
  - Permitir **login com Azure Active Directory**.
  - Ativar o **desligamento automático**, útil para economizar recursos quando a VM não estiver em uso.
  - Ativar **Backup automático** e configurações de **atualização do sistema operacional**.
  - Configurar **patch dinâmico** e opções de orquestração de atualização.

### 5. Configurar Monitoramento
- Ative o **monitoramento de diagnósticos** para registrar dados como logs de inicialização, uso de CPU, memória, entre outros.
- Isso facilita a análise de desempenho e identificação de problemas futuros.

### 6. Configurações Avançadas (opcional)
- Aqui é possível instalar **extensões** (como agentes de monitoramento ou antivírus), entre outras opções.


### 7. Marcas (opcional)
- Embora não sejam obrigatórias, as **marcas** (tags) ajudam a organizar os recursos por categoria, departamento, projeto ou centro de custo.
- Cada marca é um par chave/valor que pode ser usado para filtragens e relatórios.

### 8. Revisar e Criar
- Revise todas as configurações feitas.
- O portal exibirá uma **estimativa de custo** por hora da VM, baseada nas escolhas feitas.
- Se tudo estiver certo, clique em **Criar**.
- O Azure iniciará o processo de provisionamento da máquina virtual — geralmente, em poucos minutos, ela estará pronta para uso.

---

## 🧠 O Que Você Aprende com Esse Processo

Ao realizar esse desafio, você aprende de forma prática:

- Como criar e configurar uma máquina virtual no Azure com controle total sobre recursos e escalabilidade.
- A importância de cada etapa para garantir segurança, desempenho e economia na nuvem.
- Como integrar recursos como backup, monitoramento, atualizações automáticas e redes virtuais.
- A flexibilidade que o Azure oferece ao configurar desde o sistema operacional até o gerenciamento de identidade.


