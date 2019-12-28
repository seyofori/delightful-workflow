**user experience and user interface design plan (if applicable)**
* ensure design is created for the various screen types to be supported.
* [Link to UI/UX workflow prototype](https://yourlinkhere.com)

**engineering and implementation plan**

*for each step*
* briefly state the step, 
* define any implementation details right under the step. 
* details can be expressed in pseudocode, but the closer to the real implementation, the better.
* when unsure about how to implement a particular feature, isolated experiments and demos can prove very helpful.
* these codesandbox experiments and demos for individual steps can be linked right under the step.
* and then the various tests that will be written for that particular implementation detail
* eg:
```
  ...

5. Create sign in input validation function
   - validate (string username, string password):
        handle invalid input errors
        sanitize the input
        return sanitized input

    - unit tests
         - returns correct value for correct input
         - handles invalid input well. 
            - empty username or password ...  
            - undefined, null, invalid non-alphanumeric characters, 

   ...

```
NB: don't forget; implementing the UI is part of the steps to be indicated here. details should be provided as well. pseudocode or even real code in codesandboxes are appreciated.


 *after all the steps have been listed*
- integration tests


- end-to-end tests


