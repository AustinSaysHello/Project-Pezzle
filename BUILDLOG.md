# BUILD LOG

## September 22, 2023

* In doing some research, if I plan to build out components using anything other than Google analytics, I'll either have to pay for an account, ask for a developer account, or host it myself. If I pay for hosting, I might as well pay for the service, although it could be cheaper.
* Here's what I've thought to far about this:
  * I could just bite the bullet on this and try with google, or a free alternative like cloudflare or posthog
  * If I wanted to self host, I could get free credits on AWS, Google, Oracle, Azure, Linode, or Digital Oceans
  * Upon further research, it's probably even easier if I used a container service instead of a whole VPS. AWS has one, docker and github both have free ones, probably the easiest thing to do.
* For now I think I'll just start with Posthog, I like the look of their product and their community looks very indie focused. I'll start looking into the container hosting so I can try with Plausible next.

# September 26, 2023

# Before Dev

* Been working a little more on crystal ball and other activities like blog posts, but I've been doing market research on this one and been trying to set up the environment
* Issue with trying to test analytics libraries when I'm not really using them commercially so I don't want to pay, free trials are pretty generous but not a long term solution. Could fork over the scratch since none of them are not that expensive but wanted to look into them first

# After Dev

* Considered self hosting since a lot of them are open source, I tried using docker and google cloud run but kept running into issues. Might try digital ocean next but want to get started on main dev in the mean time and not get lost in the weeds of environment set up
* Decided to start with Posthog as an analytics lib since they have a generous free tier and are pretty popular, also they're cloud based so minimal set up on my end, also going to start with working with alpine.js since it's a simple and popular library, I enjoyed working through the example and using in a different project of mine
* I was able to sign up for posthog and add here in replit right away, and it's already tracking events so that seems straightforward. It actually autocaptures more than I was expecting so that's great. Going to start working with the custom events library and seeing how that meshes with the Alpine codebase.