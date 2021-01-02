# Welcome!

This C# template lets you get started quickly with a simple one-page playground.

```C# runnable
using System;
using System.Collections.Generic;
using System.Linq;

class Hello 
{
    static void Main() 
    {
        List<string> animalNames = new List<string> {"fawn", "gibbon", "heron", "ibex", "jackalope"};

        IEnumerable<string> longAnimalNames = 
        from names in animalNames 
        where names.Length >= 5 
        orderby names.Length
        select names;

        Console.WriteLine(longAnimalNames);
    }
}

```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced C# template](https://tech.io/select-repo/386)
