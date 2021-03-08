
<div id="schema-header-title">
  <h2>BeaconInfoRequestMeta <span id="schema-header-title-project">schemas <a href="https://github.com/progenetix/schemas" target="_BLANK">&nearr;</a></span> </h2>
</div>

<table id="schema-header-table">
  <tr>
    <th>{S}[B] Status <a href="https://schemablocks.org/about/sb-status-levels.html">[i]</a></th>
    <td><div id="schema-header-status">community</div></td>
  </tr>

  <tr>
    <th>Provenance</th>
    <td>
      <ul>
<li><a href="https://github.com/ga4gh-beacon/specification-v2">Beacon v2</a></li>
<li><a href="https://github.com/progenetix/bycon/">Progenetix `bycon` project</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Used by</th>
    <td>
      <ul>
<li><a href="https://github.com/progenetix/schemas/">Progenetix database schema (Beacon+ backend)</a></li>
      </ul>
    </td>
  </tr>

<!--more-->

  <tr>
    <th>Contributors</th>
    <td>
      <ul>
<li><a href="http://beacon-project.io">ELIXIR Beacon project team</a></li>
<li><a href="https://orcid.org/0000-0002-9903-4248">Michael Baudis</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Source (v2021-03-08)</th>
    <td>
      <ul>
        <li><a href="current/BeaconInfoRequestMeta.json" target="_BLANK">raw source [JSON]</a></li>
        <li><a href="https://github.com/progenetix/schemas/blob/master/schemas/BeaconInfoRequestMeta.yaml" target="_BLANK">Github</a></li>
      </ul>
    </td>
  </tr>
</table>

<div id="schema-attributes-title">
  <h3>Attributes</h3>
</div>

  
__Type:__ object  
__Description:__ Requested schemas and versions to be used in the response.

### Properties

<table id="schema-properties-table">
  <tr>
    <th>Property</th>
    <th>Type</th>
  </tr>
  <tr>
    <th>apiVersion</th>
    <td>string</td>
  </tr>
  <tr>
    <th>requestedSchemas</th>
    <td>BeaconInfoRequestedSchemas.yaml#/properties</td>
  </tr>

</table>


#### apiVersion

* type: string

Schemas & versions default for this Beacon version will be used to 
format the response.


##### `apiVersion` Value Example  

```
"v2.0"
```

#### requestedSchemas

* type: BeaconInfoRequestedSchemas.yaml#/properties




