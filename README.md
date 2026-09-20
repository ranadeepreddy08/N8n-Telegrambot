# 🤖 n8n Telegram AI Bot

An automation-based Telegram bot built using **n8n**. The project demonstrates how a Telegram bot can receive messages, process them through an automated workflow, and send responses back to the user.

The project was created to explore **workflow automation, Telegram bot integration, APIs, and event-driven automation using n8n**.

## ✨ Features

* 💬 Receive messages through Telegram
* ⚡ Process messages automatically using an n8n workflow
* 🤖 Generate automated responses
* 📤 Send responses back to Telegram
* 🔄 Event-driven workflow automation
* 🧩 Connect different services through n8n nodes

## 🏗️ Workflow

```text
        Telegram User
              │
              ▼
       Telegram Bot
              │
              ▼
       Telegram Trigger
              │
              ▼
       Process Message
              │
              ▼
        n8n Workflow
              │
              ▼
       Generate Response
              │
              ▼
        Telegram Node
              │
              ▼
        User Receives
          Response
```

## 🛠️ Technologies Used

| Technology           | Purpose                                          |
| -------------------- | ------------------------------------------------ |
| **n8n**              | Workflow automation                              |
| **Telegram Bot API** | Communication with users                         |
| **Telegram**         | User interface                                   |
| **APIs / Services**  | Processing and connecting external functionality |

## 🔄 How It Works

### 1. User Sends a Message

A user sends a message to the Telegram bot.

### 2. Telegram Trigger

The Telegram trigger in n8n detects the incoming message and starts the workflow.

### 3. Message Processing

The message is passed through the required n8n workflow nodes for processing.

### 4. Response Generation

The workflow generates the appropriate response based on the configured logic or connected services.

### 5. Response Sent to Telegram

The response is sent back to the user through the Telegram Bot API.

## 📌 Key Concepts Learned

Through this project, I explored:

* Workflow automation
* Event-based triggers
* Telegram Bot integration
* API-based communication
* Connecting multiple services
* Designing automation workflows using visual nodes
* Basic automation logic using n8n

## 🚀 Getting Started

### Prerequisites

* A Telegram account
* A Telegram bot created using **BotFather**
* An n8n instance
* Required API credentials for any connected services

### Setup

1. Create a Telegram bot using BotFather.
2. Copy the bot token.
3. Open your n8n instance.
4. Create a new workflow.
5. Add a **Telegram Trigger** node.
6. Configure the Telegram credentials.
7. Add the required processing nodes.
8. Add a Telegram node to send the response.
9. Activate the workflow.
10. Send a message to the bot to test it.

## 📂 Project Structure

Since this project is primarily an n8n workflow, the main project component is the workflow configuration.

```text
n8n-telegram-bot/
│
├── workflow/
│   └── telegram-bot.json
│
└── README.md
```

> Export the workflow from n8n and place the exported JSON file inside the `workflow` folder if you want to make the workflow directly importable.

## 🎯 Purpose

The main purpose of this project was to understand how **n8n can be used to build practical automation workflows without developing every component from scratch**.

Instead of manually writing the complete backend for a Telegram bot, n8n allows different services and APIs to be connected visually through workflow nodes.

## 🔮 Possible Improvements

* Add AI-powered responses
* Connect an LLM API
* Add conversation memory
* Add commands such as `/start` and `/help`
* Connect databases for storing user information
* Add scheduled notifications
* Add more external API integrations
* Deploy the workflow on a cloud server

## 📌 Project Status

🚧 **Workshop / Learning Project**

This project was developed to gain hands-on experience with **n8n workflow automation and Telegram bot integration**.
