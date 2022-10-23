Proje 3
[Patika.dev](https://www.patika.dev/tr)

Binary-Search-Tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Root 7'dir. 5, 7'den küçük olduğu için 7'nin soluna yazılır. 1, 7 ve 5'ten küçük olduğu için 5'in soluna yazılır. 
8, 7'den büyük olduğu için 7'nin sağına yazılır. 3, 7 ve 5'ten küçük ama 1'den büyük olduğu için 1'in sağına yazılır.
6, 7'den küçük ama 5'ten büyük olduğu için 5'in sağına yazılır. 0; 7, 5 ve 1'den küçük olduğu için 1'in soluna yazılır.
9, 7 ve 8'den büyük olduğu için 8'in sağına yazılır. 4, 7 ve 5'ten küçük ama 1 ve 3'ten büyük olduğu için 3'ün sağına yazılır.
Son olarak 2, 7 ve 5'ten küçük ama 1'den büyük aynı zamanda 3'ten küçük olduğu için 3'ün soluna yazılır.


                                   7				
                                 /	 \			
                               5			 8		
                             /	 \			 \	
                           1		   6			 9
                         / 	 \							
                       0	  	 3						
                             /	 \					
          	               2		   4	
