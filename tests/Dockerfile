FROM ansible/ubuntu14.04-ansible

MAINTAINER Bryan CS <@iambryancs>

RUN echo "localhost ansible_connection=local" > /etc/ansible/hosts

COPY . /etc/ansible/roles/iambryancs.ppa-ondrej
