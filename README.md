# Lab8-Starter
no partners

Graceful degradation and service workers are related because of the way we usually implement these services. We started our software with the assumption that we have reliable and maxed internet networks, so we did not yet need service workers. But then we gracefully degraded to lower level concerns like poor connection, in which we added our service workers. So we only get to service workers because we targeted a lower level conern (bad network) after we targeted a higher level concern (fetching correctly).

https://trhenry33.github.io/Lab8_Starter/
