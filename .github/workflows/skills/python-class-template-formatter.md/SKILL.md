---
name: python-class-template-formatter
description: 
  This skill formats a class template according to a specific convention. It ensures that the class definition, attributes, methods, and docstrings follow a consistent structure, making the code more readable and maintainable.
---

Sample of a good output:

```python
class ClassName:
    """
    A brief description of what the class does.

    Attributes:
        attribute1 (type): Description of attribute1.
        attribute2 (type): Description of attribute2.
    """

    def __init__(self, parameter1: type_hint, parameter2: type_hint):
        """
        The constructor for the ClassName class.

        Args:
            parameter1 (type): Description of parameter1.
            parameter2 (type): Description of parameter2.
        """
        self.attribute1 = parameter1
        self.attribute2 = parameter2

    def method1(self, parameter: type_hint) -> return_type:
        """
        Description of what method1 does.

        Args:
            parameter (type): Description of parameter.

        Returns:
            return_type: Description of the return value.
        """
        # Method implementation
        pass

    def method2(self) -> return_type:
        """
        Description of what method2 does.

        Returns:
            return_type: Description of the return value.
        """
        # Method implementation
        pass
```
