# Back-end developer

The back-end job involves, but is not limited to, developing and maintaining
our cloud micro services written in Go and  Java - that includes technologies
such as AWS Lambda functions, MySQL and MongoDB. The job also needs critical
thinking in order to make the best and most scalable decisions.


## Requirements

- Java
- Golang
- Git


## Coding test

To attend to this positions you must deliver the two tests below.


### Golang

Create and deploy an AWS Lambda function using the AWS SAM toolkit and API Gateway
with the following capabilities:

- Receive a POST request with a JSON containing random data in the format described
in the net section, return 203 if ok or 500 on error
- Respond to a GET request returning metadata about the previous requests

**POST request format**

```
{
    "type": ("text" | "number"),
    "data": ( "RANDOM TEXT" | RANDOM NUMBER)
}
```

*Examples:*

A text example:

```
{
    "type": "text",
    "data": "Lorem ipsum dolor sit amet, consectetur adipiscing elit,\nsed do eiusmod tempor incididunt ut labore et dolore\nmagna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.\nDuis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
}
```

And a number example:

```
{
    "type": "number",
    "data": 3.141516
}
```


**GET request**

You must pass a URL parameter to specify the type of data you want to receive
the metadata, you are free to choose the metadata returned, but must have at least
one field different per type.


### Notes

You should persist the data or part of the data received in a database of your choice.


### Good luck

Now keep reading the README file to know how to return your results and
what should not be done.
