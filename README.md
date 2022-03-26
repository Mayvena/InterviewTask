# NuveiTask

Task:
The following json structure (example.json is attached) containing 2 important objects:

1. props which defines selected properties' values

2. meta which defines type of component, values, default value, description and label.

 

The task is to present components based on meta data..

The initial state should be the default value as per meta data definition.

Upon selecting new values, they should be updated in props object.

 

Under the form we expect 3 buttons :

     “Set Defaults” – it returns all controls to their default state according to meta.

     “Reset” – it returns all controls to their initial state ( from props)

     “Save” – Which shows (dialog or in html below form) same input json structure, but props represent state of the form.

