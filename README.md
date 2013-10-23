Advanced Ldap Domain
====================

Sample configuration containing a security domain defined with the AdvancedLdapLoginModule.

The configuration is also updated for security related TRACE logging and the management interfaces updated to use JAAS.

Also a standalone.conf for debug logging.

The schema this was tested against defined memberOf as an extension of distinguishedName, this has led to a more complex filter being required - memberOf should probably not be an extension of that type.

