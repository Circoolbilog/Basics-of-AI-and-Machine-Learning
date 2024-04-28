# Basics of AI and Machine Learning
"Welcome to our journey through the realms of artificial intelligence (AI) and machine learning. In today's interconnected world, AI is omnipresent, revolutionizing industries and reshaping our daily lives. From personalized recommendations to autonomous vehicles, its impact is undeniable. As we embark on this exploration, we'll delve into the history of AI, distinguish between AI and machine learning, and navigate through the diverse landscapes of supervised, unsupervised, and reinforcement learning. Join us as we unravel the mysteries and possibilities of AI and machine learning."

I figured most of you would notice, but that introduction was written by ChatGPT
![chatgpt](chat-gpt2.png)
If you noticed, Congratulations! You most likely have used ChatGPT or similar tools. 

Since we're talking about AI today I thought it fitting to introduce everyone to this topic. I want to first talk about the use of AI in today's World.

# AI in Today's World:

A few years ago, when the word AI or Artificial Intelligence were to be mentioned, most people would usually think of futuristic concepts portrayed in science fiction movies like the terminator. Others, the more technologically aware would probably think of the early AI assistants like Siri, or other existing technology at the time. Today, A lot of companies use AI mainly as a marketing buzzword. "AI powered search engine," "AI powered appliances," I even saw an ad about a "ChatGPT E-Bike!" There is a lot of confusion today with AI, my hope is that by the end of this, you all will armed with the knowledge to navigate the ever changing world dominated by AI and be inspired to venture to the world of AI Research and Development.

## Machine Vision / Computer Vision
![computervisiongif](computer-vision.gif)

One of the most popular branches of Artificial Intelligence right now, this is also the branch of machine learning where my current work is related to. Computer vision helps computers understand digital videos and images. 

Some examples of Computer vision:
- Facial Recognition- Used in Various applications including but not limited to: Security Systems, Access control, and authentication processes
- Object Detection/Tracking - Surveillance and Security systems used computer vision technology for monitoring and analyzing video footage
- Image Classification - Image Classification is widely used in medical images for diagnosing conditions, Quality control in manufacturing, Content moderation for Social Media, and Plant/Animal identification
- Optical Character Recognition - Used in Document Digitization, Automatic License Plate Recognition, and Handwritten Text Recognition

Here's an excellent example of computer vision right in your pocket. If you have an android phone, you can open up google lens, where you can see some of the applications for computer vision. "Translate", "Text", and "Homework" are all examples of Optical Character Recognition (OCR). OCR enables computers to extract text from images to which google can then process the text depending on your needs. The other features of the google lens use different applications of Computer Vision like Object recognition.

## Generative AI
While Computer Vision uses Machine Learning to help computers understand and interpret the world through digital Images, Generative AI is focused on creative endeavors. Generative AI, much like computer vision is a broad term that encompasses a variety of techniques designed to generate new content such as text, images, audio, or other types of data. Generative Adversarial Networks (GANs), Variational Autoencoders (VAEs), and Diffusion Models are examples of Generative AI. They are trained to understand and replicate underlying patterns and structures present in the training data allowing them to create "new" content that is similar but not too identical to the original data.

### Large Language Model (LLM)

![GTP-Trends](GPT-Trends.png)

ChatGPT is the most popular example of Large Language models but even before the emergence of ChatGPT, the foundation for these models was laid out by the development of Generative Pre-trained Transformer by OpenAI, that's where the GPT in ChatGPT comes from. GPT, introduced in 2018 was a groundbreaking approach to Natural Language Processing (NLP).

GPT works by using something called a Transformer, first breaking down the text into tiny pieces called "tokens" and then understanding the relation of each tokens to one another to build context. In essence GPT is just predicting what word comes next by analyzing what words came before and doing it over and over again to create coherent sentences. The way ChatGPT works is that there, every time you start a conversation, there are hidden messages providing ChatGPT the context that what comes next is what a helpful ai assistant would say.

Aside from GPT, there are other models like Meta's [LLAMA 3](https://ai.meta.com/blog/meta-llama-3/) which released just last Apr 18, 2024, it is an open source model that you can download and use if you have a powerful enough computer. If you are interested to try it out for yourself, I personally use the [text-generation-webui](https://github.com/oobabooga/text-generation-webui) on github, and download my models on [Hugginface](https://huggingface.co/TheBloke) provided by user "The Bloke" since the model that they provide are already quantized.
![oobabooga](https://raw.githubusercontent.com/oobabooga/screenshots/main/print_instruct.png)
(screenshot of text-generation-webui)
### Text to Image
Text to Image models are generative models which gained popularity over the past several years. They work by "destroying" an image by gradually adding gaussian noise to an image and learning to reverse this process. That's not all though, there is also embeddings added to these images. If you want to learn more go to the [Computerphile channel on youtube](https://www.youtube.com/watch?v=1CIpzeNxIhU&t=939s) for an easy to understand explanation. 
![ytthumbnail](YT-SD-how-it-works.png)
There are several text to image models out there such as [Dall-e 2](https://openai.com/dall-e-2) and [Dall-e 3](https://openai.com/dall-e-3) by OpenAI, [Midjopurney](https://www.midjourney.com/home), and [Stable Diffusion](https://stability.ai/news/stable-diffusion-public-release) by Stability AI. They all use slightly different methods for generating the images but the Idea is roughly the same. I personally use Stable diffusion using  [AUTOMATIC1111's stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) on github for my personal use. It allows me to train my own data and use it however I want. Here are some example images I generated back in 2023:

| Anime | Realistic |
| -------- | ---------- |
| ![anime-clark](SD-anime-clark.bmp)  | ![sd-ninja-clark](SD-realistic-ninja-clark.bmp) |


In these images I trained a model with my face. There is of course one thing to keep in mind if you want to go and train your own models, you need consent before you train these models. There is nothing preventing us from training models of other people's likeness so be responsible.


And those are just some examples of AI in today's world! Now that we're caught up on How AI is used today, let's explore now the history of AI, Specifically Machine Learning.
# A Brief History of AI

The History of AI and ML dates back to the 1940's alongside the invention of electronic computers. Here's a condensed timeline from an article written by [Dan Franklin](https://www.linkedin.com/pulse/brief-history-ai-ml-dan-franklin/)

### 1. The Early Days of AI

#### 1.1. The Birth of AI (1940s - 1956)
- **1943:** Warren McCulloch and Walter Pitts proposed a model of artificial neurons. Their model described how interconnected neurons could perform complex computations, mimicking the behavior of the human brain.
- **1947:** Alan Turing discussed computer intelligence and self-altering machines. Turing gave a public lecture in which he mentioned computer intelligence and the possibility of letting the machine alter its own instructions
- **1950:** Claude Shannon created "Theseus," the first AI system.
- **1956:** John McCarthy organized the Dartmouth Conference, marking the birth of AI.

### 2. The Emergence of Machine Learning

#### 1.2. The Rise of Machine Learning (Late 1950s - 1959)
- **Late 1950s:** Arthur Samuel introduced the term "Machine Learning" to describe a field of study that gives computers the ability to learn without being explicitly programmed.
- **1958:** FORTRAN, the first programming language for scientific computing, was introduced.This allowed researchers to write algorithms that could perform complex calculations and process large amounts of data.
- **1959:** John McCarthy and Marvin Minsky founded the MIT Artificial Intelligence Project, which focused on developing new AI and ML algorithms. That same year, McCarthy also proposed the idea of using LISP, the first AI programming language, for AI research.

### 3. The Evolution of AI and ML

#### 1.3. Progress in AI and ML (1960s - 1990s)
- **1967:** General Problem Solver (GPS) was developed.
- **1970:** The first computer vision system was created, which could recognize handwritten digits
- **Late 1970s:** Emergence of connectionism which focused on creating neural networks that could learn from data.
- **1980s:** Introduction of the backpropagation algorithm. 
- **1997:** IBM's Deep Blue defeated Garry Kasparov in chess.

# What is the Difference Between AI and Machine Learning?
*Source: [Pathmind.com](https://wiki.pathmind.com/ai-vs-machine-learning-vs-deep-learning)*

AI is the broadest term, referring to any computer program that exhibits intelligent behavior. It includes techniques like rules-based systems (symbolic AI) as well as machine learning.

![AI](AI-ML_DL.png)
**Artificial Intelligence** - The ability of a computer or computer-controlled robot to perform tasks that are commonly associated with the intellectual processes characteristics of humans.
**Machine Learning** - Constantly improving a machine through tweaking of parameters based on experience which imitates the way humans learn. 
**Deep Learning** - A sub type of ML that uses Neural Networks. it uses a network of Nodes called "neurons" designed after the human brain.

The future of AI is uncertain, with different perspectives on whether rapid progress will continue, stagnate, or raise existential risk concerns. Combining deep learning with other AI techniques like symbolic reasoning shows promise.
# Types of Machine Learning
Source: [Vijay Kanade - Spiceworks](https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-ml/)

Machine Learning algorithms are used to create a model from a training dataset. The created model uses what it "learned" from the training dataset to make a prediction on new input data. 
![how-ml-work](How-machine-learning-work.png)

Machine Learning can be broadly categorized in to three main types based on the approach on learning and the availability of  labeled data: 
## Supervised Learning
![supervised-learning](supervised-learning.png)
Supervised learning is where models are trained on labeled datasets and are enabled to predict outputs based on the provided labeled training data. The training dataset includes the input and the expected output. The goal of supervised learning is to have a model that can corelate an input variable to an output variable and do this even with a fresh input that it has never seen before.
Supervised learning can further be classified into two categories: 
### Classification
Algorithms that tackles the problem of classifying objects. The output of these algorithms are categorical, some examples include Email Spam Detection, Handwritten Digit Recognition, Speech Recognition, DNA Sequence Classification and much more. 
![classification](Classification.png)
*(in this example the algorithm correctly classifies the blue and orange dots)*
### Regression
Algorithms that predict continuous values based on input features. Examples include predicting house prices based on features like size and location, forecasting stock prices using historical data, and estimating future temperatures using weather patterns. These algorithms learn relationships between input features and the target variable to minimize the difference between predicted and actual values. 

![regression](Regression.png)
## Unsupervised Learning
![unsupervised-learning.png](unsupervised-learning.png)
Unsupervised Learning Deals with unlabeled data, where the algorithm tries to find patterns or structures in the input data without explicit supervision. Some applications include  customer segmentation, anomaly detection, recommendation systems(like tiktok), and data comression. Unsupervised Learning can also be further classified into two main types:
### Clustering
Clustering is just a way of grouping similar data points together. An example of this is clustering a customers based on their purchase Behaviors.
### Association
Association on the other hand is Discovering the relation between variables in large datasets. Examples include market basket analysis to find frequently co-occurring items in transactions. 

## Reinforcement Learning
![[Reinforcement Learning.png]]
Reinforcement learning is a type of learning where the AI model learns to make decisions by interacting with an environment. It learns through trial and error, receiving feedback in forms of rewards or punishments. Some examples include, Robotics(Robots train to perform tasks like walking or grabbing objects), [Playing Games (AI models trained how to play games)](https://www.youtube.com/watch?v=ovIykchkW5I), and Autonomous Driving.
# Practical Examples
## MENACE The Matchbox who learned to play tic-tac-toe
[Menace.pdf](Menace.pdf)
The 1993 paper 


## Neural networks
[playground](https://circoolbilog.github.io/Basics-of-AI-and-Machine-Learning/Assets/neura-networks-playground.html)

# The Future of AI
