# libProvider

libProvider is a very simple class provider that automatically injects dependency of any class for any project.
The trick is possible through PHP's Reflection Class.

libProvider automatically determines the dependency of a class through its constructor.

libProvider has some limitations through
  * libProvider can not inject non-class dependency (primitive data type like int, string, etc)
  * libProvider can not inject interfaces (to be done on next version maybe...)
  * libProvider can not inject classes with circular dependency (I really think that it's impossible to do it... So please, don't attempt)

libProvider is inspired from Laravel's Service Container

Created with love, by ghabxph