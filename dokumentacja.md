# Potyczki Młodych Adminów: Final 2026
## Zespól 9

## Część 1: Pierwsze kroki w Krzak-Polu

### Misja 1:

Został utworzony nowy namespace `krzak-pol-web`

![Create Namespace](misja1/1.png)

![Namespace](misja1/2.png)

Oraz deployment z obrazem `nginx:alpine` i dwoma replikami z labelem "app": "krzak-nginx"

todo fix nagranie to image
![Nagranie](misja1/3.mp4)

Stworzony został serwis dla klastra
![Create](misja1/4.png)

![Cluster IP](misja1/5.png)

![Service Ports](misja1/6.png)

![Labels](misja1/7.png)

Stworzony został ingress
![Ingress](misja1/8.png)

http://krzakpol.193.187.69.224.nip.io/



### Misja 3:
Pierwszy błąd to zła nazwa zdjęcia kontenera (httpd a nie httpdd)
![Nazwa](misja3/1.png)

Zły label (ksiegowosc-app a nie ksiegowosc-backend)
![Label](misja3/2.png)

Port ustawiony na 80 (czyli na ten na który httpd słucha)
![Port](misja3/3.png)




### Misja 5:

Liczba replik krzak-pol-web (nginx) została zwiększona do 5
![Repliki](misja5/1.png)

Ustawiono zasoby na 128 Mi RAMu oraz 150mCPU
![Resources](misja5/2.png)



## Część 2: Prezes wchodzi na wyższe obroty

### Misja 6:



### Misja 7:

Utworzona klasa o nazwie `krzak-longhorn-retain` z polityką `Retain`
![StorageClass](misja7/1.png)

Utworzony namespace `klienci-premium`
![Namespace](misja7/2.png)

Stworzony serwis dla StatefulSet
![Cluster IP](misja7/3.png)

