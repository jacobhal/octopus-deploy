# Octopus Deploy

## Best Practice

TODO

## Download NuGet Packages in OD

Library > Search for your project -> Select your project -> Select the version that you want to download -> Download

## Transforms

The .NET Configuration Transforms feature is one of the configuration features you can enable as you define the steps in your deployment process.

https://octopus.com/docs/projects/steps/configuration-features/configuration-transforms

### Replace
We can omit the Locator and name if we want Replace to only replace the first element.
```CS
<connectionStrings>
  <add name="MyDatabaseConnection" connectionString="#{OctoFXDatabase}" xdt:Transform="Replace" xdt:Locator="Match(name)"/>
</connectionStrings>
```

## Tools

### NuGetPackageExplorer

A good tool to use to get an overview of downloaded NuGet packages.

https://github.com/NuGetPackageExplorer/NuGetPackageExplorer

### Wev.config Transformation Tester

https://webconfigtransformationtester.apphb.com/
