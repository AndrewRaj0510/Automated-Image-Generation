# Automated-Image-Generation
Fully automated image-generation workflow that auto-posts and markets the business on social media. Integrated with Web APIs(Google, Meta, X) into the automation pipeline to enable seamless multiplatform campaign execution and data synchronization.

What it does:

• The workflow runs four timed triggers⏱️ across the day, optimized for social peak hours to maximize reach.

• Pulls a random persona (digital nomad, freelancer, promo hunter, etc..) and a random keyword from a list of 400+ keywords, then sends the keyword to GPT-4 for structured analysis📊.

• Creates a style specific (meme / cinematic / direct ad / shock bait) text prompts using persona and the structured analysis of the keyword using OpenAI🧠.

• Generates 1536x1024 images using gpt-image-1 model based on the text prompts.

• Writes short captions and relevant hashtags#️⃣ (context-aware) based on the prompt, keyword and the image using chatgpt-4o🤖 model. 

• Renames files, uploads to Google Drive☁️, creates a public URL🔗 via ImageKit🌐, and logs metadata for audit and retries so it can run daily without me touching a thing .

• Creates a container id to publish them as carousels or individual posts on social media.

Whether it’s social media posting or content publishing, n8n automation🤖 has made marketing campaigns easier by turning repetitive, error-prone steps🔁 into a reliable system✅ and dramatically reducing manual effort.

![ImgGen](https://github.com/user-attachments/assets/401835a5-b8e1-4865-ae4c-a91b36c6088b)
