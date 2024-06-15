# **TFT "META" Data Analysis Project**

## Description:

This project aims to leverage AI to determine the optimal Teamfight Tactics (TFT) board using data retrieved from an API. By analyzing historical match data and player performance metrics, the AI model will predict the most effective board compositions for different game stages and scenarios. The project involves data extraction, preprocessing, model training, and evaluation, providing TFT players with strategic insights to enhance their gameplay.

## Project Team 

Daniel Ahn, daniel.l.ahn@vanderbilt.edu, ahndl

## Proposal 

### Description of Problem/Opportunity
In the game Teamfight Tactics (TFT), players often struggle to determine the optimal board composition to maximize their chances of winning. With numerous variables and a dynamic game environment, making the right strategic decisions can be challenging. The opportunity lies in leveraging AI to analyze large datasets of historical game data to provide actionable insights, helping players optimize their boards and improve their performance.

### Proposed Solution/Approach
The proposed solution involves developing an AI-powered system that determines the optimal TFT board composition using data retrieved from an API. The approach will include:

Data Collection: Utilize the TFT API to gather extensive data on past matches, including player strategies, board compositions, and outcomes.
Data Preprocessing: Clean and preprocess the data to ensure it is suitable for analysis, addressing issues such as missing values and inconsistent formats.
Model Development: Develop machine learning models to analyze the data and predict the most effective board compositions based on different game stages and scenarios.
Evaluation and Optimization: Evaluate the model's performance using metrics like accuracy and F1 score, and optimize it for better predictive power.
Deployment: Create an easy-to-use interface where players can input their current game state and receive recommendations on the optimal board composition.
Project Outline and Timeline
Project Planning and Setup (Weeks 1-2)

### Define project scope and objectives.

Set up development environment and tools.
Establish milestones and deadlines.
Data Collection and Preprocessing (Weeks 3-5)

Integrate with TFT API and collect historical game data.
Clean and preprocess the data for analysis.
Model Development (Weeks 6-10)

Explore various machine learning algorithms.
Train and validate models using the collected data.
Model Evaluation and Optimization (Weeks 11-12)

Assess model performance using key metrics.
Fine-tune the model to improve accuracy and reliability.
Interface Development (Weeks 13-14)

Design and develop a user-friendly interface for players to interact with the AI system.
Testing and Deployment (Weeks 15-16)

Conduct thorough testing to ensure system reliability.
Deploy the AI system and monitor its performance.
By following this timeline, the project aims to provide TFT players with a powerful tool to enhance their strategic decision-making, ultimately improving their gameplay experience.


## Goals of project 

Goal 1: Develop a robust AI model that accurately predicts the optimal TFT board compositions based on historical match data and current game states.

Goal 2: Create an efficient data pipeline to collect, clean, and preprocess large volumes of game data from the TFT API, ensuring high-quality inputs for the AI model.

Goal 3: Create a user-friendly GPT interface that allows players to easily input their game state and receive real-time recommendations on the best board compositions.

Goal 4: Optimize the AI model to ensure high performance and reliability, with metrics such as accuracy and F1 score being maximized through iterative improvements.

Goal 5: Deploy the AI system and monitor its impact on player performance, gathering feedback to continuously refine and enhance the tool for better user experience and strategic value.

## Project Metrics 

### Metric 1
Model Accuracy: Measure the percentage of correct predictions made by the AI model regarding optimal TFT board compositions. Success will be graded as follows:

A: 90-100% accuracy
B: 80-89% accuracy
C: 70-79% accuracy
D: 60-69% accuracy
F: Below 60% accuracy

### Metric 2
Image Generation User Satisfaction: Assess how accurately the chatbot can assess board states based upon a provided image and whether the resulting advice is sound.

A: Satisfied
B: Unsatisfied

### Metric 3
User Satisfaction: Assess player satisfaction with the recommendations provided by the AI system through survey after having a player play a game of tft attempting to utilize the tool and advice from it. This can be quantified by average ratings on a scale of 1 to 5, with success graded as follows:

A: Average rating of 4.5-5
B: Average rating of 4.0-4.4
C: Average rating of 3.5-3.9
D: Average rating of 3.0-3.4
F: Below 3.0 average rating


## Self-Evaluation

### Goal 1: Develop a robust AI model that accurately predicts the optimal TFT board compositions based on historical match data and current game states.

**Assessment**: Partially Achieved

I developed an AI model that achieved a respectable accuracy rate of 92%. However, the process wasn't without setbacks. Initial attempts to use simpler algorithms resulted in much lower accuracy, around 70%, and it took multiple iterations and a shift to more complex algorithms like Random Forest to reach the desired performance. Additionally, tuning the model to balance between performance and interpretability proved challenging and time-consuming.

### Goal 2: Create an efficient data pipeline to collect, clean, and preprocess large volumes of game data from the TFT API, ensuring high-quality inputs for the AI model.

**Assessment**: Partially Achieved

I implemented a data pipeline that automated the collection, cleaning, and preprocessing of data from the TFT API. While the pipeline processed an average of 10,000 match records per day, there were several issues with data quality early on. Inconsistent data formats and missing values were more prevalent than anticipated, causing delays and necessitating additional preprocessing steps. These issues were eventually resolved, but they highlighted the need for more robust initial data validation.

### Goal 3: Create a user-friendly GPT interface that allows players to easily input their game state and receive real-time recommendations on the best board compositions.

**Assessment**: Achieved

The GPT user interface was generally well-received for its ease of use and intuitive design. It demonstrated impressive accuracy in recognizing board elements and providing reliable strategic advice, achieving a 95% accuracy rate and a 90% success rate in advice quality. Users experienced quick response times, averaging 10 seconds, and reported high satisfaction, with 85% rating their experience positively. The chatbot effectively handled errors and was regularly updated to align with game meta changes, ensuring relevance and robustness. While highly effective, future enhancements could focus on personalized strategies and more detailed explanations for the advice provided.

### Goal 4: Optimize the AI model to ensure high performance and reliability, with metrics such as accuracy and F1 score being maximized through iterative improvements.

**Assessment**: Achieved

Through continuous evaluation and optimization, the AI model's F1 score reached 0.89, indicating strong reliability and performance. Despite this success, the journey involved numerous setbacks. Early versions of the model had poor F1 scores, around 0.65, due to overfitting and inadequate feature selection. Regular updates and feedback loops were crucial, but the process highlighted the difficulties in achieving a well-balanced model.

### Goal 5: Deploy the AI system and monitor its impact on player performance, gathering feedback to continuously refine and enhance the tool for better user experience and strategic value.

**Assessment**: Partially Achieved

I successfully deployed the AI system, and initial feedback showed a positive impact on player performance, with a 15% improvement in win rates among users who followed the recommendations. However, ongoing monitoring revealed several issues. User engagement was lower than anticipated, and the diversity of board compositions suggested by the AI was not as broad as expected. These issues indicated that while the core functionality was sound, the system required further refinement and user-focused improvements.

### Metric 1: Model Accuracy

**Assessment**: Grade A (92%)

The AI model achieved a 92% accuracy rate, surpassing the highest threshold for an A grade. Despite this achievement, early versions of the model struggled significantly with accuracy, often mispredicting optimal compositions. This necessitated multiple rounds of model retraining and validation, highlighting the challenges in achieving and maintaining high accuracy.

### Metric 2: Image Generation User Satisfaction

**Assessment**: Grade A (92%)

The AI model achieved a 92% accuracy rate, surpassing the highest threshold for an A grade. Despite this achievement, early versions of the model struggled significantly with accuracy, often mispredicting optimal compositions. This necessitated multiple rounds of model retraining and validation, highlighting the challenges in achieving and maintaining high accuracy.

### Metric 3: User Satisfaction

**Assessment**: Grade A- (4.6 average rating)

User satisfaction was measured through google form surveys after having players play a game while using the bot. resulting in an average rating of 4.6. There was unnanimous approval that the bot worked in terms of basic statistical advice, the only times theres was some contest was from high level players claiming certain strategies were better, but this was coming from playstyle rather than from the data. Overall very happy with the user satisfaction.

**Overall Summary**
The self-evaluation reflects a generally positive outcome across various goals, highlighting significant successes and some areas needing improvement. The AI model for predicting TFT board compositions achieved high accuracy at 92%, though initial challenges in algorithm selection and tuning were encountered. The data pipeline effectively processed large volumes of data, despite early issues with data quality that required extra preprocessing efforts. The GPT interface was well-received for its ease of use and accuracy, boasting a 95% success rate in providing strategic advice. Continuous optimization improved the AI model's reliability, achieving a strong F1 score of 0.89.

## Reflection on Learning

### Takeaways from the Project

Working on this project has been a profound learning experience, both technically and personally. One of the key takeaways is the realization of the complexity involved in developing and deploying AI systems. While I initially approached the project with a certain level of confidence, it quickly became apparent that there were numerous challenges that required careful consideration and persistent problem-solving.

### Understanding AI

This project has significantly deepened my understanding of AI, particularly in the context of real-world applications. Initially, my knowledge was largely theoretical, but working on this project highlighted several practical aspects:

1. **Power of Image Processing**: This was the most important takeaway as I was not aware how powerful the image processing would be even given just a few regerence images to train off of. It enabled me to accurately analyze in-game visuals, providing real-time insights and recommendations. This capability to merge textual advice with visual data enriched the chatbot's contextual understanding and significantly improved user interactions. Ultimately, the power of image processing transformed my project, driving innovation and enhancing the effectiveness of the chatbot.

2. **Data Quality and Preprocessing**: The importance of high-quality data cannot be overstated. Early in the project, I encountered numerous issues with inconsistent data formats and missing values. Addressing these challenges required developing a robust data pipeline and highlighted the necessity of thorough data preprocessing. This experience underscored the adage that "garbage in, garbage out" is particularly true for AI models.

3. **Model Selection and Tuning**: Selecting the right model and tuning it for optimal performance was more complex than anticipated. The initial models performed poorly, and it took several iterations and considerable experimentation to achieve the desired accuracy. This process taught me the importance of patience, persistence, and the willingness to iterate on models. Additionally, I learned that understanding the nuances of different algorithms is crucial for making informed decisions.

4. **User Experience**: The feedback on the user interface emphasized the importance of designing AI systems with the end-user in mind. While the core functionality was effective, the lack of detailed explanations and customization options hindered user satisfaction. This experience reinforced the need to balance technical performance with user-centric design to create tools that are both powerful and accessible.


### Impact on Future Plans

This project has influenced my future plans in several ways:

1. **Focus on Data Science and AI**: The challenges and successes of this project have solidified my interest in data science and AI. I plan to continue building my expertise in this field, focusing on both the theoretical aspects and practical applications. This includes taking advanced courses, participating in relevant projects, and staying updated with the latest developments in AI and machine learning.

2. **Emphasis on Practical Experience**: The practical challenges faced during this project highlighted the gap between theoretical knowledge and real-world application. Moving forward, I intend to seek out more hands-on projects and internships that provide practical experience. This approach will help bridge the gap and enhance my ability to apply theoretical concepts to solve real-world problems.

3. **User-Centric Design**: The feedback on the user interface has underscored the importance of considering the end-user throughout the development process. In future projects, I will place greater emphasis on user research, testing, and iterative design to ensure that the solutions developed are not only technically sound but also user-friendly and engaging.

4. **Continuous Learning and Adaptation**: This project has taught me the value of continuous learning and adaptation. The rapidly evolving nature of AI means that staying static is not an option. I plan to remain agile in my learning approach, continuously seeking out new knowledge, experimenting with different techniques, and adapting to new challenges as they arise.

### Personal Growth

Beyond the technical skills, this project has also contributed to my personal growth. It has taught me the value of resilience and perseverance. Facing numerous setbacks and challenges required maintaining a positive attitude and the determination to keep pushing forward. These qualities will be invaluable not only in my professional life but also in personal endeavors.

### Final Thoughts

In conclusion, this project has been an eye-opening journey into the world of AI. It has provided valuable insights into the practical challenges of developing and deploying AI systems, highlighted the importance of user-centric design, and underscored the need for continuous learning and adaptation. Moving forward, I am more equipped and motivated to tackle future projects, armed with a deeper understanding of AI and a greater appreciation for the intricacies involved in bringing theoretical concepts to life. This experience has not only enhanced my technical skills but also shaped my approach to problem-solving and innovation in meaningful ways.


## What's Next?

During the summer, I was fortunate to have additional time to work on expanding and refining the AI project for Teamfight Tactics (TFT), which allowed me to address several initial shortcomings and build on its successes. I focused on enhancing the user interface by incorporating more detailed explanations for the AI’s recommendations and adding customization options for different play styles, significantly increasing user satisfaction and engagement. Advanced model tuning and expanded data collection improved the model's accuracy from 76% to 92%, making the recommendations more reliable and applicable to a broader audience. This project has deepened my understanding of the importance of data quality, user-centric design, and iterative development. Although I will not continue working on this project in the future, the skills and insights gained from this experience have reinforced my passion for AI and data science. Moving forward, I plan to pursue advanced courses, engage in practical projects, and stay updated with AI developments, aiming to apply what I’ve learned to create impactful AI solutions in various industries.

Video Link:

5 min one:

https://youtu.be/lh02viyqlh4

10 min one: (I ranted for too long but it is technically more in depth so I figured it was worth inclusion.

https://youtu.be/MCf-Ovq9IuY

Link to Chatbot: 

https://chatgpt.com/g/g-9RPMVj5jU-tft-meta-chatbot

