# PyRepec

A python client for [RePEc API](https://ideas.repec.org/api.html).

Current Version: 0.0.1

Report any bugs by opening an issue here: (https://github.com/caps6/pyrepec)


### Usage

```python
from pyrepec import Repec

repec = Repec("TOKEN")

res = repec.get_org_authors("RePEc:edi:bdigvit")
```


### Installation

1. Installation using pip:

```bash
pip install pyrepec
```


### Methods

Featured methods:

- get_org_authors(org_id: str)
- get_author_data(author_id: str)
- get_authors_for_item(item_id: str)
- get_jel_codes(item_id: str)
- get_error(err_code: int)