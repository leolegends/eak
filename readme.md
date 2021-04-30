
# EAK

ElasticSearch, APM e Kibana.



## Instalação 

Para o perfeito funcionamento é necessário a instalação do Docker e do docker compose.

```bash 
  apt-get install docker.io && docker-compose -y
```
    
Após a instalação, edite o arquivo docker-compose para mudar as credenciais do proxy reverso.

```yaml
  environment:
      - BASIC_AUTH_USERNAME=kibana
      - BASIC_AUTH_PASSWORD=password
```

## Subir o serviço

e por último, suba o serviço:

```bash
docker-compose up -d
```

valide se tudo está ok na rota abaixo:

```
http://localhost:8085
```
## Badges


[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

  
## Author

- [@leolegends](https://www.github.com/leolegends)

  