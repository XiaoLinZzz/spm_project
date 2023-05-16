# VR1Family Charity Aid Services Web Application


## Tech

![VScode](https://img.shields.io/static/v1?label=VScode&message=v1.72&color=3374FF&style=for-the-badge&logo=Visual-Studio-Code)
![Node.js](https://img.shields.io/static/v1?label=Node.js&message=v14.16.0&color=339933&style=for-the-badge&logo=Node.js)
![MongoDB](https://img.shields.io/static/v1?label=MongoDB&message=v4.4.4&color=47A248&style=for-the-badge&logo=MongoDB)
![Express](https://img.shields.io/static/v1?label=Express&message=v4.17.1&color=000000&style=for-the-badge&logo=Express)


## Features
- Manage aid items, including name, category, quantity, and details
- Manage aid kits, which are collections of aid items
- Manage recipient information, including general and private data
- View and manage aid categories and their respective quantities and statuses
- Basic user interface for easy navigation and data management


## Installation
1. Make sure you have [Node.js](https://nodejs.org/en) and [MongoDB](https://www.mongodb.com/) installed on your machine.

2. Clone the repository:
```
git clone https://github.com/XiaoLinZzz/VR1Family-Charity-Aid-Services.git
```

3. Navigate to the project directory and install dependencies:
```
cd aid-distribution-platform
npm install
```

4. Create a .env file in the root folder of the project and add the following environment variables:
```
PORT=3001
URL=http://localhost
MONGO_URI=<your_mongodb_connection_string>
```
Replace `<your_mongodb_connection_string>` with the connection string for your MongoDB database.

5. Start the server:
```
npm start
```
The server should now be running on `http://localhost:3001`.



## Contributing
1. Fork the project repository and create a new branch for your feature or bugfix.

2. Make your changes and commit them to your branch.

3. Push your branch to your forked repository on GitHub.

4. Create a pull request to merge your changes into the main repository.

5. Once your pull request is reviewed and approved, it will be merged into the main repository.

Please follow the code style and conventions already present in the project.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.