---
Module Name: Team
Module Guid: 22fe5207-1749-4832-9648-e939fe074b7f
Help Version: 1.0.0.0
Locale: en-US
---

# VSTeam Module

## Description

Welcome to VSTeam. VSTeam is a [PowerShell module](https://www.powershellgallery.com/packages/VSTeam/) that wraps the [REST API provided by Team Foundation Server and Visual Studio Team Services](https://cda.ms/ys). This allows you to access the power of TFS and VSTS from [PowerShell on Windows, MacOS and Linux](https://github.com/PowerShell/PowerShell).

## VSTeam Functions

### [Add-VSTeam](Add-VSTeam.md)

Adds a team to a team project.

### [Add-VSTeamAccount](Add-VSTeamAccount.md)

Stores your account name and personal access token for use with the other
functions in this module.

### [Add-VSTeamAzureRMServiceEndpoint](Add-VSTeamAzureRMServiceEndpoint.md)

Adds a new Azure Resource Manager service endpoint.

### [Add-VSTeamBuild](Add-VSTeamBuild.md)

Queues a new build.

### [Add-VSTeamBuildDefinition](Add-VSTeamBuildDefinition.md)

Creates a new build definition from a JSON file.

### [Add-VSTeamBuildTag](Add-VSTeamBuildTag.md)

Adds a tag to a build.

### [Add-VSTeamExtension](Add-VSTeamExtension.md)

Install the specified extension into the account / project collection.

### [Add-VSTeamFeed](Add-VSTeamFeed.md)

Adds a new feed to package management.

### [Add-VSTeamGitRepository](Add-VSTeamGitRepository.md)

Adds a Git repository to your Visual Studio Team Services or Team Foundation Server account.

### [Add-VSTeamKubernetesEndpoint](Add-VSTeamKubernetesEndpoint.md)

Adds connections to Kubernetes clusters

### [Add-VSTeamNuGetEndpoint](Add-VSTeamNuGetEndpoint.md)

Adds a new NuGet service endpoint.

### [Add-VSTeamPolicy](Add-VSTeamPolicy.md)

Adds a new policy to the specified project.

### [Add-VSTeamProfile](Add-VSTeamProfile.md)

Stores your account name and personal access token as a profile for use with
the Add-TeamAccount function in this module.

### [Add-VSTeamProject](Add-VSTeamProject.md)

Adds a Team Project to your account.

### [Add-VSTeamRelease](Add-VSTeamRelease.md)

Queues a new release

### [Add-VSTeamReleaseDefinition](Add-VSTeamReleaseDefinition.md)

Creates a new release definition from a JSON file.

### [Add-VSTeamServiceEndpoint](Add-VSTeamServiceEndpoint.md)

Adds a generic service connection

### [Add-VSTeamServiceFabricEndpoint](Add-VSTeamServiceFabricEndpoint.md)

Adds a new Service Fabric service endpoint.

### [Add-VSTeamSonarQubeEndpoint](Add-VSTeamSonarQubeEndpoint.md)

Adds a new SonarQube service endpoint.

### [Add-VSTeamUser](Add-VSTeamUser.md)

Adds a user to the account.

### [Add-VSTeamWorkItem](Add-VSTeamWorkItem.md)

Adds a work item to your project.

### [Clear-VSTeamDefaultProject](Clear-VSTeamDefaultProject.md)

Clears the value stored in the default project parameter value.

### [Disable-VSTeamAgent](Disable-VSTeamAgent.md)

Disables an agent in a pool.

### [Enable-VSTeamAgent](Enable-VSTeamAgent.md)

Enables an agent in a pool.

### [Get-VSTeam](Get-VSTeam.md)

Returns a team.

### [Get-VSTeamAgent](Get-VSTeamAgent.md)

Returns the agents in a pool.

### [Get-VSTeamApproval](Get-VSTeamApproval.md)

Gets a list of approvals for all releases for a team project.

### [Get-VSTeamBuild](Get-VSTeamBuild.md)

Gets the builds for a team project.

### [Get-VSTeamBuildArtifact](Get-VSTeamBuildArtifact.md)

Returns the artifacts of a build.

### [Get-VSTeamBuildDefinition](Get-VSTeamBuildDefinition.md)

Gets the build definitions for a team project.

### [Get-VSTeamBuildLog](Get-VSTeamBuildLog.md)

Displays the logs for the build.

### [Get-VSTeamBuildTag](Get-VSTeamBuildTag.md)

Returns all the tags of a build.

### [Get-VSTeamCloudSubscription](Get-VSTeamCloudSubscription.md)

Gets the Azure subscriptions associated with the Team Services account.

### [Get-VSTeamExtension](Get-VSTeamExtension.md)

Get the installed extensions in the specified Visual Studio Team Services or Team Foundation Server project.

### [Get-VSTeamFeed](Get-VSTeamFeed.md)

Returns a list of package feeds for the account.

### [Get-VSTeamGitRef](Get-VSTeamGitRef.md)

Queries the provided repository for its refs and returns them.

### [Get-VSTeamGitRepository](Get-VSTeamGitRepository.md)

Get all the repositories in your Visual Studio Team Services or Team Foundation Server account, or a specific project.

### [Get-VSTeamInfo](Get-VSTeamInfo.md)

Displays your current account and default project.

### [Get-VSTeamMember](Get-VSTeamMember.md)

Returns a team member.

### [Get-VSTeamOption](Get-VSTeamOption.md)

Returns all the versions of supported APIs of your TFS or VSTS.

### [Get-VSTeamPolicy](Get-VSTeamPolicy.md)

Get the code policies in the specified Visual Studio Team Services or Team Foundation Server project.

### [Get-VSTeamPolicyType](Get-VSTeamPolicyType.md)

Get the policy types in the specified Visual Studio Team Services or Team Foundation Server project.

### [Get-VSTeamPool](Get-VSTeamPool.md)

Returns the agent pools.

### [Get-VSTeamProcess](Get-VSTeamProcess.md)

Returns a list of process templates in the Team Services or Team Foundation Server account.

### [Get-VSTeamProfile](Get-VSTeamProfile.md)

Returns the saved profiles.

### [Get-VSTeamProject](Get-VSTeamProject.md)

Returns a list of projects in the Team Services or Team Foundation Server account.

### [Get-VSTeamPullRequest](Get-VSTeamPullRequest.md)

Returns one or more open pull requests from your team, project, or Id.

### [Get-VSTeamQueue](Get-VSTeamQueue.md)

Gets a agent queue.

### [Get-VSTeamRelease](Get-VSTeamRelease.md)

Gets the releases for a team project.

### [Get-VSTeamReleaseDefinition](Get-VSTeamReleaseDefinition.md)

Gets the release definitions for a team project.

### [Get-VSTeamResourceArea](Get-VSTeamResourceArea.md)

List all the areas supported by this instance of TFS/VSTS.

### [Get-VSTeamServiceEndpoint](Get-VSTeamServiceEndpoint.md)

Gets a service endpoint.

### [Get-VSTeamServiceEndpointType](Get-VSTeamServiceEndpointType.md)

Get service endpoint types.

### [Get-VSTeamTfvcBranch](Get-VSTeamTfvcBranch.md)

Gets a branch for a given path from TFVC source control.

### [Get-VSTeamTfvcRootBranch](Get-VSTeamTfvcRootBranch.md)

Gets root branches for all projects with TFVC source control.

### [Get-VSTeamUser](Get-VSTeamUser.md)

Returns a list of users for the account.

### [Get-VSTeamWorkItem](Get-VSTeamWorkItem.md)

Returns one or more a work items from your project.

### [Get-VSTeamWorkItemType](Get-VSTeamWorkItemType.md)

Gets a list of all Work Item Types or a single work item type.

### [Invoke-VSTeamRequest](Invoke-VSTeamRequest.md)

Allows you to call any TFS/VSTS REST API. All the Auth and Route Structure is taken care of for you. Just provide the parts of the API call you need.  If you need to send a non-standard URL use the -Url parameter.  If the -Url is used the Url is not changed but the header and UserAgent are added for you.

### [Remove-VSTeam](Remove-VSTeam.md)

Removes a team from a project.

### [Remove-VSTeamAccount](Remove-VSTeamAccount.md)

Clears your default project, account name and personal access token.

### [Remove-VSTeamAgent](Remove-VSTeamAgent.md)

Removes an agent from a pool.

### [Remove-VSTeamBuild](Remove-VSTeamBuild.md)

Deletes the build.

### [Remove-VSTeamBuildDefinition](Remove-VSTeamBuildDefinition.md)

Removes the build definitions for a team project.

### [Remove-VSTeamBuildTag](Remove-VSTeamBuildTag.md)

Removes the tag from a build.

### [Remove-VSTeamExtension](Remove-VSTeamExtension.md)

Uninstall the specified extension from the account / project collection. 

### [Remove-VSTeamFeed](Remove-VSTeamFeed.md)

Removes a package feed from the account.

### [Remove-VSTeamGitRepository](Remove-VSTeamGitRepository.md)

Removes the Git repository from your Visual Studio Team Services or Team Foundation Server account.

### [Remove-VSTeamPolicy](Remove-VSTeamPolicy.md)

Removes the specified policy from the specified project.

### [Remove-VSTeamProfile](Remove-VSTeamProfile.md)

Removes the profile.

### [Remove-VSTeamProject](Remove-VSTeamProject.md)

Deletes the Team Project from your Team Services account.

### [Remove-VSTeamRelease](Remove-VSTeamRelease.md)

Removes the releases for a team project.

### [Remove-VSTeamReleaseDefinition](Remove-VSTeamReleaseDefinition.md)

Removes the release definitions for a team project.

### [Remove-VSTeamServiceEndpoint](Remove-VSTeamServiceEndpoint.md)

Removes a service endpoint.

### [Remove-VSTeamUser](Remove-VSTeamUser.md)

Removes a user from the account.

### [Set-VSTeamAPIVersion](Set-VSTeamAPIVersion.md)

Sets the API versions to support either TFS2017, TFS2018 or VSTS.

### [Set-VSTeamApproval](Set-VSTeamApproval.md)

Sets the status of approval to Approved, Rejected, Pending, or ReAssigned.

### [Set-VSTeamDefaultProject](Set-VSTeamDefaultProject.md)

Sets the default project to be used with other calls in the module.

### [Set-VSTeamEnvironmentStatus](Set-VSTeamEnvironmentStatus.md)

Sets the status of a environment to canceled, inProgress, notStarted, partiallySucceeded, queued, rejected, scheduled, succeeded or undefined.

### [Set-VSTeamReleaseStatus](Set-VSTeamReleaseStatus.md)

Sets the status of a release to Active or Abandoned.

### [Show-VSTeam](Show-VSTeam.md)

Opens TFS or VSTS site in the default browser.

### [Show-VSTeamApproval](Show-VSTeamApproval.md)

Opens the release associated with the waiting approval in the default browser.

### [Show-VSTeamBuild](Show-VSTeamBuild.md)

Opens the build summary in the default browser.

### [Show-VSTeamBuildDefinition](Show-VSTeamBuildDefinition.md)

Opens the build definition in the default browser.

### [Show-VSTeamFeed](Show-VSTeamFeed.md)

Opens the feed in the default browser.

### [Show-VSTeamGitRepository](Show-VSTeamGitRepository.md)

Opens the Git repository in the default browser.

### [Show-VSTeamProject](Show-VSTeamProject.md)

Opens the project in the default browser.

### [Show-VSTeamPullRequest](Show-VSTeamPullRequest.md)

Opens the pull request in the default browser.

### [Show-VSTeamRelease](Show-VSTeamRelease.md)

Opens the release summary in the default browser.

### [Show-VSTeamReleaseDefinition](Show-VSTeamReleaseDefinition.md)

Opens the release definitions for a team project in the default browser.

### [Show-VSTeamWorkItem](Show-VSTeamWorkItem.md)

Opens the work item in the default browser.

### [Update-VSTeam](Update-VSTeam.md)

Updates the team name, description or both.

### [Update-VSTeamBuild](Update-VSTeamBuild.md)

Allows you to set the keep forever flag and build number.

### [Update-VSTeamBuildDefinition](Update-VSTeamBuildDefinition.md)

Updates a build definition for a team project.

### [Update-VSTeamExtension](Update-VSTeamExtension.md)

Update an installed extension. Typically this API is used to enable or disable an extension.

### [Update-VSTeamPolicy](Update-VSTeamPolicy.md)

Updates an existing policy in the specified project.

### [Update-VSTeamProfile](Update-VSTeamProfile.md)

Allows you to update the Personal Access Token for your profile.

### [Update-VSTeamProject](Update-VSTeamProject.md)

Updates the project name, description or both.

### [Update-VSTeamServiceEndpoint](Update-VSTeamServiceEndpoint.md)

Updates an existing service connection

### [Update-VSTeamUser](Update-VSTeamUser.md)

Updates the users for the account. (Currently only supports updating the LicenseType)

### [Update-VSTeamWorkItem](Update-VSTeamWorkItem.md)

Update a work item in your project.



