# Social_Net_18

# NoSQL Challenge: Social Network API

  ## Table-of-Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Feedback](#feedback)




# [Installation](#table-of-contents)
To get started with the social network API, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running

        npm install

3. Set up a MongoDB database and provide the connection details in the configuration file.
4. Run the command npm start to start the server and sync the Mongoose models with the MongoDB database.

<!-- # [Walkthrough Video](#table-of-contents) 
Please watch the following walkthrough video that demonstrates the functionality of the social network API: `Link to Video` -->

# [API Usage](#table-of-contents)
## [Users](#table-of-contents)

    GET /api/users: Retrieves a list of all users in the database. The response is in a formatted JSON format.

    POST /api/users: Creates a new user in the database. Provide the necessary user details in the request body.

    PUT /api/users/:userId: Updates an existing user in the database. Provide the user ID in the URL parameter and the updated user details in the request body.

    DELETE /api/users/:userId: Deletes a user from the database. Provide the user ID in the URL parameter.

## [Thoughts](#table-of-contents)

    GET /api/thoughts: Retrieves a list of all thoughts in the database. The response is in a formatted JSON format.

    POST /api/thoughts: Creates a new thought in the database. Provide the necessary thought details in the request body.

    PUT /api/thoughts/:thoughtId: Updates an existing thought in the database. Provide the thought ID in the URL parameter and the updated thought details in the request body.

    DELETE /api/thoughts/:thoughtId: Deletes a thought from the database. Provide the thought ID in the URL parameter.

   ## [Reactions](#table-of-contents)
    POST /api/thoughts/:thoughtId/reactions: Creates a reaction to a thought. Provide the thought ID in the URL parameter and the necessary reaction details in the request body.

    DELETE /api/thoughts/:thoughtId/reactions/:reactionId: Deletes a reaction from a thought. Provide the thought ID and the reaction ID in the URL parameters.

## [Friend List](#table-of-contents)

    POST /api/users/:userId/friends/:friendId: Adds a friend to a user's friend list. Provide the user ID and the friend ID in the URL parameters.

    DELETE /api/users/:userId/friends/:friendId: Removes a friend from a user's friend list. Provide the user ID and the friend ID in the URL parameters.

# [Acceptance Criteria](#table-of-contents)
The social network API meets the following acceptance criteria:

- The server starts successfully, and the Mongoose models are synced to the MongoDB database upon invoking the application.

- The API provides formatted JSON responses for GET routes related to users and thoughts when accessed through tools like Insomnia.

- The API allows successful creation, updating, and deletion of users and thoughts in the database when tested using POST, PUT, and DELETE routes in Insomnia.

- The API enables the creation and deletion of reactions to thoughts and the management of a user's friend list when tested using POST and DELETE routes in Insomnia.

## [License](#table-of-contents)
This project is licensed under the MIT License.

  ## [Feedback and Questions](#table-of-contents)

  To contact me please utilize the provided links below:

  [GitHub](https://github.com/skye143)
  
  [LinkedIn](https://www.linkedin.com/in/skye-h-988a7a221)

  [Email](mailto:skyeheredia@gmail.com)