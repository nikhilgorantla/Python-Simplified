# The json.loads\(\) Method

The json.loads\(\) method converts a given JSON string to a corresponding Python object \(dict, list, string, etc.\).

```
import urllib.request
import json

title = ""
url = "https://wikimedia.org/api/rest_v1/metrics/pageviews/per-article/en.wikiversity/all-access/user/" + \
    "Python_Programming%2fInternet_Data" + \
    "/daily/2016100100/2016103100"

try:
    page = urllib.request.urlopen(url).read()
    page = page.decode("UTF-8")
except Exception as exception:
    print(str(exception) + " reading " + url)
    exit(1)

print("Page Views")
dictionary = json.loads(page)
for item in dictionary["items"]:
    print("%s: %s" % (item["timestamp"], item["views"]))
```

Output:

```
<Page views for this page for 2016 October ...>
```



