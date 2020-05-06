# Siguria_29
CAESAR CIPHER   
1.Udhezime per ekzekutimin e programit  
-caesar cipher(kodi i cezarit) ndryshe njihet edhe si shift cipher dhe ky kod i fsheh mesazhet duke  shtyer secilen shkronje per disa vende ne alfabet.se sa shtyhet nje shkronje varet nga vlera e qelesit qe kemi vendosur si p.sh nese qelesi eshte 2 atehere shkronja A na behet C.  
2.Pershkrimi per secilen komande
-Pershkrimi i komandeve per kodin e cezarit eshte bere brenda kodit me anen e komenteve qe te jete me qarte se per qfare eshte perdorur secila nga komandat.  
3.Rezultatet e ekzekutimit(I gjeni tek folderi images)  
3.1 Rezultatet e ekzekutimit te caesar encrypt(encriptimit me kodin e cezarit)  
![](images/caesarencrypt.PNG)
3.2 Rezlutatet e ekzekutimit te caesar decrypt
![](images/caesardecrypt.PNG)
3.3 Rezultatet e ekzekutimit te caesar brute-force
![](images/caesarbruteforce.PNG)

BEALE CIPHER
1.Udhezime per ekzekutimin e programit  
-Ne fillim e krijojm nje folder te zbrazet, pastaj ne ate folder i vendosum fajllin e tipit text edhe ate te tipit python.Pastaj pasi i vendosum ne nje folder hym tek ai folder dhe e hapum nje command line ne kete folder.Pastaj i kemi disa hapa te ekzekutimit:
1.Shenojm python, pastaj Enter.  
2.Shenojm quit(), pastaj Enter.  
3.Shenojm python emri_fajllitpython.py, pastaj Enter.  
5.Pastaj na shfaqet teksti nese deshirojme te encodojme apo decodojme, shtypim sipas deshires ose "e" ose "d", pastaj shtypim Enter.  
6.Shenojm text file si qeles, pastaj Enter.  
7.Pastaj shenojme fjalen qe deshirojme ta kodojme, pastaj shtypim Enter, dhe ne fund na shfaqet fjala e koduar.  
-Beale cipher perdoret per kodimin e nje teksti duke u bazuar ne poziten e atyre shkronjave te tekstit ne nje dokument tjeter(ne rastin tone ne nje tekst file).  
2.Pershkrimi i komandave  
Pershkrimi i shkurte i komandave eshte bere brenda kodit me ane te komenteve.
3.Rezultatet e ekzekutimit  
3.1 Rezultatet e enkriptimit me komanden beale
![](images/beale_encrypt.PNG)
3.2 Rezultatet e dekriptimit me komanden beale
![](images/beale_decrypt.PNG)


KOMANDA PERMUTATION
1.Udhezime per ekzekutimin e programit  
-Ne fillim e krijojm nje folder te zbrazet, pastaj ne ate folder e vendosum fajllin e tipit python.Pastaj pasi e vendosum ne nje folder hym tek ai folder dhe e hapum nje command line ne kete folder.Pastaj i kemi disa hapa te ekzekutimit:  
1.Shenojm python, pastaj Enter.  
2.Shenojm quit(), pastaj Enter.  
3.Shenojm python emri_fajllitpython.py, pastaj Enter.  
5.Pastaj na shfaqet teksti nese deshirojme te encodojme apo decodojme, shtypim sipas deshires ose "e" ose "d", pastaj shtypim Enter.
6.Shenojm nje permutacion qe e perdorum si qeles, pastaj Enter.  
7.Pastaj shenojme fjalen qe deshirojme ta kodojme, pastaj shtypim Enter, dhe ne fund na shfaqet fjala e koduar.  
-Komanda permutation e tarnsformon plaintekstin ne blloqe ,duke i ndare ato ne baze te nje permutacioni te caktuar.  
2.Pershkrimi i komandave  
-Pershkrimi i komandave eshte bere te kodi me ane te komenteve perkatese.
3.Rezultatet e ekzekutimit  
3.1 Rezultatet e enkriptimit me komanden permutation(2 shembuj)
![](images/permutation_encrypt.PNG)
![](images/permutation_encrypt2.PNG)
3.2 Rezultatet e dekriptimit me komanden permutation(2 shembuj)  
![](images/permutation_decrypt.PNG)
![](images/permutation_decrypt2.PNG)

# KOMANDAT
Ekzekutimi i komandave eshte bere me COMMAND PROMPT , programi ne te cilen kemi vendosur kodin e detyres se pare dhe vazhdimin e detyres se dyte e kemi quajtur "ds" , te gjitha veprimet e programit do te kryhen ne programin e njejte dhe i kemi respektuar edhe rregullat per argumente,kodi per programin eshte shenuar ne gjuhen PYTHON.Ndersa sa i perket ekzekutimit te komandave dhe menyren e ekzekutimit do te paraqesim ne vijim per secilen komande.  

## Komanda create-user
Tek komanda create-user , kerkesa behet me emrin e komandes dhe emrin me te cilin deshirojme ti emerojme fajllat ku do te ruhen qelesat privat dhe publik te RSA.  
Si p.sh kerkesa mund te behet ne formen "create-user gentrit" , me qe rast do krijohen dy fjalla njeri qe permban qelesat privat dhe tjetri qe permban qelesat publik me po ate emer.

## Komanda delete-user
Kjo komande ekzekutohet ne formen p.sh "delete-user genti" , me kete rast i fshijme te gjitha fjallat me ate emer qe permbajne qelesa te RSA, nese ekzekutojm komanden perseri me te njejtin emer lajmrohemi se fajllat me ate emer jane fshire paraprakisht.

## Komanda export-key
Me ane te kesaj komande behet eksportimi i qelesave prej nje fajlli ne fajllin tjeter.  
Kjo komande ekzekutohet si p.sh "export-key public/privat emri path" , ne kete rast emri percakton qelesi i cilit perdorues do te eksportohet ndersa path paraqet fajllin ku do te ruhet qelesi i eksportuar.
