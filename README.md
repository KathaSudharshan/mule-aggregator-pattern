# mule-aggregator-pattern
Aggregation is a design principle used for solving data processing issues based on size and time based. Aggerators are different types like as below,

1. Time Based Aggregator
2. Size Based Aggregator

# Time Based Aggregator
Time based aggregator is worked based on the time. Its like holding a data for a mentioned period of time and end the process once time period is over.  For eaxmple, If we want to transfer all the appicatoion logging tracebile entries into thrid party apis like Splunk/New Relic based on the time period then we have to set up a time to capture entires and then process all the entires once into third party APIs instead of for each request. This will helps the application performance and as well for logging analytics.


# Size Based Aggregator
Size based aggregator is worked based on the Size/Count. Its like holding a data for a mentioned size to reach and then process at once the size if reached.  For eaxmple, If we want to transfer all the appicatoion logging tracebile entries into thrid party apis like Splunk/New Relic based on the size based then we have to set up a size of entires to capture and then process all the entires once into third party APIs instead of for each request. This will helps the application performance and as well for logging analytics.

