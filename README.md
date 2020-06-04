# signalk-libschema
Library for handling Signal K plugin schema definitions.

## Constructor

To obtain a new Schema instance for a particular schema file, you should
use the __createSchema()__ factory method.

__createSchema(*filename* [, *dictionary*)__

Create a Schema instance from *filename*.

If *dictionary* is specified, then it must be a 
