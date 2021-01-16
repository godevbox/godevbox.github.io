# DevBox - Cloud Development Environment

Imagine to **access your entire development environment though your browser**, using your favourite IDE and the tools that makes your work easier: [VSCode][vscode] and [Docker][docker].

- Your work is independent from your hardware
- Demo your progress with HTTPs enable custom urls
- Pay only what you use
- Choose your hardware based on the task ad hand

# Features Comparison Matrix:

|                                           |      DevBox     | GitPod | Local |
| :---------------------------------------- | :-------------: | :----: | :---: |
| [Docker-Compose](#docker-compose)         |      👍         |  ❌    |   👍  |
| [Multi Repo](#multi-repo)                 |       👍        |   ❌   |   👍  |
| [Fluid Experience](#fluid-experience)     |       👍        |   👍   |  ❌   |
| [Custom ports](#custom-ports)             |      👍         |  ❌    |   😕  |
|  [Parallel projects](#parallel-projects)  |      👍         |   👍   |  ❌   |
|  [Automatic HTTPS](#automatic-https)      |     👍          |   👍   |  ❌   |
| [Auto Stop](#auto-stop)                   | optional/custom |   30m  |   ❌  |
| [Planned Start](#planned-start)           |      👍         |   ❌   |  ❌   |
| [Authenticated URLs](#authenticated-urls) |      👍         |   ❌   |  ❌   |
| [Custom DNS](#custom-dns)                 |      👍         |   ❌   |  ❌   |
| [On Demand Power](#on-demand-power)       |      👍         |   ❌   |  ❌   |
| [Full Linux server](#full-linux-server)   |      👍         |   ❌   |  ❌   |
| [Reverse Proxy](#reverse-proxy)           |      👍         |   ❌   |  ❌   |
| [Startup Tasks](#startup-tasks)           |        ❌       |   👍   |  ❌   |
| [Files Manager](#files-manager)           |      👍         |  ❌    |   👍  |
| [Monitoring](#monitoring)                 |      👍         |  ❌    |   ❌  |

> **NOTE:** Some of the listed features are in the roadmap.

## Docker Compose

Do you need to run multiple service dependencies <small>(DBs, Message bus, queue system...)</small>?  
👉 _We got you covered!_

Run anything with [Docker][docker] and expose services with customized reverse-proxy rules that you apply as simple container's labels!

## Multi Repo

Are you working on a multi-repo or a mono-repo project?  
👉 _We got you covered!_

DebBox gives you access to a full Linux machine (Ubuntu >= 20.04), you can clone any repo from any versioning provider, with any versioning system that is known to the Linux world.

## Fluid Experience

Start working on your laptop, use your tablet on the bus and finish up by borrowing your dad’s PC to fix that silly bug right just before a family dinner.

> You can even work from your smartphone, if you are so inclined 🤣.

**Did you spill that coffee on your Mac?**  
👉 _We got you covered!_

Just borrow the first available laptop and complete your work while your boss orders your next machine! It won't take any setup time, you will find the file you were editing, with the cursor at the exact position as you left it, **even if you didn't save**!

## Custom Ports

Need to run a database like [PostgreSQL][postgres] and want to connect to it with your client (like [Postico][postico]) via TCP/UDP?  
👉 _We got you covered!_

You can **configure port mapping** for any process you are running, locking it down to your home or office IP, or opening it up for the world to enjoy.

> _This feature is currently in our high priority roadmap._

## Parallel Projects

[[TO BE COMPLETED]]

## Automatic HTTPS

[[TO BE COMPLETED]]

## Auto Stop

You can configure your preferred timeout to auto-stop your instance, and configure automatic reboot based specific rules

[[TO BE COMPLETED]]

> _This feature is currently in our high priority roadmap._

## Planned Start

Are you a 9-5er? Get your machine ready just before you start and stop if afterward so to save credits. Automatically.

[[TO BE COMPLETED]]

> _This feature is currently in our high priority roadmap._

## Authenticated URLs

Want to share your work-in-progress but under a custom password? We got you covered with configurable per-service basic-auth!

[[TO BE COMPLETED]]

> _This feature is currently in our high priority roadmap._

## Custom DNS

Want a human-friendly url for your work? We got you covered! Free custom 3rd levels domain are included, and you can always attach your custom DNS as well!

[[TO BE COMPLETED]]

> _This feature is currently in our high priority roadmap._

## On Demand Power

Change CPU and RAM based on the current workload. Pay only what you need for the task at hand.

[[TO BE COMPLETED]]

> _This feature is currently in our high priority roadmap._

## Full Linux Server

Do anything with it, full ssh access with custom PEM key.

[[TO BE COMPLETED]]

## Reverse Proxy

Easily configure sub-domains rules or sub-directory rules for your work!

[[TO BE COMPLETED]]

## Startup Tasks

But you can use screen or tmux and work like a real Matrix pro!

[[TO BE COMPLETED]]

## Files Manager

Upload and download assets and entire folders from/to your instance easily, with a simple web based UI!

[[TO BE COMPLETED]]

## Monitoring

Monitor CPU, RAM, Disk and Network workload for each of your instances!

[[TO BE COMPLETED]]

[docker]: https://www.docker.com/
[vscode]: https://code.visualstudio.com/
[posgres]: https://www.postgresql.org/
[postico]: https://eggerapps.at/postico/
