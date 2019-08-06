# com.unity.nuget.newtonsoft-json
Unity package manager setup for Newtonsoft's JSON library (https://www.newtonsoft.com/json)

# Version

This package includes the DLL version of JSON.Net

Version: 12.0.1.22727

# Add to your project with git url (2019.3+)

Open the manifest.json for your project and add the following entry to your list of dependencies

```"com.unity.nuget.newtonsoft-json": "git@github.cds.internal.unity3d.com:unity/com.unity.nuget.newtonsoft-json.git",```

For example:

```
{
  "dependencies": {
    "com.unity.nuget.newtonsoft-json": "git@github.cds.internal.unity3d.com:unity/com.unity.nuget.newtonsoft-json.git",
    "com.unity.ads": "2.0.8",
    "com.unity.analytics": "3.2.2",
    "com.unity.collab-proxy": "1.2.15",
    ...
    }
 }
 ```

# Add to your project with version

Open the manifest.json for your project and add the following entry to your list of dependencies with the desired version

```"com.unity.nuget.newtonsoft-json": "1.0.0-preview.4",```

For example:

```
{
  "dependencies": {
    "com.unity.nuget.newtonsoft-json": "1.0.0-preview.4",
    "com.unity.ads": "2.0.8",
    "com.unity.analytics": "3.2.2",
    "com.unity.collab-proxy": "1.2.15",
    ...
    }
 }
 ```
 
# Using the package
 
 In the target package, modify the asmdef to include the `NewtonsoftJson.dll` under the Assembly References section
 in the asmdef inspector.  The section will not appear until the Override References toggle above is toggled on.
 Once that is done, your package will have full access to Newtonsoft Json apis.