# Documento de Visão

### 1. Descrição do Projeto

* O programa irá auxiliar Bolsistas e Estagiários em algumas atividades como a sua regularização de presença com o serviço social, já que o recebimento da bolsa depende da comprovação do cumprimento de suas atividades, bem como ajudar os servidores a terem mais controle sobre as atividades de seus aprendizes.  
* O sistema terá acesso a diferentes “cargos”, logo facilitará interações entre os usuários de diferentes tipos. 

#### 1.1 Escopo 

* Em geral pode-se dizer que o objetivo do programa é proporcionar maior interação entre os servidores e Bolsistas/Estagiários para facilitar o trabalho de ambos.

### 2. Descrição do Problema

* Vimos que no IFRN a grande maioria dos bolsistas tem muita dificuldade em bater ponto, manter contato com os servidores responsáveis pela bolsa, ver os locais e horários onde deve comparecer, principalmente para regularizar sua situação com o serviço social. Pensando no problema vimos que se estende para estagiários e servidores já que a interação entre eles tem alguns problemas pela falta de um meio para organização e gerenciamento dos mesmos.
Esse problema pode afetar principalmente os bolsistas já que a maneira atual de gerenciamento está muito sujeita a falhas que podem atrapalhar o recebimento de seus auxílios.
Assim, a solução mais viável seria a criação de um sistema único para que o gerenciamento ficasse mais funcional e seguro.

### 3. Descrição dos Usuários  
 Os usuários seriam todos do IFRN e seriam divididos em Estagiários, Bolsistas e Servidores, também será possível entrar como apenas Aluno, mas não terá acesso a todas as funcionalidades do sistema.  
 
 Nome |	Representa | Papel 
 ---- | ---------- | ------
Bolsista |	Alunos que necessitam “bater ponto” e de uma interação com o serviço social. |	Declarar presença em sua bolsa e declarar motivo de falta se necessário, se comunicar com os servidores, ver informações da bolsa.  
Estagiário |	Alunos que iram “bater ponto” assim como os bolsistas, porém eles não estão vinculados ao serviço social. |	Declarar presença em seu estágio, se comunicar com os Servidores, ver informações de suas atividades.  
Servidor |	Servidores que são responsáveis por estágios ou bolsas nos setores do IFRN. |	Gerenciar seus respectivos bolsistas ou estagiários podendo relatar faltas, emitir comunicados referentes aos trabalhos, confirmar presença. 

### 4. Ambiente de Uso

* Os bolsistas/estagiários terão acesso as informações de sua bolsa como horários, servidor responsável, local onde deve comparecer, notas deixadas pelos servidores, além de ter a área para marcar a presença na bolsa/estagio além de registrar suas atividades diárias. 
 Os servidores irão poder gerenciar as informações dos estágios, verificar a presença dos alunos participantes, deixar notas, mudar locais e horários. A parte de cadastro de bolsistas e de estagiários no sistema será feita pelos próprios servidores responsáveis por cada setor, a partir das matrículas dos estudantes, bem como o cadastro das bolsas e dos estágios existentes na instituição serão inseridos por meio dos mesmos responsáveis. 

### 5. Visão geral do Sistema 
#### 5.1 Perspectiva do Sistema

* Inicialmente o projeto foi visado para ser integrado ao IFRN já que o problema foi identificado nessa instituição, sendo assim estaria diretamente ligado ao SUAP pela questão das matriculas dos estudantes, estagiários e servidores da escola já que a troca de dados constante é vital para o sistema. 
			Porém como essa ligação não é possível ainda o sistema será desenvolvido com bolsas, estágios e servidores. Os servidores serão pré-definidos afim de apenas mostrar as funcionalidades do programa, deixando essa integração com uma instituição em segundo plano. 

#### 5.2 Funcionalidades do Sistema

* O sistema depois de pronto poderá ser adaptado para uma instituição em especifico já que suas funcionalidades estarão prontas, somente o cadastro seria feito de forma diferente.  

O sistema contaria com: 

- Portal de ponto para bolsistas e estagiários
  - Um dos pontos principais do sistema, permitindo que alunos possam marcar presença eletronicamente em suas atividades como bolsista ou estagiário. 
  
- Atualizador de hora e local da bolsa 
  - Caso necessário o servidor responsável pelo estagio ou bolsa pode modificar o local e hora do mesmo. 

- Comunicação fácil entre servidor e estagiário 
  - O servidor poderá deixar notas e avisos para os bolsistas, facilitando a comunicação.

 
- Cadastro de Estagiários/Bolsistas 
  - Os 2 tipos de usuários poderão ser cadastrados pelos servidores responsáveis pelo setor.

- Cadastro de Bolsas e Estágios 
  - Os servidores responsáveis pelos setores poderão cadastrar as bolsas ou estágios. 

- Emissão de relatório de presença  
  - Os servidores poderão gerar um relatório de presença e outas informações, de seus bolsistas e estagiários. 

- Filtros na pesquisa de bolsistas ou estagiários 
  - Se necessário o servidor poderá buscar através de filtros, bolsistas e estagiários, para facilitar a resolução de possíveis problemas. 

### 6. Interligação com outros sistemas 
#### 6.1. SUAP 
* Como já foi citado antes neste documento o programa visaria uma ligação com o SUAP por ser pensado inicialmente para o IFRN, mas outro sistema semelhante poderia ser usado para o cadastro de estudantes e servidores

### 7. Restrição

* A principal restrição seria o fato de não estar conectado à rede de uma instituição. 

