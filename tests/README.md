This folder contains one example, "definition" file of each type of component that can be imported to a PiLR project directly.  Each folder contains a README file that describes the specifics of what should be configured on the project after you import the definition.

## Overview of definitions
For any individual project, there are a several project "components" that you can add and configure simply by importing a component "definition".  This definition is just a JSON object.  At the top most level, you can directly and individually import definitions of the following types:

```
Instrument - (instrument)
Tool - (tool)
Dashboard panel - (dashboard)
Dataset - (dataset)
Participant variable - (pt_variable)
File tag - (file_tag)
Project period - (period)
```

You also could import an entire "Project definition", which would contain one or multiple of the top level components above.

Within a top level component, the definition can specify other top level components to create or content specific to that component.  The list below outlines the available definitions you can next within a parent defintion:

```
Instrument
- dataset
- settings

... TBD
```
