# Alfabetização Emocional com Agentes GenAI

[![Status do Projeto](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)](https://github.com/seu-usuario/seu-repositorio)
[![Licença](https://img.shields.io/badge/Licença-MIT-green)](https://opensource.org/licenses/MIT)

> Uma plataforma inovadora que utiliza múltiplos agentes GenAI para auxiliar usuários a compreenderem e lidarem melhor com suas emoções através da análise de narrativas pessoais, reflexão guiada e sugestões de estratégias personalizadas.

**🚀 Concorrendo à Bolsa Alura/IFAP! Ajude-nos a transformar essa ideia em realidade com o seu voto!**

## Sobre o Projeto

Este projeto nasceu da ideia de utilizar o poder da inteligência artificial generativa para promover a alfabetização emocional de forma acessível e personalizada. Muitas pessoas enfrentam dificuldades em reconhecer, nomear, compreender e regular suas emoções, o que pode impactar negativamente sua saúde mental e seus relacionamentos.

A solução proposta é um sistema simples construído no Google Colab que emprega uma arquitetura com múltiplos agentes GenAI, cada um com um papel específico no processo de apoio emocional do usuário. Ao compartilhar uma experiência pessoal carregada de emoção, o usuário é guiado por esses agentes em um processo de análise, reflexão e descoberta de estratégias para lidar com emoções futuras.

### Principais Funcionalidades

* **Coleta de Narrativas Pessoais:** Um agente (Agente 1) interage com o usuário para coletar uma descrição detalhada de um momento emocionalmente significativo.
* **Análise Emocional Detalhada:** Um agente especializado (Agente 2) analisa a narrativa para identificar emoções primárias e secundárias, intensidade, gatilhos, padrões de pensamento e estratégias de enfrentamento.
* **Reflexão Guiada e *Insights*:** Um agente (Agente 3) utiliza a análise para gerar perguntas reflexivas personalizadas e conectar a experiência do usuário com conceitos de inteligência emocional.
* **Sugestão de Estratégias Personalizadas:** Um agente (Agente 4) recomenda estratégias de regulação emocional e ações futuras adaptadas à narrativa e às reflexões do usuário.

## Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Google AI](https://img.shields.io/badge/Google%20AI-4285F4?style=for-the-badge&logo=google-ai&logoColor=white)
`google-generativeai` (Biblioteca GenAI do Google)

## Como Contribuir

Este projeto é um protótipo inicial desenvolvido para a Bolsa Alura/IFAP. No momento, o foco principal é na sua conclusão e avaliação. No entanto, futuras contribuições podem ser consideradas. Se você tiver ideias ou sugestões, sinta-se à vontade para abrir uma issue neste repositório para discussão.

1.  Abra uma issue para discutir sua ideia ou problema.
2.  Se a contribuição for aprovada, siga o fluxo de trabalho padrão de fork, branch, commit e pull request.

## Como Executar o Projeto (Instruções de Uso)

Este projeto foi desenvolvido principalmente para ser executado no Google Colab.

1.  **Pré-requisitos:**
    * Uma conta Google para acessar o Google Colab.
    * Uma chave de API do Google AI Studio ([https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)).

2.  **Instalação:**
    * Clone este repositório para o seu Google Drive ou localmente:
      ```bash
      git clone git@github.com:evanmeira/alfabetizacao-emocional.git
      ```
    * Abra o arquivo `.ipynb` (notebook do Colab) no Google Colab.
    * Na primeira célula, substitua `"YOUR_API_KEY"` pela sua chave de API do Google AI Studio.
    * Execute todas as células do notebook em ordem.

3.  **Execução:**
    * A interação com o sistema começará na célula que chama a função `agente1_coletar_narrativa()`. Siga as instruções no output do Colab para compartilhar sua experiência emocional.
    * O sistema guiará você através da interação com os diferentes agentes, apresentando a análise, reflexões e sugestões formatadas ao final.

## Status do Projeto

O projeto está atualmente **em desenvolvimento** e foi criado como parte da aplicação para a Bolsa Alura/IFAP. O objetivo principal é demonstrar a viabilidade e o potencial da ideia. Os próximos passos podem incluir:

* Refinar as instruções dos agentes com base em testes.
* Melhorar a interação com o usuário.
* Explorar a possibilidade de uma interface de usuário mais amigável.

## Agradecimentos

Gostara de agradecer à [Alura](https://www.alura.com.br/) pela incrível oportunidade de participar da Imersão IA. O apoio e a iniciativa são fundamentais para impulsionar projetos inovadores como este.

## Contato

Evandro Moreira - [Linkedin](https://www.linkedin.com/in/evandromef/)
