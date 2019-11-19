Roadmap:
###

1. First steps.
   - User stories:
     - As postgres administrator i want to know which activities are going right now.
     - As postgres administrator i want to konw wich datatabase are in database.
   - Features sketch:
     - list of activities
     - backend duration for list of activities
     - filter list of activities by database
     - sorting list of activities by duration
     - list of databases
     - show database size
     - live refresh
     - autorization
   - Design
     - sketch of activities list
2. Nest steps.
   - databases 
     - checkout to table list
     - show circle diagram by space
   - tables
     - sizes 
     - locks
     - active queries
     - indexes
     - checkout to list of indexes
   - indexes
     - sizes
     - usage
     - code 
     - filter by table
   - activities
     - control (pg_terminate_backend)
   - locks
     - reasons of locks
     - kill the query, which is the reason of locking
   - vacuum
     - statistics
   - queries
     - plans 
    - explain 
  - helps 
