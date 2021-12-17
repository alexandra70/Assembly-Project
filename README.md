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


3 - Sortare de cuvinte


4 - Conturi Bancare
