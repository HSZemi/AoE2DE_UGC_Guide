*Written by: KSneijders (MrKirby)*

---

## What is the Parser used for?

When working with scenarios you might have had to do some repetitive tasks many times. Some common examples are: placing units in a grid, copying triggers for all players or creating many similar effects. These sorts of problems can easily be done using a programming language!

It's also a perfect tool to be able to tweak your minigames or maps. Let's say you have a minigame where you get 10 gold for each unit you kill. And later you find out, it's quite over powered, so you want to change all effects to 5 gold per unit. If you used the parser to setup all triggers and effects and you had a variable like: `gold_per_unit = 10` you can just change it to 5, rerun the code and you fixed it in one go!

The parser works by reading a scenario file, and converting it to objects in the programming language `Python3`. You can then use the functions available to easily add or change things in the scenario. A couple example functions: `add_unit`, `add_trigger`, `copy_trigger_per_player` and many, many more!

Check out the [official AoE2ScenarioParser documentation] for the most up-to-date installation guide and how to get started!

[official AoE2ScenarioParser documentation]: https://aoe2scenarioparser.readthedocs.io/en/master/getting_started.html

## Python Installation

For the most up-to-date installation guide, you should check out the official `AoE2ScenarioParser` docs. 

Which can be found [here].

[here]: https://aoe2scenarioparser.readthedocs.io/en/master/install.html

---

You can install the project using pip:

    pip install AoE2ScenarioParser

If you don't know what pip is, you can read about it in [their documentation]

[their documentation]: https://pip.pypa.io/en/stable/