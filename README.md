1) Automated tests should be fitted within a Github action that runs whenever code is pushed as this process will automatically run for every push. Doing so will provide consistant feedback on any possible errors as one continues add on to the build.

2) If looking to just see if a function is returning the correct output, I would not use an end to end test to check as using one would waste a lot of time checking the entirety of your code when you just need to check one function.





