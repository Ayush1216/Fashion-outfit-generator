# Buy More


### Conversational Fashion Outfit Generator using GenAI
- *Revolutionizing Fashion Discovery*: Gen AI-powered outfit generator reshapes fashion search, offering personalized recommendations from past purchases, preferences, and social trends.
- *Personalized Trendy Outfits*: Utilizes past purchases, style preferences, and current trends to craft well-coordinated outfits, elevating user shopping on Flipkart.
- *Social Trend Integration*: Incorporates social media insights, aligning fashion choices with influencer trends for on-point outfit suggestions.
- *Interactive Shopping Experience*: Users interactively fine-tune outfits, ensuring a confident shopping journey tailored to individual needs and occasions.

### Project Structure
- [Recommendation System - Python, Vector DB, Falcon 7B LLM, Flask, PyMongo](https://github.com/Ayush1216/Fashion-outfit-generator/tree/source_code/backend)
- [Social Media Trends Extraction - Selenium, Instagram, Twitter, PyTrends, Tweepy](https://github.com/Ayush1216/Fashion-outfit-generator/tree/source_code/scrappers)
- [Frontend - React JS, Redux, Axios, Vite](https://github.com/Ayush1216/Fashion-outfit-generator/tree/source_code/client)
- [Backend - Node JS, MongoDB, Express JS, PayTM payment gateway](https://github.com/Ayush1216/Fashion-outfit-generator/tree/source_code/server)

### Challenges we ran into
- Adapting the outfit recommendations to accommodate diverse cultural and regional preferences like occasion, age, body_type, fit, size and regional nuances - Solved by incorporating [Rent-the-runway dataset](https://cseweb.ucsd.edu/~jmcauley/datasets.html#clothing_fit).
- Developing a conversational model that understands user data and accordingly generates outfit suggestions - Used [free and open-source Falcon 7B LLM](https://huggingface.co/TheBloke/WizardLM-Uncensored-Falcon-7B-GPTQ), unlike conventional APIs that often come with costs.
- GPU limitations - Tackled by setting up an ngrok server on Kaggle's cloud notebook, leveraging GPU-P100 for seamless and resource-efficient model training.

### Demo
https://github.com/Ayush1216/Fashion-outfit-generator/assets/117370033/65bb4a73-2783-45ac-aa91-078bbaf5a9b7

