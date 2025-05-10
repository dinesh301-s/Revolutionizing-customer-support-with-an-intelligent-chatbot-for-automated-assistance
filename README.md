# customer-support-chatbot
customer-support-chatbot description 
intents.json

{
  "intents": [
    {
      "tag": "greeting",
      "patterns": ["Hi", "Hello", "Good morning"],
      "responses": ["Hi there! How can I help you today?"]
    },
    {
      "tag": "order_status",
      "patterns": ["Where is my order?", "Track my order"],
      "responses": ["Please provide your order ID."]
    },
    {
      "tag": "complaint",
      "patterns": ["I want to complain", "Not satisfied"],
      "responses": ["Sorry to hear that. Please share more details."]
    }
  ]
} 
