# Introduction

(WIP) FabCode is set to provide GUI based programming of business logic for building cloud native services.
Later to be extended to allow building edge applications too.
Development of FabCode is to consist of few core layers.

1. FabCode DSL
2. FabCode GUI
3. FabCode Adapters
4. FabCode Schedule 
5. FabCode Monitor
6. FabCode Orchestrate
7. FabCode Tracer
8. FabCode Audit

# Usage

Work in progress, to be updated as project develops

# FabCode DSL

FabCode DSL will be a DSL & its interpreter + type checker. This DSL will allow describing a workflow / 
state machine which represents target business logic. DSL will support elements like conditions, loops,
function calls. DSL can provide bounded time execution given no recursion or recursion with bound variant.
DSL will have optional metadata to be used for help with rendering on GUI layer, this metadata can be kept totally 
separate.
Long term outlook of FabCode is to allow Saga pattern & Microservice Architecture.

# FabCode GUI

FabCode GUI will target a look very similar to UE Blueprint. This will be used on top of FabCode DSL and used to
write business logic.

# FabCode Adapters

FabCode will allow adapters, for example HTTP Fetch Adapter can be made to make API calls, this way functionality
or business logic that is not written in FabCode remains accessible to FabCode. A generic way is to be also
provided to write Custom Adapters, so any end usage can be achieved.

# FabCode Schedule

FabCode Schedule will allow writing of recurrent Logic basis either a trigger or time based policy.

# FabCode Monitor

FabCode Monitor is to provide a way to assess resource consumption, usage and failure / success rates of logic written.

# FabCode Orchestrate

FabCode Orchestrate is to provide an orchestration layer to auto scale up and down resources required to serve 
business logic at desired load.

# FabCode Tracer

FabCode tracer is going to allow distributed tracing cross business logic written in FabCode ecosystem.

# FabCode Audit

FabCode Audit module will be the optional provenance layer to allow Audit of Data Change happening through FabCode.