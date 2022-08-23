# Goals

1. Be able to create programs through GUI.
   * Allow Assignment
   * Variable declarations
   * Basic Arithmetic & String Manipulation operators
   * Schema based read writes
   * Function Creation
   * Reusable Snippets, like Macros
   * Classes
   * Pure / Stateless Functions
   * Stateful Functions
   * Conditionals
   * Recursion / Function Calls
     - Prefer bounded recursion over this, but to be provided for easy of use.
   * Basic Boundedness Checks
   * Models to connect to Data Sinks & Taps
     - Can be extended to carry permission info to trace permission info like in taintdroid
     - Models should auto generate optimised or nearly optimised queries to corresponding data source
     - Model target storage code can be done through plugin like manner.
   * Allow accessor control (like public and private, but need to redefine from cloud native perspective)
   * Allow Adapters to connect to language specific code snippets. Think of how NodeJS / Java use Native C code.
   * Build Cost functions to predict resource usage and as well for potential billing
   * Allow conversion of fabcode to EVM / other blockchain bytecodes if all used components are compatible.
   * Think of future possibility of writing a verified compiler of the same.
2. Provide way to test logic.
3. Allow Flag Based nodes, like Some node executed only if DEBUG flag on.
4. Allow breakpoints and debugging of logic / traceability.
5. Allow undoable actions, for long term ability to build saga pattern.
   * Can be achieved through counter transactions instead of undo. Makes life simpler.
6. Versioning of Logic and Data to provide provenance.
   * Provide way to specify version matching between data and logic to provide higher degree of control and consistency.
7. Build orchestration tools on top of core layer
8. Build Monitoring and distributed tracing for all logic written in the ecosystem.
   * Easy to build using notion of request id & parent request id.
9. Allow tagging logic chunks as idempotent and build fault tolerance on idempotent components automatically through replayability.
10. Allow Node Live previews in the future.

