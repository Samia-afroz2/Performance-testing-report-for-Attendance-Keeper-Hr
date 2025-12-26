Project Overview

This project demonstrates end-to-end performance testing of the Attendance Keeper HR web application using Apache JMeter.
The goal is to evaluate system behavior under load, measure response times, throughput, and identify potential performance bottlenecks across key business modules.

The test plan includes multiple user flows executed using Throughput Controllers, realistic delays via Timers, and results analysis through Aggregate Reports.

2️⃣ Scope of Testing

The following application modules were tested:

🔐 Login

📝 Registration

👤 Employee Management

📊 Dashboard

🕒 Attendance

🏢 Branch

🏖 Leave

💰 Payroll

Each module was executed with different request distributions to simulate real user behavior.

3️⃣ Tools & Technologies Used

-Apache JMeter 5.6.3

-HTTP Request Sampler

-Throughput Controller

-Uniform Random Timer

-Aggregate Report Listener

-View Results Tree

MacOS 

4️⃣ Test Strategy

-Multiple user scenarios handled using Throughput Controllers

-Request execution percentage controlled per module

-Think time simulated using Uniform Random Timer

-Load distribution designed to mimic real production usage

-Performance metrics collected via Aggregate Report

5️⃣ Key Performance Metrics Analyzed

From the Aggregate Report:

Average Response Time

90th / 95th / 99th Percentile

Throughput (requests/sec)

Error Percentage

Min / Max Response Time

Received & Sent KB/sec

📊 Result Summary:

-Total Requests: 619
-Error Rate: 0.00%
-Average Response Time: 187 ms
-Throughput: 13.8/sec
-System remained stable under configured load
