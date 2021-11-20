# CSharp10Arhi
Implicit using

In *.csproj 

```XML
<ItemGroup>
   <Using Remove="System.Net.Http"/>
   <Using Include="System.Text" />
   <Using Include="System.Math" Static="true" /> 
 <ItemGroup>


