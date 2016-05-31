![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# Monkies!

> ***Note:*** *This can be a pair programming activity or done independently.*

Create a `Monkey` class in `lib/monkey.rb`, which has the following attributes:
* name - (a string)
* species - (a string)
* foods_eaten - (an array)

And the following methods:

* `eat(food)` - adds the food (a string) to the list of foods eaten
* `introduce` - introduces self, with name, species, and what it's eaten.

![monkey](http://thewondrous.com/wp-content/uploads/2015/04/funny-images-of-monkey.jpg)

## Goal

Run tests using `rspec`. Write code in a Monkey class to make the tests pass. When you first run the code you should get a big error message. When scrolling to the top it should say `uninitialized constant Monkey`.

### What is RSpec?

[RSpec](http://rspec.info/) is a tool for writing automated tests for programs written in ruby. We write tests in ruby (specifically `spec/monkey_spec.rb`), that describe what we expect to happen when we use our code.

Install it: `gem install rspec`

When we run the tests, it compares what our code does to what our tests expect, and tells us which pass and which fail.

### Solution

Checkout the branch `solution` for an example solution.

### Bonus

Uncomment the bonus tests in `spec/monkey_spec` and make them pass.

### Self Evaluation

During the previous exercise, rate your progress on a scale of 1-5 (5 being the highest) for the following criteria:

- **Persistence:** Do you handle frustration well? Do you independently pursue understanding?
- **Organization:** Do you thoughtfully implement best coding patterns and practices?
- **Collaboration:** Do you make an effort solve problems and share your ideas with others?
- **Communication:** Do you clearly convey your thoughts to others in illustrative and clear ways?
- **Self-compassion:** Do you make productive use of turning failures into learning opportunities?
- **Resourcefulness:** Do make an effort to compare and contrast new ideas with ones you already know? 