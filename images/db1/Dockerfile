#FROM rastasheep/ubuntu-sshd
FROM rastasheep/ubuntu-sshd:16.04
RUN echo "StrictHostKeyChecking no" >> /etc/ssh/ssh_config
ADD files/.ssh /root/.ssh
