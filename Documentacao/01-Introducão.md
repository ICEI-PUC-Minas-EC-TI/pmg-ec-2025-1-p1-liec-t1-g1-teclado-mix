# Introdução

Este projeto tem como foco o desenvolvimento de um teclado customizado, denominado Teclado MIX, que utiliza um microcontrolador ESP32 para comunicação via Bluetooth com um aplicativo móvel desenvolvido no App Inventor. O objetivo principal é proporcionar uma interface de controle intuitiva e interativa, onde os usuários possam utilizar botões físicos para enviar comandos ao smartphone, possibilitando aplicações como controle remoto, automação residencial e interfaces alternativas para dispositivos móveis. O projeto se justifica pela crescente demanda por dispositivos personalizados que conectem hardware físico com interfaces digitais, oferecendo uma solução acessível e fácil de usar. O público-alvo são entusiastas de tecnologia, desenvolvedores de aplicações móveis e usuários interessados em soluções práticas para interação homem-máquina..

## Problema

Atualmente, muitas soluções de controle remoto e interfaces para dispositivos móveis dependem de telas sensíveis ao toque ou comandos de voz, o que pode limitar a usabilidade em determinadas situações ou para pessoas com necessidades específicas. Além disso, a comunicação entre dispositivos físicos e smartphones nem sempre é direta ou intuitiva, exigindo soluções complexas ou caras. O projeto do Teclado TIX surge nesse contexto para oferecer uma alternativa simples e eficiente, onde botões físicos possam ser usados para enviar comandos via Bluetooth, facilitando a interação com aplicativos móveis. Essa aplicação pode ser utilizada, por exemplo, em ambientes domésticos para controlar dispositivos, em apresentações para avançar slides, ou em jogos como um controle extra.

## Objetivos

Objetivo Geral:
Desenvolver um sistema integrado composto por um teclado físico baseado em ESP32 e um aplicativo móvel em App Inventor que se comuniquem via Bluetooth, permitindo o envio de comandos através de botões físicos para controlar dispositivos ou aplicações no smartphone.

Objetivos Específicos:

Projetar e implementar o firmware do ESP32 que detecte o acionamento de 9 botões físicos e transmita os respectivos comandos via Bluetooth Serial para o aplicativo móvel.

Desenvolver a interface no App Inventor capaz de se conectar ao ESP32 via Bluetooth, receber os comandos dos botões e responder adequadamente, exibindo mensagens ou executando ações específicas conforme o botão pressionado.
 
## Público-Alvo

O projeto é especialmente direcionado a pessoas com deficiências motoras ou cognitivas que enfrentam dificuldades para utilizar interfaces tradicionais, como telas sensíveis ao toque ou comandos complexos em dispositivos móveis. O Teclado TIX oferece uma solução acessível e intuitiva, com botões físicos que facilitam a interação, minimizando barreiras de usabilidade. Assim, o sistema contribui para a inclusão digital, permitindo que usuários com limitações físicas ou cognitivas controlem aplicativos e dispositivos móveis de forma mais simples e eficiente. Além disso, o projeto pode ser utilizado por cuidadores e profissionais que auxiliam essas pessoas, ampliando as possibilidades de comunicação e controle em ambientes domésticos, educacionais e terapêuticos.
