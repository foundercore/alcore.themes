# refernce from here for theme

https://github.com/foundercore/edx-platform/tree/open-release/ironwood.master


# deployment
Themes Update
- Login to Server where you have deployed the portal
- Go to path: /home/bitnami/alcore.infra
- run command `make alcore.update.theme`
- Enter the following details :
  - Enter the platform name: Endeavor Careers LMS
  - Enter the machine private IP: 172.31.21.107
  - Enter the sub-domain name: iendeavor
  - Enter the cms-domain name: staff.iendeavor
  - Enter system user's email: no-reply@foundercore.org
  - Enter system user's password: XXXXXX(get from teams)
