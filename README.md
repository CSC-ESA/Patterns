# CSC-Patterns
This is the homepage for the Architectural Security Patterns library of the Belgian [Cyber Security Coalition](https://cybersecuritycoalition.be/).

**To go to the Patterns Library environment, click [here](https://csc-esa.github.io/Patterns/html)**

## Viewpoints
|  | **Threat viewpoint** | **Control viewpoint** |
|---|---|---|
| **Concerns** | Understand threats against an architecture, and define how these threats can be countered.  | Understand which elements in the architecture realize the controls |
| **Abstraction level** | Logical | Logical |
| **Layers** | All layers | All layers |
| **Aspects** | Active structure | Active structure |
| **Allowed elements** | * Business event (threat event)<br>* Application component<br>* Node<br>* Communication network<br>* Requirement<br>* Triggering relationship<br>* Association relationship<br>* Influencing relationship<br>* Specialization relationship | * Business event (threat event)<br>* Application component<br>* Node<br>* Communication network<br>* Requirement<br>* Triggering relationship<br>* Specialization relationship |
| **Modeling conventions** | * We use triggering relationships between active structure to model interaction<br>* We use nesting between active elements and communication networks (zones)<br>* We use directed association relationships to link controls to threats (from control to threat)<br>* We use directed association relationships to link an element to a threat (from element to threat) <br>* We use specialization relationships to link detailed requirements to high-level requirements.  | * We use triggering relationships between active structure to model interaction<br>* We use nesting between active elements and communication networks (zones)<br>* We use realization relationships between active structures and requirements to model which structure realizes a certain requirement<br>* We use specialization relationships to link detailed requirements to high-level requirements. <br>* Each triggering relationship must have two properties: 'Protocol' and 'Authentication', and the values must be completed. <br>* Each triggering relationship must have the label expression: [${property:Protocol}][${property:Authentication}] |

## Methodology

## Contributing

## References
1. [Open Security Architecture](https://www.opensecurityarchitecture.org/cms/library/patternlandscape)
2. [securitypatterns.io](https://securitypatterns.io)
