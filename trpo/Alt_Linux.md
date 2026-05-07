# Alt Linux в Docker
> Никогда в разработке не используйте русские имена файлов и каталогов!

> Никогда в разработке не используйте пробелы и спец.символы в именах файлов и каталогов!!

#### Использовать контейнер с Alt

##### Загрузить готовый образ Alt
```shell
docker pull alt:sisyphus
```
![](./image/pervv.png)

##### Запустить и использовать
```shell
docker run -ti --rm --name alt alt:sisyphus /bin/bash
```
![](./image/vtorr.png)

#### Установить приложение Fastfetch в контейнере
```shell
apt-get update && apt-get install fastfetch
```
![](./image/trett.png)

#### Запустить Fastfetch
```shell
fastfetch
```
![](./image/chertv.png)

##### Выйти из контейнера с Alt
```shell
exit
```
![](./image/pyatt.png)