1	Resumo do Projeto
O projeto desenvolvido consiste na adaptação do clássico jogo Genius para um ambiente de realidade virtual (VR), com o objetivo de auxiliar na reabilitação e estimulação das habilidades cognitivas e motoras de pessoas com necessidades especiais. Através da imersão em VR, o jogo proporciona uma experiência única, desafiando os jogadores a memorizar e reproduzir sequências de cores e sons, estimulando a memória, a atenção, a coordenação motora e outras habilidades cognitivas.
O jogo funciona ao exibir uma sequência de cores e sons, e o jogador deve interagir com os botões iluminados, utilizando controles VR para tocá-los e apagar as luzes de acordo com a sequência correta. Embora o projeto tenha sido planejado para incluir três níveis de dificuldade (2, 4 e 6 botões), essa implementação não foi concluída a tempo devido a limitações de tempo e complexidade técnica. O jogo, no entanto, funciona com um número fixo de botões e continua desafiador para o jogador.
Para o desenvolvimento do jogo, não foi utilizado o Oculus Quest 3, como originalmente planejado. Em vez disso, foi utilizado um emulador de realidade virtual, chamado XR Interaction Toolkit Simulator, para a Unity. Esse emulador permitiu testar e simular a interação em VR sem a necessidade de um dispositivo físico. O projeto foi desenvolvido utilizando Unity e o emulador XR Interaction Toolkit, com foco na acessibilidade e inclusão, garantindo uma experiência adaptada para todos os usuários.

2	Objetivos
O principal objetivo deste projeto foi criar uma experiência interativa em realidade virtual para ajudar na reabilitação das habilidades motoras e cognitivas de indivíduos com necessidades especiais, utilizando o jogo Genius como base. Os objetivos específicos foram:
1.	Desenvolver uma Experiência Imersiva em VR: Criar um ambiente virtual onde o jogador interage com botões iluminados, utilizando controles VR para tocá-los e apagar as luzes de acordo com a sequência correta.
2.	Criar Cenários com Níveis de Dificuldade Progressivos: Implementar três níveis de dificuldade, variando de 2 a 6 botões, com padrões de iluminação alternados, para oferecer desafios adequados ao desenvolvimento do jogador. Essa implementação não foi concluída a tempo devido às limitações de tempo e complexidade técnica.
3.	Estímulo às Habilidades Cognitivas e Motoras: Utilizar o jogo como uma ferramenta terapêutica para melhorar a coordenação motora e a memória, oferecendo benefícios cognitivos e motores aos jogadores.
4.	Garantir Acessibilidade e Inclusão: Desenvolver um ambiente acessível a todos, incluindo pessoas com deficiências motoras e cognitivas, proporcionando uma experiência intuitiva e adaptada às necessidades de cada usuário.
5.	Avaliar e Melhorar o Impacto do Jogo: Coletar dados sobre o desempenho do jogador para ajustar o design do jogo, garantindo sua eficácia no desenvolvimento das habilidades cognitivas e motoras.

3	Detalhamento das Atividades Desenvolvidas
O desenvolvimento do projeto foi dividido em várias etapas, focando na criação de uma experiência imersiva em realidade virtual, na integração com o emulador XR Interaction Toolkit e na implementação das funcionalidades do jogo Genius.
3.1. Estudo e Preparação da Plataforma
•	Estudo da Unity 3D e suas ferramentas para o desenvolvimento em VR.
•	Em vez do uso do Oculus Quest 3, foi utilizado o XR Interaction Toolkit Simulator, um emulador de realidade virtual que permite testar a interação em VR diretamente na Unity, sem a necessidade de dispositivos de hardware externos. Esse emulador simula o funcionamento dos controles e interações de VR, proporcionando uma experiência semelhante ao uso de dispositivos físicos.
•	O XR Interaction Toolkit Simulator foi configurado para emular os controles e o ambiente VR, facilitando a interação do usuário com os objetos no cenário.
3.2. Criação do Jogo
•	Desenvolvimento do Jogo Genius: Implementação do jogo Genius em Unity, com a criação de cubos que se iluminam e a interação do jogador com os controles VR para clicar em botões no qual geram cubos menores com as cores específicas, para serem colocados em cima do cubo maior que foi iluminado.
•	Desenvolvimento de Níveis de Dificuldade: O jogo foi projetado com a ideia de ter três níveis de dificuldade, mas devido à limitação de tempo, apenas um nível de dificuldade foi implementado com um número fixo de botões.
•	Programação da Sequência de Cores e Sons: Geração de sequências aleatórias de cores e sons que devem ser memorizadas e reproduzidas pelo jogador.
•	Integração do Sistema de Feedback: Implementação de um sistema de validação que verifica se os botões foram tocados na sequência correta e exibe a pontuação do jogador.
3.3. Testes e Ajustes
•	Realização de testes utilizando o XR Interaction Toolkit Simulator para garantir a funcionalidade correta do jogo e ajustar a dificuldade do único nível implementado.
•	Ajustes no design e na interação do jogo para otimizar a experiência do usuário e facilitar o uso, considerando os diferentes perfis de jogadores.
3.4. Avaliação e Melhoria Contínua
•	Coleta de dados sobre o desempenho do jogador, incluindo a pontuação e o progresso.
Ajustes no jogo com base no feedback dos usuários para melhorar sua eficácia como ferramenta terapêutica.

4	Conclusões
O projeto foi bem-sucedido ao criar um ambiente imersivo e interativo de realidade virtual, adaptado do jogo Genius, com o objetivo de estimular e reabilitar as habilidades motoras e cognitivas de pessoas com necessidades especiais. O jogo conseguiu atingir os objetivos de promover benefícios terapêuticos enquanto oferece uma experiência divertida e desafiadora.
A interação com os botões e a necessidade de memória, atenção e coordenação motora proporcionaram estímulos valiosos para o desenvolvimento dos jogadores. Embora a implementação de três níveis de dificuldade não tenha sido concluída a tempo, o jogo continua a proporcionar um desafio significativo para os jogadores com o número fixo de botões. A estratégia de ajustar a dificuldade para cada usuário poderá ser explorada em versões futuras do projeto.
Os testes realizados com o XR Interaction Toolkit Simulator indicaram que a experiência foi bem recebida pelos usuários, com destaque para a eficácia do jogo como ferramenta terapêutica. A utilização do emulador de RV foi fundamental para testar a funcionalidade do jogo sem a necessidade de dispositivos físicos. A implementação de feedback visual e auditivo se mostrou uma estratégia eficaz para melhorar a imersão no ambiente virtual.
Embora o projeto tenha atingido seus objetivos, ainda existem possibilidades de ajustes, principalmente no que diz respeito à adaptação da interface para diferentes perfis de usuários e ao ajuste da dificuldade. Futuros aprimoramentos serão feitos com base em mais testes e análises de desempenho.
Este projeto demonstrou o grande potencial da realidade virtual como ferramenta de reabilitação cognitiva e motora, com amplas possibilidades de aplicação em contextos educacionais e terapêuticos.
Embora o projeto tenha atingido seus objetivos, ainda existem possibilidades de ajustes, principalmente no que diz respeito à adaptação da interface para diferentes perfis de usuários e ao ajuste da dificuldade. Futuros aprimoramentos serão feitos com base em mais testes e análises de desempenho.
Este projeto demonstrou o grande potencial da realidade virtual como ferramenta de reabilitação cognitiva e motora, com amplas possibilidades de aplicação em contextos educacionais e terapêuticos.
