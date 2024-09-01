# NESN Assessment

## Overview

This repository contains the test plans, scripts, and documentation for the NESN Assessment project. The project includes various testing approaches to ensure the scalability, performance, and functionality of a live streaming platform after integrating a newly acquired API.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation and Setup](#installation-and-setup)
- [Test Plans](#test-plans)
  - [Functional Test Plan](#functional-test-plan)
  - [Automated Test Plan](#automated-test-plan)
  - [Load Test Plan](#load-test-plan)
- [Test Scripts](#test-scripts)
  - [API Testing](#api-testing)
- [Running the Tests](#running-the-tests)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The NESN Assessment project aims to test the integration of CompanyB's API into CompanyA's live streaming platform. The goals are to ensure that the API scales under load, maintains backward compatibility, and integrates seamlessly across multiple client applications.

![Screenshot of the application](https://github.com/razor0184/nesn-assessment/blob/main/LiveStreamingProduct_pipelineDiagram.png)

## Test Plans

### Functional Test Plan

The functional test plan covers all major functionalities of the integrated API and client applications. It includes scenarios like user authentication, content posting, and viewing, ensuring cross-platform compatibility.

- [Functional Test Plan Document](https://github.com/razor0184/nesn-assessment/blob/main/functionalTestPlan.docx)

### Automated Test Plan

The automated test plan focuses on reducing manual effort by automating key test cases across API and client applications. Tools like Selenium, Postman, and Appium are recommended.

- [Automated Test Plan Document](https://github.com/razor0184/nesn-assessment/blob/main/automatedTestPlan.docx)

### Load Test Plan

The load test plan ensures that the platform can handle expected user loads during live streams and identifies the system’s breaking points under stress.

- [Load Test Plan Document](https://github.com/razor0184/nesn-assessment/blob/main/loadTestPlan.docx)

## Test Scripts

### API Testing

Automated scripts for validating API endpoints, ensuring data consistency, and handling error cases.

- [API Test Scripts](https://github.com/razor0184/nesn-assessment/blob/main/nesn-assessment.postman_collection.json)

## Running the Tests

### Step 1: Download and Install Postman

1. **Go to the Postman website**: 
   - Visit [Postman's official website](https://www.postman.com/downloads/).
   
2. **Download Postman**:
   - Choose the appropriate version for your operating system (Windows, macOS, or Linux).
   - Click the **Download** button to get the installer.

3. **Install Postman**:
   - Once the download is complete, open the installer file.
   - Follow the on-screen instructions to install Postman on your computer.

### Step 2: Launch Postman

1. **Open Postman**:
   - After installation, launch the Postman application.
   - You may need to sign in with your Postman account or create a new one if you don't have an account.

### Step 3: Import a JSON File

1. **Navigate to the Import Button**:
   - In the Postman app, look for the **Import** button at the top-left corner of the interface and click on it.

2. **Select the JSON File**:
   - In the Import dialog, click on the **Upload Files** button or drag and drop your JSON file into the window.

3. **Confirm the Import**:
   - Once your JSON file is selected, Postman will automatically detect it as a collection or environment (depending on the file content).
   - Click the **Import** button to add the file to your Postman workspace.

### Step 4: Run the Collection

1. **Open the Imported Collection**:
   - After importing, your collection should appear in the **Collections** tab on the left sidebar of the Postman interface.
   - Click on the collection name to expand and view its requests.

2. **Run a Request**:
   - Click on any request in the collection to open it in the main window.
   - Review the request details, such as method (GET, POST, etc.), URL, and parameters.

3. **Execute the Request**:
   - Click the **Send** button in the top-right corner to run the request.
   - Postman will send the request and display the response in the lower pane.

4. **Run All Requests in the Collection**:
   - If you want to run all requests in the collection sequentially, click on the **Run** button next to the collection name in the sidebar.
   - In the **Collection Runner** that opens, configure the run options (e.g., number of iterations, delay between requests).
   - Click **Start Run** to execute all the requests in the collection.

### Demo
[Click here to watch the video](https://github.com/razor0184/nesn-assessment/blob/main/screen-capture.webm)

### Additional Resources

- [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/): Learn more about how to use Postman effectively.
- [Postman Community](https://community.postman.com/): Get help from the Postman community.

## Contributing
Contributions are welcome! Please follow these steps:

 - Fork the repository.
 - Create a new branch for your feature/bugfix.
 - Commit your changes and push to your branch.
 - Submit a pull request detailing your changes.
   
## License
None
