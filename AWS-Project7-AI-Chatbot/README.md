# AI-Powered Chatbot with Amazon Lex, Bedrock, S3, and RAG

## Overview
This project is an AI-powered chatbot built using Amazon Lex and Bedrock. The chatbot leverages Retrieval-Augmented Generation (RAG) to enhance responses with relevant data from an S3 knowledge base. AWS Lambda is used for business logic and API interactions.

## Technologies Used
- **Amazon Lex** – For building and deploying the conversational interface.
- **Amazon Bedrock** – For leveraging foundational AI models to enhance chatbot responses.
- **Amazon S3** – For storing and retrieving knowledge base data.
- **AWS Lambda** – For handling backend logic and API calls.
- **Retrieval-Augmented Generation (RAG)** – To improve chatbot responses by fetching relevant information.

## Features
- **Natural Language Understanding (NLU)**: Uses Lex to process user queries.
- **AI-Enhanced Responses**: Bedrock provides contextual AI-driven replies.
- **Data Augmentation**: RAG improves response accuracy with real-time knowledge retrieval from S3.
- **Serverless Deployment**: Lambda functions manage logic and API requests.
- **Scalability**: Built using AWS services for seamless scaling.

## Architecture
1. **User Query**: The user interacts with Amazon Lex.
2. **Lex Processing**: Lex processes the query and invokes Lambda.
3. **Knowledge Retrieval**: The Lambda function queries S3 using RAG to fetch relevant information.
4. **AI Response Generation**: Bedrock refines the response with AI capabilities.
5. **Final Response**: The chatbot replies to the user with an intelligent and context-aware response.

## Setup Instructions
### Prerequisites
- AWS account with permissions for Lex, Bedrock, S3, and Lambda.
- AWS CLI installed and configured.

### Deployment Steps
1. **Create an Amazon Lex bot**:
   - Define intents and utterances in the Lex console.
   - Configure fulfillment with Lambda.
2. **Set up an Amazon S3 bucket**:
   - Upload relevant documents for knowledge retrieval.
3. **Deploy AWS Lambda functions**:
   - Write and deploy a function to handle requests and fetch data from S3.
4. **Integrate Amazon Bedrock**:
   - Use Bedrock to enhance responses with AI capabilities.
5. **Enable RAG (Retrieval-Augmented Generation)**:
   - Implement logic in Lambda to retrieve relevant context from S3.
6. **Test and Deploy**:
   - Train the chatbot and test interactions.
   - Deploy for production use.

## Usage
- Users can interact with the chatbot via a web or mobile interface.
- The chatbot processes queries, retrieves relevant data, and responds intelligently using AI-enhanced capabilities.

## Future Enhancements
- **Multi-turn Conversations**: Enhance contextual understanding.
- **Integration with DynamoDB**: Store user interaction history for personalized responses.
- **Support for Additional AI Models**: Expand AI capabilities with different Bedrock models.

## Author
**Javier Davis**

## License
This project is licensed under the MIT License.

