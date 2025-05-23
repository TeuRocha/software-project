### Descrição do Problema

Uma grande empresa química iniciou um processo para atualização dos seus sistemas 
de tecnologia, envolvendo a área financeira, de produção e comercial. O projeto em cada uma 
das áreas será desenvolvido por uma empresa diferente.

Sua empresa foi contratada para modelar o software de controle de uma das linhas de 
produção de indústria de tintas. Para isso, vocês devem disponibilizar os seguintes diagramas 
da UML: Diagrama de Caso de Uso, Diagrama de Classes, Diagrama de Objetos (opcional), 
Diagrama de Sequencia, Diagrama de Estados, Diagrama de Implantação, Diagrama de 
Componentes e Diagrama de Implantação.

---
![image](https://github.com/user-attachments/assets/d47da3a3-27e9-4262-a2b5-e89ca482ee93)

---
Esta linha produz basicamente dois tipos de tinta, cujas bases são fornecidas pelas 
bombas B1 e B2. As válvulas V1 e V2 não permitem ajuste de vazão. As mesmas possuem 
apenas dois estágios: aberta ou fechada. A Vazão deve ser controlada através da potência das 
bombas.

A cor da tinta é fornecida através da combinação de três corantes, localizados em barris 
e a quantidade de cada uma a ser produzida é determinada pelo sistema comercial. A 
quantidade de corante em cada preparo é determinada pelas válvulas V3 a V8, sendo que as 
mesmas possuem oito posições de controle de vazão. 

Os dois misturadores são responsáveis por misturar as tintas e armazená-las nos 
tanques E-7 a E-13. Notar que cada tanque pode receber tintas de quaisquer dos misturadores, 
através do acionamento das válvulas V-9 a V16, que são idênticas a V1. Para que isso ocorra, 
o tanque deve ser esvaziado para o caminhão que transportará a tinta. 

Todos os comandos ao sistema de controle são feitos através do envio/recebimento de 
mensagens. Os sensores não estão representados na figura 1, mas existem basicamente dois 
tipos de sensores: pressão nas linhas e nível dos tanques (em litros). 

A central de monitoramento da linha, que também não está representada na figura, 
possui uma tela onde o operador pode acompanhar todo o andamento do projeto e monitorar o 
status de todas as válvulas, bombas e tanques, sendo responsável por liberar a entrada de 
caminhões para esvaziamento dos tanques. Esta central também é responsável por comandar 
o início da produção de uma cor, baseada na saída do sistema de planejamento de produção 
(PCP). 

Além disso, há questões de segurança que devem permitir a sala de monitoramento 
reverter o status de qualquer uma das válvulas, caso seja detectado um problema.  
A central de monitoramento também é responsável por emitir relatórios informando as 
quantidades diárias de produção de cada um dos produtos.

**Dinâmica do Trabalho**

- O trabalho será realizado em grupos de até 4 pessoas. Não serão admitidos grupos com 5 
ou mais integrantes. 
- As entregas deverão ser feitas no MOODLE, indicando o link para a Wiki no GitHub com a 
descrição do proejto e dos seus diagramas.
