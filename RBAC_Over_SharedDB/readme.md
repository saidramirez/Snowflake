Sharing data in Snowflake is fantastic! Be aware that on the consumer side, default access to the share is read-only to add objects or nothing.
To have more granular permissions we can create a database of views over the share. This StoredProc automates the creation of views over all tables and views in the Shared database, ready for RBAC.

**Source Share** | **Views Over Share**
-----------------|---------------------

![Source Share](/RBAC_Over_SharedDB/images/SourceShare.png) | ![ViewsOverShare](/RBAC_Over_SharedDB/images/ViewsOverShare.png)
