## 1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
- Within a Github action that runs whenever code is pushed 
- Manually run them locally before pushing code
- Run them all after all development is completed

I would fit tests into a Github action that runs whenever code is pushed so that tests are run automatically whenever code is pushed(continuous integration), and errors are caught early on. 

## 2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)
no, use unit test 

# Explore: Check your understanding 
## 3. What is the difference between navigation and snapshot mode?
Snapshot takes one instance of the current state of the page and gives a report based on that, while navigation gives load times for different parts of the page and gives a report based on that. 

## 4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
We could make sure the page is following basic search engine optimization advice even more(SEO); for example, the site doesn't have a meta description. In terms of accessibility, make sure the html element has a lang attribute. For best practices, make sure the message channel doesn't close before a response is received. 

