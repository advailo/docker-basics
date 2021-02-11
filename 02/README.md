# Uzdevums 02

Iemācīties piestartēt nginx un vēl arī mysql

### Izpildes soļi
1. atveram savu iemīļoto konsoli
2. sudo vi /etc/hosts
   pievienojam rindu
   127.0.0.1 docker-basics.advailo.com
   saglabājam
3. cd docker/
4. docker-compose up -d
5. docker ps
6. averam pārlūkā http://docker-basics.advailo.com
7. izmantojot savu iemīļoto mysql klientu pieslēdzamies pie localhost:3360 un paskatāmies vai mr mysql strādā un izveidojam kādu jaunu tabulu un ierakstus
8. docker-compose down
9. docker-compose up -d
10. atkārtojam 7. soli, kur mani dati palika?
11. izlabojam docker-compose.yml pievienojot vēl vienu volume mysql servisam
```
    volumes:
      - ./mysql/data/:/var/lib/mysql/
```
12. atkārtojam 8.-10. soļus un atkārtojam 7. soli
13. atkārtojam 8.-9. soli - redz mani dati joprojām ir šeit