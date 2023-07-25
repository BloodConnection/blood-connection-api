# Blood Connection API
> An API for a Comprehensive Blood Donation platform to promote blood donation and streamline the process.

## Connected Repositories
_**This Project consists of two Repositories:**_ <br>
- **Blood Connection Frontend**. It can be accessed [HERE](https://github.com/BloodConnection/blood-connection) <br>
- **Blood Connection Backend**. It can be accessed [HERE](https://github.com/BloodConnection/blood-connection-api) <br>

## Deployments
The Blood Connection Official website, Backend and API, Blood Connection application are deployed at the following links:
### Official Website
> [BloodConnection Website](https://bloodconnection.github.io) <br>

### Blood Connection API
> [Vercel Link](https://blood-connection-api.vercel.app/api/)

### Blood Connection Web Application
> [Netlify Link](https://blood-connection.netlify.app/)



## Specifications Document
The project specifications were prepared by PRODUCT_MANAGER_LINKEDIN with meetings with Product_Designer_LINKEDIN and SoftwareDeveloper_LINKEDIN.
> [Specs Link](https://LINK_GOES_HERE)


## Requirements

To run the Blood Connection API locally, the following requirements must be met:

- Operating System: Any modern operating system (`Windows`, `macOS`, `Linux`)
- Web Browser: Latest version of `Chrome`, `Firefox`, `Safari`, or `Edge`
- Server: `Node.js` runtime environment <br><br>

## Installation

To install and set up Blood Connection locally, follow these steps:

### Clone
Clone the Blood Connection repository from [Blood Connection](https://github.com/BloodConnection/blood-connection) with the command:
```
git clone git@github.com:BloodConnection/blood-connection.git
```
### Setup Environment
Install `Node.js` from [Node.js website](https://nodejs.org/en/download) and configure it on your system.

### Install Packages
Navigate to the `root` of project directory and run the following command to install the required dependencies
```
npm install
```
### ENV File
Configure the database connection and `Access Token` and `Refresh Token` by updating the `.env` file, placed in the project root directory.
`.env` file should contain:
  - Database: Put the `Database_URL` Connection String of SQL database.
  - `ACCESS_TOKEN_SECRET` and `REFRESH_TOKEN_SECRET` in `.env` file.
   For example:

```
DATABASE_URL='mysql://<username>:<password>@aws.connect.psdb.cloud/smart-coach-api?sslaccept=strict'
ACCESS_TOKEN_SECRET='RANDOM_STRING'
REFRESH_TOKEN_SECRET='RANDOM_STRING'
```

### Database Migration
Run the database migration script to set up the required tables and schema. In case of Planet Scale, run
```
npx prisma db push
```

### Run Server
Start the application server using the command
```
npm run dev
```

### API URL
Access the Smart Coach API at
```
http://localhost:8000/api/
```
<br>


## Usage

Once the `Blood Connection API` is up and running, users can access it using `Postman`. Use the desktop version of [Postman](https://www.postman.com/downloads/).

API access and usage details are provided in the `API documentation` section.<br><br>

## API Documentation

The detailed API documentation for `Blood Connection` can be found at [API Documentation URL](https://blood-connection-api.vercel.app/api-docs). It provides information about available endpoints, `request/response` formats, authentication mechanisms, and examples of `API usage`. The documentation [API Documentation](https://blood-connection-api.vercel.app/api-docs) helps developers integrate Blood Connection with other systems or build custom applications on top of it.<br><br>


## Code Contributors

👤 **Rao Akif**
- GitHub: [@raoakif](https://github.com/raoakif)
- Twitter: [@raoakif](https://twitter.com/raoakif)
- LinkedIn: [Rao Akif](https://linkedin.com/in/raoakif)
<br>

## Acknowledgments
👤 **Project Manager:**   [Muhammad Awais Hanif](https://linkedin.com/in/muhammadawaishanif). <br><br>
👤 **Project Designer:**  [USER NAME](https://linkedin.com/in/USERNAME).
  - Thanks to my peers who are always there to offer support.
  - Contributions, issues, and feature requests are welcome!
  - Feel free to check the [issues page](../../issues/).
<br>
 
## Contributing

We welcome contributions from other developers to enhance Blood Connection. To contribute to the project, please follow these guidelines:

1. Fork the Blood Connection repository and create a new branch for your feature or bug fix.
2. Make your changes, ensuring they follow the project's coding conventions and best practices.
3. Write unit tests to cover your code changes and ensure existing tests pass.
4. Submit a pull request with a clear description of your changes and any relevant information.

<br>

## Show your support

Give a ⭐️ if you like this project!
<br>


## License

Blood Connection is distributed under the [MIT License](./MIT.md). You are free to use, modify, and distribute the project under the terms of this license.
