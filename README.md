# Turma: SI1N-A

Componentes: Cristian Rudolf Hofmeister

![picture](ANALISIS-CLINICOS-SALUD-HUMANA-ECOS-DE-ARAGON10.jpg)

TEMA : Empresa- Laboratório de análises clinicas

A empresa presta serviços de análises clínicas feitas através do estudo de material biológico colhido de pacientes, como por exemplo, sangue, urina, saliva, fezes, esperma, fragmentos de tecido e pus. A coleta pode ser feita no próprio laboratório onde são feitas as análises ou em locais como um hospital ou clínica.

Na empresa existem dois setores, um de atendimento responsável por colher os dados do paciente, agendar visitas e entregar os resultados.
E outro setor responsável por coletar diretamente o material do paciente e realizar a análise do mesmo.
Alguns dos materiais para análises podem ser entregues diretamente pelo paciente ao setor de atendimento que repassará o mesmo para os profissionais responsáveis pela análise.

A adminsitração do laboratorio e feita pelo setor de atendimento.

- Cada paciente pode ser relacionado com varias amostras enquanto as amostras podem se relacionar apenas uma vez com o paciente.
- O analista tem que se relacionar com apenas uma amostra e a amostra prescisa necessariamente se relacionar com apenas um analista.
- O paciente pode ter mais de um agendamento por dia mas um agendamento não pode ter mais de um paciente.
- O analista tem que se relacionar com apenas um laboratório enquanto as amostras podem ser de outras origens.
- O atendente atende vários pacientes por dia e o paciente pode ser atendido por varios atendentes por dia.

# O banco de dados deve ser capaz de responder às seguintes perguntas:


- Quais são as amostras coletadas por paciente ?
- O atendente realizou quantos atendimentos ?
- Quantas análises foram realizadas em determinado perido de tempo ?
- Qual é o tipo mais frequente de análises ?
- A amostra foi retirada diretamente do paciente ou entregue para análise pelo setor de atendimento ?


# Formas Normais 
FN1: Atributos de uma entidade são únicamente absolutos não havendo a possibilidade de gerar atributos adicionais ou características a determinado atributo.

FN2: Atributos são necessariamente características dependentes da entidade em que estão inseridads.

FN3: Atributos de UID não podem depender de outros atributos dentro de uma mesma entidade.

