1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

As I go through the options one by one, I recognize that some of the options are weaker. If we manually run them locally before pushing, the fallback is that sometimes we may simply just forget, inconsistent enviroments as it is done locally, and not everyone on the team may do it. The other option "Run them all after all development is completed" is not much better. Running them after all the development is completed causes problems such as finding bugs too late which are harder to track, and debugging is much harder when theres more code to review.

I think the best choice would be witnin Github Actions that runs whenever code is pushed. This ensures consistentcy of running tests, finding bugs and errors in the code in the earlier development stages, and saves times as we don't need to manually run tests each time we push our code.  


2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No.













