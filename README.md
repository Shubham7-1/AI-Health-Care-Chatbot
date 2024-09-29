# Health Care Chatbot

## Overview

The Health Care Chatbot is a desktop application developed using Python and Tkinter. It leverages a Decision Tree Classifier to provide a diagnosis based on user input symptoms. The chatbot guides users through a series of questions, analyzes their responses, and suggests potential diseases along with recommended doctors for consultation.

## Features

- **User Authentication:** Allows users to register and log in.
- **Symptom Analysis:** Collects user input on symptoms and uses a decision tree model for diagnosis.
- **Doctor Recommendations:** Suggests doctors based on the diagnosed disease, with hyperlinks to their profiles.
- **User-friendly Interface:** Simple and intuitive GUI for ease of use.

## Technologies Used

- **Python**: Primary programming language.
- **Tkinter**: For GUI development.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For implementing the Decision Tree Classifier.
- **CSV**: For data storage and retrieval.

## Installation

1. Clone this repository to your local machine using:
   ```bash
   git clone <repository-url>
   ```
   
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```

3. Install the required packages:
   ```bash
   pip install pandas numpy scikit-learn
   ```

4. Ensure you have the following CSV files in the project directory:
   - `Training.csv`: Contains training data for the model.
   - `Testing.csv`: Contains testing data.
   - `doctors_dataset.csv`: Contains doctor names and their links for recommendations.

5. Run the application:
   ```bash
   python <script-name>.py
   ```

## Usage

1. Start the application, and you will see the login screen.
2. If you are a new user, click on **Register** to create an account.
3. After registration, log in with your credentials.
4. Once logged in, the chatbot will start asking questions regarding your symptoms.
5. Respond with "Yes" or "No" to the questions.
6. After all questions, the chatbot will provide a potential diagnosis and recommend doctors for consultation.

## Data Files Structure

- `Training.csv`: Contains features and prognosis for training the model.
- `Testing.csv`: Used for testing purposes.
- `doctors_dataset.csv`: Contains doctor names and descriptions.

## Future Improvements

- Enhance the model with additional data for improved accuracy.
- Implement a more complex user interface with additional features.
- Introduce more diseases and corresponding symptoms for a wider range of diagnoses.


