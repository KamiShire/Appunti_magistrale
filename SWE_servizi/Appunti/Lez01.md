# Lection 01 - Introduction
Build large software system is complex, the complexity is faced by two approaches:
 * __Abstraction__
 * __Models__

## Abstraction
>  process of formulating generalized ideas or concepts by extracting common qualities from specific examples.

In the course will be explored two main abstraction used to manage large and complex distributed systems: 
* Service: __structural__ abstraction. Expose functions. *Service Oriented Architecture (SOA)*
* Process: __behavioural__ abstraction. Implement services. *Business Process Management (BPM)*

## Models
> A representation of the system under analysis that answers as the system does for a given set of questions

> All models are in simulacra, that is, simplified reflections of reality, but, despite their inherent falsity, they are nevertheless extremely useful

## Service-Oriented Architecture

### Service-oriented Computing (SOC)
It's a design paradigm for distributed systems, and implemets a **service-oriented** system which is a network of **services**. Services comunicate through messages. These messages are tagged with **operation** like methods in OOP.

SOC respond to different needs:
1. Integration of different applications (each one using different data protocols)
2. Need to discover at runtime where the services are located (**dynamicity**)
3. Need for **structured interaction**, logical ordere of action. 

