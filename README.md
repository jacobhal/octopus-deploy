# Octopus Deploy

## Transforms

### Replace
We can omit the Locator and name if we want Replace to only replace the first element.
```CS
<connectionStrings>
  <add name="MyDatabaseConnection" connectionString="#{OctoFXDatabase}" xdt:Transform="Replace" xdt:Locator="Match(name)"/>
</connectionStrings>
```
