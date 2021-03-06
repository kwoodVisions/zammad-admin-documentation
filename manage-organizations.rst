Organizations
*************

Organizations allow you to group customers. This has two important advantages, among other things.

1.) As an agent you have not only the overview of a customer's tickets, but also an overview of the entire organization.

For example, by searching for the organization, all the tickets are displayed and they can be opened easily by click.
This overview appears as follows:

.. image:: images/manage/Zammad_Helpdesk_-_Awesome_Customer_Inc_.jpg


2.) As a customer, you can view and edit your colleagues' tickets (if the organization is a "shared organization", you can set this as the parameter for each organization. See the Edit-Mask).

**For example:**
   A customer user who has only created one ticket himself, but whose entire organization is 6, the overview looks like this:

.. image:: images/manage/Zammad_Helpdesk_-_My_Organization_Tickets.jpg



In the organizations management area (Admin Interface --> Manage --> Organizations) you can manually add, edit or delete existing organizations. That's the Edit-Mask:

.. image:: images/manage/Zammad_Helpdesk_-_Organizations.jpg


Within the organization can be set the following things:

- if it's a shared organization (All customers who are assigned to this organization can view and edit the group tickets)
- if the assignment is domain based (assign users based on domain)
- note
- if it's active or inactive


Import of organizations via CSV file
----------
With the import action (since Zammad 2.5) you can download a sample CSV file and upload your own CSV file.

To reduce the error rate of unwanted mass changes, a test import is carried out first and a summary appears at the end. If you agree with the summary, the CSV import can be finally executed.

.. image:: images/manage/Zammad_Helpdesk_-_Organizations-Import.jpg
