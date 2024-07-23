# jmeter

## Installation
1. Download and install Apache JMeter from the [official website](https://jmeter.apache.org/download_jmeter.cgi).

## Running the Test
1. Open JMeter by running `jmeter.bat` (Windows) or `jmeter.sh` (Linux/Mac).
2. Open the test plan `petstore_load_test.jmx`.
3. Click on the start button (play icon) to run the test.

## Test Plan Details
- **Thread Group**: Configured with 20 threads and 10 minutes duration.
- **HTTP Request Defaults**: Configured for `https://petstore.octoperf.com`.
- **HTTP Requests**: 
  - Navigate to Fish: `/actions/Catalog.action?viewCategory=&categoryId=FISH`
  - View Product FI-SW-01: `/actions/Catalog.action?viewProduct=&productId=FI-SW-01`
- **Listeners**: 
  - View Results Tree
  - Summary Report
  - Aggregate Graph

## Analyzing the Results
- **View Results Tree**: Shows detailed information about each request.
- **Summary Report**: Provides statistics such as average response time, throughput, and error rate.

## Conclusions
Document your conclusions based on the generated reports.