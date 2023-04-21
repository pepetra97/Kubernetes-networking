# Notes

That file is used for writing notes about the different files, so it's like a study note

## Service Accounts in Kubernetes

Kubernetes Service Accounts are a way to authenticate and authorize applications and processes running inside a Kubernetes cluster. A Service Account provides an identity for a Pod or a set of Pods, and allows them to interact with the Kubernetes API server and other resources within the cluster.

When you create a Pod in Kubernetes, you can specify a Service Account to associate with it. The Service Account is then used to authenticate and authorize the Pod when it makes requests to the Kubernetes API server or other resources within the cluster.

Kubernetes Service Accounts are created and managed using the Kubernetes API. Each Service Account has a unique name and a corresponding token that is used to authenticate requests made by the associated Pod. Service Accounts can also be used to grant specific permissions to Pods, allowing them to access resources or perform actions within the cluster.

By default, every namespace in a Kubernetes cluster has a default Service Account created for it. Pods created within the namespace are automatically associated with this default Service Account, unless a different Service Account is specified. However, you can create additional Service Accounts if you need to grant different permissions to different sets of Pods.

Overall, Kubernetes Service Accounts are an important component of the Kubernetes security model, providing a way to control access to resources within the cluster and ensure that Pods can only access the resources they need to perform their functions.