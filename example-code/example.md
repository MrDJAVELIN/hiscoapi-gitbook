# ⚙ Example

## Javascript

```javascript
const url = 'https://hiscoapi.djavelin.repl.co/api/gif/hug';

fetch(url)
  .then(response => response.json())
  .then(data => console.log(data.response))
```



## Python

```python
import requests

url = 'https://hiscoapi.djavelin.repl.co/api/gif/hug'

response = requests.get(url)
data = response.json()
print(data["response"])
```



### Output:

```
https://hiscoapi.djavelin.repl.co/gifs/hug/hug3.gif
```
