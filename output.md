PS C:\Users\Administrateur> dsacls "DC=lab,DC=local" /AU:"Everyone:GR" /I:T
Propriétaire : BUILTIN\Administrateurs
Groupe : BUILTIN\Administrateurs

Liste d'audit :
Opération réussie LAB\Utilisateurs du domaine  ACCÈS SPÉCIAL
                                               CONTROL ACCESS
Opération réussie BUILTIN\Administrateurs      ACCÈS SPÉCIAL
                                               CONTROL ACCESS
Opération réussie Tout le monde                ACCÈS SPÉCIAL
                                               WRITE PERMISSIONS
                                               CHANGE OWNERSHIP
                                               WRITE PROPERTY
Opération réussie Tout le monde                ACCÈS SPÉCIAL pour gPLink
                                               WRITE PROPERTY
Opération réussie Tout le monde                ACCÈS SPÉCIAL pour gPOptions
                                               WRITE PROPERTY


Liste d'accès :
Autoriser LAB\Admins du domaine           ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          WRITE PERMISSIONS
                                          CHANGE OWNERSHIP
                                          CREATE CHILD
                                          LIST CONTENTS
                                          WRITE SELF
                                          WRITE PROPERTY
                                          READ PROPERTY
                                          LIST OBJECT
                                          CONTROL ACCESS
Autoriser LAB\Administrateurs de l'entreprise
                                          FULL CONTROL
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL
                                          LIST CONTENTS
Autoriser BUILTIN\Administrateurs         ACCÈS SPÉCIAL
                                          DELETE
                                          READ PERMISSONS
                                          WRITE PERMISSIONS
                                          CHANGE OWNERSHIP
                                          CREATE CHILD
                                          LIST CONTENTS
                                          WRITE SELF
                                          WRITE PROPERTY
                                          READ PROPERTY
                                          LIST OBJECT
                                          CONTROL ACCESS
Autoriser Tout le monde                   ACCÈS SPÉCIAL
                                          READ PROPERTY
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          LIST CONTENTS
                                          READ PROPERTY
                                          LIST OBJECT
Autoriser AUTORITE NT\Utilisateurs authentifiés
                                          ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          LIST CONTENTS
                                          READ PROPERTY
                                          LIST OBJECT
Autoriser AUTORITE NT\Système             FULL CONTROL
Autoriser LAB\Administrateurs clés        ACCÈS SPÉCIAL pour msDS-KeyCredentialLink
                                          WRITE PROPERTY
                                          READ PROPERTY
Autoriser LAB\Administrateurs clés Enterprise
                                          ACCÈS SPÉCIAL pour msDS-KeyCredentialLink
                                          WRITE PROPERTY
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Domain Password & Lockout Policies
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Other Domain Parameters (for use by SAM)
                                          READ PROPERTY
Autoriser AUTORITE NT\Utilisateurs authentifiés
                                          ACCÈS SPÉCIAL pour Other Domain Parameters (for use by SAM)
                                          READ PROPERTY
Autoriser AUTORITE NT\SELF                ACCÈS SPÉCIAL pour msDS-AllowedToActOnBehalfOfOtherIdentity
                                          WRITE PROPERTY
                                          READ PROPERTY
Autoriser LAB\Contrôleurs de domaine clonables
                                          Allow a DC to create a clone of itself
Autoriser LAB\Contrôleurs de domaine d'entreprise en lecture seule
                                          Replicating Directory Changes
Autoriser LAB\Contrôleurs de domaine      Replicating Directory Changes All
Autoriser BUILTIN\Administrateurs         Replicating Directory Changes In Filtered Set
Autoriser BUILTIN\Administrateurs         Replicating Directory Changes
Autoriser BUILTIN\Administrateurs         Replication Synchronization
Autoriser BUILTIN\Administrateurs         Manage Replication Topology
Autoriser BUILTIN\Administrateurs         Replicating Directory Changes All
Autoriser BUILTIN\Administrateurs         Read Only Replication Secret Synchronization
Autoriser BUILTIN\Générateurs d'approbations de forêt entrante
                                          Create Inbound Forest Trust
Autoriser AUTORITE NT\Utilisateurs authentifiés
                                          Enable Per User Reversibly Encrypted Password
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          Replicating Directory Changes In Filtered Set
Autoriser AUTORITE NT\Utilisateurs authentifiés
                                          Unexpire Password
Autoriser AUTORITE NT\Utilisateurs authentifiés
                                          Update Password Not Required Bit
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          Replicating Directory Changes
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          Replication Synchronization
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          Manage Replication Topology
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          Read Only Replication Secret Synchronization

Autorisations transmises aux sous-objets :
Transmises à tous les sous-objets
Autoriser LAB\Administrateurs de l'entreprise
                                          FULL CONTROL
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL
                                          LIST CONTENTS
Autoriser BUILTIN\Administrateurs         ACCÈS SPÉCIAL
                                          DELETE
                                          READ PERMISSONS
                                          WRITE PERMISSIONS
                                          CHANGE OWNERSHIP
                                          CREATE CHILD
                                          LIST CONTENTS
                                          WRITE SELF
                                          WRITE PROPERTY
                                          READ PROPERTY
                                          LIST OBJECT
                                          CONTROL ACCESS
Autoriser LAB\Administrateurs clés        ACCÈS SPÉCIAL pour msDS-KeyCredentialLink
                                          WRITE PROPERTY
                                          READ PROPERTY
Autoriser LAB\Administrateurs clés Enterprise
                                          ACCÈS SPÉCIAL pour msDS-KeyCredentialLink
                                          WRITE PROPERTY
                                          READ PROPERTY
Autoriser AUTORITE NT\SELF                ACCÈS SPÉCIAL pour msDS-AllowedToActOnBehalfOfOtherIdentity
                                          WRITE PROPERTY
                                          READ PROPERTY
Autoriser AUTORITE NT\SELF                ACCÈS SPÉCIAL pour Private Information
                                          WRITE PROPERTY
                                          READ PROPERTY
                                          CONTROL ACCESS

Transmises à : user
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Account Restrictions
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Logon Information
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Group Membership
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour General Information
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Remote Access Information
                                          READ PROPERTY
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          ACCÈS SPÉCIAL pour tokenGroups
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          LIST CONTENTS
                                          READ PROPERTY
                                          LIST OBJECT
Transmises à : inetOrgPerson
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Account Restrictions
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Logon Information
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Group Membership
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour General Information
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL pour Remote Access Information
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          LIST CONTENTS
                                          READ PROPERTY
                                          LIST OBJECT
Transmises à : group
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          ACCÈS SPÉCIAL pour tokenGroups
                                          READ PROPERTY
Autoriser BUILTIN\Accès compatible pré-Windows 2000
                                          ACCÈS SPÉCIAL
                                          READ PERMISSONS
                                          LIST CONTENTS
                                          READ PROPERTY
                                          LIST OBJECT
Transmises à : computer
Autoriser CREATEUR PROPRIETAIRE           ACCÈS SPÉCIAL pour Validated write to computer attributes.
                                          WRITE SELF
Autoriser AUTORITE NT\SELF                ACCÈS SPÉCIAL pour Validated write to computer attributes.
                                          WRITE SELF
Autoriser AUTORITE NT\ENTERPRISE DOMAIN CONTROLLERS
                                          ACCÈS SPÉCIAL pour tokenGroups
                                          READ PROPERTY
Autoriser AUTORITE NT\SELF                ACCÈS SPÉCIAL pour msTPM-TpmInformationForComputer
                                          WRITE PROPERTY
La commande s'est correctement terminée.
PS C:\Users\Administrat
