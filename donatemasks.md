# Where to Donate Masks

---

**Thank you** for your help in this project.

This page is a list of places that we are currently aware of that are accepting masks.  As of this moment, we are focused on the Chicago region, but if your organization would like to be listed, please let us know.

State | City | Organization | Drop-off Instructions | Donation Notes | Contact | Last Update
--- | --- | --- | --- | --- | --- 
{% for organization in site.data.organizations %} {{organization[1].state}} | {{organization[1].city}} | [{{organization[1].name}}]({{organization[1].name}}) | {{organization[1].dropOffInstructions}} | {{organization[1].donationPlans}} | {{organization[1].contactName}} - {{organization[1].contactEmail}} | {{organization[1].last_update}} |
{% endfor %}