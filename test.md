---
description: lalala
---

# Test

some content

## Some Heading 1

### Some Heading 2

#### Some Heading 3

\#\#\#\# Heading 4 does not work

* Bulleted list item 1
* other item 2
* and another...

1. Ordered list item 1
2. other item 2
3. and again another...

* [ ] Some task list
* [ ] that has checkbox
* [x] Completed!

```text
single line code block
```

```text
multi
line
code
block
```

{% code title="filename.js" %}
```javascript
// JavaScript code
console.log('SyntaxHighlight')
```
{% endcode %}

> ## Quote Heading 1
>
> ### Quote Heading 2
>
> #### Quote Heading 3
>
> some quote content

_Images are currently not available._

| Table title 1 | Table title 2 |
| :--- | :--- |
| content | another content |

{% hint style="info" %}
This is a hint
{% endhint %}

{% page-ref page="./" %}

{% api-method method="get" host="https://someservice.com" path="/v1/someapi/:query\_param" %}
{% api-method-summary %}
GET API Method
{% endapi-method-summary %}

{% api-method-description %}
Get some items from the list.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="path\_param" type="string" required=true %}
sample path parameter
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-headers %}
{% api-method-parameter name="header" type="number" required=false %}
sample header
{% endapi-method-parameter %}
{% endapi-method-headers %}

{% api-method-query-parameters %}
{% api-method-parameter name="query\_param" type="integer" required=true %}
sample query parameter
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=100 %}
{% api-method-response-example-description %}
The Continue response
{% endapi-method-response-example-description %}

```
Continue response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=101 %}
{% api-method-response-example-description %}
The Switching Protocols response
{% endapi-method-response-example-description %}

```
Switching Protocols response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=102 %}
{% api-method-response-example-description %}
The Processing response
{% endapi-method-response-example-description %}

```
Processing response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
The OK response
{% endapi-method-response-example-description %}

```
OK response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=201 %}
{% api-method-response-example-description %}
The Created response
{% endapi-method-response-example-description %}

```
Created response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=202 %}
{% api-method-response-example-description %}
The Accepted response
{% endapi-method-response-example-description %}

```
Accepted response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=301 %}
{% api-method-response-example-description %}
The Moved Permanently response
{% endapi-method-response-example-description %}

```
Moved Permanently response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=302 %}
{% api-method-response-example-description %}
The Found response
{% endapi-method-response-example-description %}

```
Found response body
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=303 %}
{% api-method-response-example-description %}
The See Other response
{% endapi-method-response-example-description %}

```
See Other response body
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://someservice.com" path="/v1/someapi" %}
{% api-method-summary %}
POST API Method
{% endapi-method-summary %}

{% api-method-description %}
Add new item to the list.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="form\_data\_param" type="boolean" required=false %}
sample form data parameter
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}

{% api-method-body-parameters %}
{% api-method-parameter name="body\_param" type="array" required=false %}
sample body parameter
{% endapi-method-parameter %}

{% api-method-parameter name="another\_body\_param" type="object" required=true %}
another sample body parameter
{% endapi-method-parameter %}
{% endapi-method-body-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% tabs %}
{% tab title="First Tab" %}
first tab content
{% endtab %}

{% tab title="Second Tab" %}
second tab content
{% endtab %}
{% endtabs %}

$$
y=x^2-2x+1
$$

_Files are not available too._

