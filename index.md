---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
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