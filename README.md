# docker-portainer

## Generate SSL Certificates
python ~/.vim/bin/request_vault_certificate.py --vault_token $(cat ~/.vault-token) --output_cert certs/portainer.crt --output_key certs/portainer.key nuc10i7fnh.home.arpa
