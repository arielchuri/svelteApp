READ ME

https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/Svelte_Todo_list_beginning
## Start up
svelteapp$ cd frontend
   npm run dev
svelteapp$ source bin/env/activate
svelteapp$ cd myproject
   python manage.py runserver
## Structure
svelteapp
  - frontend (svelte)
  - myproject (django)
    - myapp
    - myproject
## Next Steps
After setting up the Svelte frontend in the [frontend](file:///home/arielc/Documents/computing/svelteApp/README.md#4%2C5-4%2C5) directory, the next steps typically involve integrating the frontend with the backend (Django) and building the necessary features for your project. Here are some common tasks you might consider:

1. **API Integration**:
   - Create API endpoints in Django to communicate with the frontend.
   - Use tools like Django Rest Framework to build RESTful APIs.

2. **Frontend-Backend Communication**:
   - Implement logic in your Svelte components to fetch data from the Django backend.
   - Use libraries like Axios or the built-in Fetch API for making HTTP requests.

3. **Authentication and Authorization**:
   - Implement user authentication and authorization mechanisms in Django.
   - Secure your Svelte frontend by handling user authentication and access control.

4. **Database Operations**:
   - Set up database models in Django using Django's ORM.
   - Perform CRUD operations by sending requests from the frontend to the backend.

5. **Styling and UI**:
   - Design and style your frontend components using CSS or Svelte's styling capabilities.
   - Ensure a consistent and user-friendly UI/UX for your application.

6. **Testing and Deployment**:
   - Write tests for both frontend and backend code to ensure functionality.
   - Deploy your application to a hosting service or server for production use.

## AI Integration

To integrate an AI chatbot into your Django and Svelte project that can interact with the database, change the UI, and display text on the screen, you can follow these steps:

1. **Choose an AI Chatbot Platform**:
   - Select an AI chatbot platform or framework that supports integration with Django and Svelte, such as Dialogflow, Rasa, or Microsoft Bot Framework.

2. **Implement Backend API for Chatbot**:
   - Create API endpoints in Django to handle communication between the chatbot and the backend.
   - Implement logic to process chatbot requests, interact with the database, and send responses back to the frontend.

3. **Integrate Chatbot in Svelte Frontend**:
   - Use libraries like Axios or Fetch API to make API calls to the Django backend from your Svelte components.
   - Implement UI components to display the chat interface and handle user interactions with the chatbot.

4. **Chatbot Functionality**:
   - Configure the chatbot to read and edit the database by sending appropriate requests to your Django backend.
   - Implement features for the chatbot to change the UI dynamically based on user interactions.

5. **Display Chatbot Responses**:
   - Update the frontend to display chatbot responses on the screen in real-time.
   - Handle user input and send messages to the chatbot for processing.


## Learning Svelte
https://svelte.dev/tutorial/keyed-each-blocks