# Elasticsearch Postman Collection

Postman collection for Elasticsearch. Import in to Postman, create environment and set the required variables.
At a minimum you will need to set the {{url}} variable. This should include the base URL **and** the port number


# Variables used within the collection
### url
The base URL for your Elasticsearch instance or cluster. This needs to include the port number (if required), such as http://elasticsearch:9200
### index
The index in which you are performing operations
### alias
The alias in which you are performing operations
### repository
The repository in which to store snapshots
### snapshot
The name of the snapshot you are interacting with, or creating
### repository-location
The repository location, used when creating a new repo. This must match path.repo in your Elasticsearch settings or yaml file.
### remote-host
Currently only used in reindex, this is the remote server in which you are retrieving an index
### desitination-index
Currently only used in reindex, this is the name of the new index on the destination server