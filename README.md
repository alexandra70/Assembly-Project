# Assembly-Project

***1 - Sortarea albumelor - primesc un vector de structuri - unde fiecare structura are urm structura:***
  ****struct node**** {
      int val;
      struct node* next;
  };
  
  ***Parcurg vectorul - caut urmatorul element din vector dc ac exista - ? cum ? - profit de faptul ca nodurile sunt efectiv in ordine consecutive, deci e usor de determinat urm
  nod: caut nodul dupa form : next->val - 1 = cur->val, cand il gasesc actualizez campul next. Trebuie retunata o adresa - adresa primului elemetent ( elementul cu valoarea minima
  se considera a fi primul element). Caut minimul dintre valorile nodurilor din vector si retin adresa acelui nod pe care la final o voi returna.***

2 - Cosmarul lui Turing 


****3 - Sortare de cuvinte****

***Functii folosite:
 get_words - > primeste un vector de adrese, un string, nr de cuvinte din string;
 Se doreste impartirea propozitiei dupa delimitaltorii : ,.\n
 Si mai apoi pasarea fiecarui cuvant in liniile matricei primita ca argument.
 Cu strtok iau cuvintele din propozitie si le adaug treptat in matrice pana cand nu mai am 
 cuvinte de procesat.
 sort -> primeste matricea de cuvinte pe care trebuie sa le sortez, numarul lor, si size-ul unui element din vector - vector de adrese - deci 4 octeti.
 Trebuie folosit obligatoriu functie implementata deja qsort, pt care mai trebuie definita 
 o functie de compare - care primeste doua adrese (adresele elemntelor care trebuie comparate) si returneaza diferenta dintre ele. Prin diferenta ma refer la: 0 sunt egale, 1 primul string prmit ca param e mai mare decat al doilea si -1 invers.
 Prima data se compara dupa lungime si folosesc ce am scris mai sus - DAR DACA stringurile sunt egale in ceea ce priveste lungimea se va compaa lexicografic - deci se sare la compar_lexic(unde se face iarasi copmarare - de data asta cu strcmp), in final rezulatul e pus in eax.
 diff - > primeste doua valori intregi si verifica relatia de egalitate dintre cele doua. ***
 
4 - Conturi Bancare
