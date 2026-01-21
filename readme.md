


# lib_GeneratePWAAssets

Mashup Sequencer project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [generateAssets](#generateassets)
    - [generateAssetsV2](#generateassetsv2)
    - [MakeImages](#makeimages)
    - [PwaAssetGenerator](#pwaassetgenerator)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_GeneratePWAAssets=https://github.com/convertigo/c8oprj-lib-generate-assets-pwa.git:branch=8.0.0
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_GeneratePWAAssets=https://github.com/convertigo/c8oprj-lib-generate-assets-pwa/archive/8.0.0.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_GeneratePWAAssets__ project


## Sequences

### generateAssets

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>additionalParametersJSONObjectString</td><td></td>
</tr>
<tr>
<td>image</td><td></td>
</tr>
<tr>
<td>ngswFileName</td><td></td>
</tr>
<tr>
<td>onlyReGenerateNGSW</td><td></td>
</tr>
<tr>
<td>projectName</td><td></td>
</tr>
<tr>
<td>pwaBackgroundColor</td><td></td>
</tr>
<tr>
<td>pwaName</td><td></td>
</tr>
<tr>
<td>pwaShortName</td><td></td>
</tr>
<tr>
<td>pwaThemeColor</td><td></td>
</tr>
<tr>
<td>queryParameters</td><td></td>
</tr>
<tr>
<td>scrape</td><td>Scraping Apple Human Interface guidelines to fetch splash screen specs  [default: "false"]</td>
</tr>
<tr>
<td>target</td><td></td>
</tr>
</table>

### generateAssetsV2

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>additionalParametersJSONObjectString</td><td></td>
</tr>
<tr>
<td>image</td><td></td>
</tr>
<tr>
<td>ngswFileName</td><td></td>
</tr>
<tr>
<td>onlyReGenerateNGSW</td><td></td>
</tr>
<tr>
<td>projectName</td><td></td>
</tr>
<tr>
<td>projectTargetName</td><td></td>
</tr>
<tr>
<td>pwaBackgroundColor</td><td></td>
</tr>
<tr>
<td>pwaName</td><td></td>
</tr>
<tr>
<td>pwaShortName</td><td></td>
</tr>
<tr>
<td>pwaThemeColor</td><td></td>
</tr>
<tr>
<td>queryParameters</td><td></td>
</tr>
<tr>
<td>scrape</td><td>Scraping Apple Human Interface guidelines to fetch splash screen specs  [default: "false"]</td>
</tr>
<tr>
<td>target</td><td></td>
</tr>
</table>

### MakeImages

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>background</td><td></td>
</tr>
<tr>
<td>destination</td><td></td>
</tr>
<tr>
<td>logo</td><td></td>
</tr>
<tr>
<td>outputs</td><td></td>
</tr>
</table>

### PwaAssetGenerator

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>background</td><td></td>
</tr>
<tr>
<td>destination</td><td></td>
</tr>
<tr>
<td>index</td><td></td>
</tr>
<tr>
<td>logo</td><td></td>
</tr>
<tr>
<td>manifest</td><td></td>
</tr>
<tr>
<td>theme</td><td></td>
</tr>
</table>



