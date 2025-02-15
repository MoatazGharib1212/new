# ChatBot <img src="https://i.imgur.com/nSWBL7M.png" alt="LIFTA" width="42" />

Welcome to ChatBot! it's here to help you with your shopping.

## What is our ChatBot? <img src="https://i.imgur.com/Fb9YxRg.png" width="28" />

the ChatBot is a conversational AI system for an e-commerce platform that allows users to interact with a product catalog, ask complex queries, manage orders, and track deliveries.
## Who Should Care? <img src="https://i.imgur.com/1GAn0Ir.png" width="28" />

- Any online e-commerce platform onwer wants to take his website to a next level.

- Target Customers: Small to medium businesses needing digital marketing solutions, website development, and e-commerce services (e.g., startups, online stores, service-based businesses).
- Businesses or individuals needing international shipping solutions for imports and exports.

## Key Features <img src="https://i.imgur.com/yzknnL8.png" width="28" />

### Users Features <img src="https://i.imgur.com/hzABBQp.png" width="24" />

1) Product Catalog Interaction:
 - Allows users to browse and query a product catalog.
 - Handle basic queries like finding products based on specific criteria (e.g., price range, category, specifications).
2) Order Management:
 - Can manage orders (e.g., adding products to a cart, checking out).
 - Tracks order status, such as delivery times and shipping updates.
3) Delivery Tracking:
 - Tracks product deliveries and provides real-time updates on delivery status.
 - Responds to queries like "What is in my cart?" or "add Iphone 14 to my cart?"
4) Personalized Recommendations:
 - Provides product recommendations based on user preferences or past interactions.
 - Personalized suggestions for future purchases (e.g., “Here’s a laptop you might like based on your previous searches”).
5) Multi-turn Conversations:
 - Can engage in back-and-forth conversations, maintaining context across multiple exchanges.
 - Can handle tasks like adding items to a cart, checking out, and answering questions about those items all within one session.

### Admin Features <img src="https://i.imgur.com/tEvmlUx.png" width="24" />

1) External Data Integration (optional for Option 2 and 3):
 - Can pull data from external databases or APIs for real-time product availability, price changes, and other e-commerce data.
 - Supports persistent user sessions, remembering past interactions (e.g., previously viewed items).
2) Use of LangChain for Dialogue Management:
 - LangChain is integrated for modular query handling and managing complex conversations.
 - Can use memory management to retain context across multi-turn interactions.
 - Enables chaining of tools for various tasks (e.g., integrating with external APIs for stock and delivery data).
3) Performance Optimization:
 - Efficient in handling large product catalogs and datasets.
 - Quick response times, even with a high volume of data.
4) API Integration:
 - Integrates with commercial APIs (e.g., OpenAI GPT) or open-source LLMs (e.g., Hugging Face Transformers).
 - Supports integration with external tools for functionalities like SMS (via Twilio) or notifications.
5) Scalability:
 - Can scale to handle hundreds or thousands of products.
 - Efficient query processing for large datasets.
6) Error Handling and Edge Cases:
 - Handles edge cases gracefully (e.g., when a product is out of stock or a user asks about unavailable items).
 - Robust against unexpected queries (e.g., "Can I get oranges?" when out of stock).
 - Provides a user-friendly front-end interface (e.g., web or mobile app) for interacting with the chatbot.
7) Ease of Use:
 - Simple setup and execution, with easy-to-follow instructions for running the bot, especially for Option 1.
8) Complex Query Handling:
 - Capable of responding to complex, multi-turn conversations (e.g., "Find me laptops under $1000 with at least 16GB RAM").
 - Supports advanced queries involving various filters (e.g., price, availability, specifications).
 - Handles dynamic updates (e.g., product availability, delivery times).


## Devolpment Main Phases <img src="https://i.imgur.com/e1DBlTk.png" width="28" />

- *Phase 1:* In this Phase we used PHI-4 Model and HardCoded database in jason format to build the initial cahtbot
- *Phase 2:* We extended the ChatBot by loading SQL database rather than hardcoded dataset
- *Phase 3:* We could develop a complete front-end and back-end system for the chatbot, making it a fully deployable application.

## Phase 1:

- In this Phase we used PHI-4 Model and HardCoded database in jason format to build the initial cahtbot
- *[Colab NoteBook](https://colab.research.google.com/drive/1DfPu5WOCl8w90B7PTIGpDcaF_qB69vHH?usp=sharing#scrollTo=iWVdD2BxPB8s)*
- Results:

## Phase 2:

- In this Phase We extended the ChatBot by loading SQL database rather than hardcoded dataset
- *[Colab NoteBook](https://colab.research.google.com/drive/1DfPu5WOCl8w90B7PTIGpDcaF_qB69vHH?usp=sharing#scrollTo=iWVdD2BxPB8s)*
- Results:

## Phase 3:

- In this Phase We could develop a complete front-end and back-end system for the chatbot, making it a fully deployable application.
- *[FrontEnd code](https://colab.research.google.com/drive/1DfPu5WOCl8w90B7PTIGpDcaF_qB69vHH?usp=sharing#scrollTo=iWVdD2BxPB8s)*
- *[BackEnd code](https://colab.research.google.com/drive/1DfPu5WOCl8w90B7PTIGpDcaF_qB69vHH?usp=sharing#scrollTo=iWVdD2BxPB8s)*
  
## Setup Instructions <img src="https://i.imgur.com/DRfWA84.png" width="28" />

1. Clone the repository:
    
    ```bash
    git clone https://github.com/OmarGamal10/Lifta.git
    ```
    
2. Navigate to the project directory:
    
    ```bash
    cd Lifta
    ```
    
3. Install dependencies for both the backend and frontend:
    
    ```bash
    cd server
    npm install
    cd ../FrontEnd
    npm install
    ```
	
4. Create the database:
	- Run the database schema script in the lifta_schema.sql file in pgAdmin
	
5. Configure connection details:
    -  Create config.env file inside the server folder and configure connection details as follows:
    
	```
	NODE_ENV=development
	PORT=3000
	DATABASE_PASSWORD=your_database_password
	SECRETKEY=your_secret_key
	```
	
6. Start the backend server:
	
    ```bash
    cd server
    npm start
    ```
    
7. Start the frontend server:
    
	```bash
    cd FrontEnd
    npm run dev
    ```
    
8. Access the application at http://localhost:5173.
- 
## Future Features <img src="https://i.imgur.com/8i5qWJE.png" width="28" />

- Notifications and reminders for users.
- Integration of real payment methods.

## Contributors <img src="https://i.imgur.com/SfBB4jV.png" width="28" />

| <a href="https://avatars.githubusercontent.com/shady-2004?v=4"><img src="https://avatars.githubusercontent.com/shady-2004?v=4" alt="ِِAsmaa Ali" width="150"></a> | <a href="https://avatars.githubusercontent.com/mostafa1231?v=4"><img src="https://avatars.githubusercontent.com/mostafa1231?v=4" alt="Mostafa Nasser" width="150"></a> | <a href="https://avatars.githubusercontent.com/MoatazGharib1212?v=4"><img src="https://avatars.githubusercontent.com/MoatazGharib1212?v=4" alt="Moataz Mohamed" width="150"></a> |  |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|                                                           [Asmaa Ali](https://github.com/shady-2004)                                                            |                                                           [Mostafa Nasser](https://github.com/mostafa1231)                                                            |                                                          [Moataz Mohammed](https://github.com/MoatazGharib1212)                                                           |
