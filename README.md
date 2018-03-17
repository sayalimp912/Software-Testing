boehm_eece6032
==============

Software Testing and Quality Assurance Term Project (Fall 2015)

I decided to perform the following operations on ‘Fat Free CRM’ which was our system under test – It is an open source, customer relationship management (CRM) platform built using Ruby on Rails framework. (http://fatfreecrm.com/)

Software Testing Goals - 
1. Conducted manual software inspection on Dashboard, Tasks, Leads and Users module.
2. Used a static analyzer such as Rubocop to perform static analysis on the SUT and the results were further analyzed to determine any correlation with results from manual inspection.
3. Used Metric Fu, a compilation of several tools to help find areas of code that could be improved 
4. Code Coverage - I used SimpleCov to determine, analyze, and interpret structural coverage of the system.
5. I precisely generated automated test cases and results using Selenium, which is a suite of tools to automate web browsers. Our focus was to test the GUI and present a concise analysis of the same. I used Capybara which is acceptance test framework for web application.

Quality Assurance Goals - 
1. Rack-Mini-Profiler is a tool used for finding bottlenecks of your applications. It does a live speed analysis of how long it took for the request to be processed and how much of that time it was doing various renderings, database queries and DOM loading. 
2. I performed analysis on the Github commits to generate repository statistics using GitStats.
