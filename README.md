1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

As I go through the options one by one, I recognize that some of the options are weaker. If we manually run them locally before pushing, the fallback is that sometimes we may simply just forget, inconsistent enviroments as it is done locally, and not everyone on the team may do it. The other option "Run them all after all development is completed" is not much better. Running them after all the development is completed causes problems such as finding bugs too late which are harder to track, and debugging is much harder when theres more code to review.

I think the best choice would be witnin Github Actions that runs whenever code is pushed. This ensures consistentcy of running tests, finding bugs and errors in the code in the earlier development stages, and saves times as we don't need to manually run tests each time we push our code.  


2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)
No.


3) What is the difference between navigation and snapshot mode?
The difference between the snapchat and navigation mode is that the snapchat mode anaylzes the page in its current state of the page without reloading, whereas the navigation mode analyzes the page from the moment it loads. The snapchat mode is useful for component testing or specific testing for parts of the web app. The navigation mode is useful for full-page audits which tests features such as layout shift and page load performance. In conclusion navigation mode is best used for testing a full user experience whereas snapshot mode is best for auditing a specific component after interaction.


4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.













