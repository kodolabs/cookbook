# Interactors

## Introduction

*Interactors* (also known as *Service Objects*) are the place for the application's business logic. They allow you to simplify your controllers and allow them to focus on what they are responsible for. A Interactor should encapsulate a single user task such as registering for a new account, placing an order, publishing post.

## Conventions

* Interactors go under the `app/interactors` directory.
* Interactor name should contain a verb (e.g. `Create`).
* Interactor should have only one public method (`#call`).
* Focus on readability of the `#call` method, keep it short, simple and clear.
* Put all business logic into private methods with a very clear, self-explanatory and meaningful names.
* Use [Organizers](https://github.com/collectiveidea/interactor#organizers)

## References

* [Interactor](https://github.com/collectiveidea/interactor)
