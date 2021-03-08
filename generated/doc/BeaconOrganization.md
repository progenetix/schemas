
<div id="schema-header-title">
  <h2>BeaconOrganization <span id="schema-header-title-project">schemas <a href="https://github.com/progenetix/schemas" target="_BLANK">&nearr;</a></span> </h2>
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
    <th>Source (v2021-03-07)</th>
    <td>
      <ul>
        <li><a href="current/BeaconOrganization.json" target="_BLANK">raw source [JSON]</a></li>
        <li><a href="https://github.com/progenetix/schemas/blob/master/schemas/BeaconOrganization.yaml" target="_BLANK">Github</a></li>
      </ul>
    </td>
  </tr>
</table>

<div id="schema-attributes-title">
  <h3>Attributes</h3>
</div>

  
__Type:__ object  
__Description:__ Organization owning the beacon.

### Properties

<table id="schema-properties-table">
  <tr>
    <th>Property</th>
    <th>Type</th>
  </tr>
  <tr>
    <th>address</th>
    <td>string</td>
  </tr>
  <tr>
    <th>contactUrl</th>
    <td>string</td>
  </tr>
  <tr>
    <th>description</th>
    <td>string</td>
  </tr>
  <tr>
    <th>id</th>
    <td>string</td>
  </tr>
  <tr>
    <th>info</th>
    <td>object</td>
  </tr>
  <tr>
    <th>logoUrl</th>
    <td>string</td>
  </tr>
  <tr>
    <th>name</th>
    <td>string</td>
  </tr>
  <tr>
    <th>welcomeUrl</th>
    <td>string</td>
  </tr>

</table>


#### address

* type: string

Address of the organization.



#### contactUrl

* type: string

URL with the contact for the beacon operator/maintainer, e.g. link to a contact form (RFC 3986 format) or an email (RFC 2368 format).


#### description

* type: string

Description of the organization.



#### id

* type: string

Unique identifier of the organization.



#### info

* type: object

Additional unspecified metadata about the host Organization.



#### logoUrl

* type: string

URL to the logo (PNG/JPG/SVG format) of the organization (RFC 3986 format).


#### name

* type: string

Name of the organization.



#### welcomeUrl

* type: string

URL of the website of the organization (RFC 3986 format).



