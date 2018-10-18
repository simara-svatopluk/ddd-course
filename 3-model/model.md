# Model

All of us model every day.
A friend tells us a joke, we imagine the situation and if we model it as is intended, we find the situation funny.
A customer wants to have a new functionality and while he speaks, we try to imagine what does the customer wants - we model.

## Modeling

Modeling is a process that aims to capture key concepts of reality.
And modeling means also to ignore anything irrelevant, and this is as same important as capturing relevant concepts.

TODO IMAGE

The reality contains everything important, all details, everything we know and much more that is hidden.
We are not able to describe the whole reality and describing it is not really our goal.

We can tell stories that cover important concepts of reality.
We can convert the stories to use cases.
To explain deaplier these use cases we can use diagrams, images.
And in the end, we convert all this knowledge into a source code.

> **Not only Data**
> 
> Most of us are great in modeling data. But what about modeling responsibilities, modeling behavior? Let's focus also on these aspects of modeling for a better result.

## Validation

Once we have the abstract model in our heads and it is also described by documentation and in the diagrams, we should validate it.
Validation is done by domain experts who have to confirm or refute the abstract model.

TODO IMAGE reality is modeled by an abstract model and abstract model is validated by reality

Validation and modeling are bounded continous processes.
The project evolves, our domain understanding evolves, so the model evolves as well.

## Model and Language

Modeling is a difficult process, it is difficult to say where to start, how deep should we go, what should we focus on, what to omit.
But we have one great tool that helps us, the language.

Domain expert stories, terms that they repeat over and over again, all these are good starting points.
The language also shapes the way we think, and when we think in domain terms, the abstract model is likely to be close to the reality.

# Implementation model

There are always many ways how to implement the abstract model.
The implementation can be made in smooth and simple or in overcomplicated way. It is surprisingly easy to end up with a complicated solution.
But we will take the effort and introduce strategies and concepts that will help us simplify the model.

## Concrete associations

Associations between objects are naturally two-ways. But it's really difficult to think, work and program with two-ways associations. We try to simplify them if it's possible.

Imagine you are modeling a product and it's price. We can imagine the price as a sticker on the product. The sticker is on the product and of course, the product is labeled with the sticker. So it seems there have to be a two-way association betwenn price and sticker objects.

But does the price sticker care where is it stuck? We may find it irrelevant, so the association from product to price can be single-way. This simple change make thinking about product and price easier, and also the resulting code will be much easier.

Two-way association is difficult to maintain and we should use it only where it is absolutely necessary.







