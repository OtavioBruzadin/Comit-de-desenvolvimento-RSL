<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Projeto Escola INFINITO&gt;*
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

* Otavio Augusto Bruzadin
* Arthur Ryuiti Sato Furukawa
* Guilherme Florio Vieira

# Descrição do Projeto

Foi feita a análise das aulas de 5 anos diferentes, do primeiro ao quinto ano; cada sala possui, em média, 20 a 30 alunos. Os alunos possuem 8 matérias diferentes, sendo que 6 matérias são lecionadas pelo mesmo professor, outras matérias específicas foram dadas por outros professores. O registro de presença deve ser feito 2 vezes ao dia, uma no início das aulas e outra após o intervalo.
Para um aluno ser aprovado no final do ano, ele precisa ter 75% de assiduidade no total de aulas. 

# Análise de Requisitos Funcionais e Não-Funcionais
Requisitos Funcionais:
- Registros de faltas: Permite que os professores registrem as faltas e incluir outras informações como data, aluno, turma, horário.
- Relatório de faltas: Armazena e gera relatórios das faltas por disciplina ou aluno, para facilitar a visualização posteriormente.
- Acesso a partir de qualquer navegador web, inclusive em dispositivos móveis.
- Notificações: Enviar notificações aos pais  por email em caso de faltas excessivas (a partir de 20% de faltas em relação as aulas).
- Reprovar os alunos com mais de 25% de faltas do total de aulas ministradas
  
Requisitos Não Funcionais:

- Acessibilidade: Garante que o sistema seja apadtável e acessível a todos os tipos de usuários, incluindo pessoas com deficiências.
- Visualização das faltas: Permite o acesso dos responsáveis ao relatório de faltas, para assim terem informações relativas as faltas dos alunos.
- Segurança: Garantir a segurança dos dados dos alunos, professores e da escola.
- Compatibilidade: Compatível com diferentes dispositivos e sistemas operacionais.
- Implementação com multiplos acessos simultâneos
- Usuário deve escolher uma senha com caracteres alfanuméricos


# Diagrama de Atividades

![image](https://github.com/OtavioBruzadin/Comit-de-desenvolvimento-RSL/assets/89026599/89328157-5a69-4843-8597-b70e1951b59a)



# Diagrama de Casos de Uso

![image](https://github.com/OtavioBruzadin/Comit-de-desenvolvimento-RSL/assets/89026599/80feb51a-5899-4b40-83ea-0b92dce30ab9)




# Descrição dos Casos de Uso

**Ator Primário**: Professor
- Registrar Faltas: Registra a ausência de um aluno em uma aula, necessário acessar o sistema, selecionar a turma e o aluno ausente para fazer o registro da falta.
- Verificar Dados de Alunos: Verifica os dados do aluno matriculado, como nome, número de matrícula e histórico de faltas.
- Acessar Relatório de Faltas: Professor utiliza o sistema para gerar relatórios que mostras as faltas registradas dos alunos, ajudando na análise.

**Ator Primário**: Pais
- Receber Notificação de Faltas: O sistema envia notificações automáticas aos pais de alunos que estiverem com uma taxa de presença de 80% ou menos.

**Ator Primário**: Sistema
- Gerar Notificação de Faltas: Com base nos registros de faltas feitos pelos professores, o sistema envia notificações aos pais de alunos com faltas excessivas.


# Diagrama de Sequência

# Fazer Chamada
![image](https://github.com/OtavioBruzadin/Comit-de-desenvolvimento-RSL/assets/89026599/54ee499d-bba2-474c-bd6d-91a030d081c6)


# Gerar Relatório
![image](https://github.com/OtavioBruzadin/Comit-de-desenvolvimento-RSL/assets/89026599/c7f13350-4093-4af1-8e08-424849222555)



# Diagrama de Classes

![image](https://github.com/OtavioBruzadin/Comit-de-desenvolvimento-RSL/assets/89026599/c77a49f3-ff24-401a-8125-2877b5bfd531)


# Diagrama de Estados

*&lt;Diagrama para permite modelar o comportamento interno de um determinado objeto, subsistema ou sistema global&gt;*

# Diagrama de Implantação

![image](https://github.com/OtavioBruzadin/Comit-de-desenvolvimento-RSL/assets/89026599/ea3376b5-e93d-4281-a554-e351545b5ca3)


# Referências

*&lt;Lista de referências&gt;*

- Link Lucid: https://lucid.app/

- Diagrams: https://app.diagrams.net
