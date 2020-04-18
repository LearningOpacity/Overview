# High Level Design

## Overview
The Opacifier is broken into two components: Secure Gateway and Data Store. The secure gateway will provide a secure REST endpoint to clients which allows for making requests from a 3rd party data source. It will query the REST endpoint of the 3rd party source and pass the results back to the client. It will log each of the queries that it receives to the Data Store. The Data Store will simply be a database that the Secure Gateway can use for storing persistent data.

## Diagrams
### Component Diagram
![Component Diagram](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/LearningOpacity/Overview/PlanningPhase/doc/design/hld-component-diagram?changethistoupdate=1)