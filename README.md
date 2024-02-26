# Performance_Testing_Project
carnesia is a renowned cosmetic website in Bangladesh. I have executed performance testing on this website.
Performance testing of a website involves assessing its responsiveness, speed, stability, and scalability under various conditions. This testing aims to ensure that the website functions optimally, even when experiencing high loads or unfavorable conditions. Testers simulate real-world scenarios to measure the website's performance metrics such as page load times, response times, server resource usage, and overall user experience.
In JMeter, performance testing involves configuring various parameters to simulate real-world scenarios accurately. Here's how you can set up performance testing in JMeter with the given parameters:

Number of Threads (Users): Set this to 10, which represents the number of virtual users or threads that will be simulating concurrent access to the website.

Ramp-Up Period: Configure a ramp-up period of 3 seconds. This means that JMeter will gradually increase the number of threads (users) over the specified time period until it reaches the maximum number of threads.

Loop Count: Set the loop count to 1, indicating that each virtual user will execute the test plan only once. If you want to repeat the test multiple times, you can increase this value accordingly.

View Results:

Once the test is completed, the result will be showed in the listener. Then I have prepared a summary report to display the result in a tabular format showing metrics such as average response time, throughput, error count, etc.
With these settings, JMeter will simulate 10 concurrent users accessing the website, with a gradual increase over 3 seconds, and each user will execute the test plan once. This setup allows you to assess the website's performance under moderate load conditions.
