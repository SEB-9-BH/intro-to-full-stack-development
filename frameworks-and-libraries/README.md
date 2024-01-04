# ![Intro to Full Stack Development - Frameworks and Libraries](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to define the three components of a full stack: front-end, back-end, and database.

## What are frameworks and libraries?

Frameworks and libraries are vital tools in software development. They leverage pre-written code to help accomplish common tasks without having to start from that work from scratch. They can help us by:

- Simplifying complex tasks by *abstracting* them. This boosts developer productivity and development speed.
- Many frameworks and libraries are widely used and have been tested by many other developers. This typically means that they're more reliable than custom-coded solutions.
- This same community is also a considerable asset for troubleshooting and problem-solving.

These are just a few examples of the benefits. While it's possible to build full-stack applications without using frameworks or libraries, it would make the work more tedious and cause the scope of our work to massively increase. In many cases, we would be left to recreate the functionality present in existing libraries or frameworks from scratch.

> 📚 *Abstraction* hides technical complexity and details irrelevant to solving a problem. It allows programmers to interact with complex systems at a simplified level without understanding the underlying information.

Libraries and frameworks are not programming languages; they are just code written using existing languages.

### The differences between frameworks and libraries

Frameworks and libraries are similar but do differ in crucial ways. Libraries handle specific tasks - like working with dates, formatting strings, and presenting UI elements. They don't enforce how the overall application is structured or behaves.

Frameworks provide a foundation on which you build and organize your application. They'll typically offer a set of conventions to help standardize development, which means different applications built using that framework will broadly look the same (for example, they'll have a similar directory structure).

This analogy from [freeCodeCamp](https://www.freecodecamp.org/news/the-difference-between-a-framework-and-a-library-bd133054023f/) may further your understanding:

>A library is like going to IKEA. You already have a home, but you need a bit of help with furniture. You don't feel like making your table from scratch. IKEA allows you to pick and choose different things to go in your home. You are in control.
>
> A framework, on the other hand, is like building a model home. You have a set of blueprints and a few limited choices regarding architecture and design. Ultimately, the contractor and blueprint are in control. And they will let you know when and where you can provide your input.

tktk Hunter, it'd be good if we had an asset here since we're lifting this from freeCodeCamp so that we have a GA contribution to this.

## The differences between different types of frameworks

There are many different types of frameworks, but they can be broadly categorized into two groups: opinionated and unopinionated.

### Opinionated

Opinionated frameworks encourage or enforce a particular way of doing things the framework prescribes. Put another way, they prefer ***conventions*** over ***configuration***. This has a few pros and cons.

#### Pros

- **Rapid development**: Setup and configuration are typically minimized. Apps can be built from the start with sensible defaults configured, making it easier to start a project. Developers skilled in an opinionated framework can build features at an accelerated velocity.
- **Consistency**: Developers have fewer decisions due to enforced conventions. Because of this, the differences between code written in the same framework are minimal. This can make it easier for multiple developers to work together on teams or get onboarded to work more quickly.
- **Best practices**: Configuration can be complicated and error-prone - opinionated frameworks try to do that work so you don't have to. Additionally, much of the code in an opinionated framework has been critiqued and honed by the community of developers that use it, making it the best it can be.
- **Debugging and community support**: Because there is less customization, developers are less likely to encounter unique errors. This can make finding solutions to problems or getting help from the community around the framework easier.

#### Cons

- **Learning curve**: Developers must learn and follow a rigid structure prescribed by the framework.
- **Difficulty of customization**: Customization is often necessary, which can be more complicated than in an unopinionated framework.

### Unopinionated

Unopinionated frameworks are the opposite of opinionated frameworks, allowing developers more freedom in their projects. Since these frameworks are the inverse of opinionated, they prefer ***configuration*** over ***convention***. Once again, this has a few pros and cons.

#### Pros

- **Flexibility**: Unopinionated frameworks provide the freedom to choose the best path to solve a problem.
- **Ease of customization**: Unopionated frameworks are ideal for projects that require significant customization or when an established convention is unhelpful.
- **Lightweight**: Unopinionated frameworks often only include the minimal parts necessary for a project.

#### Cons

- **Inconsistency**: The need for conventions can lead to inconsistencies in the codebase introduced by multiple developers working on the same project or development approaches changing over time.
- **More decisions**: More decisions have to be made by a development team, which can slow down meaningful development.
