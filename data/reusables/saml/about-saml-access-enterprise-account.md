To access each organization's resources on {% data variables.product.github %}, the member must have an active SAML session in their browser.{% ifversion ghec %} To access each organization's protected resources using the API and Git, the member must use a {% data variables.product.pat_generic %} or SSH key that the member has authorized for use with the organization.{% endif %} Enterprise owners can view and revoke a member's {% ifversion ghec %}linked identity, active sessions, or authorized credentials{% else %}active SAML sessions{% endif %} at any time.

{% ifversion ghes %}
>[!NOTE]
> This view is only enabled when SAML with SCIM is enabled.
{% endif %}
