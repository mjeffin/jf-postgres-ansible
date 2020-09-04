ansible-playbook -i <server-name>, --extra-vars="POSTGRES_USER=<postgres-username> POSTGRES_DB=<postgres-db-name>" postgres.yml

ansible-playbook -i db.example.com, --extra-vars="POSTGRES_USER=exampleuser POSTGRES_DB=exmampledb" postgres.yml

