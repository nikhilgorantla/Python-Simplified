# The urllib.request.urlopen\(\) Method

The urllib.request.urlopen\(\) method opens the given URL. For HTTP and HTTPS URLs, it returns an http.client.HTTPResponse object that may be read like a file object.

```
import urllib.request

url = "https://en.wikiversity.org/wiki/Python_Programming/Internet_Data"
try:
    page = urllib.request.urlopen(url).read()
    page = page.decode("UTF-8")
except Exception as exception:
    print(str(exception) + " reading " + url)
    exit(1)

for line in page.split("\n"):
    print(line)
```

Output:

```
<This page's source HTML...>
```



