Integrantes do grupo - Varlei Junior De Cesare e Demetrio Webber Barreto
a) 
I)	opencv annotation - Tem a finalidade de anotar os pontos de interesse da imagem correspondente.
Assim fazendo com que o treinamento não fique tão pesado para ser rodado na máquina.

II)	opencv createsamples - Tem a finalidade de receber as anotações já criadas com o annotation e criar um
arquivo .vec com base em todas as coordenadas de imagens positivas para que seja compatível com o 
opencv traincascade.

II)	opencv traincascade - Com base nas imagens positivas e suas coordenadas já feitas e o conjunto de 
imagens negativas as quais não contém o elemento que vai ser detectado o traincascade vai fazer o trei-
namento, e com isso um arquivo .xml vai ser criado. Com o qual vai poder ser utilizado por um fácil mé-
todo. 

b)
	Para ser treinada uma Inteligência artificial necessita-se do opencv juntamente com imagens
positivas ou seja imagens do objeto a ser capturado, e imagens negativas para que em relação ao objeto
positivo sejam totalmente aleatórias e diferentes.
Com isso faz o alistamento de imagens negativas em um arquivo. Após precisasse usar o opencv annotation
para fazer a marcação de apenas os pontos de interesse. Com isso é necessário criar um arquivo vetorial
com o opencv create samples para que o próximo aplicativo do opencv possa captar todas as coordenadas 
das imagens positivas, esse aplicativo é o traincascade que vai usar as coordenadas positivas e fazer
a relação com as negativas e assim treinando a IA.





c) III) O objeto a ser detectado pela IA feita pelo grupo é o símbolo da marca Nike em camisas, calças
etc...