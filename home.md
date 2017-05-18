---
title: Hello World
---


```javascript
//javascript
(function() {
    function hello(name) {
        alert(`Hello ${name}!`);
    }

    hello('World');
})();

```

```cs
//c#
using System;

static void Hello(string name) 
{
    Console.WriteLine($"Hello {name}!"); 
}

static void Main(string[] args) 
{
    Hello("World");
}
```

```sql
--SQL
CREATE PROCEDURE dbo.HelloWorld 
     @name nvarchar(50) AS
PRINT 'Hello ' + @name +'!'
RETURN (0)

EXEC dbo.HelloWorld @name = N'World'
```