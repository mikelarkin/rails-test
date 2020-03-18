# A little background information

This code exercise is intended to evaluate your software engineering skills but also give you an introduction into the types of problems we solve at Bold Penguin. Your solution will be evaluated based on the ability to produce intended results, cleanliness, adherence to best practices, maintainability, and readability. You should write code like you would if this were an actual assignment. You do not need to gold plate your solution, but we are looking for something more than a script. Ideally your solution would demonstrate your understand of object-oriented principles and best practices.

# Helpful Information
There are 2 important entities that work together in commercial insurance.

**Carriers** create commercial insurance products. Commercial insurance carriers selectively choose which industries they sell commercial insurance policies to. That is to say, depending on the industry a business is in, you may find that some commercial insurance carriers won’t sell you a policy. For example, FarmInsure will underwrite a policy if the business’s industry is peanut farming, but will not sell a policy if the industry is building construction.

**Agents** work with the carriers in order to sell & service commercial insurance policies. Agents are licensed at the state level and have special agreements with any carriers they work with. So for example, Frank Farmer can be licensed in Kentucky and Ohio and has an agreement with FarmInsure. This means Frank Farmer can sell you a FarmInsure policy if your business operates in Ohio, but not if your business operates in Florida. Because Frank Farmer only has an agreement with FarmInsure, he can’t sell products for Homestate or Statewide.

## Getting Started

**Please DO NOT push your work to a public fork on GitHub!**

Clone **this** repo, please DO NOT make a fork of it.

```bash
$ git clone https://github.com/mikelarkin/rails-test.git
```

You'll need to setup your development environment with Ruby. This step is platform dependent, so you'll need to figure it out yourself.

```bash
$ bundle install        # Install dependencies
$ rails db:reset        # Create the local database with test data
```

## How this will be evaluated

For clarity, this is how your code sample will be evaluated:

| Criteria | Percentage |
|----------|-----|
| Object-Oriented Design Principles | 30% |
| Readability & Maintainability | 30% |
| Best Practices & Naming Convention | 20% |
| Ease of Testing Solution & Correctness | 20% |

## Submission guideliness

Be sure that all existing tests pass, and any new classes added have meaningful unit tests.
The use of Minitest is intentional, please do not change the testing framework.

`rails test`

Ensure that you have at least 80% code coverage

`open coverage/index.html`

Ensure that you adhere to the rails_best_practices

`rails_best_practices`

Ensure that you run brakeman to find any security-related issues

`brakeman`

**Please DO NOT push your work to a public fork on GitHub!**

Using the command below, create a git bundle of your changes and send it to frank@boldpenguin.com with the subject line `[AGENT_MATCH] <your name>`.

```bash
$ git bundle create your_name.bundle master
```
