
<div id="schema-header-title">
  <h2>BeaconVariantInterpretationResponseContent <span id="schema-header-title-project">schemas <a href="https://github.com/progenetix/schemas" target="_BLANK">&nearr;</a></span> </h2>
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
<li><a href="https://beacon-project.io/categories/people.html">ELIXIR Beacon project team</a></li>
<li><a href="https://github.com/jrambla">Jordi Rambla</a></li>
<li><a href="https://github.com/sdelatorrep">Sabele de la Torre</a></li>
<li><a href="https://github.com/mamanambiya">Mamana Mbiyavanga</a></li>
<li><a href="https://orcid.org/0000-0002-9903-4248">Michael Baudis</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <th>Source (v2021-03-09)</th>
    <td>
      <ul>
        <li><a href="current/BeaconVariantInterpretationResponseContent.json" target="_BLANK">raw source [JSON]</a></li>
        <li><a href="https://github.com/progenetix/schemas/blob/master/schemas/BeaconVariantInterpretationResponseContent.yaml" target="_BLANK">Github</a></li>
      </ul>
    </td>
  </tr>
</table>

<div id="schema-attributes-title">
  <h3>Attributes</h3>
</div>

  
__Type:__ object  
__Description:__ TODO

### Properties

<table id="schema-properties-table">
  <tr>
    <th>Property</th>
    <th>Type</th>
  </tr>
  <tr>
    <th>beaconHandover</th>
    <td>array of "BeaconHandover.yaml#/properties [<a href="./BeaconHandover.html">HTML</a>]"</td>
  </tr>
  <tr>
    <th>error</th>
    <td>BeaconError.yaml#/properties [<a href="./BeaconError.html">HTML</a>]</td>
  </tr>
  <tr>
    <th>exists</th>
    <td>boolean</td>
  </tr>
  <tr>
    <th>info</th>
    <td>object</td>
  </tr>
  <tr>
    <th>numTotalResults</th>
    <td>integer</td>
  </tr>
  <tr>
    <th>results</th>
    <td>array of "BeaconVariantInterpretationResponseResults.yaml#/ [<a href="./BeaconVariantInterpretationResponseResults.html">HTML</a>]"</td>
  </tr>
  <tr>
    <th>resultsHandover</th>
    <td>array of "BeaconHandover.yaml#/properties [<a href="./BeaconHandover.html">HTML</a>]"</td>
  </tr>

</table>


#### beaconHandover

* type: array of "BeaconHandover.yaml#/properties [<a href="./BeaconHandover.html">HTML</a>]"




#### error

* type: BeaconError.yaml#/properties [<a href="./BeaconError.html">HTML</a>]




#### exists

* type: boolean

Indicator of whether any variant in sample was observed in any of the
datasets queried. This should be non-null, unless there was an
error, in which case `error` has to be non-null.



#### info

* type: object




#### numTotalResults

* type: integer




#### results

* type: array of "BeaconVariantInterpretationResponseResults.yaml#/ [<a href="./BeaconVariantInterpretationResponseResults.html">HTML</a>]"




#### resultsHandover

* type: array of "BeaconHandover.yaml#/properties [<a href="./BeaconHandover.html">HTML</a>]"




