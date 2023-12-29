



Auth

- Node
    - node authorizer
    - nodes authorize with certifcate with system:node
- ABAC
    - like dev-user can get po, delete,
    - must edit the policy file and restart the kube api server
    - difficult to manage
RBAC
    - define the roles like developers
    - than assoticate all the users to this group

- webhook
    - open policy agent, this is third part tool to install
    -
- alwaysallow
    - allow without checking the auth checks
- alwayseney
    - will deny all the tiem

- Note:
    - you need set these methods on the api level authrization mode




- RBAC
    - we crate the roles and give the permission
    - we create the rolebind also
    - roles are base only on namespaces 