# Executando o PiHole usando docker-compose

## Resumo
- Em resumo, o [PiHole](https://pi-hole.net/) é um bloqueador de anúncio que bloqueia anúncio em uma rede.
- O usamos como servidor de DNS e ele bloqueia todas as URLs de anúncios cadastrados. 

## Execução
Na pasta `pihole` execute o comando:
```bash
docker-compose up -d
```

Abra o navegador e acesse o endereço `http://localhost:8088/admin/index.php`.
