# libProvider v0.1

[See Changelog](https://github.com/ghabxph/libProvider/blob/master/changelog.md)

libProvider is a very simple class provider that automatically injects dependency of any class for any project.
The trick is possible through PHP's Reflection Class.

libProvider automatically determines the dependency of a class through its constructor.

libProvider has some limitations through
  * libProvider can not inject non-class dependency (primitive data type like int, string, etc)
      * To be implemented on v0.1.1
  * libProvider can not inject interfaces
      * To be implemented on v0.1.2
  * libProvider can not inject classes with circular dependency
      * I really think that it's impossible to do it... So please, don't attempt
      
libProvider is inspired from Laravel's Service Container

Created with love, by ghabxph
