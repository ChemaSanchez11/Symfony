# ![TOAST UI Editor](https://gunkastudios.com/wp-content/uploads/2021/04/symfony-cover.png)

> Proyecto Symfony Chema Sanchez

## 🚩 Table of Contents

- [Instalacion](#-instalacion)
- [Comandos](#-comandos)

## 📦 Instalacion

### Instalacion En Windows

| Nombre | Comando |
| --- | --- |
| [`RemoteSigned`] | Set-ExecutionPolicy RemoteSigned -Scope CurrentUser |
| [`Scoop`]        | Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh') |
| [`symfony-cli`]  | scoop install symfony-cli |
| [`Proyecto`]     | symfony new concesionario --webapp |
| [`maker-bundle`] | composer require symfony/maker-bundle --dev |
| [`orm-pack`]     | composer require symfony/orm-pack |
| [`twig`]         | composer require twig |
| [`database`]     | php bin/console doctrine:database:create => 'en .env primero añadir DATABASE_URL="mysql://root@127.0.0.1:3306/blog_symfony"' |
| [`crud`]     | php bin/console make:crud entidad

## 🤖 Comandos
| Nombre | Comando |
| --- | --- |
| [`Modelo`]       | php bin/console make:entity => php bin/console make:migration => php bin/console doctrine:migrations:migrate|
| [`Controlador`]  | php bin/console make:controller |
| [`Servidor`]     | symfony server:start |

## Login
| Nombre | Comando |
| --- | --- |
| [`security`]          | composer require security
| [`user`]              | php bin/console make:user
| [`auth`]              | php bin/console make:auth
| [`form-validator`]    | composer require form-validator
| [`registration-form`] | php bin/console make:registration-form

![markdown](https://symfony.com/doc/master/cloud/_images/new-symfony-welcome-page.png)

**CommonMark + GFM Specifications**

## 📜 License

This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) © [NHN Cloud](https://github.com/nhn).
