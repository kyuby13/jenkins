# jenkins
docker jenkins

# Cara Menjalankan jenkins via docker

----

# Buat directory

mkdir ~/jenkins

---

# Jalankan docker compose

docker-compose up -d

----

# Buka jenkins via browser

http://IPaddr:8080

---

# Ambil admin password

docker exec jenkins-lts cat /var/jenkins_home/secrets/initialAdminPassword

atau

docker logs jenkins | less

# Matikan docker

docker-compose down
