This folder contains one example "component definition" file of each type of component that can be imported to a PiLR project directly.  Each folder contains a README file that describes the specifics of what should be configured on the project after you import the definition.

## Overview of definitions
For any individual project, there are a several project components and configuration content that you can add simply by importing a component "definition".  This definition is just a JSON object.  At the top most level of the JSON object, you will specify which type of definition it is, in the field "definition_type".  The available defintion types that can be imported are:

```
Instrument - (instrument)
Content for an instrument - (instrument_content) Requires addition field for "instrument_code".
Tool - (tool)
Content for a tool - (tool_content) Requires addition field for "tool_code".
Dashboard panel - (dashboard)
Dataset - (dataset)
Participant variable - (variable)
File handler - (file_handler)
Project period - (period)
Deployment template - (template)
Group categories - (group_category)
```

In addition to importing one of these components individually, you can import multiple of them by having the top level defintion type be `bundle`.  Within the bundle, you can specify arrays of sub-definitions.  View the bundle example for more details.

Every definition must be identified by specifying a `name`, `version`, and `code` in the top level JSON object.