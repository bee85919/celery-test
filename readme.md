# vsc terminal
python
from tasks import add
result = add.delay(4,4)
result.ready()
result.get()