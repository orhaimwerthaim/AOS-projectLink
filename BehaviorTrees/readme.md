# BehaviorTrees
"[BehaviorTrees](https://arxiv.org/pdf/2005.05842) (BTs) were invented as a tool to enable modular AI in computer games,
but have received an increasing amount of attention in the robotics community in the
last decade. With rising demands on agent AI complexity, game programmers found
that the Finite State Machines (FSM) that they used scaled poorly and were difficult to
extend, adapt and reuse.
In BTs, the state transition logic is not dispersed across the individual states, but
organized in a hierarchical tree structure, with the states as leaves. This has a significant
effect on modularity, which in turn simplifies both synthesis and analysis by humans
and algorithms alike. These advantages are needed not only in game AI design, but also
in robotics, as is evident from the research being done."

## How can We use BT in the AOS?
- To describe an executable plan/policy (maybe to support offline planners).

- To describe the expected behavior of the module (describe the PLP as BT).


## BT Tools (we can work with) 
- [Behavior3editor](https://github.com/behavior3/behavior3editor/)  is open-source software for an online BT graphical editor, which is output can be exported and imported in JSON format. 
- https://www.behaviortrees.com/ is a website, which is based on an altered version of Behavior3editor and can be used to create/edit/export/import behavior trees.
- VS Code has a plugin to create BT in a simple way and to graphically present it, but it does have a JSON export/import which is a drawback.  
## Examples
[BTpickPLP](https://github.com/orhaimwerthaim/AOS-projectLink/blob/main/BehaviorTrees/BTpickPLP.jpg) is a BehaviorTree that describes a pick module and contains all of the PLP data.
[BTpickPLP.json](https://github.com/orhaimwerthaim/AOS-projectLink/blob/main/BehaviorTrees/BTpickPLP.json) is the tree exported JSON.
The example was created using https://www.behaviortrees.com/
