# PreciousLife - Sistema de Atendimento de Emergência para Vítimas de Acidentes de Trânsito

O PreciousLife é um sistema desenvolvido para facilitar e agilizar o atendimento de emergência a vítimas de acidentes de trânsito, permitindo a troca de informações entre socorristas e hospitais.

O Precious Life é um projeto desenvolvido como parte do meu trabalho de conclusão de curso (TCC) na faculdade. É um projeto pessoal, criado com o propósito de aplicar os conhecimentos adquiridos durante meus estudos e também como uma forma de contribuir para a comunidade e para a área de saúde.

## Tópicos

1. [Tema e sua Delimitação](#tema-e-sua-delimitação)
2. [Justificativa](#justificativa)
3. [Objetivo](#objetivo)
4. [Metodologia](#metodologia)
5. [Tecnologias Utilizadas](#tecnologias-utilizadas)
6. [Demonstração](#Prints)
7. [Instalação e Uso](#instalação-e-uso)
8. [Contribuição](#contribuição)
9. [Licença](#licença)

## Tema e sua Delimitação

De acordo com o Portal do Trânsito e Mobilidade, durante 2019, 31.307 pessoas morreram vítimas de acidentes de trânsito. Em 2020, de janeiro a outubro foram registradas cerca de 27.839 indenizações pagas por acidentes de trânsito com vítimas fatais. O Brasil está entre os 10 primeiros com maior número de mortes geradas por acidentes nas ruas, estradas e rodovias.

Fatalidades como estas também se aplicam ao tempo gasto entre o transporte da vítima ao hospital que se adequa, por motivos como o atraso ao atendimento pela coleta de informações do paciente ou até mesmo a falta de preparo ao receber a vítima.

A falta de informações relacionadas com a situação da vítima pode levar ao atraso quanto a um atendimento adequado. Com base nessa situação, nasceu o projeto para o desenvolvimento de um software que integre as informações que os socorristas têm sobre o estado da vítima de acidente de trânsito e os possíveis hospitais para os quais ela poderá ser encaminhada. E uma vez decidido o hospital, permitir que o mesmo inicie os procedimentos para receber a vítima.

## Justificativa

Por conta dos números elevados de mortes apresentados ano após ano, e zelando pela vida e bem social, percebeu-se a necessidade de propor uma solução que pudesse melhorar e agilizar o sistema atual de pronto atendimento de emergência. Mesmo com números elevados de ocorrências, não se observa medidas diretas sendo tomadas quanto ao assunto em questão. Atualmente não se tem conhecimento sobre algo no mercado que possa atuar nessa área. Sendo assim, espera-se que o Sistema PreciousLife possa contribuir em situações de atendimento às vítimas de acidentes de trânsito, uma vez que informações passadas em tempo hábil são cruciais quando se trata de salvar vidas.

## Objetivo

O trabalho apresentado propõe o desenvolvimento de um aplicativo que tem por objetivo permitir a troca de informações entre socorristas e hospitais em casos de atendimento à vítimas de acidente de trânsito. Espera-se que o sistema ajude a melhorar e agilizar o atendimento nesses casos. Nele serão cadastrados e vinculados todos os hospitais da cidade/região, de forma que durante o atendimento de uma ocorrência de acidente, os paramédicos possam, após a realização dos primeiros socorros, verificar o hospital ou pronto-socorro mais próximo, selecionar o destino, informar o estado da vítima e designar preparativos (bolsa de sangue para transfusão, preparo de mesa de tomografia, preparo de sala de cirurgia, entre outros) que deverão ser providenciados pelo hospital para receber a vítima.

Com o desenvolvimento do PreciousLife, espera-se diminuir a taxa de mortalidade e colaborar para a eficácia do atendimento.

## Metodologia

O levantamento de requisitos feito com base em pesquisas que realizadas na internet propõe as funções a serem adicionadas ao projeto. Por se tratar de um software orientado a objeto, a documentação dos diagramas será feita com base na Linguagem Unificada de Modelagem (Unified Modeling Language – UML).

O projeto foi implementado com React Native para o front-end e Figma para o design das interfaces. No back-end, integramos um banco de dados MySQL através do framework Firebase, priorizando funcionalidade e segurança. Essas tecnologias foram estrategicamente selecionadas para garantir uma experiência de usuário otimizada e confiável.

## Tecnologias Utilizadas

- React Native
- Firebase (Autenticação, Banco de Dados)
- MySQL
- Figma
## Demonstração

Aqui estão algumas capturas de tela que demonstram o funcionamento do Precious Life:

![Captura de Tela 1](https://raw.githubusercontent.com/octaviopaula/PreciousLife/main/0.png)
* Autenticação do Firebase para permitir que os usuários façam login de forma segura e eficiente..*

![Captura de Tela 2](https://raw.githubusercontent.com/octaviopaula/PreciousLife/main/1.png)
* Checklists dinâmicos, projetados para agilizar o atendimento do paciente. *




## Instalação e Uso

1. Clone o repositório para o seu ambiente local.
2. Certifique-se de ter o ambiente de desenvolvimento React Native configurado em sua máquina.
3. Execute `npm install` para instalar as dependências do projeto.
4. Configure as credenciais do Firebase no arquivo de configuração.
5. Execute o aplicativo em um dispositivo ou emulador usando `npx react-native run-android` ou `npx react-native run-ios`.
6. Utilize o aplicativo para selecionar hospitais, informar o estado da vítima e preparar os procedimentos médicos necessários.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para sugerir melhorias, reportar problemas ou enviar solicitações de pull request. Para contribuir, siga estas etapas:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/SuaFeature`)
3. Faça commit das suas alterações (`git commit -am 'Adicione uma nova feature'`)
4. Faça push para a branch (`git push origin feature/SuaFeature`)
5. Crie um novo Pull Request

Por favor, tenha em mente que este projeto é governado pelo código de conduta [Covenant Code of Conduct](CODE_OF_CONDUCT.md). Ao participar deste projeto, você concorda em aderir a este código.

## Licença

Este projeto é licenciado sob a [Licença MIT](LICENSE).

