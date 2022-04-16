# Домашнее задание «2.4. Инструменты Git» 


1. Комит, хеш которого начинается на aefea имеет полный хеш aefead2207ef7e2aa5dc81a34aedf0cad4c32545. Коментарий: Update CHANGELOG.md
2. Коммит 85024d3 имеет тег v0.12.23
3. У коммита b8d720 два родителя - 56cd7859e и 9ea88f22f
4. Между тегами v0.12.23 и v0.12.24 было сделано 9 коммитов

    33ff1c03b (tag: v0.12.24) v0.12.24

       b14b74c49 [Website] vmc provider links

       3f235065b Update CHANGELOG.md

       6ae64e247 registry: Fix panic when server is unreachable

       5c619ca1b website: Remove links to the getting started guide's old location
    
       06275647e Update CHANGELOG.md

       d5f9411f5 command: Fix bug when using terraform login on Windows

       4b6d06cc5 Update CHANGELOG.md

       dd01a3507 Update CHANGELOG.md

       225466bc3 Cleanup after v0.12.23 release

    85024d310 (tag: v0.12.23) v0.12.23


5. Функция func providerSource(configs []*cliconfig.ProviderInstallation, services *disco.Disco) (getproviders.Source, tfdiags.Diagnostics) находится на 23-й строке в файле provider_source.go была введена в коммите 8c928e835 main: Consult local directories as potential mirrors of providers
6. Изменение функции globalPluginDirs происходило в трех коммитах:

    35a058fb3 main: configure credentials from the CLI config file

    c0b176109 prevent log output during init

    8364383c3 Push plugin discovery down into command package

7. Функция synchronizedWriters описана в коммите 5ac311e2a

    Author: Martin Atkins <mart@degeneration.co.uk>

    Date:   Wed May 3 16:25:41 2017 -0700



