# SpringBoot-and-Rest
REST API will provide a quote of the day, a word of the day, and Magic 8 Ball services.

## User Stories
Your project must implement the following user stories:

- As an API user, I want to request a random quote so that I can expand my knowledge.

- As an API user, I want to request a random word and its definition so that I can expand my vocabulary.

- As an API user, I want to request a random answer to a question so that I can be entertained.

Quote API
The Quote API provides a quote of the day service and must implement the following route:

- URI: /quote

- Method: GET

- Request Body: None

- Response Body: Quote

The **Quote** model should include the following:

- id

- author

- quote

## Word API
The Word API provides a word of the day service and must implement the following route:

- URI: /word

- Method: GET

- Request Body: None

- Response Body: Definition

The **Definition** model should include the following:

- id

- word

- definition

## Magic 8 Ball API
The Magic 8 Ball API provides a magic 8 ball service and must implement the following route:

- URI: /magic

- Method: POST

- Request Body: Question

- Response Body: Answer

    - The POST request for the Magic 8 Ball endpoint should include a user-provided question.

The **Answer** model should include the following:

- id

- question

- answer

