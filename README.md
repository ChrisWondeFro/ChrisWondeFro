# Christian Wondirad Mandefro

## Full Stack Developer | AI Enthusiast | Creative Problem Solver

![DLF](https://github.com/user-attachments/assets/8114ec01-90ed-44c2-abc6-31c7e4fc72d6)



### 👨‍💻 About Me

I lived in Ethiopia for the first 19 years of my life and had just finished my first year of law school before moving to the US in 2017 and starting all over!
I grew up a voracious reader, playing soccer, basketball and ping pong with friends, surrounded by family and living an overall social and active life. I have also always been deeply interested in nature, animals, science and art. I consider myself a creative with a rich inner world as well as musically inclined being able to sing and play the guitar.

Since picking up web development in 2023 to try and create the MVP of an idea for an app my mother had, I have gained countless valuable lessons in harnessing my creativity and passion for innovative and impactful solutions and expanded my horizon to be an enthusiastic and innovative Full Stack Developer with over two years of intensive experience in web and software development. I specialize in Django, FastAPI, Next.js and integrating AI and Cloud solutions into web applications. My passion lies in building user-centric applications and leveraging emerging technologies to solve complex problems.

- 🔭 I'm currently working on innovative health tracking solutions, DNA analysis web applications and developing a few other business to consumer SAAS ideas I believe hold potential.
- 🌱 I'm continuously learning about AI, cloud technologies, and advanced web development techniques
- 👯 I'm looking to collaborate on open-source projects and innovative web applications
- 💬 Ask me about full-stack development, AI integration, or prompt engineering

### 🛠 Skills & Technologies

- Languages: Python, JavaScript, HTML, CSS
- Frameworks: Django, Flask, FastAPI, Next.js, TailwindCSS
- Databases: PostgreSQL, DynamoDB
- Cloud: Google Cloud Platform, AWS
- AI & ML: Langchain, OpenAI, Prompt Engineering, Vector Databases
- Other: RESTful APIs, Git, Agile methodologies, D3.js

### 🚀 Projects

#### [AWS Glossary Force Directed Graph](https://aws-glossary-graph.devlookforward.com)
**Aug 2024 - Present**  

**Project Overview:** The AWS Glossary Force Directed Graph is an innovative web application designed to simplify the understanding of Amazon Web Services (AWS) and its associated terminology. This interactive visualization tool allows users to explore the complex relationships between AWS services and glossary terms, making it easier for both beginners and experienced professionals to navigate the AWS ecosystem. This project was built as a side project during my time taking on the AWS re/Start program with PerScholas, where I earned my AWS Certified Cloud Practitioner Certification, and my AWS Certified AI Practitioner Certifiedon my own initiative just before graduating the program. 

<img width="1438" alt="Screenshot 2025-03-21 at 3 30 12 AM" src="https://github.com/user-attachments/assets/15a41284-f3f1-4687-9e79-004c265d21c8" />
<img width="1410" alt="Screenshot 2025-03-21 at 3 31 28 AM" src="https://github.com/user-attachments/assets/bb9d7ba8-d626-488e-bf8c-70c1431d7285" />
<img width="1402" alt="Screenshot 2025-03-21 at 3 29 34 AM" src="https://github.com/user-attachments/assets/636284f5-b694-4470-a075-5cf1453bd7c1" />

**Key Features:**  
- **Interactive Graph Visualization:** Utilizes a force-directed graph to display interconnected AWS services and glossary terms, enabling users to visually explore relationships, easily observe clustering behaviour and which services and terms are the most connected to by how big they are.
- **Category-Based Filtering and Search:** Users can filter services by category, search for specific terms, and see only relevant linkages for quick and targeted information retrieval. 
- **Advanced Graph Controls:** Users can toggle night mode, enable or disable AWS service nodes or glossary terms, and adjust zoom levels.  
- **Service Category Filter:** Select an AWS service category (e.g., Management & Governance) to display only relevant nodes and linkages.  
- **Hover and Search Enhancements:** Hovering over nodes displays AWS service or term definitions. The advanced search feature dynamically moves the viewpoint to match queries, centering on the matched node, highlighting linked nodes, and greying out unrelated ones. Definitions appear in an expandable section within the graph controls panel.
- 
**Technology Stack:**  
- **Backend:** FastAPI, a high-performance Python web framework, handles API endpoints.  
- **Frontend Visualization:** D3.js, a powerful JavaScript library, creates dynamic and interactive data visualizations.  
- **Styling:** Tailwind, Custom CSS and Flowbite are used for rapid UI development and consistent, modern design.
- **Platform Services:** GoogleCloudRun.  

**Future Enhancements:**  
- **Regular Updates:** Continuously updated to include new AWS services and terminology, ensuring that the graph remains current and relevant using Langraph from Langchain.  
- **Integration with AWS Documentation:** Aiming to provide additional information on each node besides the aws glossary definition by linking to official AWS documentation.  
- **User Accounts and API Access:** Developing features for saving custom graph configurations and providing API access for developers to integrate the graph data into their own applications.  

**Use Cases:** This project serves as an experimental educational tool for those looking to gain a deeper understanding of AWS, whether for personal knowledge, professional development, or as a resource for teaching and training purposes.

---

#### [BellyBioMe](https://belly-biome.com)
**Jul 2024 - Present**  
**Project Overview:** BellyBioMe is a comprehensive nutrition and wellness tracking application designed to empower users to monitor and improve their health. Utilizing branded food data from a DynamoDB table and SR Legacy food nutrition data stored in a vector database, BellyBioMe enables barcode image uploading, scanning and similarity-based food item searches for accurate meal tracking. It also has goal tracking features and a dashboard for personalized insights.  

As the software engineer of a five-member team in the Per Scholas AWS re/Start program, I helped develop and deploy this application to AWS ElasticBeanStalk and on the web securely for our capstone project. Our team, later reduced to four members, presented last in front of additional important guests, raising the stakes. Despite this, we received top marks and were recognized as the best project in our cohort by far.

<img width="1490" alt="Screenshot 2025-03-21 at 3 37 49 AM" src="https://github.com/user-attachments/assets/b879d88e-eb33-4096-bf95-82d402e8e18c" />
<img width="1452" alt="Screenshot 2025-03-21 at 4 38 14 AM" src="https://github.com/user-attachments/assets/7989bc3c-003f-4565-b8f4-f481a70781ee" />
<img width="1426" alt="Screenshot 2025-03-21 at 4 38 50 AM" src="https://github.com/user-attachments/assets/0adc6177-8bdd-4d10-b14e-328f955ffe25" />
<img width="1433" alt="Screenshot 2025-03-21 at 4 39 34 AM" src="https://github.com/user-attachments/assets/7e431e07-9daf-4cc0-b15a-c0267741fe8d" />

**Key Features:**  
- **Barcode Scanning and/pr Uploading:** Quickly scan food items or upload an image of a food items barcode to log meals and track nutritional intake 
- **Similarity-Based Searches:** Use advanced search features to find food items with ease.   
- **Actionable Dashboards:** View and analyze health metrics, including calorie intake, nutrient consumption, and get basic feedback that notifies users when certain thresholds have been met or are not being met.

**Technology Stack:**  
- **Backend:** Django for the backend integrating Postgres for user data, DynamoDB for branded foods data and Pinecone vector database for SR Legacy food nutrition data. Also uses S3 for user uploaded barcode images, a Lambda Function and an API Gateway service using the function to handle cleaning images from s3 manually by the user for their profile picture and automatically when user uploaded barcode images are being processed and are stored in s3 for a short time. Boto3 for AWS services interactions.
- **Frontend:** Custom UI with user-friendly dashboards for health monitoring.
- **Platform Services:** AWS ElasticBeanStalk, CloudFlare Domains.

**Future Plans:**  
- **Personalized Insights:** Receive tailored and highly interactive feedback on diet and health through machine learning and generative AI. 
- **Enhanced AI Capabilities:** Integration of more sophisticated machine learning models for deeper insights.  
- **Cross-Platform Syncing:** Sync data across multiple devices for seamless user experience.  
- **Integration with myDNA:** Provide a holistic approach to nutrition and genetic wellness by linking genetic insights from myDNA with BellyBioMe's nutrition tracking.  

---

#### [myDNA](private)
**Jul 2023 - Present**  
**Project Overview:** myDNA is a web application that enables users to upload and analyze raw DNA data from AncestryDNA files, providing genetic insights, disease risk assessments, and interactive visualizations. Utilizes generative AI, machine learning techniques, and interactive visualizations to deliver personalized health risk assessments and transform complex genetic information into accessible and actionable insights. 

<img width="1491" alt="Screenshot 2025-03-21 at 3 40 28 AM" src="https://github.com/user-attachments/assets/b7fb5e54-998f-403b-ad3b-c08295d19c3e" />
<img width="1449" alt="Screenshot 2025-03-21 at 3 16 48 AM" src="https://github.com/user-attachments/assets/a2bf2248-9ed3-4901-b706-15141369ee79" />
<img width="1404" alt="Screenshot 2025-03-21 at 4 33 10 AM" src="https://github.com/user-attachments/assets/2fb8321d-dd74-43ca-81b9-c7e2e1830474" />


**Key Features:**  
- **DNA Upload and Analysis:** Process raw DNA data for genetic variant insights.
- **Disease Risk Assessment:** Utilize comprehensive datasets for risk classification and personalized health insights.
- **Interactive Visualizations:** D3.js-powered force-directed graphs to explore variant and disease relationships dynamically. 
- **Generative AI Integration:** AI-driven assistant leveraging vector embeddings, RAG (Retrieval-Augmented Generation), and prompt engineering for personalized insights.
- **Drag & Drop Learning:** Users can drag specific terms or full sections into the chatbot to trigger explanations.


**Technology Stack:**  
- **Backend:** Django for application logic, PostgreSQL for data storage.  
- **Visualization:** D3.js for interactive knowledge graph representation.
- **AI & ML:** OpenAI LLMs with LangChain for chatbot functionalities, embeddings stored in Pinecone for user-specific data retrieval. 
- **Frontend:** Bootstrap5
- 
**Future Plans:**  
- **Machine Learning Roadmap:** Implement machine learning for predictive analysis and personalized health insights.  
- **Integration with BellyBioMe:** Integration with BellyBioMe: Merge genetic and dietary data for personalized wellness recommendations.

---

#### [Chatflight](https://chatflight.devlookforward.com)
**Aug 2023 - Aug 2023**
**Project Overview:** Chatflight is a prototype application that provides users with detailed flight information through natural language queries. Utilizing advanced AI and natural language processing techniques, Chatflight aims to offer a superior user experience by making flight information easily accessible and understandable.

<img width="1484" alt="Screenshot 2025-03-21 at 4 50 43 AM" src="https://github.com/user-attachments/assets/13ff5f21-3a36-4715-bb33-c5ac061b19b7" />
<img width="1477" alt="Screenshot 2025-03-21 at 4 24 33 AM" src="https://github.com/user-attachments/assets/9de10a63-9d60-4c7d-8ef6-ac5a327852ce" />

**Key Features:** 
- **Natural Language Queries:** Users can ask questions about flights in plain language and receive detailed responses.
- **Flight Information:** Access information about flight schedules, availability, and more.
- **Schema Modeling and Prompt Engineering:** Clean and effective usage of Pydantic and advanced prompt engineering techniques to ensure proper usage of tools and relevant responses.

**Technology Stack:** 
- **Backend:** FastAPI for handling API requests.
- **AI and NLP:** Langchain and OpenAI for natural language understanding and response generation.
- **Frontend:** Custom-built UI with Tailwind CSS and Flowbite components for a smooth and seamless interaction with users.

**Future Plans:** 
- **Booking Capabilities:** Integrate with flight booking systems to allow users to book flights directly through the app.
- **Enhanced Personalization:** Use machine learning to provide even more personalized responses and suggestions.
- **Expanded Data Sources:** Incorporate additional data sources for more comprehensive flight information.

---

#### [BustPDF](https://github.com/ChrisWondeFro/BustPDF)
**Oct 2023 - Oct 2023**  
**Project Overview:** BustPDF is a simple, user-friendly PDF processing tool for handling PDF documents. The application enables users to perform OCR on images from PDF files and output text files, extract text from PDF's into text files and tables into CSV files, automating research document processing.

<img width="1463" alt="Screenshot 2025-03-21 at 4 27 07 AM" src="https://github.com/user-attachments/assets/118cb31f-3b0f-474c-9bd5-f8091c84d00d" />
<img width="1431" alt="Screenshot 2025-03-21 at 4 27 13 AM" src="https://github.com/user-attachments/assets/93cf734b-a36e-49c1-a37c-fdfd9f109a32" />

**Key Features:**  
- **Text Extraction:** Extract text from PDF files and output them into TXT files.
- **OCR Capabilities:** Perform OCR on images from PDF files and output the text into TXT files for easy access.
- **Table Conversion:** Extract tables from PDFs and convert them into CSV files for easy data manipulation.

**Technology Stack:**  
- **Backend:** Flask for handling requests and serving the application.  
- **OCR and Conversion:** Google Cloud OCR API for text recognition, custom scripts and python libaries for table and text extraction.  
- **Frontend:** Bootstrap for responsive and intuitive user interface design.  

**Future Plans:**  
- **Advanced Parsing Features:** Introduce features for more complex document processing, including multi-page table extraction.  
- **Improved UI/UX:** Further refine the user interface for better user experience.  
- **Integration with Other Tools:** Allow seamless integration with other document management and data analysis tools.
  
---

#### [GenAI Chatbots for Nonprofits](https://github.com/ChrisWondeFro/hopecommunity-chatbot-test)
**Aug 2023 - Sep 2023**  
**Project Overview:** GenAI Chatbots for Nonprofits was a demonstration project aimed at enhancing user engagement on nonprofit websites through the use of generative AI chatbots. The project stemmed from a collaboration with nonprofit organizations, including Ethiocommunity (Aurora, Colorado) and Hope Communities, both of whom were exploring AI-driven solutions to replace outdated messaging systems. These chatbots provided accurate and up-to-date information using retrieval-augmented generation (RAG) and were tailored specifically for nonprofit organizations.  

**Key Features:**  
- **Generative AI Chatbots:** Provide automated, intelligent responses to user queries on nonprofit websites.  
- **Retrieval-Augmented Generation:** Ensure information provided by chatbots is accurate and relevant.  
- **Prompt Engineering:** Tailor chatbot responses to specific nonprofit needs and user queries.  
- **Easy Deployment:** Designed for simple integration into existing nonprofit websites.  

**Technology Stack:**  
- **Backend:** FastAPI for building and managing API endpoints. Langchain as the framework to bring OpenAI LLM API, Vector Database similarity search and the prompt template together in a RAG chain.  
- **AI and NLP:** Langchain for natural language processing and generating responses.  
- **Integration:** Easy to integrate with various content management systems used by nonprofits.
- **Platform Services:** GoogleCloudRun 

**Future Plans:**  
- **Expanded AI Capabilities:** Incorporate more sophisticated AI features to handle complex queries.  
- **Multilingual Support:** Develop capabilities to support multiple languages.  

---

### 📫 Let's Connect

- [LinkedIn](https://www.linkedin.com/in/christian-mandefro)

### 🌟 Fun Facts

- **I broke my left arm in 7th grade after falling on it while trying to jump from an elevated area and swing from a roof**
- **I stayed up two full days not too long ago coding and composing code all night, all day then all night again!**
- **I have had two official names so far in my life and still have three more unofficial names family members and relatives call me by!**

---

<p align="center">
  <i>Let's turn ideas into reality through code!</i>
</p>
