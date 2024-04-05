# Challange-sprint3-Edge - projeto Wokwi
Visão geral do problema:
A proposta conjunta da FIAP em parceria com o HC (Hospital das Clínicas) concentra-se na otimização da experiência dos pacientes e seus acompanhantes no contexto hospitalar, especialmente abordando a escassez de informações para esses acompanhantes e pacientes sobre seus procedimentos médicos, além da melhoria da experiência geral do usuário durante o processo de atendimento. Nosso projeto visa a humanização dessa experiência, ao mesmo tempo em que busca inovações nos processos de atendimento e espera, com foco especial nos públicos jovem e infantil.

Visão geral da solução:
A solução proposta, centrada na tecnologia Edge, consiste na implementação de um sistema de lembretes automatizados, os quais serão enviados aos responsáveis pelos pacientes via WhatsApp, a fim de notificá-los sobre consultas, exames, cirurgias e outras etapas relevantes do tratamento. Além disso, será desenvolvido um circuito simulado no site Wokwi, compatível com o ambiente Node-RED, permitindo assim o envio direto de mensagens a partir do dispositivo. Esse sistema integrado visa melhorar significativamente a comunicação entre o hospital e os pacientes, proporcionando um acompanhamento mais eficaz e personalizado, contribuindo assim para uma experiência mais satisfatória e humanizada no ambiente hospitalar.

Intruções de configuração e execução da aplicação:
Para iniciar o projeto no Wokwi, é necessário acessar o link fornecido no ReadMe. Dentro do ambiente de simulação, será apresentado um projeto simples contendo um botão, uma tela LCD e um Arduino Uno. Ao iniciar a simulação do projeto, o usuário deve pressionar o botão, o que resultará na exibição da mensagem "Mensagem enviada" no visor do LCD. Após 3 segundos, a mensagem desaparecerá, e cada subsequente acionamento do botão resultará na reapresentação da mensagem.

Para executar o Node-Red, é necessário importar o arquivo JSON disponível no repositório e implementar o código dentro do ambiente do Node-Red. Uma vez importado, o usuário deverá pressionar o botão de injeção presente na célula "inject". Ao acionar o botão, uma mensagem contendo "Olá!" será enviada para o número de telefone cadastrado no WhatsApp, por meio de um chat com o bot previamente configurado.

Atualmente, não há uma integração direta entre o Arduino e o Node-Red. Contudo, é importante ressaltar que uma conexão entre ambos foi explorada e encontra-se em processo de desenvolvimento.

https://wokwi.com/projects/394172285318429697
