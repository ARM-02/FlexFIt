# FlexFit

README FLEXFIT 


# Description: 

FlexFit is an innovative app designed to empower users by allowing them to create and follow personalized workout plans. Built using Python, a versatile and widely-used programming language known for its readability and robust libraries, FlexFit ensures efficient and reliable performance for users of all technical levels.

This project is important for our team as we faced real-world challenges in coding and problem-solving. FlexFit reflects our commitment to delivering a seamless experience for fitness enthusiasts. Future updates will include enhanced features and tools to further elevate the user experience.


# Table of Contents
	1.	Installation and Setup
	2.	How to Use FlexFit
	3.	Database
	4.	Further Improvements
	5.	Credits
	6. 	License


# Installation and Setup
To get started with FlexFit, follow these steps:
1. Download the Exercise Database:
	- Navigate to the project main page on github and locate the “exercise_database.csv file”
	- Click on the three dots to the right of the page and download the file. Note the folder where you save it.
2. Access the Code:
	- Go back to the main page of the repository and open the FlexFit_Final_Working_Code.ipynb file.
	- Click the “Open in Colab” button at the top center of the page to open the code in Google Collaborator.
3. Set Up Google Collaborator:
	- If you don't have google colaboratory connected to google drive:
		- Open drive and click '+ New' as if you were to create a new folder or file
		- Click on 'more'. It's the last option.
		- Click on 'Connect more apps'
		- Search for ' Colaboratory' 
		- Click on it, and install it.
	- Run the first code cell to initialize the environment.
4. Upload the Exercise Database:
	- Scroll down the notebook until you see the “Choose Files” option.
	- Click it and upload the exercise_database.csv file you downloaded in step 1.
5. Start Using FlexFit:
	- Once the database is uploaded, the program will start. You can now explore and interact with FlexFit. Enjoy!

* The code was developed using Python 3.10.12

  
# How to Use FlexFit
FlexFit allows users to:.
	•	Create custom workout plans tailored to specific fitness goals.
	•	Access past gym workout plans
	•	Search for a variety of exercises based on keywords


# Database
The raw dataset consists of 7 different features: Category, Exercise Name, Description, Targeted Muscles, Equipment Needed, Difficulty, Repetitions. 
Additionally, the exercises are divided into 11 different categories based on different muscles (ex.  back_exercises) or objectives (ex. cardio_exercises) . 


# Further Improvements
The implementation of simple search algorithms and  hashtable structures was sufficient for FlexFit’s MVP. For a small scale implementation, this was the most efficient solution. However, in case of future scalability the implementation of more advanced algorithms and data structures, like a binary search tree, must be adopted to ensure the continuity of the app’s efficiency. 


# Credits
This project was collaboratively developed by:
- Andrea Restrepo - arestrepo.ieu2023@student.ie.edu
- Lucia Burmeister- lburmeister.ieu2023@student.ie.edu
- Francesca Lentini - flentini.ieu2023@student.ie.edu
- Juan Jose Jaramillo - jjaramillo.ieu2023@student.ie.edu
- Andres Cuellar - acuellar.ieu2023@student.ie.edu


# License
This project is licensed under the GNU General Public License v3.0.
You are free to:
	•	Share: Copy and redistribute the material in any medium or format.
	•	Adapt: Remix, transform, and build upon the material for any purpose, even commercially.
Under the following terms:
	•	Attribution: Provide appropriate credit, a link to the License, and indicate if changes were made.
	•	ShareAlike: If you remix or build upon the material, you must distribute your contributions under the same License.
For more details, visit the GPL License Overview.

