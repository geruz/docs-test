## Repositories

RepositoryBase is a base class for all repositories. It provides a pool connection to the database.
All repositories should extend this class.
All methods in the repositories should be async and return a promise.
All methods in the repositories should use context as first argument.
