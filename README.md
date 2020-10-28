<img src="/img/banner-principal.png">

# Robocode Aspira

Olá! Meu nome é Fábia, sou estudante do curso de Analise e Desenvolvimento de Sistemas da Ucsal. 
Montei o robô Aspira para participar do desafio Solutis Robot Arena 2020. Eu escrevi "Montei", porque eu analisei o comportamento, estratégias, pontos fortes e fracos de alguns dos principais Robocode e utilizei partes dos códigos de alguns deles para montar a minha lógica de combate.

O nome "Aspira" foi inspirado no filme Tropa de Elite. O robô Aspira também é forte e obstinado como os aspirantes do filme, persegue inimigo até que ele seja eliminado. 

## **Linguagem Utilizada:**
☕︎ JAVA

## **Sobre o Código:**
<img src="https://cronicasdojoker.files.wordpress.com/2013/12/o-sistema.png">

- ### run():
<p>É o metodo principal, define o comportamento do robô. O Aspira mantém a arma independente do movimento do robô e o radar gira independente do giro da arma. Foi utilizado um loop para manter o robô e suas partes sempre em movimento.</p>

- ### onHitByBullet():
<p>É executado quando o robô é atingido por uma bala, ele revida com força 3 e se afasta 50 pixels.</p> 

- ### onHitWall:
<p>É executado quando o robô bate na parede, neste caso ele deve seguir na direção contraria para se desviar da parede.</p> 

- ### onHitRobot:
<p>É executado quando seu robô colide com outro robô. Ele aproveita que o inimigo já está ali tão perto, o define como alvo, identifica ele e atira com força 3, depois ele se afasta.</p> 

- ### onScannedRobot:
<p>Este talvez, seja o melhor incremento do meu robô, isso porque este evento é executado quando o robô encontra outro robô adversário. A partir dele o robô obtém informações como a distância do robô inimigo, seu ângulo, velocidade, se ele está perto ou não. A partir das informações coletadas vem a tomada de decisão para que o ataque seja feito de forma mais eficaz. O código do Aspira foi estruturado para que ele seja um robô que vai para cima do adversário e o ataca com agressividade e caso ele esteja distante o Aspira vai em busca dele para o atacar. Sua arma está sempre apontada para o seu inimigo, mas ele economiza energia quando o inimigo está distante.</p>

- ### onWin:
<p>Este método é chamado quando o robô vence uma batalha. A querida dancinha da vitória! :-D </p>


## **Pontos Fortes:**
<img src="https://i.makeagif.com/media/2-28-2017/VRIwsd.gif">

- O robô é bastante agressivo, ele vai em busca do adversário, o encontra e ataca; 
- Sua arma está sempre apontada para o inimigo;
- Ele diminui a força do tiro economizando energia quando inimigo está mais distante dele;


## **Pontos Fracos:**
<img src="https://2.bp.blogspot.com/-Q8XuVcqn4bE/TkiRC217vWI/AAAAAAAAAHQ/xqebXm1erV4/s1600/muleque00sm5.gif" height="160" width="280">

- Quando ele é encuralado, principalmente se for muito próximo de uma parede ele tem dificuldade de sair desta situação.  
- Por conta de sua caracteristica agressiva, de um robô que persegue o seu adversário, ele se expõe demais quando está em uma arena com muitos robôs deixando a retaguarda descoberta enquanto segue em sua perseguição. 
-  Podem existir outros pontos fracos que não foram evidenciados nos teste que fiz :-( 


## **O que eu achei da experiência?**
Para mim foi uma oportunidade fantástica de adiquirir experiências multiplas em tão pouco tempo. Meu conhecimento na linguagem Java ainda é bem inicial, ainda estou no 3 semestre da faculdade, só havia utilizado Java em pequenas atividades na faculdade, mas nunca foi com um projeto tão legal e divertido como o Robocode. Li a documentação e os tutoriais, utilizei os fóruns, vi vídeos, encontrei muita coisa boa no site da IBM, enfim para mim foi enriquecedor demais. Apesar de não ter o domínio de tudo que tem nos códigos que encontrei, eu me senti muito feliz em conseguir entender a lógica por trás dos códigos de outros robôs e a utilizei a favor do meu projeto, bem como adaptar os seus parametros para a lógica que eu entendi que seria mais funcional. 

Esta foi a primeira vez que utilizei o GitLab, então foi mais um aprendizado adicionado à minhas grande lista. 


### **_Obrigada Solutis! Eu quero mais!!!_**

<img src="https://i.pinimg.com/originals/34/27/94/3427943873a9a66f4686a6b574807bf9.gif">




 

