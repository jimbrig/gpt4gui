# GPT4 Chat Graphical User Interface

> [!NOTE]
> This project is a simple React-based chat interface that uses Next.js and communicates with OpenAI's GPT-4 (or GPT-3.5-turbo) language model to generate responses.

<details><summary>View Screenshot 📷</summary><p>

![image](https://github.com/jimbrig/gpt4gui/assets/32652297/23776027-aacc-4add-b4dc-1f1343ccfe59)

</p></summary></details>

## Features

- Responsive chat interface
- Auto-scroll to the latest message
- Message input validation
- OpenAI GPT-4 integration
- Loading indicator during API requests

## Usage

These instructions will help you set up the project on your local machine.

### Prerequisites

- Node.js (>= 14.x)
- npm

### Dependencies

- **`@emotion/react`**: ^11.10.6
- **`@emotion/styled`**: ^11.10.6
- **`@mui/material`**: ^5.11.14
- **`@types/node`**: 18.15.10
- **`@types/react`**: 18.0.29
- **`@types/react-dom`**: 18.0.11
- **`eslint`**: 8.36.0
- **`eslint-config-next`**: 13.2.4
- **`next`**: 13.2.4
- **`openai`**: ^3.2.1
- **`react`**: 18.2.0
- **`react-dom`**: 18.2.0
- **`react-markdown`**: ^8.0.6
- **`typescript`**: 5.0.2

### Installation

1. Clone the repository:

```bash
# GitHub CLI
gh repo clone jimbrig/gpt4gui

# SSH
git clone git@github.com:jimbrig/gpt4gui.git

# HTTPS
git clone https://github.com/jimbrig/gpt4gui.git
```

1. Change to the project directory:

```bash
cd gpt4gui
```

1. Install dependencies:


```bash
npm install
```

1. Create `.env` and add your OpenAI API Key (`OPENAI_API_KEY`):

```bash
touch .env
echo "envCopy code" >> .env
echo "OPENAI_API_KEY=<KEY>" >> .env
```

1. Run local development server:

```bash
npm run dev
```

Now you can open your browser and navigate to **`http://localhost:3000`** to see the chat interface in action.

## Deployment

To deploy the application, follow the **[Next.js deployment documentation](https://nextjs.org/docs/deployment)**.

## **Built With**

- **[Next.js](https://nextjs.org/)** - The React framework used
- **[TypeScript](https://www.typescriptlang.org/)** - The programming language used
- **[OpenAI API](https://beta.openai.com/docs/)** - The AI language model used

## Acknowledgements

- Completely based off original solution from <https://github.com/hillis/gpt-4-chat-ui> 
- Used Template and converted to Typescript
- Frontend of this repo is inspired by langchain-chat-nextjs **[LangChain-Chat-NextJS](https://github.com/zahidkhawaja/langchain-chat-nextjs)**
