# Domestic robot example

The Domestic robot example is from the *Jason* book, available in https://github.com/jason-lang/jason/tree/master/examples/domestic-robot . The description is reported as follow:

> "A domestic robot has the goal of serving beer to its owner. Its mission is quite simple, it just receives some beer requests from the owner, goes to the fridge, takes out a bottle of beer, and brings it back to the owner. However, the robot should also be concerned with the beer stock (and eventually order more beer using the supermarket’s home delivery service) and some rules hard-wired into the robot by the Department of Health (in this example this rule defines the limit of daily beer consumption)."

In this repository, the example is configured to be used with the [*logging component*](https://github.com/yan-elena/agent-logging) for a **Multi-level explainability framework** for engineering and understanding BDI Agent Systems.

After running the system, the generated log files of the system can be found in the `/log` folder, and the `.json` files can be loaded into the [*explanation web application*](https://yan-elena.github.io/agent-explanation/) to explore the generated narrative of the example at different levels of abstraction.
