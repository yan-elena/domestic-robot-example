# Domestic robot example

The Domestic robot example is from the *Jason* book, available at https://github.com/jason-lang/jason/tree/master/examples/domestic-robot . The description is reported as follows:

> "A domestic robot has the goal of serving beer to its owner. Its mission is quite simple, it just receives some beer requests from the owner, goes to the fridge, takes out a bottle of beer, and brings it back to the owner. However, the robot should also be concerned with the beer stock (and eventually order more beer using the supermarket’s home delivery service) and some rules hard-wired into the robot by the Department of Health (in this example this rule defines the limit of daily beer consumption)."

In this repository, the example is configured to be used with the [*logging component*](https://github.com/yan-elena/agent-logging) for a **Multi-level explainability framework** for engineering and understanding BDI Agent Systems.

After running the system, the generated log files of the system can be found in the `/log` folder, and the `.json` files can be loaded into the [*explanation web application*](https://yan-elena.github.io/agent-explanation/) to explore the generated narrative of the example at different levels of abstraction.

## Narrative of the domestic robot example - things to try out:

Once the `supermarket`, `owner` and `robot` files are uploaded, the user can select the agent with which he wants to view the narration.

<img src="https://github.com/yan-elena/domestic-robot-example/assets/78790594/59dde0f8-8248-4957-bb1d-dcb6055d41dc" width=50%>

Through the application, it is possible to explore the different levels of explanation of the various agents in the system.
An interesting use of the application is to exploit the search bar to filter, for instance, all the desires of an agent:

<img src="https://github.com/yan-elena/domestic-robot-example/assets/78790594/89ab342c-b088-4eab-bc3f-cd6b85abc8dc" width=50%>

or to explore the life cycle of a particular desire or event:

<img src="https://github.com/yan-elena/domestic-robot-example/assets/78790594/a6fc8079-315d-48e3-a630-6c50e5e984b6" width=50%>
