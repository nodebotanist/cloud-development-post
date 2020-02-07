# Cloud Development: How moving your developer environment to the cloud can impact your workflow

Development environments: when you think of them, an individual laptop or desktop usually springs to mind; customized with months or years of library and driver installs, a favorite IDE and/or terminal-- a fingerprint for the developer that uses it on a daily basis. But as the world of software development moves more and more onto the cloud, we need to think about developer environments in ways that better fit the cloud-based way of doing things. This means the idea of the cloud-based development environment; the idea that the developer's physical machine is used as a tool to interact with the developer environment that is now a cloud instance.

Now all this isn't to say we want to take away the individualism of a developer's way of coding; luckily, most IDEs have already started to think in terms of the cloud-based development environment. VS Code has an ssh extension, virtually all terminal IDEs can be easily used on a cloud machine, etc. The point isn't to take away these quintissennial tools of the software development trade-- the argument being made is to essentially use the local machine as a virtual extension of the developer onto the development machine that is now in the cloud. 

Let's dive deeper into the abilities and benefits that using cloud-based development environments gives us.

## Debugging and the "works on my machine" problem

Debugging build and environment issues on a physical development machine can be a nightmare. The "works on my machine" problem is one that has plagued software development for the entire life of the profession. Between having to actually get your hands on the machine in question and walking through each possible environmental variable, debugging this way can get sticky, fast.

With cloud-based development environments, you can ensure two main things: that the machines in question have identical environments, and that other developers, no matter their geographical location, can access their teammates' machines to assist in debugging. The first premise of identical environments tends to eliminate nearly all cases of "works on my machine" because the code will run (or not) in the same way on any cloud-based development environment because there are fewer (in most cases zero) variables to consider between the environments. The second premise allows easier development by making collaboration easier; no matter where your colleagues are, you can access their development machine in the cloud and help debug remotely-- you could even use tools to clone their machine and start working from there!

Overall, the use of cloud-based development platforms allow you to isolate your team from issues that arise from myriad working environments, and increase debugging speed and teamwork by allowing easier access and replication of your team's development machines.

## Speeding up development with stronger, accesible machines

Sometimes the development machine you have just isn't the one you need-- your regular machine is being repaired, for instance, and so you're stuck on an older laptop with minimal hardware. This is where cloud-based development environments can really come into play-- changing physical machines doesn't change your development environment. Even though the hardware you're using to write the code may be sub-optimal, your build and deployment times won't be affected due to running on cloud machines that have as much power as you need. Once you've installed your IDE on your temporary machine, and tweaked your interface, it'll be almost like your regular machine isn't even in the shop (except it doesn't have the same cool stickers).

This can be useful even if the hardware you're on is ideal-- who wants to use all of their CPU for minutes at a time on a build when we can be writing the next feature (or checking Twitter)? Letting a cloud-based environment run all of your code-adjacent tasks allows you to more effectively use the hardware sitting in front of you.

## Cloud environments, connected services

There's a lot that goes into deploying a web application-- continuous integration, unit testing, linting...these are all manageable by services found easily online, and many of them have a free tier! But trying to utilize all of these with a local machine can be implausible, and integration with a git repository takes away a lon of flexibility to run these services when you want.

Being able to connect services like these to a cloud-based environment is not only easy in many cases, but allows these services to react to real-time changes in your working environment-- allowing you to see exactly what your new code is doing within seconds. Being able to more easily use cloud services in your development environment gives you an extra boost of efficiency and power when coding.

---

Overall, it can feel like you're giving up a modicum of control when moving to a cloud-based development environment. But the benefits are numerous and ever-growing as the paradigm of software development shifts further and further into the cloud. 

[CTA to use Coder here]