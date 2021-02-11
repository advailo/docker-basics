# Uzdevums 01

Iemācīties piestartēt vienkāršu aplikāciju dokerī

### Izpildes soļi
1. atveram savu iemīļoto konsoli
2. sudo vi /etc/hosts
   pievienojam rindu
   127.0.0.1 docker-basics.advailo.com
   saglabājam
3. cd docker/
4. docker-compose up -d
5. docker ps
6. docker logs -f nginx
7. stveram pārlūkā http://docker-basics.advailo.com
8. docker exec -it nginx bash
   cd /var/www/
   ls -la
9. docker-compose down
