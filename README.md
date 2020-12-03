<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/django-owner-required.svg?maxAge=3600)](https://pypi.org/project/django-owner-required/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/django-owner-required.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/django-owner-required.py/actions)

### Installation
```bash
$ [sudo] pip install django-owner-required
```

#### Examples
```python
from django_owner_required.views import OwnerRequiredMixin

class MyView(OwnerRequiredMixin,...):
    def get_object(self):
        return ...
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
