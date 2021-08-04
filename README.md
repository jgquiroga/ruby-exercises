# ruby-exercises
Exercises in Ruby

Cucumber for BDD

Install

1) Create a "Gemfile" with cucumber and rspec dependencies

2) Install packages:

```cmd
    bundle install
```

3) In the first time, Initialize cucumber directory

```cmd
    cucumber --init
```

The last step, creates the folder "features"

Example 1:

1) Create a Ghetkin feature file in "Features" called card_minimum.feature

2) Write the feature and one scenario
3) Execute cucumber:

```cmd
    cucumber
```

4) Create new steps definition in ruby called: "steps.rb" inside "step_definitions"

5) Copy the definitions created by cucumber in the file
6) Re run "cucumber" to see the results:

```cmd
    cucumber
```

