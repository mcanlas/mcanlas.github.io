* not about eliminating state
  * without state, there would be no useful programs
* about moving stateful computations to predictable boundaries (like keeping db value classes stateless and moving all db operations to a single layer)
* state manipulation is moved to the stack (where no one cares about manipulation, it's automatic)
* with tail recursion, stack depth is cheap
* functional without tail recursion (perl!) is an odd fit; religious belief only w/ no practical benefit
* more scala, but if you think of functions as objects (as they are in scala), they have very regular interfaces (apply)
* fold left as a method of iteration (i.e. divorcing iteration from action/verbage)
* tail recursion is a venn diagram (i.e. specific type of recursion where the implementation cost COULD BE cheap)
* given that "all languages are turing complete", it is a necessity that accessibility is a critical factor of language use/adoption
* about deferring your commitments (error handling, optionality, structured mutability), and isolation/compartmentalization of functions vs side effects
