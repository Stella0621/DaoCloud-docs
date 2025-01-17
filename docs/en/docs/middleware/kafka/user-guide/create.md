---
hide:
  - toc
---

# Create Kafka

In the Kafka message queue, perform the following operations to create a Kafka instance.

1. Click __New Instance__ in the upper right corner.

    <!--screenshot-->

2. On the __Create Kafka Instance__ page, after setting the basic information, click __Next__ .

    <!--screenshot-->

3. After configuring the specifications, click __Next__ .

    - Version: The version number of Kafka, currently only supports Kafka 3.1.0.
    - Number of copies: 1, 3, 5, 7 copies are supported.
    - Resource Quota: Select the rules according to the actual situation.
    - Storage Volume: Select the storage volume and the total amount of storage space for the Kafka instance.

    <!--screenshot-->

4. After setting up the service, click __Next__ .

    - Access method: You can choose intra-cluster access or Nodeport access.
    - Service Settings: Set the username and password for connecting to the Kafka instance.

    <!--screenshot-->

5. Confirm that the instance configuration information is correct, and click __OK__ to complete the creation.

    <!--screenshot-->

6. On the instance list page, check whether the instance is successfully created. The status of the newly created instance is __Not Ready__ , and it will change to __Running__ after a few minutes.

    <!--screenshot-->