# Event
An Event is a combination of
1. Notification (When?)
2. State (What?)

**Alarm Clock Example:**
- I have set an alarm to wake up on time in the morning. This is an event.
- The alarm started ringing is an event
- The alarm snoozed for 5 minutes is also an event
- The alarm stopped is an event as well

When we design our systems, we often think unilaterally that the data is need to flow from service A to service B.

Traditional system which are built with this mindset, at scale, they use batch processing to provide the data to other systems. This reminds me of a great example of traffic crossing.

Would you cross a busy intersection based on data that was taken 5 minutes ago?

In reality, the data is needed in more than one place near real-time. If you haven't figured out other avenues of your data, then that simply means you have yet to capitalize on the true value of it.

Going back to our **alarm clock** example, here are some ways other systems can use the events:
1. Sleep monitoring system to track your sleep habits
2. Smart devices to prepare your environment, such as coffee machine, thermostat, light bulb, etc.
3. Smart notifications system to showcase your preferred morning updates