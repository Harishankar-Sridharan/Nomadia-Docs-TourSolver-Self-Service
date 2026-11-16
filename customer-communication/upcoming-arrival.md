# Upcoming Arrival

Send your customer an estimated time of arrival (ETA) link when the delivery process begins, so that they can track the live location of the deliverer.

## Before you begin

* Sign in to **TourSolver**.
* Set up the outgoing email and SMS services. See [General Configuration](general-configuration.md).
* Click **Upcoming Arrival** to open its configuration.

![](../.gitbook/assets/CustomerCommunication-UpcomingArrival_timestamp_0_to_00–0_to_06.gif)

## Feature overview

The Upcoming Arrival feature provides real-time delivery status updates and enables proactive communication, so that customers are ready to receive their items. Its core benefit is transparency: the customer clicks the link and tracks the live location of the deliverer.

| Feature | Description |
| ------- | ----------- |
| **ETA Link** | A link with the estimated time of arrival (ETA) is created automatically and sent once the delivery completes. |
| **Email Subject Editing** | Lets you customize the **email subject**, so customers know the purpose of the message at once. |
| **Message Body Editing** | Lets you **edit the message** sent to your customers, with personalized language and important details. |
| **Personalization Tags ($)** | Entering the **dollar symbol** ($) shows options that you can insert and edit in the body of the email. |
| **Preview Window** | Shows a **preview** of the exact message before you save, so that it looks professional and accurate. |
| **Live Location Tracking** | The link lets the customer track the live location of the delivery (or the deliverer). |
| **Outgoing Email** | Option to send the ETA link by email. |
| **Outgoing SMS** | Option to send the ETA link by text message. |

## Set up the customer notifications

Choose the communication channels for the ETA and the live location link.

1. Click **Upcoming Arrival**.
2. Enable the **outgoing emails** option.

![](../.gitbook/assets/CustomerCommunication-UpcomingArrival_timestamp_0_to_24.png)

3. Optional: Enable the **outgoing SMS** option.
4. Optional: To include dynamic information, such as the customer's name or specific appointment details, enter the **dollar symbol** ($). The options that you can use to edit the body of the email are displayed.

![](../.gitbook/assets/CustomerCommunication-UpcomingArrival_timestamp_0_to_31.png)

5. Recommended: Select the option to **see the preview of the email**, to confirm the customer experience.
6. Click **Save**.

![](../.gitbook/assets/CustomerCommunication-UpcomingArrival_timestamp_1_to_19–1_to_25.gif)

### Result

The customer receives the following email.

<figure><img src="../.gitbook/assets/msedge_0JrRthQwup.png" alt=""><figcaption></figcaption></figure>

## Avoid unwanted Upcoming Arrival notifications

The Upcoming Arrival notification is sent when the deliverer accepts the visit in the mobile app and goes to the customer. If the deliverer accepts a visit and then cancels it, the customer has already received the notification.

* **Refuse instead of Accept and Cancel**: Ask your deliverers to **refuse** the visits that they cannot perform, instead of accepting them and then cancelling them. A refused visit does not send the notification. To allow it, turn on **Decline deliveries** in **Configuration** > **Configure the mobile app** > **DELIVERIES**. See [Refuse or Cancel a Visit Without Notifying the Customer](https://nomadia-docs.gitbook.io/products/toursolver-mobile/intervention/refuse-or-cancel-without-notifying-the-customer).
* **Turn off the notification temporarily**: Click **Upcoming Arrival**, and then turn off **Outgoing emails** and **Outgoing SMS**. Turn them on again when you want to notify your customers again. While the notification is turned on, the **acceptance step** in the mobile app cannot be turned off.

## Understand the delay alerts

TourSolver compares the planned time of each visit with the current time and the progress of the deliverer.

* **Delayed deliveries**: In the **Fulfillment** tab, the map shows the deliveries that are late, by delay range: **10-30 mins**, **30-60 mins**, and **> 60 mins**.
* **Alert before the start of the route**: If the deliverer has not opened the route in the mobile app at the planned start time, the visits are already considered late, and the delay alerts start. Ask your deliverers to open and start their route on time.
* **Alerts in the mobile app**: In **Configuration** > **Configure the mobile app** > **OPTIONS**, set **Display late visits**, the **Lateness threshold** (in minutes), and the **Lateness notification display frequency** (in minutes).

<figure><img src="../.gitbook/assets/UpcomingArrival_LatenessSettings_001.jpg" alt=""><figcaption></figcaption></figure>

## Tips

{% hint style="info" %}
**Use both channels**: Enable both the outgoing emails and the outgoing SMS. The customer then receives the ETA information whether they check their inbox or their text messages first.
{% endhint %}

{% hint style="info" %}
**Use personalization tags**: Tags make the message feel more direct and professional.
{% endhint %}

{% hint style="info" %}
**Always preview**: Use the option to **see the preview of the email** before you save. It lets you verify that the message contains the live location link.
{% endhint %}

{% hint style="warning" %}
**Trigger point**: The ETA link is sent once the deliverer completes the delivery phase, which means that they are on their way to the customer. Make sure that this matches when you want the customer to start tracking the live location.
{% endhint %}

## Related topics

* [General Configuration](general-configuration.md)
* [Time Window to Communicate](time-window-to-communicate.md)
* [Next Visits](next-visits.md)
* [Why are my customer SMS or emails not sent?](../faq/why-are-my-customer-sms-or-emails-not-sent.md)
* [Refuse or Cancel a Visit Without Notifying the Customer](https://nomadia-docs.gitbook.io/products/toursolver-mobile/intervention/refuse-or-cancel-without-notifying-the-customer)
