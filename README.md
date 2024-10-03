<h1 align="center">Hi there, I'm Henry 👋</h1>

<h3 align="center">Devoted to developing aesthetically pleasing and awesome web apps!</h3>

---

### 🚀 Featured Projects

- **🔭 QueryQuill**  
  [Frontend Repository](https://github.com/hheennrryyb/QueryQuill-Frontend) | [Live App](https://query-quill-8pqht.ondigitalocean.app)  
  *Custom document processing and AI query assistant, built with React, Django, and FAISS.*

- **🔭 Locally E-commerce**  
  [GitHub Repository](https://github.com/hheennrryyb/Locally-Capstone) | [Live App](https://locally-capstone.vercel.app)  
  *E-commerce platform showcasing handcrafted local products. Built with Next.js, Sanity, and Stripe.*

- **🔭 Rhythm Music**  
  [GitHub Repository](https://github.com/hheennrryyb/rhythm-music) | [Live App](https://rhythmmusic.netlify.app)  
  *Discover, share, and curate playlists with a sleek music player app. Developed with React, Node.js, and MongoDB.*

---

### 📫 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/henry-bellman/"><img src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin" /></a> 
  <a href="mailto:henrybellman@gmail.com"><img src="https://img.shields.io/badge/Email-henrybellman%40gmail.com-red?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://docs.google.com/document/d/1nkZmBwQAAQ407IDoCs1TUBe7lOm4DOa5/edit?usp=sharing&ouid=100506516036689234773&rtpof=true&sd=true"><img src="https://img.shields.io/badge/Resume-View-yellow?style=flat-square" /></a>
</p>
<p align="center">**Feel free to reach out if you'd like to collaborate or chat about web development and tech!**</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hheennrryyb&layout=donut&theme=graywhite" alt="Top Languages" />
</p>

---

# 🚀 Project Showcase

> *These projects are personal hobbies and side projects that I’ve built to showcase my skills, explore new technologies, and continual learning. They reflect my passion for development and experimenting with various tech stacks, but do not include my professional work. For a full overview of my professional experience, please refer to my [resume](https://docs.google.com/document/d/1nkZmBwQAAQ407IDoCs1TUBe7lOm4DOa5/edit?usp=sharing&ouid=100506516036689234773&rtpof=true&sd=true).*

## Query Quill - Ultimate Document Processing & AI Query Assistant
https://query-quill-8pqht.ondigitalocean.app/
[Backend](https://github.com/hheennrryyb/QueryQuill-Backend) |
[Frontend](https://github.com/hheennrryyb/QueryQuill-Frontend)

Query Quill enables you to build custom-trained RAG (Retrieval-Augmented Generation) models effortlessly. Upload your documents, process them, and perform smart queries with ease. No deep technical expertise required! It’s all about creating tailored AI assistants that understand and respond based on the specific content you provide.

![QueryQuill](https://github.com/user-attachments/assets/2e95ba28-a58e-470f-843b-786b2f9c7734)

🛠️ How It Works:

- 📄 Document Ingestion
Upload various document types like web pages, PDFs, and raw text. We parse and normalize them for seamless processing.

- 🧠 Vector Embedding
Your documents undergo semantic analysis using LangChain Models. The high-dimensional vector representations are then indexed in a FAISS database for lightning-fast similarity searches.

- 💬 Semantic Querying
Utilize natural language processing to interpret your queries, retrieve relevant document segments, and generate context-aware responses through ChatGPT, RAG, and vector search.

💡 Tech Stack:
- Frontend: React & TypeScript, Tailwind
- Backend: Django & PostgreSQL
- AI & ML: FAISS, PyTorch, LangChain
- Other Tools: JWT for authentication, Celery for asynchronous tasks, Redis for caching and message brokering

## Reconnector - Work Place Social Media Platform **(1.5 Week Hackathon, Winner 🥇 )**
[Frontend](https://github.com/hheennrryyb/reconnector-frontend)

Reconnector is a dynamic social platform centered around building community by highlighting shared interests among co-workers. By fostering empathy and mutual understanding, our app lays the foundation for strong workplace relationships. It addresses the challenges of remote work by bridging the gap created by physical distance, restoring bonds through shared interests, and promoting company pride through engaging features.

![Reconnector](https://github.com/user-attachments/assets/2918efb4-b7c5-4262-a118-4c86c66ed347)

With Reconnector, employees can share events and experiences, reviving workplace kinship and creating a sense of belonging. Additionally, our app incorporates gamification elements that encourage a competitive spirit—employees can participate in events and compete against other companies to earn points. This fun and interactive approach not only strengthens internal bonds but also boosts overall engagement and morale.

Placed 1st 🏆 in the Hackathon Event: [Linkedin Post](https://www.linkedin.com/posts/jordandavidmcrae_in-june-stack-five-hosted-a-two-week-long-activity-7218711606602407936-BeL8?utm_source=share&utm_medium=member_desktop)

💡 Tech Stack:
Frontend: React & TypeScript
Backend: Supabase, OAuth

## Rhythm Music - Music Player to Discover and Share Playlists
https://rhythmmusic.netlify.app/

[Backend](https://github.com/hheennrryyb/rhythm-music-server) |
[Frontend](https://github.com/hheennrryyb/rhythm-music)

Rhythm music app was created to discover, share and curate playlists! The app is a full-fledged music app with all the core features of a modern music app, such as account authentication, the ability to save and create shareable links, and most importantly discover tunes from a plethora of genres. Rhythm is also fully responsive for all screen sizes with an intuitive and beautifully sleek UI. The project proved to be an incredible undertaking to build out such a feature-rich application with many moving parts. **(1.5 months to develop)**

![Rhythm](https://user-images.githubusercontent.com/79873814/203249486-3794e86f-7cc8-425d-938f-952430830632.gif)

💡 Tech Stack:

**Frontend**
-   React JS
-   Redux Took Kit: Redux was a treat to use to manage states around the complexities of handling music player functionality and user session data after authentication. RTK query was also used to automate data fetching & caching for CRUD playlist functionality. Although I’ve used useContext API before, RTK will be my go-to for state management for every future project for its amazing features.
-   Tailwind: Was entirely done with tailwind, creating the amazing-looking UI.

**Backend**
-   NodeJS, Express: Entire backend was built to handle charts/ genre data, user accounts, shareable links, and many more features.
-   MongoDB, Mongoose: MongoDB/mongoose is used to handle storing all user, playlists, and song data. Users are able to register for an account, save playlists, and many more features using this excellent document oriented database.
-   Becrypt, JWT: Used to help hashing, and authenticating users.
    

## Locally E-commerce - Buy Beautifully Crafted Local Items
https://locally-capstone.vercel.app/

[GitHub Repo](https://github.com/hheennrryyb/Locally-Capstone)

Locally is my NextJS Ecommerce website centered around giving local boutique handcraft makers an accessible B2C platform. This project was a part of my final capstone project for my time at Brain station. The website is a feature-packed with e-commerce cart and checkout functionality, many dynamic routes and a beautiful UI. The project was a big undertaking considering the short time span I had and the functionality I had to develop for an MVP. Although I gained so much knowledge about new technologies, the app was also fulfilling to create because of the social responsibility and sustainability behind the project. **(2 Weeks to Develop)**

![Locally](https://user-images.githubusercontent.com/79873814/203249507-2596df34-a533-4ccf-851f-588cb1b8c062.gif)

💡 Tech Stack:
-   Next JS - was a vital framework and was the best option for developing an ecommerce platform like this.
	-   An intuitive dynamic routes and page-based routing, building dynamic filebase routing for product, makers and categories pages.
	-   Pre-rendering, server-side rendering (SSR) are supported for fast load times and improved SEO
	-   Automatic code splitting for faster page loads.
	-   Client-side routing with optimized prefetching.
	-   API routes to build API endpoints with Serverless Functions.

-   Sanity CMS - was handling all the content on the website without the need for a complex backend. Data were queried using GROQ and using Next function getServerSideProps pre-render the page on each request. Sanity rich text, image handling, and content management were crucial in having a content-heavy website work.
-   UseContextAPI - Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.
-   Tailwind - was amazing to use to create an elegant UI
-   Stripe Payments SDK - Handling safe payments and checkout experiences.
-   Auth0 - Centralize and manage users from multiple identity providers and give them branded, seamless signup and login experiences.
-   Google Maps API

## Telus Bubble App - Indecisive? Use Bubbles to Navigate and Pick Your Favourite Shows

TELUS Digital challenged us on developing an application & design to tackle the option paralysis surrounding the multitude of streaming available. The 24 hour hackathon was exhilarating from the ideation process to developing the react app. We are super proud of our innovative app that solves option paralysis creatively and practically. This was a great opportunity to work cross-collaboratively with the UX team for ideation and creative design. Telus also provided a very open challenge that sparked ingenuity and critical thinking to solve a major issue many large companies struggle with. **(24 hour hackathon )**

![Telus Bubbles](https://user-images.githubusercontent.com/79873814/203248893-5e089151-ac25-4b8e-a59d-2b114405d190.gif)


## InStock Warehousing & Inventory Management - Robust AF 

A group project collaborating using GitFlow and Agile (Jira) workflows to produce a warehousing application to manage inventory & warehouses. InStock is a full-stack react app with a nodeJS backend handling all the data. Building this inventory management app taught us the intricacies of these applications, the necessity of building reusable components, and working collaboratively. **(1 Week)**

![inStock](https://user-images.githubusercontent.com/79873814/203248878-6d91db50-af55-44a0-bd2c-904cbd727c6a.gif)


## BrainFlix - Youtube Clone

BrainFlix is a video-sharing and social media platform built on react. The application features video commenting and engaging , uploading placeholder videos, and setting username session data. The application used a node express backend to create an API for video and comments. **(2 Weeks)**

![Brainflix](https://user-images.githubusercontent.com/79873814/203248859-159e4750-da1d-4208-b3a2-228da33bc0fd.gif)



## Bandsite - Humble Beginnings 

Project assignment for the BrainStation Bootcamp that leverages beautifully responsive design for all screens, advanced Javascript for adding commenting functionality and pulling data from APIs for displaying vital information, and using the document object model to display information. **(2 Weeks)**

![Bandsite](https://user-images.githubusercontent.com/79873814/203248818-cde6a26c-d0fe-47f2-87ee-3cf57697866c.gif)

