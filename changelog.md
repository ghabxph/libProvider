# Changelog

## libProvider v0.1
  * Initial Release
     * Can instantiate almost any class, except the following
         * Classes' constructor that has primitive data type
             * Target to be implemented on v0.1.1
         * Classes that is dependent on an interface
            * Target to be implemented on v0.1.2
         * Classes that has circular dependency
             * This can never be done. 
