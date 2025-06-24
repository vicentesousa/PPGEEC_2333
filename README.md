# PPGEEC 2333: Comunicações Móveis

## PARTE III: Arquitetura e prototipagem de funcionalidades para sistemas Comunicações Móveis e Apresentações

### Parte I: Instalação de sistemas 5G com o OpenAirInterface (OAI)
   - Instalação de versão do OAI 5G simulada por compilação do código
      - Hands-on 00: Instalação de Máquina Virtual - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H00_VM_VBox.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H00_VM_VBox.ipynb). 
         - Instalar e configurar uma maquina virtual Linux Ubuntu 22.04 LTS (Focal Fossa). **ATENÇÃO:** Ubuntu 22.04 e não o 20.04!!!.
      - Hands-on 01: Instalação de Núcleo do Rede 5G (5GC) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H01_5GCore_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H01_5GCore_UNI_III.ipynb)
      - Hands-on 02: Instalação da estação base 5G (gNB) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H02_5G_gNB_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H02_5G_gNB_UNI_III.ipynb)
      - Hands-on 03: Instalação do User Equipment (UE) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/blob/main/howtos/H03_5G_UE_UNI_III.ipynb) - [Link alternativo via nbviewer](https://nbviewer.jupyter.org/github/vicentesousa/DCO1020/blob/main/howtos/H03_5G_UE_UNI_III.ipynb)
   - **Entregas:**
      - As entregas estão especificadas ao longo do Hands-on e devem ser feitas em sala de aula (data a combinar).
### Construção de HOWTOS (Entregas)
   - **Marilia/William:** Configuração e verificação de canal no OAI – Construção de HOWTO baseado em https://gitlab.eurecom.fr/oai/openairinterface5g/-/blob/develop/openair1/SIMULATION/TOOLS/DOC/channel_simulation.md. O tutorial precisa ter no mínimo:
      - Mudança de pathloss e verificação se seu efeito em alguma métrica de rede
      - Mudança da potência do ruído e verificação se seu efeito na constelação do sinal recebido
      - Instruções para instalar a ferramenta "nr-scope constellation tool" e seu uso para analisar as mudanças de potência do ruído
      - Instruções para controle e monitoramento em tempo real (via Telnet)
   - **Jonathas**: Instalação do OAI em Kubernetes - Construção de HOWTO baseado em https://gitlab.eurecom.fr/oai/cn5g/oai-cn5g-fed/-/blob/master/docs/DEPLOY_SA5G_HC.md. O tutorial precisa ter no mínimo:
      - Instruções de como instalar todo o OAI em Kubernetes
      - Checagem se a rede foi implantada corretamente
      - Fazer isso para os três Use Cases
   - **Entregas:**
      - As entregas estão especificadas ao longo do Hands-on e devem ser feitas em sala de aula (data a combinar). Um arquivo .ipynb deve ser produzido para cada tutorial.
   <!--
   - Instalação do OAI em Docker e com múltiplos UEs - Construção de HOWTO baseado em https://gitlab.eurecom.fr/oai/openairinterface5g/-/blob/develop/ci-scripts/yaml_files/5g_rfsimulator/README.md. O tutorial precisa ter no mínimo:
      - Instruções de como instalar todo o OAI em Kubernetes
    
      - https://gitlab.eurecom.fr/oai/cn5g/oai-cn5g-fed/-/blob/master/docs/DEPLOY_SA5G_HC.md
      -    
   -->
### Parte II: Instalação de sistemas 5G com o open5GS e o srsRAN 5G
   - Hands-on 04: Instalação de Núcleo do Rede 5G (open5GS) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H04_5GC_open5GS_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H04_5GC_open5GS_UNI_III.ipynb)
   - Hands-on 05: Instalação da estação base 5G (gNB) srsrRAN, do RIC da O-RAN SC e do srsUE - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H05_5G_srsRAN_RIC_gNB_UE_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H05_5G_srsRAN_RIC_gNB_UE_UNI_III.ipynb)
   - **Entregas:**
      - A entrega é mostrar o sistema 5G implantado em seu Laptop. Você deve mostrar em para sala de aula (data a combinar).
<!--
## PARTE I: Warmup em tecnologias de Comunicações Móveis Contemporâneas
### Apresentações:
   - OPEN-RAN Introduction ([slides](https://github.com/vicentesousa/PPGEEC_2333/tree/main/slides/); [vídeo](https://github.com/vicentesousa/PPGEEC_2333/tree/main/slides/))
   - 5G prototyping tools: OAI ([slides](https://github.com/vicentesousa/PPGEEC_2333/tree/main/slides/); [vídeo](https://github.com/vicentesousa/PPGEEC_2333/tree/main/slides/))
   - 5G prototyping tools: srsRAN ([slides](https://github.com/vicentesousa/PPGEEC_2333/blob/main/slides/srsRAN%20-%20Matheus%20e%20Ricardo.pdf); [vídeo](https://drive.google.com/file/d/1zdIbXCy7g-2vaRk11EU5FE6MtgmAXX_t/view?usp=drive_link))
   - 3GPP Releases 17, 18 e 19 ([slides](https://github.com/vicentesousa/PPGEEC_2333/blob/main/slides/3GPP%20Releases%2017%2C%2018%20e%2019.pdf); [vídeo](https://drive.google.com/file/d/15ZIs2g_15l4eKC23fp3WQibihL4DWmyA/view?usp=drive_link))
   - 6G: iniciativas e visão sobre aplicações e requisitos ([slides](https://github.com/vicentesousa/PPGEEC_2333/tree/main/slides/); [vídeo](https://github.com/vicentesousa/PPGEEC_2333/blob/main/slides/))

## PARTE II: Arquitetura e prototipagem de funcionalidades para sistemas Comunicações Móveis Ciclo de seminários

### Instalação de sistemas 4G e 5G (Discussão em sala sobre como explorar o código ou melhorar nos HOWTOS)
   - Instalação de versão do OAI 5G simulada por compilação do código
      - Hands-on 00: Instalação de Máquina Virtual - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H00_VM_VBox.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H00_VM_VBox.ipynb)
      - Hands-on 01: Instalação de Núcleo do Rede 5G (5GC) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H01_5GCore_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H01_5GCore_UNI_III.ipynb)
      - Hands-on 02: Instalação da estação base 5G (gNB) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H02_5G_gNB_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H02_5G_gNB_UNI_III.ipynb)
      - Hands-on 03: Instalação do User Equipment (UE) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/blob/main/howtos/H03_5G_UE_UNI_III.ipynb) - [Link alternativo via nbviewer](https://nbviewer.jupyter.org/github/vicentesousa/DCO1020/blob/main/howtos/H03_5G_UE_UNI_III.ipynb)
   - Instalação de versão OAI 5G simulada via imagens Docker [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H01_5GFast_Deployment_UNI_III.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/tree/main/howtos/H01_5GFast_Deployment_UNI_III.ipynb)
   - Instalação de versão OAI 4G simulada (Todos) – [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/blob/main/howtos/H04_4G_EPC.ipynb) - [Link alternativo via nbviewer](https://github.com/vicentesousa/PPGEEC_2333/blob/main/howtos/H04_4G_EPC.ipynb)
   - Instalação de um sistema OAI 5G SA completo (atualizado para a versão mais estável em 05.04.2024) - [Link via Github](https://github.com/vicentesousa/PPGEEC_2333/blob/main/howtos/H01_5G_Complete_Deployment.ipynb)
   - Validação de Instalação de versão mais atualizada do OAI (todos) – HOWTO a ser construído

### Construção de HOWTOS
   - Instalação de versão OAI 4G simulada (Paulo) – Construção de HOWTO
   - Instalação de versão mais atualizada do OAI (Ricardo) – Construção de HOWTO
   - Instalação de 5G com srsRAN simulada (Carlos e Matheus) – Construção de HOWTO
-->
