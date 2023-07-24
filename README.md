# [Achimid Site](https://achimid.com.br/)
------------------------

Site para organizar e apresentar os conteúdos e APIs desenvolvidos.

![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white)

## Serviços e APIs
- [Achimid Site] https://achimid.com.br/
- [AniFan] https://anifan.com.br/
- [AnimeX] https://animex.achimid.com.br
- [Puppeteer API] https://puppeteer-api.achimid.com.br/
- [UpTime Kuma] https://status.achimid.com.br/status/sites
- [Telegram Notify] https://telegram-notify-api.achimid.com.br/


### Techs
- HTML
- CSS
- Javascript
- Bootstrap
- Nginx
- Github Actions
- Docker
- Cloudflare

### Docker [docker-compose.yml]
````shell
version: '2'

services:
    achimid-site:
        image: 'achimid/achimid-site:latest'
        container_name: achimid-site
        ports:
        - "80:80"
````
