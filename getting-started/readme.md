# Getting Started

Dapr is a portable, event-driven runtime that makes it easy for enterprise developers to build resilient, microservice stateless and stateful applications that run on the cloud and edge and embraces the diversity of languages and developer frameworks.

Read the Dapr [overview](../overview.md). To get started with Dapr, we recommend the following steps:

#### 1. Setup Dapr on your local machine or Kubernetes cluster

To build and run your Dapr applications, you first need to [setup your environment](./environment-setup.md) and install Dapr:

1. [Setup local development](./environment-setup.md#prerequisites)
2. [Setup Kubernetes environment](./environment-setup.md#installing-dapr-on-a-kubernetes-cluster)

Once you have Dapr installed on your local machine in Standalone mode, try out the [Hello World sample](https://github.com/dapr/samples/tree/master/1.hello-world) or continue reading for further guidance.

#### 2. Setup Dapr components for state store and pub-sub on Kubernetes (optional)

Some features of Dapr, mainly [Pub/Sub](https://github.com/dapr/docs/tree/master/concepts/publish-subscribe-messaging) and [State Management](https://github.com/dapr/docs/blob/master/concepts/state-management/state-management.md), require that you set up Dapr components for them.

Using the Dapr CLI, these components are set-up automatically for you when running on a local machine in Standalone mode<br><br>
The following links enable you setup a state store and pub/sub components when running on Kubernetes:

* [Setup State Management on Kubernetes](../howto/setup-state-store)
* [Setup Pub/Sub on Kubernetes](../howto/setup-pub-sub-message-broker)

#### 3. Run a Kubernetes sample
Once you have set up the Kubernetes environment and the Dapr components then try out [Hello World Kubernetes sample](https://github.com/dapr/samples/tree/master/1.hello-kubernetes) or continue reading for further guidance. 

#### 4. Read through the concepts and how-to guides (optional)

Dapr has several concepts, which can be found [here](../concepts). The concepts provide a deeper understanding of the core features of Dapr and how they work.

Reading the [How To](../howto) guides, you can walk through specific tasks, for example, how to create a [rate limited app](../howto/control-concurrency) using Dapr.

#### 4. Run more samples

The best way to learn is through experience! The Dapr [samples repo](https://github.com/dapr/samples) contains more samples that walk you through scenarios of building applications with Dapr involving service invocation, using pub/sub, handling state and more.
