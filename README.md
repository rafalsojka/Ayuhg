Here’s a polished response you can send:

Subject: RE: Performance Testing / Capacity Recommendations

Hi [Name],

Yes, as part of the engagement, we will work with Marta and Michał to design the performance test scenarios, workload, and execution approach. As usual, we plan to execute the load tests together with the development team so that any issues observed during the test can be investigated in real time.

Following the execution, our team will provide a performance test report summarizing the results, observations, and findings. This will include any performance bottlenecks or capacity-related concerns identified through the test results, Splunk data, infrastructure monitoring, or observations made jointly with the development team during the execution. Where appropriate, we will also recommend areas where the solution capacity or configuration may need to be tuned.

I would recommend involving the Cloud Engineering team during the load test execution itself rather than waiting until after testing is complete. In particular, we will need their support/access to monitor the relevant infrastructure metrics, including the performance and resource utilization of the pods running in OpenShift. Having them involved during the test will also make it easier to correlate application behavior with infrastructure utilization and investigate any potential bottlenecks as they occur.

If the testing identifies areas that require infrastructure changes or more detailed capacity analysis, those can then be followed up jointly by the development and Cloud Engineering teams, using our test results and findings as input.

So, in short, our report should provide a good indication of where performance or capacity constraints exist and what requires further investigation, while Cloud Engineering involvement during the actual test execution will be important for getting the complete picture.

Best regards,
Rafal# Ayuhg
