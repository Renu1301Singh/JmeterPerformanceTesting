# Performance Testing Repository

Welcome to the Performance Testing Repository! This repository is dedicated to showcasing various performance testing scenarios using Apache JMeter. Performance testing using JMeter involves assessing the performance and scalability of web applications, APIs, and servers under various load conditions. JMeter offers a range of components that aid in creating realistic test scenarios, executing tests, and analyzing results. 

The repository contains test scripts, configurations, and data files for conducting performance tests on web applications using Apache JMeter. It covers a wide range of functionalities and scenarios, including:

- Basic Test Plan Creation
- Recording Browsing Scenarios with HTTP(S) Test Script Recorder
- Adding Assertions for Response Validation
- Using Timers to Simulate Real User Think Time
- Designing Load Test Plans with Increasing User Load
- Analyzing Test Results with Different Listeners



## Tasks Performed  Are:

> Task 1: Create a basic Test Plan and describe the purpose of each component added.
> Objective: Familiarize yourself with the JMeter GUI. Explore elements like Test Plan, Thread Group, Samplers, Listeners, etc.

> Task 2: Record a simple browsing scenario on a demo website (e.g., navigating through pages) using the HTTP(S) Test Script Recorder and run the test.
> Objective: Understand how to test a web application.

> Task 3: Create a test that logs into a demo web application using multiple user credentials stored in a CSV file.
> Objective: Learn how to use external data for testing.

> Task 4: Add assertions to a test plan to validate the presence of specific texts in the response of a web request.
> Objective: Grasp how to verify the correctness of a response.

> Task 5: Insert a Constant Timer to add a delay between requests in a test plan and observe the impact on the load test results.
> Objective: Understand the use of timers to simulate real user think time

> Task 6: Design a load test plan for a web page with increasing users (thread) over time and analyze the results.
> Objective: Understand the basics of load testing.

> Task 7: Run a test and use different Listeners (e.g., View Results Tree, Aggregate Report) to analyze and interpret the data collected during the test.
> Objective: Learn to interpret test results for better insights.

## Requirements

To run the tests in this repository, you'll need the following:

1. **Apache JMeter**: Install Apache JMeter on your local machine. You can download it from the official Apache JMeter website: [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi)

2. **Java Runtime Environment (JRE)**: Ensure you have Java Runtime Environment installed on your machine as Apache JMeter requires Java to run.

3. **Web Application URL**: For recording browsing scenarios or testing specific web applications, you'll need the URL of the web application under test.

## Getting Started

Follow these steps to get started with the repository:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Renu1301Singh/JmeterPerformanceTesting.git
    ```

2. Install Apache JMeter on your machine if you haven't already.

3. Open Apache JMeter and navigate to the directory containing the `.jmx` files in the cloned repository.

4. Open the desired JMeter test plan file (.jmx) in Apache JMeter.

5. Configure the test plan as needed (e.g., update the target URL, adjust thread groups, add assertions).

6. Run the test plan in Apache JMeter and analyze the results using various listeners.


### The document link is attached below :
  " https://docs.google.com/document/d/1-cT-qrKHiTw-2vtjYFhK-zgp3ta9Hls7yDBw6YaM08U/edit?usp=sharing "
