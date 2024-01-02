# ![Intro to Full Stack Development - Frameworks and Libraries](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to define the three components of a full stack: front-end, back-end, and database.

## What are frameworks and libraries?

Frameworks and libraries are vital software development tools and key components of full-stack development. They leverage pre-written code to help accomplish common tasks without having to start from that work from scratch.

Libraries and frameworks are not programming languages; they are are just code written using existing languages.

## Why do we use frameworks and libraries?

They can help us by:

- Simplifying complex tasks by *abstracting* them. This boosts developer productivity and development speed.
- Many frameworks and libraries are widely used and have been tested by many other developers. This typically means that they're more reliable than custom-coded solutions.
- This same community is also a huge asset for troubleshooting and problem-solving.

These are just a few examples of the benefits. While it's possible to build full-stack applications without using frameworks or libraries, it would make the work more tedious and cause the scope of our work to massively increase. In many cases, we would be left to recreate the functionality present in existing libraries or frameworks from scratch.

> 📚 *Abstraction* is the process of hiding technical complexity and details not fully relevant to solving a given problem. It allows programmers to interact with complex systems at a simplified level without having to understand the underlying details.

## The differences between frameworks and libraries

Frameworks and libraries are similar but do differ in key ways. Libraries handle specific tasks - like working with dates, formatting strings, and presenting UI elements. They don't enforce how the overall application is structured or behaves.

Frameworks provide a foundation on which you build and organize your application. They'll typically provide a set of conventions to help standardize development, which means different applications built using that framework will largely look the same (for example, they'll have a similar directory structure).

This analogy from [freeCodeCamp](https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/) may further your understanding:

> A library is like going to IKEA. You already have a home, but you need a bit of help with furniture. You don't feel like making your table from scratch. IKEA allows you to pick and choose different things to go in your home. You are in control.
>
> A framework, on the other hand, is like building a model home. You have a set of blueprints and a few limited choices when it comes to architecture and design. Ultimately, the contractor and blueprint are in control. And they will let you know when and where you can provide your input.

tktk Hunter, it'd be good if we had an asset here since we're lifting this from freeCodeCamp so that we have a GA contribution to this.

## The differences between different types of frameworks

Frameworks tend to come in one of two distinct varieties: opinionated and unopinionated.

### Opinionated

Opinionated frameworks encourage or even enforce a particular way of doing things. Put another way, they prefer ***conventions*** over ***configuration***. This has a few pros and cons.

#### Pros

- **Rapid development**: Setup and configuration are typically minimized. Apps can be built from the start with sensible defaults configured, making it easier to start a project. Developers skilled in an opinionated framework can build features at an accelerated velocity.
- **Consistency**: Developers have fewer decisions to make due to enforced conventions. Because of this, the differences between code written in the same framework tend to be minimal. This can make it easier for multiple developers to work together on teams or get onboarded to work more quickly.
- **Best practices**: Configuration can be complicated and error-prone - opinionated frameworks try to do that work so you don't have to. Additionally, much of the code in an opinionated framework has been critiqued and honed by the community of developers that use it, making it the best it can be.
- **Debugging and community support**: Because there is less customization, developers are less likely to encounter unique errors. This can make it easier to find solutions to problems or get help from the community that exists around the framework.

#### Cons

- **Learning curve**: Developers are required to learn and follow a rigid structure prescribed by the framework.
- **Difficulty of customization**: Customization is often necessary, and accomplishing this can be more complicated than in an unopinionated framework.

### Unopinionated

Unopinionated frameworks invert the patterns of opinionated frameworks.

#### Pros

- **Flexibility**: Unopinionated frameworks provide the freedom to choose the best path to solve a problem.
- **Ease of customization**: Unopionated frameworks are ideal for projects that require significant customization or when an established convention is unhelpful.
- **Lightweight**: Unopinionated frameworks often only include the minimal parts necessary for a project.

#### Cons

- **Inconsistency**: The lack of conventions can lead to inconsistencies in the same codebase introduced by multiple developers working on the same project or development approaches changing over time.
- **More decisions**: More decisions have to be made by a development team, which can slow down meaningful development.
