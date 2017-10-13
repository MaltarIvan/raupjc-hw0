#Pitanje 1:
U Bin/Debug folderu pojavile su se dvije nove datoteke: ClassLibrary1.ddl i ClassLibrary1.pdb. 
Ako maknemo .dll datoteku nakon pokretanja .exe datoteke konzola æe nam javiti da se dogodila greška 'System.IO.FileNotFoundException', jer aplikacija ne sadrži class library. 
Ako bi htjeli nekome poslati ovu aplikaciju, uz .exe datoteku morali bi poslati i .dll datoteku.

#Pitanje 2:
Ako promjenimo string koji ispisuje PrintHelloWorld metoda i pokrenemo .exe datoteku bez prevoðenja class library projekta 
konzolna aplikacija ispisuje stari string zato jer koristi staru verziju class library-a.

#Pitanje 3:
Nakon brisanja NodaTime direktorija aplikacija se i danje normalno builda, a nakon buildanja ponovo se stvara NodaTime direktorij.