# compiler

Pour certains langages, la compilation consiste à convertir du code source en binaire de la façon la plus déterministe possible, de sorte que les variations dans les résultats obtenus, et quelque soient le compilateur utilisé ou l'environnement système, soient extrêmement réduites et même nulle dans certains cas où les paquets doivent être signés. 

## compiler de façon reproductible 

Les compilateurs en effet peuvent rendre des résultats différents selon la place attribuée à l'horodatage dans le processus de compilation, l'ordre de lecture des fichiers qu'ils suivent par défaut, l'organisation du système de fichiers de la machine et le système d'allocation de la mémoire. 
Les "packageurs" qui desservent en logiciel des communautés entières ont appris à utiliser des compilateurs reproductibles qui suppriment ces aleas, ce qui fait par exemple que le taux de reproductibiltié atteint par les codes sources et logiciels livrés par Debian [dépassent de peu les 96%](https://isdebianreproducibleyet.com/), mais n'atteignent pas encore les 100%

