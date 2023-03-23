# Rapport TLC
Pour la TLC, j'ai eu énormément de mal à faire fonctionner mes dockerfiles et mes docker compose et donc je n'ai pas pu mettre le tout sur la VM de l'ISTIC. J'ai eu 2 erreurs principales que je n'ai pas réussi à résoudre.
  1. J'ai réussi à créer mes dockerfiles front et back et mon docker compose mais lors de la soumission de mes horaires sur l'application WEB il me retournai une erreur 502 Bad Gateway (image ci-dessous)
![image](https://user-images.githubusercontent.com/47176899/227282406-e083f5f3-d389-4a66-8ff8-b34d1612e23e.png)
  2. Ensuite, j'ai voulu recréer mes images dockers mais cela m'a créé une autre erreur au niveau de mon image api (image ci-dessous), très probablement une erreur au niveau de mes fichiers conf
 ![image](https://user-images.githubusercontent.com/47176899/227284742-a30daf99-bd6f-47a5-aead-e090b5cddf49.png)

voici le schéma qui résume mon implémentation :
![image](https://user-images.githubusercontent.com/47176899/227287421-0737e828-22e6-4780-9103-58a9ae392951.png)



# Remote meetings planning

This project is used in a course on the *ops* part at the [University of Rennes](https://www.univ-rennes1.fr/), France. It is a kind of doodle clone developed in so-called "native cloud" technologies in order to allow students to work on a continuous deployment chain in a containerized environment. Among the feature, the application automatically initializes a pad for the meeting and a chat room for the meeting participants.

- The [back](https://github.com/barais/doodlestudent/tree/main/api) is developed using the [quarkus.io](https://quarkus.io/) framework. 
- The [front](https://github.com/barais/doodlestudent/tree/main/front) is developed in [angular](https://angular.io/) using the [primeng](https://www.primefaces.org/primeng/)  angular UI component library and the [fullcalendar](https://fullcalendar.io/) graphical component.

A demo of the application is available [here](https://doodle.diverse-team.fr/).

Three videos (in french) are available. They present:
- the [main application feature](https://drive.google.com/file/d/1GQbdgq2CHcddTlcoHqM5Zc8Dw5o_eeLg/preview), 
- its [architecture](https://drive.google.com/file/d/1l5UAsU5_q-oshwEW6edZ4UvQjN3-tzwi/preview) 
- and a [short code review](https://drive.google.com/file/d/1jxYNfJdtd4r_pDbOthra360ei8Z17tX_/preview) .

For french native speaker that wants to follow the course. The course web page is available [here](https://hackmd.diverse-team.fr/s/SJqu5DjSD).
