Roles
*******

... are the aggregation of groups. These should represent the field of activity / functional description of the agent. A user can be active in several roles.
The assignment of rights directly via a group should be avoided when roles are used.

**Admin**
An admin role can be given access to different areas in the admin interface. You can give someone full access to the admin area (Admin - Admin Interface = yes). However, it is also possible to distribute only access to some areas.
For example, you could choose someone as a "Text-Module-Coordinator" who is a normal agent, but coordinates all changes in this area. In this way the admin can be relieved. You can give access to the following sections:
.. image:: images/manage/Zammad_Helpdesk_-_Roles2

**Agent**
The authorization can be assigned to the individual communication functions:
.. image:: images/manage/Zammad_Helpdesk_-_Roles3

In addition, access rights can be given to the individual groups:
.. image:: images/manage/Zammad_Helpdesk_-_Roles4

**Customer**
For each of both agents and customers, you can define which areas are available in the user preferences:
.. image:: images/manage/Zammad_Helpdesk_-_Roles5


**Default at signup**
One of the roles should be created as the "default role" (default at signup = yes). When someone registers in the system who has not yet been assigned another role, this role is given to them.
This is usually the role "Customer". All other roles must be set to "no".

To keep this overview, the field selection (yes/no) is displayed in a column in the role overview:
.. image:: images/manage/Zammad_Helpdesk_-_Roles7