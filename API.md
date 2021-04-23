# API Reference

**Classes**

Name|Description
----|-----------
[EventNotify](#cdk-events-notify-eventnotify)|*No description*


**Structs**

Name|Description
----|-----------
[EventNotifyProps](#cdk-events-notify-eventnotifyprops)|*No description*


**Interfaces**

Name|Description
----|-----------
[ISlackEventNotify](#cdk-events-notify-islackeventnotify)|*No description*



## class EventNotify 🔹 <a id="cdk-events-notify-eventnotify"></a>



__Implements__: [IConstruct](#constructs-iconstruct), [IConstruct](#aws-cdk-core-iconstruct), [IConstruct](#constructs-iconstruct), [IDependable](#aws-cdk-core-idependable)
__Extends__: [Construct](#aws-cdk-core-construct)

### Initializer




```ts
new EventNotify(scope: Construct, id: string, props?: EventNotifyProps)
```

* **scope** (<code>[Construct](#aws-cdk-core-construct)</code>)  *No description*
* **id** (<code>string</code>)  *No description*
* **props** (<code>[EventNotifyProps](#cdk-events-notify-eventnotifyprops)</code>)  *No description*
  * **lineNotifyToken** (<code>string</code>)  Line Notify Token for Lambda send notify permisson. __*Optional*__
  * **slack** (<code>[ISlackEventNotify](#cdk-events-notify-islackeventnotify)</code>)  Notify target to Slack channel. __*Optional*__




## struct EventNotifyProps 🔹 <a id="cdk-events-notify-eventnotifyprops"></a>






Name | Type | Description 
-----|------|-------------
**lineNotifyToken**?🔹 | <code>string</code> | Line Notify Token for Lambda send notify permisson.<br/>__*Optional*__
**slack**?🔹 | <code>[ISlackEventNotify](#cdk-events-notify-islackeventnotify)</code> | Notify target to Slack channel.<br/>__*Optional*__



## interface ISlackEventNotify 🔹 <a id="cdk-events-notify-islackeventnotify"></a>




### Properties


Name | Type | Description 
-----|------|-------------
**slackChannelName**🔹 | <code>string</code> | slack Channel Name for Lambda send message to slack.
**slackWebhookUrl**🔹 | <code>string</code> | slack Webhook Url for Lambda send message to slack.



