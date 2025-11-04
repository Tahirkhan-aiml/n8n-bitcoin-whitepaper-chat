Bitcoin Whitepaper Chat (with Citations)

Ask questions about the Bitcoin whitepaper — get answers with exact source citations.

"Which email provider does the creator of Bitcoin use?"_ → Gets answer + chunk references.

How to Use

 1. Import Workflow
→ Click [bitcoin-whitepaper-chat.json](bitcoin-whitepaper-chat.json) → Copy all  
→ In n8n: New → Import from Clipboard (or drag file)

 2. Fix Red Warnings (Credentials)
Create these exact names:

| Credential | Name |
|----------|------|
| Google Drive | `Google Drive account (David)` |
| OpenAI | `OpenAi account 7` |
| Pinecone | `PineconeApi account (David)` |

 3. Setup
1. Pinecone Index: Create `test-index` with 1536 dimensions
2. Test File: Already set to Bitcoin Whitepaper  
   [View on Google Drive](https://drive.google.com/file/d/11Koq9q53nkk0F5Y8eZgaWJUVR03I4-MM/view)

 4. Test
1. Click "Execute Workflow" → Loads whitepaper into Pinecone
2. Click "Chat"→ Ask:
   > `Which email provider does the creator of Bitcoin use?`

Output Example:
