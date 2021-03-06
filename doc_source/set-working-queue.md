# Contact Block: Set Working Queue<a name="set-working-queue"></a>

## In contact flow types<a name="set-voice-types"></a>

You can use this block in the following [contact flow types](create-contact-flow.md#contact-flow-types):
+ Generic Contact flow
+ Transfer to Agent flow
+ Transfer to Queue flow

## Description<a name="set-voice-description"></a>
+ This block specifies the queue to be used when **Transfer to queue** is invoked\.
+ A queue must be specified before invoking **Transfer to queue** except when used in a customer queue flow\. It’s also the default queue for checking attributes, such as staffing, queue status, and hours of operation\.

## Properties<a name="set-voice-properties"></a>

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/set-working-queue-properties.png)

Note the following properties:
+ **By queue > Use attribute**\. To set the queue dynamically, you must specify the Amazon Resource Name \(ARN\) for the queue rather than the queue name\. To find the ARN for a queue, open the queue in the queue editor\. The ARN is included as the last part of the URL displayed in the browser address bar after /queue\. For example, `.../queue/aaaaaaaa-bbbb-cccc-dddd-111111111111`\.

## Configured block<a name="set-voice-configured"></a>

When this block is configured, it looks similar to the following image:

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/set-working-queue-configured.png)

## Sample flows<a name="set-voice-samples"></a>

See these sample flows for scenarios that use this block:
+ [Sample Queue Customer](sample-queue-customer.md)
+ [Sample Queue Configurations](sample-queue-configurations.md)

## Scenarios<a name="set-voice-scenarios"></a>

See these topics for scenarios that use this block:
+ [Transfer Contacts to a Specific Agent](transfer-to-agent.md)