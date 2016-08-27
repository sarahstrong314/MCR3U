Domains and Ranges of Functions
-------

### Sets

A **set** is a collection of things. Sets are denoted using curly braces and can contain anything. The "things" inside sets are referred to as **elements**. 

We can put anything inside a set. For example, here is a set of animals: {elephant, panda, bunny}.

Unlike tuples, the order of the elements in a set do not matter. Also, if we write out a set with duplicate elements, we can remove them. For example, {penguin, llama, deer, penguin} can be simplified to {penguin, llama, deer}.
 
In this course we will mostly be working with set of numbers.

Some well-known sets of numbers have names, but they can also be written using set notation.

We can explicitly write out each element, and use ellipses (the "...") to mean "you get the idea" if the trend is clear.

For example, the set of natural numbers, denoted \mathbb{N}, is {1, 2, 3, 4, ...}. 

There is also the set of integers, denoted \mathbb{Z} for the German word for number, which is {... -3, -2, -1, 0, 1, 2, 3, ...}. 

To denote whether an element is contained in a set, we use the symbol \in, often pronounced "in". It is neither an "e" nor an epsilon. We can also use \notin to denote that an element is not contained in a set.

For example, 1 \in \mathbb{N}, 1 \in \mathbb{Z}, -1 \notin \mathbb{N}, 0.5 \notin \mathbb{Z}.

Sometimes we cannot explicitly write out the elements in a set. If this is the case, we can describe a pattern. We write out a general expression for the elements, then a colon or a pipeline, then the condition of the constants in the expression.

The set of rational numbers, denoted \mathbb{Q}, is {a/b : a,b \in \mathbb{Z}, b \ne 0}. We would read this as  "a over b where a and b is in the set of integers and b is not equal to 0".  Another way to think of this example is that \mathbbb(Q) contains all fractions in the form a/b where a and b are both integers and b is not 0.

The set of real numbers is denoted \mathbb{R} cannot be written in set notation like the others. 

\mathbb{N}, \mathbb{Z}, \mathbb{Q}, and \mathbb{R} are all **infinite sets** since they have infinitely many elements. Sets that have finitely many elements are called **finite sets**.

We can also use subscripts to denote a specific set greater than or less than a specific number. For example, \mathbb{Z}_\ge{0} is the set of integers greater than or equal to 0, and \mathbb{R}_{>0} is the set of real numbers greater than 0. 

We can combine sets using \cap and exclude elements using -. For example, {1, 2, 3} \cap {4, 5, 6} = {1, 2, 3, 4, 5, 6}, and {1, 2, 3, 4} - {1, 3} = {2, 4}.


### Domain and Range

The **domain** of a function is the set of values that the independent variable can be.
The **range** of a function is the set of values that the dependent variable can be.

Here are some examples of domains and ranges of common functions.

| | Domain | Range |
| --- | --- | --- |
| f(x) = x | \mathbb{R} | \mathbb{R} |
| f(x) = x^2 | \mathbb{R} | \mathbb{R} |
| f(x) = \sqrt{x} | \mathbb{R}_\ge{0} | \mathbb{R}_\ge{0} |
| f(x) = 1/x | \mathbb{R} - {0} | \mathbb{R} - {0} |
| f(x) = 2^x | \mathbb{R} | \mathbb{R}_{>0} |