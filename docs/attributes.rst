Attributes
----------

..
    >>> from pyquery import PyQuery as pq

You can play with the attributes with the jquery API::

    >>> p = pq('<p id="hello" class="hello"></p>')('p')
    >>> p.attr("id")
    'hello'
    >>> p.attr("id", "plop")
    [<p#plop.hello>]
    >>> p.attr("id", "hello")
    [<p#hello.hello>]


Or in a more pythonic way::

    >>> p.attr.id = "plop"
    >>> p.attr.id
    'plop'
    >>> p.attr["id"] = "ola"
    >>> p.attr["id"]
    'ola'
    >>> p.attr(id='hello', class_='hello2')
    [<p#hello.hello2>]
    >>> p.attr.class_
    'hello2'
    >>> p.attr.class_ = 'hello'


