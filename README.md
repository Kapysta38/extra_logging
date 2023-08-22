# extra_logging
Library complementing the `logging` library for quick customization of logging in the project
## Installing

`pip isntall extra_logging`

# Quick start

```python
import extra_logging as ex_log

log = ex_log.Logging('app', 'log.log', max_bytes=ex_log.kb * 10).get_log

for i in range(100):
    log.info(i)

```