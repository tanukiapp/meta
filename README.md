# Tanuki's Meta

## What is Tanuki?

Tanuki is an opensource anime schedule built for Kitsu community. It uses Syoboi API and Kitsu.io API to get current airing and upcoming shows, just to create a schedule with your favourite shows. Currently is under development, but there is an stable beta version at https://tanuki.surge.sh/

## How does Tanuki works?

Tanuki runs over nginx http server, however it has its own specific server-side application that makes it faster, secure and functional.

* **Tanuki App**. The frontend of Tanuki. It's a responsive website based on Angular and Bulma. [Repository here](https://github.com/tanukiapp/tanuki)

* **Tanuki Server**. The server-side application, where the magic occurs. Using wopian's kitsu module and some JavaScript magic powders, it can build a anime schedule, just for you! [Repository here](https://github.com/tanukiapp/tanuki-server)

## I want to contribute!

There is a lot of issues opened on both repositories, just check them and select one you think you can fix! The same for bugs, if you find any bug, report it or fix it and leave us a pull request.

### Non developer contributing guide

Do you want to contribute with Tanuki but you're not a developer? You can make a donation! Just select your favourite way: Patreon, LiberaPay or Ko-Fi

## Tanuki tools

Some tasks needs an special tool. I'm developing some libraries and tools to resolve this issues.

* **Sukejuuru**. Node Syoboi's calendar scrapper.
