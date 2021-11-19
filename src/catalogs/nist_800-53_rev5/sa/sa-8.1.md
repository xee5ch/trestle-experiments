# sa-8.1 - \[System and Services Acquisition\] Clear Abstractions

## Control Statement

Implement the security design principle of clear abstractions.

## Control guidance

The principle of clear abstractions states that a system has simple, well-defined interfaces and functions that provide a consistent and intuitive view of the data and how it is managed. The elegance (e.g., clarity, simplicity, necessity, and sufficiency) of the system interfaces, combined with a precise definition of their functional behavior promotes ease of analysis, inspection, and testing as well as the correct and secure use of the system. The clarity of an abstraction is subjective. Examples reflecting application of this principle include avoidance of redundant, unused interfaces; information hiding; and avoidance of semantic overloading of interfaces or their parameters (e.g., not using a single function to provide different functionality, depending on how it is used). Information hiding, also known as representation-independent programming, is a design discipline to ensure that the internal representation of information in one system component is not visible to another system component invoking or calling the first component, such that the published abstraction is not influenced by how the data may be managed internally.
