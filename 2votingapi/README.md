## Project 2: Voting API

## Installation (MacOS)
1. Clone Repository
2. `cd` into **2votingapi** directory
2. Run `swift build && .build/debug/2votingapi`
3. Go to an available route (listed below) to see JSON from CouchDB database

#### Routes
* CouchDB must be running
1. `http://localhost:8090/polls/list` - GET request to list all polls
2. `http://localhost:8090/polls/create` - POST request to create a new poll
3. `http://localhost:8090/polls/vote/:pollid/:option` - POST request to vote on an existing poll