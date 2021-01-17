# Pricing

**👉 The goal of a Cloud Developement Environment is to reduce waste.**

> A computer that doesn't run is a wasted resource, and it makes me sick
> to have a powerful computer that most of the time is doing nothing at all!

## Development Station:

We work with complex systems that often require lot of resources:

| MacBook Pro 16"                      |  XPS 15 Laptop                       |
| ------------------------------------ | ------------------------------------ |
| <small>Ram 32Gb, Storage 1Tb</small> | <small>Ram 32Gb, Storage 1Tb</small> |
| $2959                                | $1700                                |

## Office Station:

Just to play safe, we picked top-shelf hardware to run this comparison:

| MacBook Pro 13"                       |  Yoga Duet 7i (13”) 2 in 1             |
| ------------------------------------- | -------------------------------------- |
| <small>Ram 8Gb, Storage 512Gb</small> |  <small>Ram 8Gb, Storage 512Gb</small> |
| $1399                                 |  $1200                                 |

## Virtual Hardware:

120 engineering hours/month  
<small>(8h day at 75% efficiency, 20 days month)</small>

50Gb disk (that can grow to 16TB)  
<small>$4.40/month fixed cost</small>

| Power                                         |        Hour |      Month |   4 Years |
| --------------------------------------------- | ----------: | ---------: | --------: |
|  1 CPU, 2Gb Ram<br><small>t3.small</small>    |     $0.0228 |      $7.14 |      $314 |
|  2 CPU, 4Gb Ram<br><small>t3.medium</small>   |     $0.0456 |      $9.87 |      $434 |
|  4 CPU, 16Gb Ram<br><small>t3.xLarge</small>  |     $0.1824 |     $26.29 |     $1156 |
|  8 CPU, 32Gb Ram<br><small>t3.2xLarge</small> |     $0.3648 |     $48.18 |     $2119 |
|  **Average:**                                 | **$0.1539** | **$22.87** | **$1000** |

> 👉 In most cases, 4 CPU and 16Gb of Ram would suffice as this computer does not need
> to run any graphical stuff, nor antivirus, nor Office stuff.
>
> The real average would be **$640**.

## What is the margin for improvement?

Let's recap with the average cost of a physical working machine:

| coding station |  office station | DIFFERENCE |
| -------------: | --------------: | ---------: |
|          $2329 |           $1300 |  **$1029** |

And let's take a look at how we spend our time as engineers:

| hours in a month |      720 |
| ---------------: | -------: |
|          working |      160 |
|  **engineering** |  **112** |

In any given month, an engineer machine is **NOT CODING for about 608 hours**, but we still
pay the full cost of the computational power that is necessary while we do code.  
Which luckily is only 15% of our time.

> 🤬 **We waste $218 / developer / year** in hardware that gets obsolete
> while it is NOT being used!

Over the course of 4 years, a great office station that allows for classic Office work,
whiteboarding with touch screen and pen, paired with a cloud-based on-demand coding machine
would cost: $1300 + $640 = $1940.

> 👍 **We could save $97 / developer / year** while still giving out the best possible
> hardware, real + virtual.

This is a 9.4% improvement on how we manage our developement infrastructure.

## Is there more?

I'm glad you asked! Yes, there is more.

We did this comparison using a fantastic piece of hardware as "office machine", but not every
component in the team needs such thing. Junior develpers and interns may do well with less
fancy hardware anyway.

A virtual computer is more resilient to incidents: you can't spill coffee on it, it can't be
stolen, you can programmatically back it up using simple snapshots.

A developer can kill a machine when they don't need it, as well as "freeze" a machine and only
store a snapshot of it during weekends, lowering the costs even more.

All these scenarios are made possible by DevOp automation and powerful online IDE like VSCode or Theia.
