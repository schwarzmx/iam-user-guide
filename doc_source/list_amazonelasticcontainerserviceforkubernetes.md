# Actions, Resources, and Condition Keys for Amazon Elastic Container Service for Kubernetes<a name="list_amazonelasticcontainerserviceforkubernetes"></a>

Amazon Elastic Container Service for Kubernetes \(service prefix: `eks`\) provides the following service\-specific resources, actions, and condition context keys for use in IAM permission policies\.

References:
+ Learn how to [configure this service](https://docs.aws.amazon.com/eks/latest/userguide/)\.
+ View a list of the [API operations available for this service](https://docs.aws.amazon.com/eks/latest/APIReference/)\.
+ Learn how to secure this service and its resources by [using IAM](https://docs.aws.amazon.com/eks/latest/userguide/IAM_policies.html) permission policies\.

**Topics**
+ [Actions Defined by Amazon Elastic Container Service for Kubernetes](#amazonelasticcontainerserviceforkubernetes-actions-as-permissions)
+ [Resources Defined by Amazon Elastic Container Service for Kubernetes](#amazonelasticcontainerserviceforkubernetes-resources-for-iam-policies)
+ [Condition Keys for Amazon Elastic Container Service for Kubernetes](#amazonelasticcontainerserviceforkubernetes-policy-keys)

## Actions Defined by Amazon Elastic Container Service for Kubernetes<a name="amazonelasticcontainerserviceforkubernetes-actions-as-permissions"></a>

You can specify the following actions in the `Action` element of an IAM policy statement\. Use policies to grant permissions to perform an operation in AWS\. When you use an action in a policy, you usually allow or deny access to the API operation or CLI command with the same name\. However, in some cases, a single action controls access to more than one operation\. Alternatively, some operations require several different actions\.

The **Resource** column indicates whether each action supports resource\-level permissions\. If there is no value for this column, you must specify all resources \("\*"\) in the `Resource` element of your policy statement\. If the column includes a resource type, then you can specify an ARN of that type in a statement with that action\. Required resources are indicated in the table with an asterisk \(\*\)\. If you specify a resource\-level permission ARN in a statement using this action, then it must be of this type\. Some actions support multiple resource types\. If the resource type is optional \(not indicated as required\), then you can choose to use one but not the other\.

For details about the columns in the following table, see [The Actions Table](reference_policies_actions-resources-contextkeys.md#actions_table)\.


****  
[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/IAM/latest/UserGuide/list_amazonelasticcontainerserviceforkubernetes.html)

## Resources Defined by Amazon Elastic Container Service for Kubernetes<a name="amazonelasticcontainerserviceforkubernetes-resources-for-iam-policies"></a>

The following resource types are defined by this service and can be used in the `Resource` element of IAM permission policy statements\. Each action in the [Actions table](#amazonelasticcontainerserviceforkubernetes-actions-as-permissions) identifies the resource types that can be specified with that action\. A resource type can also define which condition keys you can include in a policy\. These keys are displayed in the last column of the table\. For details about the columns in the following table, see [The Resource Types Table](reference_policies_actions-resources-contextkeys.md#resources_table)\.


****  

| Resource Types | ARN | Condition Keys | 
| --- | --- | --- | 
|   [ cluster ](https://docs.aws.amazon.com/eks/latest/userguide/getting-started.html)  |  arn:$\{Partition\}:eks:$\{Region\}:$\{Account\}:cluster/$\{ClusterName\}  |   [ aws:ResourceTag/$\{TagKey\} ](#amazonelasticcontainerserviceforkubernetes-aws_ResourceTag___TagKey_)   | 

## Condition Keys for Amazon Elastic Container Service for Kubernetes<a name="amazonelasticcontainerserviceforkubernetes-policy-keys"></a>

Amazon Elastic Container Service for Kubernetes defines the following condition keys that can be used in the `Condition` element of an IAM policy\. You can use these keys to further refine the conditions under which the policy statement applies\. For details about the columns in the following table, see [The Condition Keys Table](reference_policies_actions-resources-contextkeys.md#context_keys_table)\.

To view the global condition keys that are available to all services, see [Available Global Condition Keys](reference_policies_condition-keys.html#AvailableKeys) in the *IAM Policy Reference*\.


****  

| Condition Keys | Description | Type | 
| --- | --- | --- | 
|   [ aws:RequestTag/$\{TagKey\} ](https://docs.aws.amazon.com/eks/latest/userguide/reference_iam-permissions.html#iam-contextkeys)  | Filters access by a key that is present in the request the user makes to the EKS service\. | String | 
|   [ aws:ResourceTag/$\{TagKey\} ](https://docs.aws.amazon.com/eks/latest/userguide/reference_iam-permissions.html#iam-contextkeys)  | Filters access by a tag key and value pair\. | String | 
|   [ aws:TagKeys ](https://docs.aws.amazon.com/eks/latest/userguide/reference_iam-permissions.html#iam-contextkeys)  | Filters access by the list of all the tag key names present in the request the user makes to the EKS service\. | String | 