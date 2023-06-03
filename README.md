# LangChain for Web-Chatbot on Next.js


## Services used in this app
- LangChain
- Pinecone
- Supabase
- clerk

# **Setup**
## 1. Clone this repository
```
git clone https://github.com/khanovico/LangChain-next-chatbot
```

## 2. Install dependencies
```
cd LangChain-next-chatbot
yarn
```

## 3. Move your .env.example to .env
```
mv .env.example .env
```

## 4. Pinecone store
- Assuming you already have a Pinecone Account, you will need the index name of your vectors data and your Pinecone API and Pinecone Environment.

## 5. Supabase
- Create an account
- Create a new project
- Add a new table named "conversations" with the following columns: user_id (type: text), entry (type: text), speaker (type: text)
    

## 6. Clerk
- Create an account
- Create a new project

## 7. Supabase and Clerk walkthrough
- You need to be familiar with Supabase and Clerk to access to full control of this project.

## 8. Add your keys to the .env
```
OPENAI_API_KEY=
PINECONE_API_KEY=
PINECONE_ENVIRONMENT=
PINECONE_INDEX_NAME=
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_KEY=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
```

## 9. Start the project
```
yarn dev
```

### - **I'm thinking of rebuilding the UI very soon, so keep an eye out! 👀**