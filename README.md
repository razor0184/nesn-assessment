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
  - [Client Application Testing](#client-application-testing)
  - [Load Testing](#load-testing)
- [Running the Tests](#running-the-tests)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The NESN Assessment project aims to test the integration of CompanyB's API into CompanyA's live streaming platform. The goals are to ensure that the API scales under load, maintains backward compatibility, and integrates seamlessly across multiple client applications.

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

### API Testing

1. **Run Postman/Newman tests**:
   ```bash
   newman run api-tests.postman_collection.json
