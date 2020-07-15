# EasyCLA is Disabled

EasyCLA is disabled so the organizations that I want EasyCLA to monitor are not monitored.

**Solution:**

This is a known issue. GitHub is set up to permit administrators and organization owners to have maximum flexibility, which includes disabling apps like EasyCLA. Do the following steps to mitigate this problem immediately. Be sure to educate your administrators and organization owners about this GitHub setup and solution.

**Do these steps:**

1. As the GitHub organization owner or administrator, go to the GitHub repository that you want EasyCLA to monitor.

2. Click **Settings** from the top menu.

![CLA GitHub Repository Settings](../../../../.gitbook/assets/cla-github-repository-settings.png)

3. Settings appear with Options in the left pane.

4. Click **Branches** under Options.

![CLA GitHub Options](../../../../.gitbook/assets/cla-github-options.png)

**Result:** Branch settings appears.

5. Select **master** for the Default branch. Click **Edit** or **Add rule** for Branch protection rules of your organization.

![CLA GitHub branch Add Rule](../../../../.gitbook/assets/cla-github-branch-add-rule.png)

**Result:** Branch protection rule settings appears

6. Select the following check boxes in Rule settings and click **Create**.

* Require status checks to pass before merging
* Require branches to be up to date before merging
* Include administrators

![CLA GitHub Branch Protection Rule](../../../../.gitbook/assets/cla-github-branch-protection-rule.png)

