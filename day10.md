# Readings

**Spring guide: Accessing Data with JPA**



**Baeldung: Comparing repositories **

- Simply put, every repository in Spring Data extends the generic Repository interface, but beyond that, they do each have different functionality.

- findAll() – get a List of all available entities in database
- findAll(…) – get a List of all available entities and sort them using the provided condition
- save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch
- flush() – flush all pending task to the database
- saveAndFlush(…) – save the entity and flush changes immediately
- deleteInBatch(…) – delete an Iterable of entities. Here, we can pass multiple objects to delete them in a batch


## Things I want to know more about.

- Effective Styling within an MPA
