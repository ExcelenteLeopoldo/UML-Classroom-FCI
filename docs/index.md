<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/ciencia-da-computacao">Ciência da Computação</a></h3>


<font size="+12"><center>
*&lt;Sistema de Presença - Escola Infinito&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do Projeto](#introdução-do-projeto)
- [Análise de Requisitos Funcionais e Não-Fucionais](#descrição-dos-requisitos)
- [Diagrama de Atividades](#diagrama-de-atividades) 
- [Diagrama de Casos de Uso](#diagrama-de-comportamento-atores)
- [Descrição dos Casos de Uso](#descrição-das-funcões)
- [Diagrama de Senquencia](#diagrama-de-ordem-interações)
- [Diagrama de Classes](#diagrama-orientado-objetos)
- [Diagrama de Estados](#diagrama-estrutura-componente)
- [Diagrama de Implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* André Moreira Guimarães
* Leonardo Patriani Cardoso
* Matheus Queiroz Gregorin
* Pedro Henrique Cagnoni Guimarães
* Vitor Arantes Vendramini

# Descrição do Projeto

*&lt;O projeto visa desenvolver um sistema de controle e monitoramento de faltas para uma escola de Ensino Fundamental I, que atende turmas do 1º ao 5º ano. Cada turma é composta por 20 a 30 alunos e conta com um professor principal responsável pela maior parte das disciplinas, como Matemática, Português, Artes, Ciências, História e Geografia, além de professores especializados para matérias como Educação Física e Inglês.&gt;*

*&lt;O sistema terá como principais funcionalidades o registro fácil e intuitivo das faltas pelos professores e a geração de relatórios detalhados sobre as ausências. Dentro destes relatórios terá as informações coletadas diariamente em chamadas em dois períodos dos dias letivos, uma ao ínicio das aulas do dia e outra logo após o retorno do intervalo escolar. Estes relatórios poderão ser organizados por data, ano escolar, turma, professor, disciplina ou aluno, facilitando a análise e o acompanhamento das faltas. Além disso, o sistema enviará notificações por e-mail para os pais ou responsáveis quando a porcentagem de presença de um aluno estiver abaixo de 80%, ajudando a garantir que os alunos mantenham um bom nível de comparecimento às aulas, considerando que se o aluno atingir menos de 75%, será reprovado devido a suas faltas.&gt;*

*&lt;O projeto também se preocupará com a acessibilidade, assegurando que o sistema seja inclusivo para todos os usuário, incluindo pessoas com deficiências, através de recursos como ajuste de tamanho de fonte. Finalmente, o sistema será acessível de qualquer navegador web e em dispositivos móveis, proporcionando flexibilidade e conveniência para todos os envolvidos.&gt;*

# Análise de Requisitos Funcionais e Não-Funcionais

## Requisitos Funcionais 

|Registros de Faltas|
|----------------------------------------------------|
| O sistema deve permitir que os professores registrem faltas dos alunos de forma fácil e intuitiva.|
| Deve possibilitar o registro de faltas tanto no início das aulas quanto após o intervalo.|
| Base de controle de presença, para coletar as faltas dos alunos de forma organizada.|


|Cadastro|
|---------------------------------------------------|
| Professores, alunos, turmas e matérias serão cadastrados no sistema para viabilizar o registro de faltas.|
| O cadastro é essencial para identificar corretamente os atores do sistema e suas respectivas disciplinas.|


|Relatórios de Faltas| 
|---------------------------------------------------|
 O sistema deve gerar relatórios de faltas agrupados por critérios como data, ano do ensino, turma, professor, disciplina ou aluno.|
 Relatórios exportáveis em formatos comuns, como PDF e Excel, para análise e acompanhamento.|
 Organização de todos os dados de faltas.|


|Envio de Notificações|
|---------------------------------------------------|
| O sistema deve enviar notificações por e-mail para os responsáveis quando a presença de um aluno estiver abaixo de 80%.|
| As notificações devem incluir informações detalhadas sobre as faltas do aluno, alertando os usuários sobre a situação.|


## Requisitos Não Funcionais 

|Acessibilidade e Usabilidade|
|----------------------------------------------------|
| O sistema deve ser acessível para todas as pessoas envolvidas, garantindo que todos consigam utilizar de forma fácil e eficiente.|
| Deve ser acessível em todos os navegadores e dispositivos, permitindo o acesso de qualquer lugar.|
| Garantir uma interface intuitiva e de fácil utilização.|


|Segurança e Confiabilidade|
|---------------------------------------------------|
| Garantir medidas de prevenção para possíveis ameaças e vulnerabilidades|
| Garantir a sincronização dos dados presentes na base de dados e disponibilizados para alteração.|


|Desempenho e Responsividade| 
|---------------------------------------------------|
| Garantir um tempo de resposta adequado após a inserção de informações pelo usuário.|
| O sistema deve ser ágil para alterar e buscar informações de alunos na base de dados, facilitando o seu uso.|


|Preservação dos Dados|
|---------------------------------------------------|
| Garantir a preservação dos dados (em nuvem ou disco) para restauração, caso necessário.|


# Diagrama de Atividades


![DiagramadeAtividades](https://github.com/user-attachments/assets/147bcd1e-f0cd-40ea-8f20-964dda9283e3)


# Diagrama de Casos de Uso


![WhatsApp Image 2024-10-01 at 18 10 52 (1)](https://github.com/user-attachments/assets/a82c3f12-ffe7-4789-a232-9e9a4ea0812f)



# Descrição dos Casos de Uso
![Descricao 1](https://github.com/user-attachments/assets/2163509a-967c-4895-84f4-427f21b25b3e)
>*Descrição 1: Relacionamento entre sub-processo e sistema, caso seja detectado faltas acima de 20% desenvolvido no formato narrativa fragmentada.*

![Descricao2](https://github.com/user-attachments/assets/69b98c5e-4e4e-4d9b-9b57-b0c7956245e4)
>*Descrição 2: Relacionamento entre professor e sistema desenvolvido no formato narrativa fragmentada.*

![Descricao3](https://github.com/user-attachments/assets/a372c545-387c-4248-902c-1227f1adf148)
>*Descrição 3: Relacionamento entre Responsável e sistema desenvolvido no formato narrativa fragmentada.*

![Descricao4](https://github.com/user-attachments/assets/d52f2432-4d96-418a-b25b-b65b964b2773)
>*Descrição 4: Relacionamento entre sub-processo e sistema, caso seja detectado faltas acima de 25% desenvolvido no formato narrativa fragmentada.*

# Diagrama de Sequência

![Sequencia](https://github.com/user-attachments/assets/46e5d593-ffb8-4d31-8c14-fda17c08d089)

# Diagrama de Classes

![Classes](https://github.com/user-attachments/assets/f0956672-f24b-46ce-96f4-d17bc27841a8)

# Diagrama de Estados

![Estado](https://github.com/user-attachments/assets/a5f3e897-3bcf-4d3a-a3a5-a22efdb703f4)

# Diagrama de Implantação

![Implantacao](https://github.com/user-attachments/assets/7082bb46-ed16-47a6-8e7a-41754650f159)

# Referências

*&lt;Lista de referências&gt;*
