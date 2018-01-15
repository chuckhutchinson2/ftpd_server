FROM stilliard/pure-ftpd:hardened

# for documentation go here -> https://github.com/stilliard/docker-pure-ftpd

# create user bob with password password
RUN (echo password; echo password) | /usr/bin/pure-pw useradd bob -f /etc/pure-ftpd/passwd/pureftpd.passwd -m -u ftpuser -d /home/ftpusers/bob

