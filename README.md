<p align="center">
<img src="https://github.com/user-attachments/assets/0a722dae-d9e3-41a5-aa0f-ad112e37a4fc"/>
</p>

<h1 align="center"> Comparação do RMSE para diferentes métodos de "fits" na computação: uma aplicação Cosmológica  </h1>
Projeto final individual realizado como encerramento da disciplina de Introdução à Computação em Física, 2º semestre do curso de Bacharelado em Física pela Universidade Federal de Minas Gerais.

# Índice
* [Descrição do Projeto](#descrição-do-projeto)
* [Ementa do curso](#ementa-do-curso)
* [Tópicos abordados](#tópicos-abordados)
* [Status do Projeto](#status-do-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Conclusão](#conclusão)

# Descrição do projeto 
O projeto em questão foi dado como avaliação final dos conhecimentos adquiridos na disciplina de Introdução à Computação na Física, obrigatória do 2º semestre do curso de Bacharelado em Física da UFMG. Foi exigido que os alunos fossem capazes de utilizar Python e suas bibliotecas para ajustar e utilizar informações relacionadas a dados em uma questão física da escolha de cada um. Resolvi implementar métodos e ajuste aprendidos ao longo do curso para ajustar dados reais de Freedman et. al (2001) de velocidade de recessão por distância de Supernovas tipo Ia, a fim de calcular a constante de Hubble $H_0$ e fazer uma análise quantitativa sobre a capacidade desses diferentes ajustes de prever dados nunca antes vistos com o cálculo da Raíz do Erro Quadrático Médio (RMSE). 

# Ementa do curso
- Interpolação e ajustes de curvas;
- Suavização de curvas;
- Integração numérica;
- Diferenciação numérica;
- Números aleatórios;
- Integração de Monte Carlo;
- Raízes de equações;
- Ordenamento;
- Sistemas lineares;
- Busca local de mínimos.

# Tópicos abordados
- Interpolação e ajustes de curvas;
- Suavização de curvas;
- Plot de curvas;
- Números aleatórios;
- Bibliotecas científicas (Pandas, Matplotlib, Scikit, Scipy etc.);
- Cálculo de tempo de execução de uma célula.

# Status do projeto
O projeto foi concluído em dezembro de 2024.

# Tecnologias utilizadas
Todo o código foi escrito em Python 3.0 em um Jupyter Notebook.

# Conclusão
Dentre os ajustes realizados, o método dos mínimos quadrados foi o mais eficiente no que tange a previsão de novos dados e com relação à minimização de custo computacional. No entanto, percebeu-se que um ajuste linear pelo método dos gradientes também foi extremamente eficaz nessa mesma tarefa. O valor estimado para a constante de Hubble usando os dados reais foi $H_0 = 67.8$ km/s/Mpc, o que foi extremamente próximo ao valor sugerido pela literatura ($H_0 = 68$ km/s/Mpc, vide Freedman et. al (2001)).
