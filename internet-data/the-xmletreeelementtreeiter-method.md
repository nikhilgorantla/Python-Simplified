# The xml.etree.ElementTree.iter\(\) Method

The xml.etree.ElementTree.iter\(\) method returns an iterator that loops over all elements in the tree, in section order.

```
import urllib.request
import xml.etree.ElementTree

url = "http://www.w3schools.com/xml/note.xml"
try:
    page = urllib.request.urlopen(url).read()
    page = page.decode("UTF-8")
except Exception as exception:
    print(str(exception) + " reading " + url)
    exit(1)

root = xml.etree.ElementTree.fromstring(page)
tree = xml.etree.ElementTree.ElementTree(root)

for element in tree.iter():
    print("%s: %s" % (element.tag, element.text))
```

Output:

```
<The XML elements in the page http://www.w3schools.com/xml/note.xml...>
```



