"# APITesting" 

# Latency Testing REST APIs

The Latency Testing (Folder APILatencyTesting ) is based on NGINX tool https://www.nginx.com/blog/api-real-time-test-latency-responsiveness-nginx-rtapi-tool/ .  Thanks to NGINX rtapi tool , which can be used for quick testing REST API Latencies.

# Steps to do Latency testing of REST APIs
1. As I was using windows , download the windows distribution from https://github.com/nginxinc/rtapi/releases
2. Unzip rtapi-windows.zip 
3. Rename rtapi to rtapi.exe 
4. Clone this repository 
5. Replace rtapi.exe  with the exe from Step 3
6. Change the endpoints.yml to valid HTTP POST End Point.
7. run rtapi.exe --file endpoints.yml --output report.pdf
8. Examine the report.pdf to find how your API stands out in 99th percentile
9. Sample report is attached .

