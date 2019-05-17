# devops-trial-day

Your mission, should you choose to accept it, is to deploy the world's worst application (in /deploy) to AWS.

It prints some technical jibberish and calculates bits of Pi. Don't ask why. Let's pretend it's what the client asked for 😂

How you deploy it is entirely up to you - you could use plain EC2, leverage some of the management features/primitives in AWS or go down the route of containers/serverless-style deployments.

At it's most basic, you should have a URL when you're finished that will serve up the index.php and the error.php files

The following bonus points are not exhaustive - feel free to go off script as long as the primary objective has been achieved. If you have some cool DevOps tricks up your sleeve show them off!

It's unlikely that you will have time to complete every one of these bonus points in time. Focus on a few of them that you're confident with.

Finally, this isn't really a test of having something that works perfectly and is production ready, we're more interested in what you've struggled with and what you've researched and learned to help you progress.

Going down a route and failing and then deciding that's the wrong way of doing things is also totally fine - explain how/why you've made your decisions at the end of the day in the debrief.

## Bonus points:

* Something that will autoscale in some way/survive load testing. We'll test it using apache bench.
* Availability zone failure survivability
* Caching that caches the application's output for the correct period of time
* SSL with an HTTP -> HTTPS redirect
* SSL that's encrypted right up to where you serve the application from
* Purchasing and configuring a domain to work with the app
* Centralised logs of some kind/somewhere to see what the application is doinng
* Dashboard showing application health and metrics
* Secure configuration at the network level
* Secure configuration at the software level
* Architecture diagram
* Automatic deploys when code is merged to master