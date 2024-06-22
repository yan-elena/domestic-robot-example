# Domestic robot example

The Domestic robot example is from the *Jason* book, available at https://github.com/jason-lang/jason/tree/master/examples/domestic-robot . The description is reported as follows:

> "A domestic robot has the goal of serving beer to its owner. Its mission is quite simple, it just receives some beer requests from the owner, goes to the fridge, takes out a bottle of beer, and brings it back to the owner. However, the robot should also be concerned with the beer stock (and eventually order more beer using the supermarket’s home delivery service) and some rules hard-wired into the robot by the Department of Health (in this example this rule defines the limit of daily beer consumption)."

In this repository, the example is configured to be used with the [*logging component*](https://github.com/yan-elena/agent-logging) for a **Multi-level explainability framework** for engineering and understanding BDI Agent Systems.

After running the system, the generated log files of the system can be found in the `/log` folder, and the `.json` files can be loaded into the [*explanation web application*](https://yan-elena.github.io/agent-explanation/) to explore the generated narrative of the example at different levels of abstraction.

## Narrative of the domestic robot example:

Once the `supermarket`, `owner` and `robot` files are uploaded, the user can select the agent with which he wants to view the narration.

<img src="https://github.com/yan-elena/domestic-robot-example/assets/78790594/556bb0f3-45b4-43f0-ad9d-39858bbeedf0" width=70%>

Through the web application, it is possible to explore the different levels of explanation of the various agents in the system:

### Narrative at the Implementation Level
A detailed and technical level that follows Jason's operational semantics and reasoning cycle.

<img src="https://github.com/yan-elena/agent-explanation/assets/78790594/11728883-60e6-4dc9-aa81-26cbe472cec2" width=50%>

### Narrative at the Design Level
A higher level that narrates the agent's decisions following its cognitive abstraction according to the Belief-Desire-Intention model.

<img src="https://github.com/yan-elena/agent-explanation/assets/78790594/e9131856-fcb1-4eb7-96d8-3254be392411" width=50%>

### Explanation of a specific event
Some events are associated with an explanation of a previous event that caused it.

<img src="https://github.com/yan-elena/agent-explanation/assets/78790594/eac6a6e1-23a4-4d9d-8c13-c0c0b2eb2126" width=70%>
