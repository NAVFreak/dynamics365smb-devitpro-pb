> [!NOTE]
> In version 22, [!INCLUDE[server](server.md)] runs on .NET 6.0 instead of .NET 4.8 as with earlier versions. This change has significant impact on the technical upgrade to version 22 because many references to .NET assemblies in source code will no longer work, unless they're updated to .NET 6.0. Updating the references requires extensive modifications to extensions, especially the system and base applications, because of the many [dotnet package](../devenv-get-started-call-dotnet-from-al.md) references to .NET assemblies.
>
> Instead of a technical upgrade, we recommend that you do a full upgrade (platform and application) to save time and benefit from the latest application features. A full upgrade will also ease future upgrades, and it aligns with our [Universal code initiative](https://cloudblogs.microsoft.com/dynamics365/it/2022/10/28/the-dynamics-365-business-central-universal-code-initiative-is-live/#:~:text=The%20Universal%20Code%20initiative%20is%20designed%20to%20encourage,the%20right%20apps%20on%20the%20Microsoft%20AppSource%20marketplace.).