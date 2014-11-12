utils
=====
1. data-migration
   Ridiculously simple Data Migration utility using dbunit and ant.
   How to use:
   a. Update source and target db properties in build.properties
   b. Update source and target dbunit datatypeFactory based on db types. Refer dbunit documentation for the name class names
   c. List table names to be migrated in the export.sourcedb target section. By default all tables will be migrated. Schema name can also be specified as an attribute in dbunit tag. Refer dbunit documentation for more details
