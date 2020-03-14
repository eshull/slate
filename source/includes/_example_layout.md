# Main Header
<!-- this denotes the main tab navigation on the left side of web page -->
## Secondary Header ONE
<!-- This denotes first layer under the main header on the left side of the web page -->
<aside class="success">I am writing HTML here with code inside of it: <code>&lt;api = Kittn::APIClient.authorize!&gt;</code> finished code and now back to html.</aside>

```ruby
require 'script'

ruby_stuff = Ruby::APIClient.authorize!('things')
ruby_stuff.things.delete(2)
```

```python
import python_library

python_stuff = python.authorize('ssssssss')
python_stuff.python.delete(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -X DELETE
  -H "Authorization: letmein"
```

```javascript
const javascriptThing = require('javascriptThing');

let api = javascriptThing.authorize('knock_knock');
let max = api.javascriptThings.delete(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "deleted" : ":("
}
```
### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

## Secondary Header TWO
<!-- This denotes first layer under the main header on the left side of the web page -->
<aside class="notice">Using class notice to make this blue,I am writing HTML here with code inside of it: <code>&lt;api = Thing::APIClient.authorize!&gt;</code> finished code and now back to html.</aside>

```ruby
require 'another_script'

more_ruby_stuff = Ruby::APIClient.authorize!('things')
more_ruby_stuff.things.delete(2)
```

```python
import python_library

python_stuff = python.authorize('ssssssss')
python_stuff.python.delete(2)
```

```shell
curl "http://example.com/api/kittens/2"
```

```javascript
const anotherJavascriptThing = require('javascriptThing');

let api = anotherJavascriptThing.authorize('knock_knock');
let max = api.anotherJavascriptThings.delete(2);
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "deleted" : "record"
}
```
### HTTP Request

`DELETE http://example.com/things/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID that you want to delete