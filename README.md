/* Chatbot Container */
.chatbot-container {
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 1000;
}

/* Chatbot Icon Button */
.chatbot-icon {
    background-color: #007bff;
    border: none;
    padding: 12px;
    border-radius: 50%;
    cursor: pointer;
    width: 55px;
    height: 55px;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: background 0.3s ease, transform 0.2s ease;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

.chatbot-icon:hover {
    background-color: #0056b3;
    transform: scale(1.1);
}

.chatbot-icon img {
    width: 28px;
    height: 28px;
}

/* Chatbox UI */
.chatbox {
    background-color: #ffffff;
    width: 360px;
    height: 500px;
    position: absolute;
    bottom: 70px;
    right: 20px;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    display: none;
    transform: scale(0.9);
    opacity: 0;
    transition: transform 0.3s ease, opacity 0.3s ease;
}

.chatbox.show {
    display: block;
    transform: scale(1);
    opacity: 1;
}

/* Chatbox Header */
.chat-header {
    background-color: #007bff;
    color: white;
    padding: 12px 16px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 18px;
    font-weight: bold;
}

.close-chat {
    background: none;
    border: none;
    color: white;
    font-size: 18px;
    cursor: pointer;
    transition: color 0.3s ease;
}

.close-chat:hover {
    color: #f8d7da;
}

/* Chat Messages Area */
.chat-messages {
    padding: 12px;
    overflow-y: auto;
    max-height: 380px;
    background: #f8f9fa;
    display: flex;
    flex-direction: column;
    gap: 10px;
}

/* Chat Messages */
.message {
    max-width: 80%;
    padding: 10px 14px;
    border-radius: 15px;
    font-size: 14px;
    line-height: 1.4;
    word-wrap: break-word;
}

.message.user {
    background-color: #007bff;
    color: white;
    align-self: flex-end;
    border-bottom-right-radius: 4px;
}

.message.bot {
    background-color: #e9ecef;
    color: #333;
    align-self: flex-start;
    border-bottom-left-radius: 4px;
}

/* Chat Input Area */
.chat-input {
    padding: 10px;
    border-top: 1px solid #ddd;
    background: white;
    display: flex;
    gap: 8px;
    align-items: center;
}

/* Input Box */
.chat-input input {
    flex: 1;
    border: none;
    padding: 10px;
    font-size: 14px;
    border-radius: 20px;
    background: #f1f1f1;
    outline: none;
}

/* Send Button */
.send-button {
    background-color: #007bff;
    border: none;
    padding: 8px 12px;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    align-items: center;
    transition: background 0.3s ease, transform 0.2s ease;
}

.send-button:hover {
    background-color: #0056b3;
    transform: scale(1.1);
}

.send-button img {
    width: 20px;
    height: 20px;
}
