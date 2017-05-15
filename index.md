# About
These Amiibo Backups work just like the real Amiibo. They are perfect to take on the go with
you instead of your precious figures. If you are a collector, these will allow you to keep your
collectibles unopened.

# Available Amiibo

Name | Series | Notes
:--- |:--- |:---
**Wolf Link** |  | *with 20 hearts*
**Link** | Super Smash Bros. |
**Zelda** | Super Smash Bros. |
**Sheik** | Super Smash Bros. |
**Toon Link** | Super Smash Bros. |
**Link - Twilight Princess** | The Legend of Zelda | *Not yet available in stores*
**Link - Skyward Sword** | The Legend of Zelda | *Not yet available in stores*
**Link - Majora's Mask** | The Legend of Zelda | *Not yet available in stores*

# Test

<table>
  <thead>
    <tr>
      <th style="text-align: left">Name</th>
      <th style="text-align: left">Series</th>
      <th style="text-align: left">Notes</th>
    </tr>
  </thead>
  <tbody>
    {% for amiibo in site.data.amiibo.units %}
      <tr>
        <td style="text-align: left"><strong>{{ amiibo.name }}</strong></td>
        <td style="text-align: left">{{ amiibo.name }}</td>
        <td style="text-align: left"><em>{{ amiibo.notes }}</em></td>
      </tr>
    {% endfor %}
  </tbody>
</table>
