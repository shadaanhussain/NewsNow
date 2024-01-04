# NewsNow


## Project Details
In this project, I developed a web application using React and JavaScript, and I have utilized bootsrap for CSS styling to create a visually appealing and responsive user interface. The primary goal of this project was to built a web application which provides the latest news articles from all over the world. I placed a strong emphasis on ensuring a smooth and intuitive user experience, including the graceful handling of null and empty data cases.

The project's codebase is meticulously organized, with an emphasis on readability and adherence to best coding practices. To aid anyone interested in the project, I provided a comprehensive README that includes details on the project's folder structure and essential pointers for understanding the code. The GitHub repository is accessible to the public, enabling easy review and assessment by potential collaborators or employers.

This project not only demonstrates my proficiency in React, API integration, state management, and UI development but also underscores my commitment to maintaining developer-friendly practices. The use of Bootstrap for CSS styling ensures that the dashboard is aesthetically pleasing, user-friendly, and fully responsive across various devices, making it a valuable asset in any web development portfolio.


### Built With

- [React.js](https://react.dev/)
- [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)


# Getting Started
## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js**: Make sure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).

- **Code Editor**: You'll need a code editor to work on this project. We recommend using [Visual Studio Code](https://code.visualstudio.com/) for the best development experience.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/shadaanhussain/NewsNow.git

   ```
2. Go to the project folder
   ```sh
   cd Newsnow

   ```
3. Install packages with npm
   ```sh
   npm i
   ```
4. Start  your applicatoin using
   ```sh
   npm run start
   ```

# Components
## NavBar Component
The `NavBar` component contains name of all the category and country dropdown and a search. 

<div align="center">
    <img width="1007" alt="Screenshot 2023-11-06 at 7 12 37 PM" src="https://private-user-images.githubusercontent.com/75877797/294225657-b7c0d261-cbc1-45c1-bc74-5efbfe35c31d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDQzODI4OTEsIm5iZiI6MTcwNDM4MjU5MSwicGF0aCI6Ii83NTg3Nzc5Ny8yOTQyMjU2NTctYjdjMGQyNjEtY2JjMS00NWMxLWJjNzQtNWVmYmZlMzVjMzFkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMDQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTA0VDE1MzYzMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdmODRlMjE4MzY4YzIzNDU2OWZmZGVkNDEwY2MyNTE5NTE1NjIxZjI0Nzg4Mjg1YWMzMjViYmM0N2MxNDdmMTgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.ReG3To8eIpnbIZJjQOFIrZPWSt6IJevzljkRNsT9dsY">
</div>

## News Component
The `News` component shows all the news of the chosen category and country. 

<div align="center">
    <img width="1007" alt="Screenshot 2023-11-06 at 7 12 37 PM" src="https://private-user-images.githubusercontent.com/75877797/294225661-0743e05d-fc5f-4324-b344-e38316643abe.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDQzODI4OTEsIm5iZiI6MTcwNDM4MjU5MSwicGF0aCI6Ii83NTg3Nzc5Ny8yOTQyMjU2NjEtMDc0M2UwNWQtZmM1Zi00MzI0LWIzNDQtZTM4MzE2NjQzYWJlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMDQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTA0VDE1MzYzMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM4Y2M2NzRlMzczNzAxM2UxNTMzZDdlNTg2YmYxZDY5ZDYwMThmYzdkZDM4ZmQ3ZTkzYjIxNWY5NTNiY2RmM2MmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.fjTe2eEjTSHmg5Id-NWLLlGc652wyj4_QWQzTC4hUXU">
</div>

## NewsItem Component
The `NewsItem` component shows all the information about the news it has read more option which will redirect the user to the news link, it also the the news agency name on top right by which the news was published and it has share button which allow user to share the news with others. 

<div align="center">
    <img width="430" alt="Screenshot 2023-11-06 at 7 12 37 PM" src="https://private-user-images.githubusercontent.com/75877797/294225630-e85a16e2-ea5a-4343-b9fa-992357967d98.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDQzODI4OTEsIm5iZiI6MTcwNDM4MjU5MSwicGF0aCI6Ii83NTg3Nzc5Ny8yOTQyMjU2MzAtZTg1YTE2ZTItZWE1YS00MzQzLWI5ZmEtOTkyMzU3OTY3ZDk4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMDQlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTA0VDE1MzYzMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTc2NWU2MzIwMTZlMTY2ZDZjZDkyNmNjODNhMTFkODU4MWJhYzE5YTZlMGQzZWE4ZTk1ZTcxZDBmZDEyMWYxOWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.azp68UgnnyQ3JseEzMy6d-h7fVIbiLponhUmOnZjunE">
</div>
