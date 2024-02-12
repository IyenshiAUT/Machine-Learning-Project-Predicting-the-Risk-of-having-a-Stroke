
<html lang="en">
<body style="font-family: 'Arial', sans-serif; margin: 20px;">

  <h1 style="color: #000066;">Predicting the Risk of having a Stroke using Demographics and Health Factors a Person</h1>

  <h2 style="color: #000066;">Overview</h2>
  <img src ="https://tse1.mm.bing.net/th?id=OIP.1VJKfDu_CCGShGGKAKE9RAHaE8&pid=Api&P=0&h=220" align="right"/>

  <p>A considerable number of people are dying a year due to strokes because many of them have not any idea whether they are like to face this condition. So the model that we are going to implemented can be used in health sectors for predicting whether a person is going to have a stroke and if the result is possible they can take necessary actions to prevent from having a stroke.</p>

  <h2 style="color: #000066;">Defining ML Problem</h2>
  <ul>
    <li>Task T: Predicting the risk of having a stroke</li>
    <li>Performance Measure P: Percent of correctly predicted result out of the total test data set</li>
    <li>Training experience E: Using a set of data with given the stroke possibility</li>
  </ul>


  <h2 style="color: #000066;">Algorithms Used</h2>
<ul>
    <li>Logistic Regression</li>
    <li>Naive Bayes</li>
  </ul>

  <h2 style="color: #000066;">Directory Structure</h2>

  <p>Give an overview of the project's directory structure to help users navigate through your code.</p>

  <pre style="font-family: 'Courier New', monospace; background-color: #f8f8f8; padding: 10px; border: 1px solid #ddd; border-radius: 4px; overflow-x: auto;">
    .
    ├── EE5253_2023_Code_Group01.ipynb(Includes the code)
    ├── EE5253_2023_Code_Group01.pdf(Includes the research paper)
    ├── README.md
    └── health-dataset-stroke-data.csv
  </pre>
   <h2 style="color: #000066;">Workflow</h2>
   <img src = "https://private-user-images.githubusercontent.com/139426452/304016787-a87e63dc-eb0e-45ac-8d6c-9204d6a361b3.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDc3MzI2MjQsIm5iZiI6MTcwNzczMjMyNCwicGF0aCI6Ii8xMzk0MjY0NTIvMzA0MDE2Nzg3LWE4N2U2M2RjLWViMGUtNDVhYy04ZDZjLTkyMDRkNmEzNjFiMy5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMjEyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDIxMlQxMDA1MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1kZDc5ZDQ5NTA0YTZkNGZhZTQyMzI2MzBlZWY1M2IyNjNmNTgzYTg0ZGYwZTgyZGQwNDQxODQ2NDQ4NTQ5MTEzJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Pqu-ZqImHfZ9xv3KSLC9-xOVUVRfEaJy71B8PYzthB0" width="75%/>

  <h2 style="color: #000066;">Results</h2>
  <div style="display: flex;">
      <h4>Performance of two models</h4>
  <img src="https://private-user-images.githubusercontent.com/139426452/304016749-e06b7d86-d316-4a87-9a73-f00e967b8d9f.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDc3MzI2MjQsIm5iZiI6MTcwNzczMjMyNCwicGF0aCI6Ii8xMzk0MjY0NTIvMzA0MDE2NzQ5LWUwNmI3ZDg2LWQzMTYtNGE4Ny05YTczLWYwMGU5NjdiOGQ5Zi5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMjEyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDIxMlQxMDA1MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jZTY2NzJkYzM3MmE4YTU2MTVlOTI5OGM0ZGZlMzRhZTM0ZGQ3MTA2YjZhMDZhNDk0Yjk2MzAyNWJiMDI1MDIwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.LMKkU6R9p1F8AHaiUtdADCJ1vFxQf8qxrKCnD07PnXI" width = "50%"/>
  <h4>ROC Curve for two models</h4>
<img src = "https://private-user-images.githubusercontent.com/139426452/304016709-96dfb19c-973e-48c8-9735-fb8866f5a4ce.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDc3MzI2MjQsIm5iZiI6MTcwNzczMjMyNCwicGF0aCI6Ii8xMzk0MjY0NTIvMzA0MDE2NzA5LTk2ZGZiMTljLTk3M2UtNDhjOC05NzM1LWZiODg2NmY1YTRjZS5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMjEyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDIxMlQxMDA1MjRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05NWUxYjA5Y2Y5N2E1YmEwYjc4NTAyNWU4MWJkNjkwNTFhNjY0NjRkZDlkYjdhZWVhZGYxY2QyMjY2NWVkZWI2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.omsRoVbgeU8RAPjZDf2IDLayp_aXo2NI0RwBCtTLhew" width="50%"/>
    </div>

  


  <h2 style="color: #000066;">License</h2>

  <p>This project is licensed under the <span style="color: #e74c3c;">MIT License</span> - see the <a href="LICENSE.md" style="color: #e74c3c;">LICENSE.md</a> file for details.</p>

  

</body>
</html>
