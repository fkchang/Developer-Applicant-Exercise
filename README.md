# Web Developer Applicant Exercise

To be considered for a developer position at [Hedgeye](http://www2.hedgeye.com), you must successfully complete these steps [**](#footnote)

**Please note:** your code will be tested on Ruby 1.9.2.  If we need a browser to test, it will be the latest version of Chrome, Firefox, Internet Explorer, and/or Safari.

1. Fork this repository
2. In the *why_hire_me* directory
    * Add a file `cover_letter.txt` with cover letter type verbiage.
    * Add a file that describes one of your preferred development tools (editor, desktop app, etc.) and why you use it (max 3 paragraphs)
    * Fill out the questionnaire.txt and commit it
    * Anything else we should know
3. In the *simple_refactoring_exercise* directory you will find some Ruby code that needs to be refactored.
    * An rspec spec is provided
    * Please [refactor](http://www.refactoring.com) the implementation.  Clarity, and duplication a given, flawed implementation also likely
    * Please note: feel free to change the specs, but they should all be passing when you turn in your code.
    * Leave a note what you refactored and why.  Calling specific smells and specific refactorings recommended.
4. In the *simple_public_timeline* directory, please create a simple web app (use the Ruby framework of your choice. Suggestion: Sinatra is good for a tiny app like this) that looks close to the middle column in logged out state of http://twitter.com/public_timeline
    * A headline with "Recent Public Tweets"
    * A smaller headline "What everyone on Twitter is talking about"
    * Displays 20 entries from twitter's public timeline.  Use the data/API of your choice
        * For each entry, show:
            * image profile on the left
            * a "stack" on the right including a link to the users profile, followed by the tweet text on the same line.  Below that the relative time of the tweet (i.e. 1 minute ago) and source attribution (i.e. "via Twitter for Android")
            * Barebones style adequate.  No need for nice css, text wrapping.
    * Provide the previously described view in 2 ways
      1. have the route "/" retrieve the twitter data on the server side and then render
      2. have the route "/via_js" retrieve the twitter data with Javascript and render it after the document loads
    * Required
        * `.rvmrc` and `Gemfile`
        * at least 1 spec
    * Optional (Extra Credit)
        * Comprehensive specs
        * More/Nicer Styling
        * More things that look like the original
    * Tips
        * Do use gems, and Javascript libraries.  
        * If you are Ruby, Javascript and web development savvy, it shouldn't take you that long.  A sample implementation, sans specs, is less than 100 lines of text total.
        * Optional stuff at the end. Don't get caught up on styling, that's what designers are for.
6. Commit and Push your code to your fork
7. Send a pull request, we will review your code and get back to you.  If your GitHub profile does not include your name, please include your name in the pull request.



<a name="footnote"></a>** The awesome idea of github pull request as
job application task was previously done by [Integrum](http://integrumtech.com) [here](https://github.com/integrum/job-application)
