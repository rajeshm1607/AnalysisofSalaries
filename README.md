<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salary Prediction System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        .project-structure {
            white-space: pre;
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .code {
            background: #f4f4f4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .code pre {
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Salary Prediction System</h1>
        <img src="Salary%20Prediction%20System.jpg" alt="Salary Prediction System" style="max-width: 100%; border-radius: 5px;">

        <h2>🚀 Overview</h2>
        <p>The <strong>Salary Prediction System</strong> is a machine learning project aimed at predicting the salaries of employees based on various factors. This project uses a dataset to train and test the model and includes a Jupyter Notebook for implementation.</p>

        <h2>📁 Project Structure</h2>
        <div class="project-structure">
            <code>
                Salary-Prediction-System/<br>
                ├── .gitattributes<br>
                ├── LICENSE<br>
                ├── README.md<br>
                ├── Salary Prediction System.jpg<br>
                ├── Salary_Prediction.ipynb<br>
                └── dataset.csv
            </code>
        </div>
        <ul>
            <li><strong>.gitattributes</strong>: Git attributes for managing repository settings.</li>
            <li><strong>LICENSE</strong>: License information for the project.</li>
            <li><strong>README.md</strong>: Project documentation file.</li>
            <li><strong>Salary Prediction System.jpg</strong>: Image representing the project.</li>
            <li><strong>Salary_Prediction.ipynb</strong>: Jupyter Notebook containing the implementation of the salary prediction model.</li>
            <li><strong>dataset.csv</strong>: Dataset used for training and testing the model.</li>
        </ul>

        <h2>💻 Requirements</h2>
        <p>To run this project, you need to have the following installed:</p>
        <ul>
            <li>Python 3.x</li>
            <li>Jupyter Notebook</li>
            <li>pandas</li>
            <li>numpy</li>
            <li>scikit-learn</li>
            <li>matplotlib</li>
        </ul>
        <p>You can install the required packages using pip:</p>
        <div class="code">
            <pre><code>pip install pandas numpy scikit-learn matplotlib</code></pre>
        </div>

        <h2>📖 Usage</h2>
        <ol>
            <li><strong>Clone the repository</strong>:
                <div class="code">
                    <pre><code>git clone https://github.com/yourusername/Salary-Prediction-System.git</code></pre>
                </div>
            </li>
            <li><strong>Navigate to the project directory</strong>:
                <div class="code">
                    <pre><code>cd Salary-Prediction-System</code></pre>
                </div>
            </li>
            <li><strong>Open the Jupyter Notebook</strong>:
                <div class="code">
                    <pre><code>jupyter notebook Salary_Prediction.ipynb</code></pre>
                </div>
            </li>
            <li><strong>Run the cells</strong> in the notebook to train and test the salary prediction model.</li>
        </ol>

        <h2>📊 Dataset</h2>
        <p>The dataset (<code>dataset.csv</code>) contains the following columns:</p>
        <ul>
            <li><code>YearsExperience</code>: Number of years of experience of the employee.</li>
            <li><code>Salary</code>: Salary of the employee.</li>
        </ul>

        <h2>📜 License</h2>
        <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for more details.</p>

        <h2>🤝 Contributing</h2>
        <p>Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.</p>

        <h2>🙏 Acknowledgments</h2>
        <p>This project is inspired by various machine learning tutorials and resources available online.</p>
    </div>
</body>
</html>
