## We have a few scenarios:

### 1) At the beginning of the day, u open ur account to check out new tickets, therefore u wanna see all the new tickets.

=Procedures:
- Open Freshdesk,
- Filter by Status **(Open and Pending)**,
- Filter by Group **(Implementation)**.

Now, u can see _all the new tickets_ and check them one by one.

----------

### 2) Checking a ticket, 

### A) If u will respond immediately,
=Procedures:
- Respond and send,
- Set Status as **Closed**
- Add suitable Tag/s.
- Select **Your Name** from the Agent menu (Mandatory)

- **Update**

If it u expect the client gonna reply to the ticket:
-- Assign a task from the **Implementation** drop-down menu,
-- Set the Resolution Due as u want SO THAT the ticket is never red-flagged 
as an **OVERDUE**
-- **Update**

### B) If u gonna skip, do not skip before:
=Procedures:
- Open up the ticket,
- Check out the question,
- Assign a task from the **Implementation** drop-down menu,
- Add suitable Tag/s.
- Set the Resolution Due as u want SO THAT the ticket is never red-flagged 
as an **OVERDUE**
- Select **Your Name** from the Agent menu (Mandatory) 
- Add suitable Tag/s.
- **Update**

---------

### 3) In the middle of the day, u wanna check out ur tasks:

=Procedures:
- Open Freshdesk,
- Filter by Status **(Open and Pending)**,
- Filter by Group **(Implementation)**,
- Filter by Agent **(Your Name)**

Now, u can see only the tickets assigned to u.


---------

### 4) In case of delivering:

=Procedures:
- Open the ticket finished,
- Remove **active** from Tags,
- Add **revision** tag,
- Update,
- Wait for a response.
---------

### 5) In case of exceeded 7 days with no reply:

=Procedures:
- Open the ticket,
- Remove all tags,
- Add **noreply** tag,
- Add **No Reply** label from **Implementation** field,
- Update.

Now, u can see only the tickets assigned to u.
-----------------

--------------------

## Notes:

* Tags: 

>We may have a set of certain tags to use, to easily look up a specific old ticket if needed, I suggest starting with the following 3 tags:
>_active:_ for an ongoing ticket that takes up to 2 days or more (made a payment).
>_buggy:_ for a ticket that refers to a bug/anything that needs a fix.
>_hustler:_ for a client who sends in a lot and never stops! (more than 3 times)
>_any suggested cases that may need to be tagged?_
>_revision:_ after the first delivery.
>_noreply:_ more than 7 days passed.
>_delivered:_ for exporting Implementation finished jobs.

>- u can add more than one tag on a ticket.
>- those tags will help to identify clients (when open their Freshdesk profile and see their tickets tagged)

* Responding: 

>There are two approaches to look at **"How Should We Respond To Every Day's Tickets?"** 

>- First: Responding to one by one, which leads to wasting a big amount of time. Here are some facts:

>I skimmed over the tickets created _last week_:
>- 8 Tickets received per day on Avg.
>- We on Avg. respond almost 5 times to each ticket.
>- 13 open/pending tickets. 27 unresolved. _(Total)_
>- It takes almost 7h on Avg. to make the 1st response.
>- It takes almost 68h (2.8 days) on Avg. to resolve a ticket.  _(The 7-day-template gigs surges up that metric for sure)_

>- Second: Grouping tickets into clusters, which will happen when using the new categorization, then u respond based on scenarios.

>- *Remember*: You can always respond in 3 different ways: 
**Ticket By Ticket
Canned Responses
Scenarios** _(The Best Option)

>If gonna respond based scenario:s

> Procedures:
>- Set the Resolution Due date as u see,
>- Select Your Name in the Agent menu,
>-**Update**
>- Select the suitable scenario.


>_Common Scenarios:_

>Case 1: Request a Template:

>- We will Ask **Account Info**.
>- We will send **Applicability**.
>- We will send **Pricing**.
>- We will send **Payment Info**.
>- We will send **Automatic Response After Payment is Made**.

>2) Request a Modification:

>- We will send **Self Help**.
>- We will Ask **Account Info**.
>- We will send **Pricing**.
>- We will send **Payment Info**.
>- We will send **Automatic Response After Payment is Made**.


>3) Request a Zoom Call:

>- We will send **When We Are Available**.
>- We will send **The Scheduled Appointment**.

>4) Asks for Support:

>- We will send **To Support Team**.

>5) Others:

>- We will send **How to Set The Tax Invoice Tem.**.
>- We will Ask **Create an Epson Invoice**.
>- We will Ask **Epson Invoice Price**.
>- We will send **Create New Invoice**.
>- We will send **Payment Info**.
>- We will make **A Scenario WITHOUT Response to be used as a Template**.

----

Recommended: 

* Authorize **Google Calendar** to keep tracking ur scheduled Zoom calls. _(from the sidebar)_
* Use the **Time Log** for tickets that require long responses for efficiency and better time management. _(from the sidebar)_
* Use to **Do list** to break down the ticket into tasks. _(from the sidebar)_
* USe Notes to summarize the ticket and height the most important details.

Updates: (Newly added)
1) No Reply: new categorization to label a ticket that had been without a response for 7 days or longer.

----

Auto Ref: 
Traffic cop: If someone sent a reply before u hit send, it alerts u to check out the reply so that we do not reply twice to the same ticket.
Collision detection: Red circle => How many people and who are viewing the ticket ur viewing now? 
