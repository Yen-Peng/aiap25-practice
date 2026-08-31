---
name: python-function-template-formatter
description: 
  This skill formats a function template according to a specific convention. It ensures that the function definition, parameters, and docstrings follow a consistent structure, making the code more readable and maintainable.
---

Sample of a good output:

``` python
def function_name(parameter1: type_hint, parameter2: type_hint) -> return_type:  
    """
    Brief description of what the function does.
    
    Detailed description explaining the purpose of the function, 
    how it works, and any other relevant information if necessary.
    
    Args:
        parameter1 (type): Description of the first parameter.
        parameter2 (type): Description of the second parameter.
        
    Returns:
        return_type: Description of the return value.
    """
    # Function body
    result = parameter1 + parameter2
    final_result = result * 2
    return final_result

```
