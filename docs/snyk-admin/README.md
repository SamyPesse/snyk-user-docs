# Snyk admin

## Introduction

{% hint style="info" %}
**Feature availability**\
Some functions (such as Groups) are only available on certain [pricing plans](https://snyk.io/plans/).
{% endhint %}

### Groups, Organizations, and Projects

Snyk has a hierarchy that allows you to control access to features and scans:

* **Group:** the highest level; for example, the entire company.
* **Organization:** the second level of grouping; for example, your team.
* **Projects:** the lowest level for individual projects; for example, a container image.

#### Snyk Groups

A [Snyk Group](../user-and-group-management/managing-groups-and-organizations/whats-a-snyk-group.md) represents your entire base of Snyk users.

Groups can contain multiple Snyk Organizations, allowing you to collaborate with multiple teams.

#### Snyk Organizations

[Organizations](../user-and-group-management/managing-groups-and-organizations/whats-a-snyk-organization.md) represent business areas such as teams, products or environments.&#x20;

Organizations can contain multiple Snyk Projects, allowing your team to see scan details for the applications they are working on.

{% hint style="info" %}
When you sign up to Snyk using a social login, you have a default Organization. Any projects you add appear in this Organization by default.
{% endhint %}

#### Snyk Projects

[Snyk Projects](./#snyk-projects) are contained in Organizations.

A Snyk Project defines the items that Snyk scans for issues (such as manifest files), along with configuration information defining how to run that scan.

### Snyk user types

Snyk provides four different types of members or users:

* Collaborator
* Organization administrator
* Group member
* Group administrator

For definitions of the associated permissions per role, see [Managing permissions](../user-and-group-management/managing-users-and-permissions/managing-permissions.md#permissions-per-role).

{% hint style="info" %}
**Feature availability**\
Group administrators and collaborators are available with Enterprise plans. See [pricing plans](https://snyk.io/plans/) for more details.
{% endhint %}

### Management tools

Snyk offers a wide range of tools to manage Groups, Organizations, and users.

#### Enable authentication

Snyk offers API tokens to enable authentication to service accounts or third party tools; see [Managing authentication](../user-and-group-management/authentication/).

#### Set up Single Sign-On (SSO)

SSO makes authentication and provisioning simple; see [Setting up Single Sign-On (SSO) for authentication](../user-and-group-management/setting-up-sso-for-authentication/).

<figure><img src="../.gitbook/assets/image (167) (1) (1) (1) (1) (1) (1) (1) (2).png" alt="Single Sign-On"><figcaption><p>Single Sign-On</p></figcaption></figure>

#### Manage users and permissions

You can manage users and permissions in your groups; See [Managing users & permissions](../user-and-group-management/managing-users-and-permissions/).

<figure><img src="../.gitbook/assets/image (245) (1).png" alt="Manage users and permissions"><figcaption><p>Manage users and permissions</p></figcaption></figure>

#### Manage Groups and Organizations

Learn how Snyk groups and organizations help keep cross-team collaboration seamless; see [Managing groups & organizations](../user-and-group-management/managing-groups-and-organizations/).

#### Define notifications

You can manage email notifications, for yourself and your organization. See [Managing notifications](../user-and-group-management/notifications.md).

<figure><img src="../.gitbook/assets/image (6).png" alt="Manage email notifications"><figcaption><p>Manage email notifications</p></figcaption></figure>

#### Manage settings

Customize your Snyk account for your needs. See [Managing settings](../user-and-group-management/managing-settings/).