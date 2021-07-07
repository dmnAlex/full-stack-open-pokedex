# Exercise 11.1

- Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google. <br>
There are a lot of options presented for the task. For python linting purposes the most common tool seems to be Flake8. Its is easy to install, configurate and integrate with most common IDE. As for testing framework, pytest is considered to be common, easy, flexible and powerful tool.
Building step seems to be usually done by CI framework.

- What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google! <br>
Another commonly used alternatives are: Travis CI, Circle CI, GitLab CI, Azure Pipelines. They all share a lot of similarities and is hard to pinpoint any differences between them unless you try it yourself.

- Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision? <br>
As it was mentioned before, the choice depends on the scale of the application, and on the fact if a specific hardware resources needed. Considering a team of 6 people cloud based environment would probably be better suited for the task. 