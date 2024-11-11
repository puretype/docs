---
description: Detailed documentation of the Cursor / Visual Studio Code integration
---

# Cursor / Visual Studio Code

To facilitate consistent feedback in the context of your editor, [the Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=puretype.puretype) offers:

* feedback and quick fixes for currently open files
* (if configured) reminders to engage with learning material at suitable moments in a developer's workflow

Forks of Visual Studio Code, such as [Cursor](https://www.cursor.com/), are also supported.

<figure><img src="../../.gitbook/assets/Screenshot 2024-11-11 at 14.10.38 (1).png" alt=""><figcaption><p>Further detail is provided alongside each check, so developers can read up further on the idiom</p></figcaption></figure>

## Installation

The Visual Studio Code extension can be set up during the initial onboarding process:

<figure><img src="../../.gitbook/assets/Screenshot 2024-11-11 at 15.04.11.png" alt="" width="375"><figcaption><p>The authentication prompt after installing the extension</p></figcaption></figure>

{% stepper %}
{% step %}
### Install the extension

You will be prompted to install the Visual Studio Code extension as one of the initial onboarding steps once you have logged into [the web interface](https://app.puretype.ai/learn).
{% endstep %}

{% step %}
### Authenticate the extension

Once the extension has been installed, a dialog will appear to prompt you to log in to PureType.
{% endstep %}

{% step %}
### Receive feedback

Once authenticated, you will receive feedback and suggestions in your open files, and if, configured, prompts to engage with your personalised learning material.
{% endstep %}
{% endstepper %}

<figure><img src="../../.gitbook/assets/Screenshot 2024-11-11 at 14.10.17.png" alt=""><figcaption><p>Quick fixes are available for many of the checks</p></figcaption></figure>

## Usage

The hints, suggestions and fixes are the same as those suggested during the [code review](../scm-integrations/) stage.

In [the notification settings page](https://app.puretype.ai/settings/notifications), you can optionally configure your extension to remind you to review and revise your personalised learning. The exact pattern of these reminders is currently subject to change.

## Code

The source code for the Visual Studio extension (and its forks) is available on [GitHub](https://github.com/puretype/puretype-vscode), released under [the MIT license](https://github.com/puretype/puretype-vscode/blob/main/LICENSE).
