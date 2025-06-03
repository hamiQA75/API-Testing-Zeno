🎥 Demo Video
Watch the full API Load Testing process and results here:
# 🎥 Demo Video  
Watch the full API Load Testing process and results here:  
[Load Testing Video on Loom](https://www.loom.com/share/99ec8a07e8d44108b560e66ead2fdf0c?sid=1e63974a-4e67-4ae0-9789-c5330b5dac5b)

🚀 API Load Testing Report
📋 Overview
This project demonstrates load testing of an API by ramping up to 50 users and hitting the API continuously for 5 minutes. The goal was to observe the API's performance, stability, and response times under increasing load.

⚙️ Test Details
Test Type: Load Testing

Users: Ramp-up from 1 to 50 concurrent users

Duration: 5 minutes

Objective:

Validate API response under high concurrency

Identify performance bottlenecks

Ensure no crashes or errors during peak load

🔍 Test Approach
Start with a single virtual user hitting the API endpoint.

Gradually increase the number of users up to 50 over the test period.

Monitor response times, throughput, error rates.

Collect logs and metrics for analysis.

📊 Key Observations
API maintained stable response times under load.

No critical errors observed during the ramp-up and steady load phases.

Minor latency increase near max user load but within acceptable limits.

CPU and memory usage monitored on the server stayed within thresholds.

🛠️ Tools Used
JMeter / Locust / Gatling / (replace with your tool)

Server monitoring tools (CPU, memory, network)

📌 Notes & Recommendations
Consider longer duration tests for endurance.

Test more API endpoints for full coverage.

Use real-world data for realistic testing.

Setup alerts for errors during testing.
