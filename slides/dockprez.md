# Container ?

![Container](./slides/images/container-history.jpg)


&#9835; J'aurais aimé être un artiiiiiiiiiiste &#9835;

![ContainerArtist](./slides/images/container-artist.jpg)  


&#9835; Pour pouvoir faire mon numérooooooo &#9835;

![ContainerNumero](./slides/images/container-numero.jpg)


&#9835; Quand l'avion se crash sur la piste .... &#9835;

![ContainerCrash](./slides/images/container-crash.jpg)


Quand j'étais petit ...

![Lego](./slides/images/lego.jpg)


![LegoToContainer](./slides/images/lego-to-container.png)


![ContainerSize](./slides/images/container-size.jpg) <!-- .element: class="alignleft" -->
![LegoSize](./slides/images/lego-size.png) <!-- .element: class="alignright" data-fragment-index="3" -->


## Une BALEINE !

 \\\_oO\_/  ??
 
![DockerWhale](./slides/images/docker-whale.png) <!-- .element: class="fragment" data-fragment-index="3" -->


![DockerLegoWhale](./slides/images/docker-lego-whale.jpg)


## The big hold up ?
*Depuis 2008...*

![DockerAvant2008](./slides/images/avant2008.png)

_... OpenVZ, Linux-VServer, FreeBSD_


*En 2013 !*

![DockerApres2013](./slides/images/apres2013.png)


## L'usage d'abord !

![ImbricationLego](./slides/images/imbrication-lego.jpg)  
__UNIVERSALITE__
* du package 	<!-- .element: class="fragment" data-fragment-index="4" -->
* des commandes d'exploitation <!-- .element: class="fragment" data-fragment-index="4" -->
* de l'intégration dans l'infrastructure <!-- .element: class="fragment" data-fragment-index="4" -->


## Comment ?

![DockerImage](./slides/images/docker-composition.png)


### Tool in Action !
![DemoInit](./slides/images/demo-funny.gif)




## Package universel
* 1 DockerFile
* 1 seule méthode de construction :
	```bash
	docker build ...
	```


## Intégration universelle
1. Récupération :

	```bash
    docker pull busybox
	```

1. ou récupération + exécution :                                              

	```bash
    docker run -d -p 80:8080 tomcat:8-jre8
	```


## Les registry
* Officiel : https://hub.docker.com 
* "Privés"



<!-- .slide: data-background-image="./slides/images/inception.jpg" -->


Commande de lancement de la présentation :
```bash
docker run -d -p 8000:8000 -v `pwd`:/show rguillom/reveal
```


Et pour vous ?

* Vos démos
* Vos devoirs
* Les exemples de cours


![EndDocker](./slides/images/end_docker.png) 

Sources :<!-- .element: style="text-align: left;" -->
 [pixabay.com](https://pixabay.com), [docker.com](https://www.docker.com), [Blog TravisCI](https://blog.travis-ci.com)

<p style="text-align: left;">
![Icon](./slides/images/twitter.png) [@RGuillom](https://twitter.com/RGuillome)
</p>

<p style="text-align: left;">
![Icon](./slides/images/website.png)  [blog.guillaumerenaudin.com](http://blog.guillaumerenaudin.com)
</p>