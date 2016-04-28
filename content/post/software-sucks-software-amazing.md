+++
date = "2016-04-22T18:04:36-07:00"
title = "Software Sucks. Software is Amazing."
Categories = ["Code"]
Tags = ["DevOps", "Software", "Infrastructure"]

+++

When I joined O'Reilly Media, I quickly took advantage of the freely available books. I loaded up my Safari queue with a wide array of titles and the best intentions of learning all the hip technologies du jour. But as with most jobs, and life in general, the desire to learn new skills outside your daily needs is often overrun by the core concerns and critical tasks of work. So one of my thoughts after the sudden dismissal from O'Reilly Media, was, "Hooray! Free time to learn things!"

Infrastructure-as-code is one of most important and revolutionary pieces in modern operations engineering. But unfortunately it didn't exist when I was a sysadmin, prior to my career path heading down the developer route. It seemed like a great place to start.

Puppet (née Labs) is one of the major players in the infrastructure-as-code/config management arena. In addition to having a great number of friends who use Puppet software, I also know quite a few Puppet staff and the company is headquartered in my hometown of Portland, Oregon – so getting help would be easy.

## Enter the Puppet Learning VM

One of Puppet's education tools is the [Puppet Learning VM](https://puppet.com/download-learning-vm), a virtual machine loaded with Puppet Enterprise Server, Puppet Agent and a host of other tools, preconfigured to help you quickly learn the Puppet software.

After downloading the sizeable (~3GB) VM and importing it into Virtual Box, I began Puppet's series of lessons called quests. But I quickly ran into a number of hurdles, beginning with some failed Puppet Enterprise services.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Me: &quot;I&#39;m gonna learn some stuff w/ the <a href="https://twitter.com/puppetize">@puppetize</a> learning VM!&quot; 😀<br>PE: Nope. 😈<br>Me: Oh right, sysadmining. 😡 <a href="https://t.co/LY08OfQQGr">pic.twitter.com/LY08OfQQGr</a></p>&mdash; Jason Yee (@gitbisect) <a href="https://twitter.com/gitbisect/status/722570427730669568">April 19, 2016</a></blockquote>

Searching [ask.puppet.com](https://ask.puppet.com/questions/query:learning%20vm/) and dusting cobwebs off my recollection of how to manage services on CentOS resolved the problem, but my educational bliss was swiftly interrupted when the VM crashed.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Me: OK <a href="https://twitter.com/puppetize">@puppetize</a> Learning VM, I got your services fixed! Let&#39;s get back to learning! 👍<br>PLVM: Oh yeah? Fuck you! 😈 <a href="https://t.co/0jKEgvU5pt">pic.twitter.com/0jKEgvU5pt</a></p>&mdash; Jason Yee (@gitbisect) <a href="https://twitter.com/gitbisect/status/722812921370296320">April 20, 2016</a></blockquote>

A couple Puppet team members quickly jumped in and pointed me to the solution. But once again, the Puppet Learning VM found a new way to hinder me.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Me: Fresh new <a href="https://twitter.com/puppetize">@Puppetize</a> Learning VM, let&#39;s do this! 🤘<br>PLVM: Sharing passwd on login screen is totally insecure! 😈 <a href="https://t.co/y3BOdCMDYw">pic.twitter.com/y3BOdCMDYw</a></p>&mdash; Jason Yee (@gitbisect) <a href="https://twitter.com/gitbisect/status/722839382189817857">April 20, 2016</a></blockquote>

One of the nice advantages of having a virtualized learning environment is that it's easy to simply delete a VM instance and import a fresh one.

## Learning more than Puppet

Despite the rough start, I should note that the Puppet Learning VM has been fantastic and I've learned quite a bit about the Puppet software in a very short amount of time. But beyond that, my experience taught me just how amazing Puppet and other configuration management tools are. 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">FWIW, I&#39;m not bashing <a href="https://twitter.com/puppetize">@puppetize</a><br>Getting software to work perfectly on all systems is hard<br>My struggle underscores why conf mgmt is amazing</p>&mdash; Jason Yee (@gitbisect) <a href="https://twitter.com/gitbisect/status/722853032086544384">April 20, 2016</a></blockquote>

Software sucks because it's hard. It's especially hard to distribute software and get it to run perfectly on all systems... even when it's in a VM.

Infrastructure-as-code doesn't just allow engineers to track software configurations and distribute them, but it also allows systems to be defined in declarative ways. Declaring the desired run state has given us the ability to build systems that monitor failed services, I/O issues and any deviation from the declared state, and in many cases can automatically remediate the problems.

And in that regard, software is _amazing_!

<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
