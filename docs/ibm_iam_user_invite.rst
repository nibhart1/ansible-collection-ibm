
ibm_iam_user_invite -- Configure IBM Cloud 'ibm_iam_user_invite' resource
=========================================================================

.. contents::
   :local:
   :depth: 1


Synopsis
--------

Create, update or destroy an IBM Cloud 'ibm_iam_user_invite' resource



Requirements
------------
The below requirements are needed on the host that executes this module.

- IBM-Cloud terraform-provider-ibm v1.2.1
- Terraform v0.12.20



Parameters
----------

  users (False, list, None)
    (Required for new resource) List of ibm id or email of user


  access_groups (False, list, None)
    access group ids to associate the inviting user


  iam_policy (False, list, None)
    None


  classic_infra_roles (False, list, None)
    None


  cloud_foundry_roles (False, list, None)
    None


  id (False, str, None)
    (Required when updating or destroying existing resource) IBM Cloud Resource ID.


  state (False, any, available)
    State of resource


  ibmcloud_api_key (True, any, None)
    The API Key used for authentification. This can also be provided via the environment variable 'IC_API_KEY'.


  ibmcloud_region (False, any, us-south)
    Denotes which IBM Cloud region to connect to













Authors
~~~~~~~

- Jay Carman (@jaywcarman)

