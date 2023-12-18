

Service Accounts

    - User Accounts
        - used by human
    - Services Accounts
        - usedd by machine
        - when service account crate a token also created which using by application/machine
        - hosting application in the kubernet and attached the service account token already created to pod to communicate
        - each namespace their on svc
        - kubernetes automatically mount default service account if you havnt mentioned
        - you can ignore the service account to mount
        - in 1.22 token is no longer exists but yohave token api
        - in 1.24 you can create token manually and its valid for 1 hour by default
        