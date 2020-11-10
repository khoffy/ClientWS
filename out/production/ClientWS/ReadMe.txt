Pour générer le "proxy" SOAP et on contenu:

1/ Avec l'outil de l'IDE (IntelliJ)
Tools => WebServices => Generate Java Code From Wsdl

proxy ==> la valeur de Package prefix

2/ Avec l'outil de java (en CLI)
==> wsimport -s . http://localhost:8686/BanqueWS?wsdl