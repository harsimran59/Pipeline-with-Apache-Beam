# Pipeline-with-Apache-Beam
The project highlights how to use the parallel computing framework of Apache Beam to reduce latency. 

## Introduction
Apache Beam is an open-source, unified programming model designed to process large-scale, unbounded, and batch data processing pipelines. It provides a simple yet powerful API for building and executing data processing pipelines that can run on a variety of execution engines such as Apache Flink, Apache Spark, and Google Cloud Dataflow.
It works on the velocity feature of the big data. The data that is collected is dynamic data and it reduces the latency in the collection of the dynamic data. 
The concept of windowing involved helps to reduce the lag to a minimum. The windows are timed to last for say 30 minutes from the time of the last response received which helps to pick data that is generated closely within the 30 minutes range from each other. The windowing can be done based on other features besides time. Since there is an interest in the Dynamic data therefore, we look into the time factor for windowing.

## Why is it useful?
The logic is written only once and it can be run on different platforms like Spark, Flink, data flow, etc. This gives the flexibility to port the same logic to multiple execution platforms.
- Provides a unified programming model for batch and stream processing. 
- Supports multiple languages such as Java, Python, Go, and others.
- Supports multiple execution engines, allowing for the portability of pipelines across different systems.
- Provides advanced features such as windowing, triggers, and side inputs.
- Offers a flexible and scalable architecture for handling large volumes of data.
- It is used to reduce the latency of individual results.

  
## Installation of Apache Beam

To install the Apache Beam Python SDK, you can follow these steps:
- **Install Python 3.x:** Make sure you have Python 3.x installed on your machine. You can download it from [the official Python website](https://www.python.org/downloads/).
- **Install pip:** Pip is the package installer for Python. You can check if pip is installed by running the command pip --version in your terminal.
      If it is not installed, you can download it from [here](https://pip.pypa.io/en/stable/installing/).
- **Install Apache Beam:** Once you have pip installed, you can install Apache Beam by running the command pip install apache-beam in your terminal.
      Run the following commands in the command prompt as an administrator:  **pip install apache-beam**
- **Verify the installation:** To verify that Apache Beam has been installed successfully, run the following command in your terminal: **python -c "import apache_beam as beam; print(beam.__version__)"**
      This prints the version number of Apache Beam that you have installed.

## Usage

This can be applied when reading from a streaming source and also keeping a check on user sessions. 
For example, when tracking usage or access to a resource or website from multiple users or keeping a record of the score of multiple users playing an online game simultaneously in a session.

## Conclusion

Overall, the components work together to provide a flexible and powerful platform for processing data at scale. 
By leveraging Apache Beam's unified programming model, developers can write data processing workflows that are portable across different execution engines, making it easier to move their pipelines between different cloud providers or on-premises environments.


