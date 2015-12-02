# Cyris-COTS Ansible playbook

## Requirement

 - Ubuntu distribution
 - Able to communicate with one ubuntu mirror to get RabbitMQ install

## COTS supported

Actually, these COTS are deployed by this playbook:
 - Apache2

## Playbook usage

To execute this playbook:
``ansible-playbook -i platform/(platforme_name) apache2.yml``

If root user isn't used, you have to uncomment the sudo line present in each specific roles (.yml file) and specify the ``--ask-sudo-pass`` argument.
