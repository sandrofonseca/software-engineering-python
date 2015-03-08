# How to structure classes, modules and packages?

## How to structure a bigger program?

### OOP
* Design Patterns
* facade
* encapsulation of your interface: web gui cli
* refactoring

### Web
* Flask, Django
*

# How the rx project started:
(MR 2012)
1. Access to repository.
2. What is the rxncon data model?
3. Where is the main page template?
4. Where is the production code:
e.g.
looking at the Quick – where is the code responsible for input parsing, creating output for each button?
where reactions and contingencies are interpreted?
5. How large is the project (how to distinguish your code and default code generated by web2py, have you deleted any default code)?
6. Is it possible to split the production code and web2py (what is your opinion – I think it would facilitate testing, but may be too much work)?
7. Which parts of the code would you advise to start working with to get to know the code. Are there any independent fragments?
8. How did you test your code?
9. Do you measure the traffic on the web?


#### quality
A program that looks good from the outside (e.g. a shiny GUI or web interface) and has produced scientific results may seem flawless from a supervisors perspective. It may still be entirely rotten from the inside.

#### bugs piling up in legacy code
What to do with all bugs? I mean: that there was a see of bugs and small features to implement all around and it felt like runing in mad circles. One thing you touch causes three next problems 1 week of work for something that was planned for one day, and the pile of 'easy fixes' is pilling ...


#### nested loops

- What is the depth of the most nested loop / if statement?

