# Tanuki's Meta

## What is Tanuki?

Tanuki is an open-source anime schedule built for Kitsu community. It uses Syoboi API and Kitsu.io API to get current airing and upcoming shows, and to creates a schedule with top animes currently airing.

## How does Tanuki works?

### [DEPRECATED] Tanuki v1.0 
Tanuki v1.0 runs over Nginx HTTP server, however it has its own specific server-side application that makes it faster, secure and functional.

* **Tanuki App**. The frontend of Tanuki. It's a responsive website based on Angular and Bulma. [Repository here](https://github.com/tanukiapp/tanuki-app)
* **Tanuki Server**. The server-side application, where the magic occurs. Using wopian's kitsu module and some JavaScript magic powders, it can build a anime schedule, just for you! [Repository here](https://github.com/tanukiapp/tanuki-server)

### Tanuki v2.0 
Tanuki v2.0 is a complete redesign of v1.0. It is still using Express and Kitsu JSON:API client, but now includes server-side template rendering, avoiding a second app to maintain, turning it all into same application. It also offers an 
open API set of endpoints, allowing you to create your own app or even adding it to your existing app.

## I want to contribute! Can I do it?

### As developer
There is a lot of issues opened on Tanuki repositories, just check them and select one you think you can fix! The same for bugs, if you find any bug, report it or fix it and leave us a pull request.

### As non-developer

Do you want to contribute with Tanuki but you're not a developer? You can make a donation! Just select your favourite way: Patreon, LiberaPay or Ko-Fi

## Tanuki tools
Some tasks needs an special tool. I'm developing some libraries and tools to resolve this issues.

* **Sukejuuru**. Node Syoboi's calendar scrapper.
