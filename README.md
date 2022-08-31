# event-driven-architecture

# Resources
- https://aws.amazon.com/event-driven-architecture/
- https://pages.awscloud.com/AWS-Learning-Path-How-to-Use-Amazon-EventBridge-to-Build-Decoupled-Event-Driven-Architectures_2020_LP_0001-SRV.html?&trk=ps_a134p000003yBd8AAE&trkCampaign=FY20_2Q_eventbridge_learning_path&sc_channel=ps&sc_campaign=FY20_2Q_EDAPage_eventbridge_learning_path&sc_outcome=PaaS_Digital_Marketing&sc_publisher=Google
- https://docs.aws.amazon.com/lambda/latest/operatorguide/event-driven-architectures.html
- https://aws.amazon.com/blogs/compute/getting-started-with-event-driven-architecture/
- https://serverlessland.com/
- https://aws.amazon.com/blogs/compute/building-an-event-driven-application-with-amazon-eventbridge/
- https://www.youtube.com/watch?v=ksRCq0BJef8
- https://www.youtube.com/watch?v=XolV-pKjVyA

# High Level Introduction
- A way of building a distributed system where different decoupled components can interact with eachother based on Events.
- Producers, Routes/MessageQueue and Consumers are the main components involved.
- For AWS, we can use either EventBridge or Amazon SNS to realize an architecture.
- Because this is a PUSH architecture and not a PULL/POLL architecture, unnecessary CPU cycles won't get wasted by the consumers to fetch messages from the producers via the route.
- Ex: ![image](https://user-images.githubusercontent.com/42272776/187732393-24b63f36-0fc1-4587-95b3-2dd391eb3165.png)




- Event Sourcing
- CQRS
- SAGA
