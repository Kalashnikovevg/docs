# Getting started with [!KEYREF iam-short-name]

In this guide, you will learn how to:

* [Add users to your cloud](#add-user).
* [Assign cloud roles to users](#cloud-role).
* [Assign folder roles to users](#folder-role).
* [Revoke the assigned roles](#revoke-roles).

## Before getting started

You must have the [role of](concepts/access-control/roles.md) `[!KEYREF roles-cloud-owner]` or `[!KEYREF roles-admin]` for the cloud.

If you have no one to add to the cloud, you can [create a new account](https://passport.yandex.com/registration) on Yandex and grant access to the cloud to this account.

If you don't have a folder yet, create one:

[!INCLUDE [create-folder](../_includes/create-folder.md)]

## Add a new user to the cloud {#add-user}

To grant another user access to your resources, add the user to your cloud:

1. [!INCLUDE [grant-role-console-first-steps](../_includes/iam/grant-role-console-first-steps.md)]
1. On the **Users and roles** page, click **Add user** in the upper-right corner.
1. Enter the user's Yandex email address.
1. Click **Add**.

[!INCLUDE [roles-cloud-member](../_includes/roles-cloud-member.md)]

## Assign a user a role for the cloud {#cloud-role}

To grant a user access to view resources in your cloud, assign the user the role of `[!KEYREF roles-viewer]`:

1. [!INCLUDE [configure-roles-console](../_includes/iam/configure-roles-console.md)]
1. In the **Roles for the cloud <cloud name>** click ![image](../_assets/plus-sign.svg).
1. Choose the role of `[!KEYREF roles-viewer]`.

## Assign a user a role for a folder {#folder-role}

To allow a user to create resources in a folder, assign the user the role of `[!KEYREF roles-editor]` for this folder:

1. If you have closed the window with the role settings, open it again.
1. Select a folder in the **Roles in folders** section and click ![image](../_assets/plus-sign.svg).
1. Choose the role of `[!KEYREF roles-editor]`.

## Revoke assigned roles {#revoke-roles}

1. If you have closed the window with the role settings, open it again.
1. Click x next to each role you would like to revoke.

> [!NOTE]
>
> If the user doesn't have any more roles for your cloud, this user disappears from the list.
>
> If you want to revoke all roles at once, [delete the user](operations/users/delete.md) from your cloud.

