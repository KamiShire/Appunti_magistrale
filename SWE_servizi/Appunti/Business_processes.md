# Business processes
Business process management is based on the observation that each product
that a company provides to the market is the outcome of a number of activities performed. Business processes are the key instrument to organizing these
activities and to improving the understanding of their interrelationships.

While at an organizational level, business processes are essential to understanding how companies operate, business processes also play an important
role in the design and realization of flexible information systems. These information systems provide the technical basis for the rapid creation of new
functionality that realizes new products and for adapting existing functionality to cater to new market requirements.

Business process management  in the 90s with Business Process Re-engineering (Hammer, Champy) where a new way of organizing  companies on the basis of business processes was proposed. 
They define a business process as a collection of activities that take one or more kinds of input and create an output that is of value to the
customer.
This definition underline the importance of input (_precondition_) and output (_postcondition_). 

## Definitions
### Business process
> Consists of a set of activities that are performed in coordination in an organizational and technical environment. These activities jointly realize a business goal. Each business process is enacted by a single organization, but it may interact with business processes performed by other organizations.

#### ISO9000
>A  Process  is  a  set  of  interrelated  or interacting  activities,  which  transforms inputs into outputs.

### Business Process Management
> Business  process  management  includes concepts,  methods,  and  techniques  to support   the   design,   administration, configuration, enactment, and analysis of business processes.

The basis of business process management is the explicit representation of business processes with their activities and the execution constraints between them. Once business processes are defined, they can be subject to analysis, improvement, and enactment.

### Business Process Management System
>Is a generic software system that is driven by explicit process representations to coordinate the enactment of business processes.
 
### Business Process Model
> A business process model consists of a set of activity models and execution constraints between them. A _business process instance_ represents a concrete case in the operational business of a company, consisting of activity instances. 

Each business process model acts as a blueprint for a set
of business process instances, and each activity model acts as a blueprint for a set of activity instances.

## Business Process Lifecycle
<div style="text-align: center">
<img src="./images/bp_life_cycle.png" alt="drawing" width="500"/>
</div>

Business process lifecycle consists of phases
that are related to each other. The phases are organized in a cyclical structure, showing their logical dependencies. These dependencies do not imply a strict temporal ordering in which the phases need to be executed.


### Design and Analysis
The business process lifecycle is entered in the Design and Analysis phase, in
which surveys on the business processes and their organizational and technical
environment are conducted. Based on these surveys, business processes are
identified, reviewed, validated, and represented by business process models.

Business process modelling techniques as well as validation, simulation,
and verification techniques are used during this phase. Business process modelling is the core technical subphase during process design.

### Configuration
Once the business process model is designed and verified, the business process needs to be implemented. It can be implemented by a set of policies and procedures that employees need to comply with. In this case the implementation is done without any support of business process managment system.

Otherwise, an implementation platform is chosen during the configuration phase.
The system needs to be configured according to the organizational environment of the enterprise and the business processes whose enactment it should control. This configuration includes the interactions of the employees with the system as well as the integration of the existing software systems with the business process management system.

Once the system is configured, the implementation of the business process needs to be tested (using traditional testing techniques). Once the test subphase is complete, the system is deployed in its target environment.


### Enactment
Business process instances are initiated to fulfill the
business goals of a company. Initiation of a process instance typically follows a defined event. 
 Process enactment needs to cater to a correct process orchestration, guaranteeing that
the process activities are performed according to the execution constraints specified in the process model.

Process monitoring is an impor-
tant mechanism for providing accurate information on the status of business
process instances. This information is valuable, for instance, to respond to a
customer request that inquires about the current status of his case.


### Evaluation
The evaluation phase uses information available to evaluate and improve business process models and their implementations.

### Administration and Stakeholders

## Process Choreography
The interactions of a set of business processes are specified in a process
choreography. The term choreography indicates the absence of a central agent that controls the activities in the business processes involved. 
 <hr/>

## Business Process Modelling Foundation


