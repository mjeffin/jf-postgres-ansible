ansible-playbook -i <server-name>, --extra-vars="POSTGRES_USER=<postgres-username> POSTGRES_DB=<postgres-db-name>" postgres.yml

ansible-playbook -i feature3.api.crm.dakshin.juspic.com, --extra-vars="POSTGRES_USER=devv12345 POSTGRES_DB=dakshinCrmfeature3" postgres.yml

ansible-playbook -i master3.api.crm.dakshin.juspic.com, --extra-vars="POSTGRES_USER=devv12345 POSTGRES_DB=dakshinCrmMaster3" postgres.yml

postgres://dakshindbuser:devv12345@master3.api.crm.dakshin.juspic.com:5432/dakshinCrmMaster3