These classes are authored/copied manually and provide support for intermediate 
compilation of autogenerated code that otherwise is not compiling satisfactorily.

Domain.java has dependencies on some autogenerated classes, so compilation order becomes tricky.

In general these are used to override autogenerated classes that are somehow insufficient.
Long-term goal is to eliminate all of these classes by properly achieving full autogeneration.

TODO move these classes to a more consistent directory tree!
