# tenbea-performance-testing

Dear,
 I’ve completed performance test on frequently used API for tenbea.com.
Test executed for below mentioned scenario in server 000.000.000.00.
10 concurrent request with 1 loop count; Avg TPS for Total Samples is ~ 150
5 concurrent request with 1 loop count; Avg TPS for Total Sample is ~ 30
While executed 10 concurrent request, found 3 request got connection timeout and error rate is 2.00%.
Summary: Server can handle almost concurrent 30 API with almost zero (0) error rate.
