# sensorfeed
This component acts as a service to feed sensor data to the local Kafka stream.

Currently, this is populated with the tutorial found at http://docs.aws.amazon.com/streams/latest/dev/learning-kinesis-module-one.html. The reason for this is the intent to use AWS Kinesis as a middle-ware to connect the data production aboard the CubeSat to the data visualization tools in the ground station. This module will ultimately be divided up between a service that feeds sensor data into a Kafka instance aboard the CubeSat and a Kinesis app in the receiver that will forward the Kafka stream to a Kinesis stream. For now, this service is standing in.

